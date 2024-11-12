# Sample Project Directions

# Final Project Overview

The final project will be a group project that will have your team present an architecture diagram and (ideally) a working prototype where you will serve an ML model using cloud computing resources. The final project directions will be available starting the first week of class. There will be a mid-semester update due on October 24th, worth 30 out of the total 90 points for the project. The final presentation is worth 30 points, and the final report and deliverables are worth 30 points.
As the semester advances, you will learn more tools and resources to help you with your final project, including NoSQL databases, serverless computing, and more.
Note that the final project does not require you to implement a generative language model; you may implement any ML or AI model that you choose.

### **Introduction**

Your group project this semester is a deep exploration of Machine Learning Operations, otherwise known as MLOps. Given the ever-increasing demand for AI and ML in business operations, this project will serve you as a project or product manager to better align business strategy with technological implementations. If your post-graduation goals are around data analytics, then this project will help you better understand how your models fit into business strategies and architectures, significantly increasing your ability to execute rapid delivery of models.

### **Directions**

Working in teams of 4, you will create a fictitious business case where the implementation of an AI or ML model will solve an important business problem. You’ll discuss the business problem in depth, choose a model that best serves that problem, define the specific task the model will achieve, define the dataset that will be used to train the model, and then implement the full end-to-end architecture using DigitalOcean infrastructure.

By the end of the semester, you will have a real-world, working inference endpoint for a model that solves a particular business challenge.

### **Project Goals:**

- Learn the foundational concepts of MLOps and how they map to each stage in the machine learning lifecycle.
- Compare costs for managed solutions vs. role-your-own approaches to MLOps.
- Implement a fully-functional end-to-end ML system in the cloud.
- Document and present your architecture in a final report and final presentation.

### **Key Deliverables:**

- Mid-term project update (30 points)
- End-of-semester presentation (30 points)
- End-of-semester report + working proof-of-concept (30 points)

### **A Note on the Use of DigitalOcean for Our Projects:**

Sustaining cloud resource usage over the course of a full semester is very costly; this is why the MIS department and DigitalOcean have paired up this semester to provide free cloud resources for use in our class.

There is an expectation that you will use DigitalOcean for all of your project resources. Although it is very important to learn how other CSPs implement MLOps, once you’ve worked through this project, you’ll be able to understand exactly what is going on “under-the-hood” of other MLOps platforms. Additionally, we will go over the major MLOps services offered by the hyper-scaler clouds during lectures. But this hands-on, brick-by-brick approach will give you much greater depth and understanding around not only what is being automated by hyper-scalers, but also determine if it’s worth the cost of using those platforms.This will allow you to make more informed financial decisions around the cost of deploying ML models in the cloud across different CSPs.

# Project Midterm Update

Your midterm update should reflect a half-semester of effort. The deliverable should be a two to three page update that identifies the following:

- Identify the business problem that you are trying to solve through the use of an ML model
- Which model you will be using and why
- The dataset that you will train your model on
- A draft architecture of your final project build
- Your next steps, identified roles, identified blockers or obstacles

At this stage in the semester, it would be a good idea to have fully trained your model once; this will help you understand the requirements of this model better. For example, were you able to train it on your local laptop? Did you run out of memory? Did you need more compute resources? If so, what was the minimally viable droplet size that let you fully train your model? If you used a Jupyter notebook to train your model, how can you think about refactoring that model code to be run as a service on a virtual machine. Have you tried containerizing it?

The midterm update is an opportunity for us to think critically together about how you can move your project forward to be successful at the end of the term. You should proactively identify any foreseen challenges you may run into when finalizing the architecture. You should indicate to the instructor and/or TA if you need some guidelines for operationalizing your model in the cloud.

***You are required to cite any sources you use throughout the course of the semester in your project work. Failure to cite your sources will result in a full letter grade deduction. Please use APA citation styles and guidelines.***

## Midterm Update Grading Rubric

| **Category** | **Description of Exemplary Work for Each Category** |
| --- | --- |
| **Presentation** | Clean formatting, clear and concise language, free of grammatical errors, architecture diagrams cleanly and neatly designed, section headers, page numbers, tables and figures labeled with meaningful names and numbers (i.e.: Table 1: Comparison of Machine Learning reference architectures) |
| **Business Goal/ Problem** | The business goal is clearly articulated and well-defined. The reasoning behind an ML-based approach to achieving this goal or solving the problem is established. |
| **Model** | The selected model is aligned with the business goal. Specifically, the model is designed to operate in the context of achieving the task outlined in the goal or problem statement. Ideally, the model has been trained once on the sample dataset to determine its usefulness for the business goal/problem statement. |
| **Dataset Selection and Data Requirements** | The dataset used to train the model has been selected and is well understood. It is clear that the team understands the data needs to solve the business problem and that the data fits the way the model operates. A database that matches the nature of the data has been identified (e.g., MongoDB for unstructured data, PostgreSQL for structure data, etc.) Preprocessing steps have been articulated and are being considered for implementation at training time and at inference time. |
| **Architecture** | The architecture has been well researched and a draft of the architecture is proposed. The architecture is described both using architectural diagrams and in prose. The team is able to articulate where the end-to-end lifecycle will require heavier compute, more bandwidth, etc. |
| **Implementation Strategy** | The team has thought through their strategy for implementing their end-to-end system. They’ve identified strengths among the team that will help them achieve their end-of-semester goals. Next steps and timelines are present. Potential obstacles and blockers are identified. If the team needs additional support, they have clearly identified the kind of help they would like. |
| **Citations/ Works Cited** | Citations are present and are thoughtfully used to inform this work. All materials used to |

## Final Presentation Grading Rubric

| **Category** | **Description of Exemplary Work for Each Category** |
| --- | --- |
| **Overall Presentation Skills** | Each team member feels confident in presenting; each team member presents content that makes both the content and the team member shine. The presentation is engaging and well rehearsed. There is room for personality in the presentation. Memes are not required, but are not frowned upon either. |
| **Presentation Style** | Teams may choose two paths for presenting: the first is to do a traditional presentation as if presenting to business stakeholders. The second path is to present as if this were a conference talk. There are key differences between these styles. Giving an engaging conference talk will look very different to giving a business stakeholder presentation. Either scenario is very difficult. Please think about your professional goals and choose an option that best fits your goals. |
| **Presentation Content** | The presentation flows from one slide to the next. Section breaks make sense in the order in which they occur. The content is presented such that audience members (your peers) are engaged and are learning new strategies, techniques, approaches, or technical skills from you. The sections are appropriate in length (e.g., the architectural choices you make are front and center- this isn’t a data analytics course, so there’s no need to go into depth about the model design or data, unless it needs to be covered in more depth in order to justify the architecture.) |
| **Audience Behavior** | Being a good audience member for your fellow classmates is a requirement for the final presentations. Be the audience you wish to have! If you do not attend other students presentations, if you are talking through them, if you’re on your phone, etc. we will notice. You will not receive full marks for your own presentation if you cannot be supportive of others. |