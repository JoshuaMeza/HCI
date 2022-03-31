# Design solutions

## Table of contents

- [Transforming requirements to UI](#transforming-requirements-to-ui)
  - [Deriving Concrete Requirements from Essential Requirements](#deriving-concrete-requirements-from-essential-requirements)
  - [Identifying Task Objects, Attributes, and Actions](#identifying-task-objects-attributes-and-actions)
    - [Task Objects](#task-objects)
    - [Attributes](#attributes)
    - [Actions](#actions)
  - [Marking Up the Concrete Requirements to Identify Task Objects, Their Attributes, and Actions](#marking-up-the-concrete-requirements-to-identify-task-objects-their-attributes-and-actions)
  - [Prototyping Task Objects, Attributes, and Actions](#prototyping-task-objects-attributes-and-actions)
  - [Creating the content diagram](#creating-the-content-diagram)
- [Project application](#project-application)

## Transforming requirements to UI

For this task, a design process described in the book User Interface Design and Evaluation (Jarret, Minocha, Stone & Woodroffe, 2005, pp. 144-164) was applied, it consists of doing four main tasks to develop a low fidelity prototype, called content diagram, that represents the organization and structure of the user interface from a designer’s perspective. The activities are the following:

1.	Derive the concrete use cases from the essential use cases.
2.	Identify the primary task objects, attributes, and actions.
3.	Identify the different containers and the task objects that go into each one.
4.	Link the containers to show the navigation flow.


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

* **Properties**. For example, in the digital library title and author are properties of the book task object. 
* **Child objects**. These are task objects. For example, an attribute could indicate who owns a CD-ROM. The owner could be an academic, making the academic task object a child object of the CD-ROM task object. It is a task object because it has its own attributes, such as the name of the academic, his e-mail address, and so on. 

This relation can influence the design process, as visual containment results when an attribute is a child object. In user interface design, this means that when the task object is displayed on a screen, the child object will also be displayed on the same screen. 

#### Actions

When users carry out their tasks, they perform various actions on the task objects. For example, in the hotel registration system, the receptionist will want to allocate guests to rooms. 
This means the room task object will need to have a corresponding allocation action. You can identify these actions by reviewing the concrete requirements. In addition, you should consider standard actions such as view, create, delete, copy, save, edit, and print.

### Marking Up the Concrete Requirements to Identify Task Objects, Their Attributes, and Actions

* Single-underline nouns that you think may correspond to task objects. 
* Double underline the attributes of these task objects.
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
*	**Vital tasks**: The user must perform these tasks quickly, even under stress.
*	**Frequent tasks**: Those tasks that users spend most of their time performing must be fast to access.
*	**Navigation aids**: The users need to understand quickly and easily what the application can do and how to accomplish their tasks.
Typically, the section of the UI corresponding to the main container will not perform any of these tasks, instead, it will provide links to the containers that do. Other containers are usually derived from the concrete use cases, in which each of them shows the sequence of steps needed to accomplish a particular task, and every functionality that makes possible accomplishing that task can be divided into one or more containers.
Finally, once we have identified the containers, we need to link them together to reflect the navigation flow (according to the concrete use cases). If any conditions determine the navigation flow to a particular container, label the arrow.

| Defining containers and linking | Generating content diagram | UI proposal |
| ![Diagram picture](../../img/clases.png) | ![Diagram picture](../../img/container.png) | ![Diagram picture](../../img/ui_template.png) |

The template used for defining containers is the next one:

| **Name** | Container’s name |
| **Purpose** | A phrase indicating its purpose in supporting the user’s task. |
| **Functions** | *	Functions invoked by the user. *	Functions invoked automatically by the system. |
| **Links** | The links with other containers, indicating the name of the container linked to and its purpose. There are two types of links:
**Single links**: A single link indicates that the user moves to another container and then that new container becomes the focus of the user’s activities.
**Double links**: A double link indicates that the work done in a second container needs the context of the first container and that the user will switch back and forth between the two; | 
| **Objects** | The task objects whose attributes and actions are required for the users to complete their tasks. |
| **Constraints** | Any constraints of the container. | 



## Project application

...

> [👈 Go back.](../specs.md)
