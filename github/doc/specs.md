# 📋 Specification

## Table of contents

- [Project definition](#project-definition)
  - [Description](#description)
  - [Target users](#target-users)
  - [Objectives](#objectives)
- [Personas](#personas)
  - [Desired attributes](#desired-attributes)
    - [...](#)
  - [Research methods](#research-methods)
    - [Interview with experts](#interview-with-experts)
    - [Survey](#survey)
  - [Results](#results)
- [Requirements definition](#requirements-definition)
  - [Non-functional](#non-functional)

## Project definition
This proyect is aiming to fight negative effects that social isolation has cause during the course of the pandemic using a diary that allows people to write, draw and paste different images while at the same time releasing their negative emotions and helping them be more relaxed lifestyle.

### Description

In this times, the pandemic has caused many problems around the people, not only healthy issues but social and psichologycal too, social isolation has caused symptoms of acute stress disorder, which means people in quarantine suffers from distress and psychological problems like anxiety, paranoia, insomnia, and others. To fight all of this psychological problems we want to develop a Diary app with different functions to help people express their feelings and other options like erasing the paper, throwing it to a trash can , burning it, all in all to releave the people of their own anxieties and stressful experiences.

### Target users
The target from this proyect are college students with a deteriortion in their academic performances due to emotional exhaustion or stress.
As for solutions, there are quite a lot of solutions, writing your experiences and organizing your ideas can detect whats causing their problems, music is a great way of relaxation, painting is a way you can express yourself and your emotions through art, etc. this proyect wants to integrate all of this things in a diary app.


### Objectives
Although there are multiple applications that are made to tackle feelings of stress and depression like Headspace and Dare, they normally have audio guides and textual sources to read but this doesnt include a therapeutic way to ventilate about your own feelings by writing or drawing and on the market there are certain cons that can propose a problem which is Not to be completly informed on these subjects, this app wants to overcome this problems so people have a better way of letting go of their feelings to make them feel better and have a good response on the people in a therapeutic way.



With all this in mind, this proyect wants to aim for a solution for all this many problems people tent to have in this times, not just because of the pandemic but because of its consequences, people expect a solution for their social isolation and psychological problems, they want to feel better and move on on their lives an sometimes is not easy for people to open up and talk about their problems with other people, they keep it private for themselves but at the same time they want to feel better anyway, this diary we think its a good solution to achieve this, one were people can express themselves anytime they want, everywhere they can.

## Personas
For this proyect we are aiming for people with social isolation problems with the pandemic but more efficiently were aiming for college students since they are a group of people with probably one of the most affected if not the most one, so we need different attributes that will help us discovered a more effective solution for our problematic, so we need to keep in mind what exactly we need to know:

- What do we expect for a solution?
- When and how would they like to use a solution?
- How much important is privacy for them?
### Desired attributes

#### Persona's Biographic Background
First we need to know about the persona's backstory, how they are and what they do and its online usage so attributes like this are what we need

- Age
- Education
- Attitudes
- Tenure of online usage
- Type of usage

#### Specific Goals/Needs/Attitudes
People want to achieve something in their lives and as for technology, people have different ways to work with it as well as how they act with it so we need this attributes:

- Frustrations
- Attitude towards technology used
- How is value defined

#### Context of Usage
People's ways to use the technology varies from others and its personalities, attitudes and environment can affect that on how they use technology:

- Surrounding environment
- Confidentiality/Privacy
- Satisfaction

#### Interaction Characteristics of Usage
We need to know the times people use technology:
- Frequency of use

#### Sensory/Immersive Characteristics of Usage
We also need attributes that can relate on what sort of thoughs people feel about technology:

- Mood/Feeling
- Pleasurable
### Research methods

#### Interview with experts

...

#### Survey

...

### Results

[Final persona]

## Requirements definition
### Functional

#### RF1:
- The system provides the user with activities that help reduce their stress level.
#### RF2:
- The system provides advice for taking a better care of mental health.
#### RF3:
- The system provides information about the relationship between having a healthy diet and keeping a good mental health.
#### RF4:
- The system will mention that it is not a substitute of profesional consultory or psychological therapy.
#### RF5:
- The system will have an activity that allows the user to write about their experiences or emotions.
#### RF6:
- The system will allow the user to make drawings in their annotations.
#### RF7:
- The system will have a community section where users can share their work or experiences.
#### RF8:
- The system must provide the user with notifications of new updates, activities and mental health information.
####RF9:
- The system must control access, only allowing it to authorized users
#### RF10:
- The system will have relaxing music in the background.

### Non-functional

#### RNF1:
- The information entered by users in the application must be completely confidential.
#### RFN2:  
- The application should be compatible with newer versions of the different systems that are made available in the future.
#### RFN3:
- People can use the diary/Application whenever need to , so it needs to be always available.
#### RFN4:
- The application should be accesible in different operating systems, such as Android and IOS.
#### RFN5:
- The application should have updated at least once per month
#### RFN6:
- People must be able to understand how to use the application by intuition, they are not supposed to spend more tan 20 seconds to find where to Access to any of the most representative features, starting in the principal menú, during their first-time use.
#### RFN7:
- Only the user can Access to their recorded experiences
#### RFN8:
- The information must always be encrypted, to guarantee the privacy of the user.
#### RFN9:
- The user can share their pages only if they want to.
#### RFN10:
- The application should have a size smaller tan 100 MB.
#### RFN11:
- The time of response on any of the functionalities on the application, excluding a saving process, should not take more than 1 second.

## Important Case Use Models
### Activities
|        | Selection of Activities                                | 
| :----: | :----------------------------------------------------- | 
| **Dependencies**  | •	RF – 05 Annotations about user experiences or emotions |
|               | •	RF – 06 History of activities carried out |
|               | •	RF – 07 Share content |
| **Precondition** | The user has entered the system through his username and password and has decided to perform an activity.|
| **Description** | The system will provide the user with a series of activities that they can choose to de-stress or distract themselves. |
| **Normal Sequence**  |  **Action** |
|    **1** |   The system displays the activities that are available   |
|    **2** |   The system displays a brief description of the activity |
|    **3** |   The user confirms the activity to be performed   |    
|    **4** |   The system loads the activity  |
|    **5** |   The user can now interact with the elements of the activity |
| **Postcondition** | The user performs the activity I select, and the system saves the progress of the activity.|

![Diagram picture](https://github.com/JoshuaMeza/HCI/blob/AlejandroCauich/github/img/Mental%20Health%20App%20Diagram%201.jpeg)

### Information
|        | Mental Health Care Information | 
| :----: | :----------------------------------------------------- | 
| **Dependencies**  | 	RF – 04 reminder that the app does not replace traditional therapy  |
|               | •	RF – 07 Share content |
| **Precondition** | The user has entered the system through his username and password and wants to consult information about mental health. |
| **Description** | The system will provide different tips, notes or information related to the topic of mental health. |
| **Normal Sequence**  |  **Action** |
|    **1** |   The system displays a menu of options    |
|    **2** |   The user goes to the information section |
|    **3** |  The user selects the note that attracts the most attention    |    
|    **4** |  The system loads the selected item   |
| **Postcondition** |The user can now read the selected information. |

![Diagram picture](https://github.com/JoshuaMeza/HCI/blob/AlejandroCauich/github/img/Mental%20Health%20App%20Diagram%202.jpeg)

### Security
|        | Security & Privacy                            | 
| :----: | :----------------------------------------------------- | 
| **Dependencies**  | RNF – 01 Information entered by users must be confidential |
|               | • RNF – 07 Only the user can access their recorded experiences |
|               | • RNF - 08  Information must be encrypted |
|               | • RF - 09 The system can be accessed by authorized users |
| **Precondition** | The user has performed multiple activities on the system, placing experiences and sensitive information. |
| **Description** | The system will save the information in a database to which only the user will have access. |
| **Normal Sequence**  |  **Action** |
|    **1** |   The user performs some of the activities    |
|    **2** |   The system analyzes the information entered by the user |
|    **3** |   The system encrypts the information  |    
|    **4** |   The system saves the information in a database  |
|    **5** |   The user accesses this information only if he enters his username and password |
| **Postcondition** |The user can consult the annotations he has made previously without the concern that his data can be exposed if he does not wish.|

![Diagram picture](https://github.com/JoshuaMeza/HCI/blob/AlejandroCauich/github/img/Mental%20health%20app%203.jpg)
> [👈 Go back.](./index.md)
