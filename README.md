# Cloud Computing Curriculum
Sample Curriculum for Teaching Cloud &amp; Cloud Native

Prepared for Attendees of Cloud Native University Kubecon 2024 Co-located Event. 

# Sample Course Curriculum
## Curriculum Overview
The following curriculum is designed for a 15-16 week semester
### Unit 1: Introduction to Cloud
- Lecture 1: What is the Cloud?
- Lecture 2: What is Computing?
- Lecture 3: Hypervisors & Virtual Machines
- Lecture 4: Containers
- Lecture 5: Cloud Storage
- Lecture 6: Cloud Database Fundamentals
- Lecture 7: Network Day 1
- Lecture 8: Network Day 2
- Lecture 9: Unit 1 Review
### Unit 2: Cloud Native
- Lecture 10: Introduction to Cloud Native
- Lecture 11: Compute (PaaS)
- Lecture 12: Microservices
- Lecture 13: Infrastructure as Code
- Lecture 14: Kubernetes Day 1
- Lecture 15: Kubernetes Day 2
- Lecture 16: Code Walk-through
- Lecture 17: Observability
- Lecture 18: Cloud Security Day 1
- Lecture 19: Cloud Security Day 2
- Lecture 20: Unit 2 Review
### Unit 3: MLOps & ML/AI in the Cloud
- Lecture 21: Introduction to MLOps- The ML Lifecycle
- Lecture 22: Cloud Architecture Decisions for MLOps
- Lecture 23: LLMOps
- Lecture 24: Common Cloud Architectural Patterns
- Lecture 25: Unit 3 Review 

# Sample Lectures
## Lecture 1: What is the Cloud
- pptx: [Lecture 1](docs/lecture_1_what_is_the_cloud.pptx)
- recording: [Lecture Proper](https://youtu.be/Ef_k156-iZE?si=wnCY0sekoUNSpPbo&t=1721)
- course introduction: [YouTube](https://youtu.be/Ef_k156-iZE?si=-gguDYy6j1iJeYQ6)

## Lecture 2: What is Computing
Note: This lecture was voted on by students when asked if they would like an overview of compute architectures. It is inteded to provide a level-set for studnets who may not come from a traditional CS background. 

- pptx: [Lecture 2](docs/lecture_2_what_is_computing.pptx)
- recording: [YouTube](https://youtu.be/QHXwPy_eyJI?si=krHuci6RZLf8lbgQ)

## Lecture 3: Compute
- pptx: [Lecture 3](docs/lecture_3_compute_iaas.pptx)
- recording: [YouTube](https://youtu.be/HrtQPOHJ5AI?si=xHuEPXKHvvsQ3mc-)

## Lecture 4: Containers
- pptx: [Lecture 4](docs/lecture_4_containers.pptx)
- recording: [YouTube](https://youtu.be/MS1ex3uK1wc)

# Sample Assignments
## IaaS Compute
### Assignment Summary: 
In the IaaS assignment, students create a VM (droplet) on DigitalOcean, launch a Jupyter server, and SSH to the Jupyter Notebook interface using SSH tunneling to connect to it. 

Link to Assignment in GitHub Classrooms: https://classroom.github.com/a/oF-d3MHd 

### Learning Objectives
1. Learn how to create a VM
2. Learn how to add an SSH key to a VM
3. Learn how to interact with VMs using the cloud console, the CLI, and an SSH client
4. Learn about port forwarding and tunneling 

### Alignment with student interests/needs: 
- This assignment helps students with other coursework as they are able to run Jupyter notebooks directly on virtual machines whose size/ computer resources they control, rather than relying on SaaS notebook solutions. 
- Students start to gain an intuition for how SaaS Notebooks are served

## PaaS
### Assignment Summary
In this assignment, students will learn how to work with static site generators, and being to explore PaaS options for deployment via DigitalOcean App Platform. 

Link to Assignment in GitHub Classrooms: https://classroom.github.com/a/eOWh3zgy 

### Learning Objectives
1. Introduce students to JAMStack
2. Introduce students to PaaS Compute
3. Allow students to explore open source ecosystem around Hugo and Hugo themes
4. Gain familiarity with CD through connecting source code to DigitalOcean App Platform. 

### Alignment with student interests/needs:
- Gives students an opportunity to showcase their resume and skills through a static webiste, which could be helpful for future job interviews. 

## Security
### Assignment Summary
In the security assignment, students have the opportunity to explore GitHub actions in greater depth than earlier assignments, and understand some foundational DevSecOps principles by building code and container image scanning pipelines. 

Link to assignment in GitHub Classrooms: https://classroom.github.com/a/CnKC29wn
### Learning Objectives
1. Give students an opportunity to explore GHA marketplace
2. Introduce students to different static code scanning tooling
3. Allow students to start to think critically about vulnerability scanning results and how to prioritize vulnerability remediation

### Alignment with student interests/needs:
- The course uses PyGOAT, a deliberately insecure webapp built by OWASP to help guide learners through exploiting the OWASP Top 10 web vulnerabilities. Students who have interest in web app exploitation can use their locally deployed instance of PyGOAT to practice pentesting/ web app exploitation. 

# Sample Supplemental Material
## Tutorials and Guides:
Written by my brilliant TA, [Vetri Ramalingam](https://github.com/orgs/MIS547-Fall-2024/people/vetrirg)
- [Creating an Account on AWS](https://vetrivelramalingam.medium.com/create-a-free-aws-account-and-explore-cloud-services-37d71623639d)
- [Creating an Account on GCP]()
- [Creating an Account on Azure]()
## Walk-throughs:
- [Creating an Azure Instance](https://youtu.be/YgSVTcjelxQ)
- [Creating an EC2 Instance](https://youtu.be/LMQJ3Plwg_E)
- [Creating a GCP Compute Instance](https://youtu.be/469xKzNFzsY)

## Interviews with Industry Experts
- [Adam Shamblin on Microservices](https://youtu.be/fBhOMs1zd-A)

# Sample Project Directions
- [Sample Project Directions](docs/sample_project_directions.md)

# Resources for Instructors
- [Student Stress Cycles](docs/23_Student_Stress_Cycle.pdf)
- [Universal Design for Learning Framework](https://www.cast.org/impact/universal-design-for-learning-udl)
- [Collaborative Learning](https://docs.google.com/document/d/1D_vUMQl6T_cqB3zu_TMMjv6-NWJh6mFq/edit)
- [Flipping Your Class to Enhance Active Learning](https://docs.google.com/document/d/1a06xwdoKvXq_ye-_KePjlpshM9Bo6OTk/edit)
- [Learning ePortfolios](https://docs.google.com/document/d/1HZnBRsg9-R-w9vpD-UjZ4SKFXl3ig78Q/edit)
- [Learning Science Strategies](https://docs.google.com/document/d/1yP-ORCaPfPeQVTEHPNzGK0rYgmB5znl4/edit)
- [Mindfulness in the Classroom](https://docs.google.com/document/d/1qH8THOhNln1edK9VXgIS20L4Isp3Yl0n/edit)
- [Balancing Work and Learning](https://cew.georgetown.edu/cew-reports/learnandearn/)
