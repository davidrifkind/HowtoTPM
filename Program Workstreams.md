## 

| Author | David Rifkind | Github: davidrifkind david.rifkind@gmail.com |
| :---- | :---- | :---- |
| **Version** | 1.0 | Initial content |
|  |  | Request for Comment: [sharanya.iyer.ks@gmail.com](mailto:sharanya.iyer.ks@gmail.com) |

## Creating Workstreams (or Tracks) for a Large Scale Technical Programs

Before we begin discussing how to create workstreams for a large scale technical program it’s necessary to talk through some details of the program lifecycle. The program lifecycle is similar in nature to the so-called project lifecycle. 

The project life cycle generally defines phases that a project goes through. In my personal experience as a technical program manager I have see the project lifecycle used with both the Agile and Waterfall methodologies. In fact, at many larger tech companies there is a blend of Agile and Waterfall methodologies to deliver most programs (we can elaborate on this later so as to maintain focus on lifecycle).Before we define each phase, let’s actually define the word “Phase” itself. Phase refers to a specific period of time of the project where key activities need to take place. To get through a phase of the project you need to close the tasks that the phase is set to accomplish. Most phases of a project are for a specific goal. For example, the goal of the initiation phase is to establish the project, understand the project scope, do high-level analysis, understand what the key deliverables are, create a stakeholder map, create a project initiation document and ultimately get approval (or budget) for the project's implementation phase.

At this point you may be wondering why this is a project lifecycle and not a program lifecycle. I’ll cover this in another document, but briefly the difference is that a program lifecycle is larger. Almost exactly the same phases but it is larger in scope as a program manages multiple projects.

 Let’s take a look at the different phases. Keep in mind this is a general, high-level view. 

**Project Phases:**

| Phase | Definition (or Goal)  and Key Activities  |
| :---- | :---- |
| Initiation (also called discovery) May include planning as one phase | Establishment of program Define what the program needs to achieve Define business goals and value Define program scope Define metrics to measure the program and deliverables Stakeholder analysis Program Initiation Document Program kick-off meeting and approval for implementation |
| Planning | Implementation Plan Program schedule Commitment from teams for program related work Establish Jira plan Planning for 3rd parties involved in the program Security review Legal review Review overall plan for approval  |
| Execution (also called implementation) | Execution of the implementation plan TPM will monitor, escalate issues and unblock teams to keep program on track Delivery of the implementation plan. Deliverables and monitoring of metrics to confirm the business impact the program established in the initiation phase  |
| Closing | Close the program, finalize remaining budget Close budget Establish incomplete deliverables (perhaps for a phase 2\) Create production plans Retrospective |

Within each phase there are many tasks for the TPM to work on. For the purposes of the topic of the workstreams we’ll focus on the initiation / planning phase.

## Creating Workstreams (aka Tracks) for the Program

The easy way to get started with workstreams within your program is to do a pre-mortem of what you need to accomplish in each phase of the program lifecycle. Let’s take initiation for example. 

As a program team is given a program to start it enters the initiation phase without knowing what it needs to ultimately build. There may be a vision or prior art written by someone in the team which would be helpful to have but often there is not.

Thinking through this the TPM needs to start organizing: what do we need to figure out? What do we neee to come out of this phase with such that the program team knows:

* What the final deliverable is  
* What the vision is  
* What the business value is  
* How to baseline the existing problem with data   
* What the plan is  
* Approvals  
* Budget  
* Schedule and long term plan   
* Detailed analysis, sketches, anything else that will define the scope of the program   
* Define the requirements  
* Stakeholders   
* Working group formation  
* Steering committee formation  
* Weekly status document templates  
* Roles and responsibilities   
* How to report risks and issues  
* How to escalate   
* How to approve changes   
* Documentation location 

The above is a general non-exhaustive list of things that the program team together with the TPM will need to work through in the initiation phase before implementation can kick off.

Taking the above tasks and generalizing them into workstreams for illustrative purposes we could loosely describe the program for Initiation as:

1. Vision and value Analysis \- baseline of current state   
2. Program administration  
3. Requirements discovery  
4. Program steerco and working group formation  
5. Scope Analysis and to-be state  
6. MVP (possibly depending on context and situation)  
7. Program Approvals 

Each one of these workstreams comes with a description, a set of deliverables and a way to measure the work with metrics. Ultimately ending with a table similar to the below.

Phase, track, deliverable, metric, driver

Now that you have the above table, you have the basic formation of the program. This is no small feat for the TPM to accomplish and takes extensive work in most large scale programs. 

## Important Note About Workstreams

Importantly this model of working on a program is different depending on the culture of the company and the program team. There is certainly a world where teams will want to take a more agile approach and there is nothing wrong with that. I believe the structure of how that works is very different and will take a large commitment to follow this methodology. Keeping in mind that most large scale tech programs are almost run as a side project. Engineers have day jobs that can be as simple as keeping the lights on (KTLO) and it takes priority over the program, especially in the initiation phase. So weaving the program into a sprint cycle or multiple sprint cycles takes dedication from the TPM to work.

I also want to call out that by defining workstreams, I am effectively saying that each workstream is a project by itself and mostly independent of other workstreams. But like any program these projects will be interconnected and have dependencies. 

The reason why most programs prefer an almost waterfall approach is because workstreams move at their own pace as projects. Some may run as waterfall, some may run as agile and from a program point of view it doesn’t really matter. Again, the TPM is running the overall  program\! Showing management how that works and looks (especially for status) is a lot harder than it sounds at first blush.

Workstreams can have their own leadership, in some cases, and can be faster or slower than other workstreams. As a TPM,  managing all the workstreams and weaving them together will require you to be a master of how the organization works (which TPMs are not, there are no wizards here). Instead the TPM delegates this task to the driver of the workstream and manages the program as a whole. This frees the TPM up to do the heavy program lifting and ultimately separate themself out from the mundane day to day of driving each individual workstream. I don’t encourage you to stay workstream agnostic, you must keep close to the workstreams and monitor them, however getting into the day to day mundane nature of running each one (I.e. taking tasks to drive the deliverable when it is not your role to do so) means you will be bogged down in ensuring the success of 1 or 2 and not all. 

Lastly, that doesn’t mean you cannot be fluid. If something isn’t working, if a workstream is broken or going red, jump-in and go deep. A program is only as strong as its TPM. The initiation phase is one of the busiest times for the TPM exactly because the TPM needs to establish these workstreams with strong context in order for them to succeed.

## Workstreams by Example

A few years ago there was a large vulnerability discovered in the log4j library that is widely used in Java based applications for logging application related activities. 

While taking this as an example does limit us from an example point of view it provides the opportunity to have a concrete set workstreams showcased as an example to help you form yours. In addition this is a problem I worked on directly in my role as a TPM and have first hand experience going across a large company to fix it (it wasn’t a pleasant experience).

Let’s put you as the TPM and management has handed you a directive to get the fix for log4j in place across the entire organization as quickly as possible. Here are some details of what you have been asked to do:

1. 

