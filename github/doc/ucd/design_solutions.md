# Design solutions

## Table of contents

- [Transforming requirements to UI](#transforming-requirements-to-ui)
  - [Introduction](#introduction)
  - [Deriving Concrete Requirements from Essential Requirements](#deriving-concrete-requirements-from-essential-requirements)
  - [Identifying Task Objects, Attributes, and Actions](#identifying-task-objects-attributes-and-actions)
    - [Task Objects](#task-objects)
    - [Attributes](#attributes)
    - [Actions](#actions)
  - [Marking Up the Concrete Requirements to Identify Task Objects, Their Attributes, and Actions](#marking-up-the-concrete-requirements-to-identify-task-objects-their-attributes-and-actions)
  - [Prototyping Task Objects, Attributes, and Actions](#prototyping-task-objects-attributes-and-actions)
  - [Creating the content diagram](#creating-the-content-diagram)
  - [Guidelines for a low fidelity user interface](#guidelines-for-a-low-fidelity-user-interface)
- [Project application](#project-application)
  - [Structure prototype](#structure-prototype)
    - [Use case 1](#use-case-1)
    - [Use case 2](#use-case-2)
    - [Use case 3](#use-case-3)
    - [Final content diagram](#final-content-diagram)
    - [Interaction design](#interaction-design)
  - [User interface](#user-interface)
    - [Low fidelity](#low-fidelity)
    - [Mid fidelity](#mid-fidelity)
    - [Usability test](#usability-test)

## Transforming requirements to UI

### Introduction

For this task, a design process known as Conceptual Design described in the book User Interface Design and Evaluation (Jarret, Minocha, Stone & Woodroffe, 2005, pp. 144-164) was applied, it consists of doing four main tasks to develop a low fidelity prototype, called content diagram, that represents the organization and structure of the user interface from a designer’s perspective. The activities are the following:

1. Derive the concrete use cases from the essential use cases.
2. Identify the primary task objects, attributes, and actions.
3. Identify the different containers and the task objects that go into each one.
4. Link the containers to show the navigation flow.

In the next sections you will see the complete process for this strategy (that is a summary of the book), but you can also check a [presentation](https://alumnosuady-my.sharepoint.com/:p:/g/personal/a16001575_alumnos_uady_mx/ESMxwAdWWfFFh95xA3KL0oMBt4aHz71UgKOVQyoew-J3Hg?e=HJ72DP) made by the team that goes step by step implementing the entire procedure.

### Deriving Concrete Requirements from Essential Requirements

Create a table, on one side is the requirement and its counterpart has the output or the behavior of the system based on said requirement, for example:

![Diagram picture](../../img/requirements_table.png)

### Identifying Task Objects, Attributes, and Actions

The next step is to identify the task objects, their attributes, and the actions the user will perform on them. These details will influence what goes into each of the containers in the content diagram and the links needed between the containers.

#### Task Objects

Primary task objects are the units of information or data with which the users interact to carry out their tasks. They are high-level objects, central to the tasks the users will be carrying out. Typically, there are only a few primary task objects, and they are easy to identify. For example, if you were designing a UI for a hotel registration system, there would probably be only two primary task objects: one corresponding to the customer, the other to the room.
These task objects will typically be translated onto your UI design as combinations of user interface objects, such as screens, windows, dialog boxes, pull-down menus, icons, combo boxes, and so on. In embedded systems, such as mobile telephones, these may take the form of physical buttons and other simple input devices, plus output on the screen.

#### Attributes

A task object must have attributes. If a task object does not have any attributes, it is not an object but rather the attribute of another task object. For example, for the hotel registration system the number of people who can occupy a hotel room is an attribute of the room object rather than an object. There are two kinds of attributes:

- **Properties**. For example, in the digital library title and author are properties of the book task object.
- **Child objects**. These are task objects. For example, an attribute could indicate who owns a CD-ROM. The owner could be an academic, making the academic task object a child object of the CD-ROM task object. It is a task object because it has its own attributes, such as the name of the academic, his e-mail address, and so on.

This relation can influence the design process, as visual containment results when an attribute is a child object. In user interface design, this means that when the task object is displayed on a screen, the child object will also be displayed on the same screen.

#### Actions

When users carry out their tasks, they perform various actions on the task objects. For example, in the hotel registration system, the receptionist will want to allocate guests to rooms.
This means the room task object will need to have a corresponding allocation action. You can identify these actions by reviewing the concrete requirements. In addition, you should consider standard actions such as view, create, delete, copy, save, edit, and print.

### Marking Up the Concrete Requirements to Identify Task Objects, Their Attributes, and Actions

- Single-underline nouns that you think may correspond to task objects.
- Double underline the attributes of these task objects.
  Verbs often correspond to actions. We do not suggest marking these up as the relationships are often less direct. However, identifying the verbs can still be useful.

![Diagram picture](../../img/requirements_table3.png)

You can see from the markup that we have identified the academic, research student, and CD-ROM task objects. In addition, by implication we have identified e-mail, a further task object. This is not mentioned explicitly, but two of its attributes are email address and message area. We have also identified the title, year, and platform attributes of the CD-ROM task object.
Once you have identified the task objects and attributes, it is helpful to compile them, along with the actions, into a single object–action–attribute table.
The actions are the standard actions, plus the reserve action, which allows the member to indicate that the CD-ROM has been reserved. You should note that the actions relate to the CD-ROM details in the digital library system, rather than to the CD-ROM itself. Thus, the table indicates that it is possible to edit these details, but it does not say it is possible to alter the CD-ROM itself.

![Diagram picture](../../img/requirements_table4.png)

![Diagram picture](../../img/requirements_table5.png)

![Diagram picture](../../img/requirements_table6.png)

### Prototyping Task Objects, Attributes, and Actions

Before continuing, it is important to notice that some of the task objects, attributes, and their actions may not necessarily come from the concrete use cases but rather from the users’ knowledge of the domain or from your own domain analysis, so the best approach is to prototype your ideas, working alongside potential users of the system.
That said, one way is using sticky notes. Write a one-sentence definition of the task object on one sticky note, the task object’s properties on another, the actions that can be applied to it on a third, and divide a fourth note into two columns, one that is headed with “I’m in” and the other one with “In me”, and write there any parent and child objects, respectively, that are related to this task object. Once done, place them together.

![Diagram picture](../../img/requirements_post.png)

### Creating the content diagram

The next step is to identify the containers that are needed for the content diagram. Each container collects functions and task objects into a coherent place in the system to support a part of the user’s work. Typically, these become screens, windows, dialog boxes, or message boxes in the UI. We also need to identify the links between the containers, that indicate the navigation around the user interface.

The first container we need to specify is the main container. This represents the first thing the users encounter and will be central to their work, so the parts that must be there include:

- **Vital tasks**: The user must perform these tasks quickly, even under stress.
- **Frequent tasks**: Those tasks that users spend most of their time performing must be fast to access.
- **Navigation aids**: The users need to understand quickly and easily what the application can do and how to accomplish their tasks.

Typically, the section of the UI corresponding to the main container will not perform any of these tasks, instead, it will provide links to the containers that do. Other containers are usually derived from the concrete use cases, in which each of them shows the sequence of steps needed to accomplish a particular task, and every functionality that makes possible accomplishing that task can be divided into one or more containers.
Finally, once we have identified the containers, we need to link them together to reflect the navigation flow (according to the concrete use cases). If any conditions determine the navigation flow to a particular container, label the arrow.

|     Defining containers and linking      |         Generating content diagram          |            User interface proposal            |
| :--------------------------------------: | :-----------------------------------------: | :-------------------------------------------: |
| ![Diagram picture](../../img/clases.png) | ![Diagram picture](../../img/container.png) | ![Diagram picture](../../img/ui_template.png) |

The template used for defining containers is the next one:

| **Name**                        | Container’s name                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| :------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Purpose**                     | A phrase indicating its purpose in supporting the user’s task.                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Functions**                   | - Functions invoked by the user. <br> - Functions invoked automatically by the system.                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Links**                       | The links with other containers, indicating the name of the container linked to and its purpose. There are two types of links: <br> **Single links**: A single link indicates that the user moves to another container and then that new container becomes the focus of the user’s activities. <br> **Double links**: A double link indicates that the work done in a second container needs the context of the first container and that the user will switch back and forth between the two; |
| **Objects**                     | The task objects whose attributes and actions are required for the users to complete their tasks.                                                                                                                                                                                                                                                                                                                                                                                             |
| **Non-functional requirements** | Any constraints of the container.                                                                                                                                                                                                                                                                                                                                                                                                                                                             |

### Guidelines for a low fidelity user interface

In the case of designing user interfaces, you probably would like to use a standard style that could make the user feel more comfortable while using your solution. You can try the following guidelines if you want:

- [Style guides.](https://www.mockplus.com/blog/post/ui-style-guide)
- [Layouts.](https://xd.adobe.com/ideas/principles/web-design/11-website-layouts-that-made-content-shine-in-2019/)
- [Icons.](https://www.redhat.com/en/about/brand/standards/icons/standard-icons)

## Project application

### Structure prototype

#### Use case 1

...

#### Use case 2

...

#### Use case 3

...

#### Final content diagram

...

#### Interaction design

...

### User interface

#### Low fidelity

...

#### Mid fidelity

...

#### Usability test

a) Selection of Usability NFR:

The objectives of this test are the following:

1. Determine if users who will use the Software product will be satisfied with the functionality and performance of the Software.
2. Decrease the probability that the user of the Software product will not experience any user interface problems during use.
3. Know the user's learnability in terms of how quickly they learn to use the system.
4. Determine the ease of use of the system.
5. Obtain the rate of effectiveness of performing the tasks, related to the effort required to learn and operate the system.

To achieve them, the following non-functional requirements were selected, which are part of the system:

* NFR6: People must be able to understand how to use the application by intuition, they are not supposed to spend more tan 20 seconds to find where to access to any of the most representative features, starting in the principal menu, during their first-time use.

* NFR13: The system will have a user tutorial on each of the activity or information search sections.

* NFR15: In case of error or bad behavior, the system must display an alert to notify the user of this behavior.

* NFR16: The rate of errors made by the user should be no more than 10% of system functionalities.

* NFR17: The system will ask the user about their level of satisfaction in the use of an activity after completing any of them.

b) Test Planning:

In general, the tests are expected to be applied to 5 people each, trying to apply it to different people, although in the same quantity, for those whose condition of application conflicts with others.

During the test, in terms of users, different scenarios may occur that could affect their performance in the use of the application, these are:

* The user has ever used an application with similar functionalities or several that have at least one of them, so he knows how to use them.

* The user has no experience in handling this type of functions and her learning curve is the most interesting.

In general, each metric should contain the following elements:

* Metric, object and measurement attribute

* Methodology

* Measurement time

* Personnel, roles and responsibilities

* Activities Calendar

* Used tools

* Data storage media

* Measurement procedure

* Criteria for suspension and resumption

* Results reports

* Analysis of results

* Conclusions

Because each metric to be used has materials, times, instruments or tools, these sections are described for each of them.

c) Usability Metrics and Usability Test Protocol

To choose the metrics to apply, a scheme of questions was followed, whose answers would be the metrics that would help us answer them, presented below:

• How easy is it to use? Referring to the ease that users have to perform the tasks of the application.

  - Efficiency based on time

  - Effectiveness rate of performing tasks

  - Number of user errors

  - Simplicity level of the interface

• How easy is it to learn? Related to how intuitive the system is so that the user knows how to use it in the shortest time possible.

  - Number of user errors

  - Interface satisfaction level

• How satisfactory is its use? In relation to the impression of the users when using the application and the simplicity of using it.

  - Simplicity level of the interface

  - Interface satisfaction level

• How quickly can the task be completed? In order to determine how much time was needed to invest to do the required activities.

  - Efficiency based on time

• How intuitive is the interface? In relation to the speed and ease of the user to understand how the application works.

  - Effectiveness rate of performing tasks

  - Number of user errors

  - Simplicity level of the interface
  
 In the following link you will find the document that contains the description of the metrics with the mentioned sections and the data collection artifacts for them:
* https://alumnosuady-my.sharepoint.com/:w:/g/personal/a16000959_alumnos_uady_mx/EZXQc20Onw1KkheW2tqq6m4BHy7FZHxMO8IiVCFKYoCEBA?e=fiv9bd

> [👈 Go back.](../specs.md)
