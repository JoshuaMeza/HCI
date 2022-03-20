# Specify user requirements

## Table of contents

- [Requirements definition](#requirements-definition)
  - [Functional](#functional)
  - [Non-functional](#non-functional)
  - [Use case diagrams](#use-case-diagrams)
    - [Use case #1](#use-case-1)
    - [Use case #2](#use-case-2)
    - [Use case #3](#use-case-3)

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

### Use case diagrams

#### Use case #1

#### Activities
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


#### Use case #2

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


#### Use case #3

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


> [👈 Go back.](../specs.md)
