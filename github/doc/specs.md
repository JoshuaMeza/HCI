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

### Description

...

### Target users

...

### Objectives

- ...

## Personas

### Desired attributes

#### [Subgroup]

- Attr

### Research methods

#### Interview with experts

...

#### Survey

For data recollection we ran a survey. This survey can be found at: https://forms.gle/2poaXFQafX54xezw8  
The survey consists of 18 questions, 7 of which are open-ended questions, 10 are closed and 1 is hybrid.  
The questions are the following:  
- 1. ¿Cuántos años tienes? 
- 2. ¿Cómo te ha afectado emocionalmente el distanciamiento social ocasionado por la pandemia? 
- 3. ¿Ha vivido alguna situación que le haya resultado especialmente frustrante o estresante durante el aislamiento social de la pandemia? Por favor, describa a su criterio cuáles han sido dichas ocasiones. 
- 4. Durante este tiempo, ¿has llegado a intentar alguna de las siguientes estrategias como método para desestresarte? Si ninguna coincide con tus experiencias o te gustaría comentar alguna otra, siéntete libre de añadir una nueva opción. 
- 5. En el supuesto caso de llegar a vivir o haber atravesado una situación muy complicada a nivel personal o emocional, ¿llegarías a considerar asistir a terapia o consultoría con algún experto del área de la salud mental para recibir ayuda? 
- 6. ¿Por qué decidiste o no asistir a terapia? (Problemas económicos, falta de confianza, otros) Comparte tu opinión si es posible. 
- 7. ¿Se considera una persona que utiliza con frecuencia su dispositivo móvil? 
- 8. ¿Para qué usa normalmente su dispositivo móvil? 
- 9. ¿Qué considera invaluable al emplear una aplicación o servicio en línea? 
- 10. ¿Alguna vez has empleado alguna aplicación o servicio en línea diseñado para ayudar a las personas a sentirse mejor emocionalmente? Por favor, responda si lo ha hecho y, en caso afirmativo, agradeceríamos que nos cuente su experiencia usándola (sea positiva o negativa). 
- 11. ¿Considera que las aplicaciones o servicios en línea anteriormente mencionados proporcionan algún tipo de ayuda real a sus usuarios? 
- 12. ¿Por qué considera lo anterior? 
- 13. ¿Usted le llegaría a dar una oportunidad a una aplicación de ese estilo? 
- 14. ¿Qué debería tener una aplicación o servicio de este estilo para que te sea de lo más agradable de usar? 
- 15. ¿Dónde se sentiría más cómodo(a) empleando una aplicación de ese estilo? 
- 16. ¿Qué tan seguido emplearía una aplicación o servicio en línea de ese estilo? Las siguientes cantidades de tiempo están pensadas para ser por día. 
- 17. ¿Cuáles son las consideraciones más importantes de privacidad que te gustaría que una aplicación de ese estilo emplee? 
- 18. Si tienes alguna sugerencia para el proyecto, se agradecería mucho. 

In this next section we declare the relation of these aforementioned questions inside the survey with the attributes to obtain, as well as other useful things to have in mind.

- What do they expect from a solution?

- - ¿Considera que las aplicaciones o servicios en línea anteriormente mencionados proporcionan algún tipo de ayuda real a sus usuarios?
- - - Unconciously, the user expects that the solution helps in a meaningful way their users

- - ¿Qué debería tener una aplicación o servicio de este estilo para que te sea de lo más agradable de usar?
- - - Unconciously, the user expects that the solution includes the expected desirable qualities

- When and how would they like to use the solution?

- - ¿Se considera una persona que utiliza con frecuencia su dispositivo móvil?
- - - If the user uses their mobile device with great frequency, they expect that the solution is available for it.

- - ¿Dónde se sentiría más cómodo(a) empleando una aplicación de ese estilo? 

- How much important is privacy for them?

- - ¿Qué debería tener una aplicación o servicio de este estilo para que te sea de lo más agradable de usar? 
- - - The user can choose if privacy is valuable for them.

- - ¿Dónde se sentiría más cómodo(a) empleando una aplicación de ese estilo?
- - - Depending on the answer, we can imply that if the user chooses a private place rather than a public one, that they value privacy.

- - ¿Cuáles son las consideraciones más importantes de privacidad que te gustaría que una aplicación de ese estilo emplee? 

- Age

- - ¿Cuántos años tienes? 

- Education

This survey is aimed for current university students

- Attitudes

- - ¿Cómo te ha afectado emocionalmente el distanciamiento social ocasionado por la pandemia?
- - - This question could tell us about the user's attitude towards their current situation

- - Ha vivido alguna situación que le haya resultado especialmente frustrante o estresante durante el aislamiento social de la pandemia? Por favor, describa a su criterio cuáles han sido dichas ocasiones. 
- - - This question could tell us about the user's attitude towards their current situation and other external factors related to it

- - Durante este tiempo, ¿has llegado a intentar alguna de las siguientes estrategias como método para desestresarte? Si ninguna coincide con tus experiencias o te gustaría comentar alguna otra, siéntete libre de añadir una nueva opción
- - - This question could tell us about the user's attitude towards searching for a solution on their own.

- - En el supuesto caso de llegar a vivir o haber atravesado una situación muy complicada a nivel personal o emocional, ¿llegarías a considerar asistir a terapia o consultoría con algún experto del área de la salud mental para recibir ayuda?
- - - This question could tell us about the user's attitude towards searching for a solution that is outside their comfort zone 

- - ¿Por qué decidiste o no asistir a terapia? (Problemas económicos, falta de confianza, otros) Comparte tu opinión si es posible.
- - - This question could tell us about the users attitude towards their current situation, their willingness to search for a solution of their own that is outside their comfort zone and the reasons why they gave up to it.

- - ¿Se considera una persona que utiliza con frecuencia su dispositivo móvil? 
- - - Depending on the answer, this question could tell us about the attitude of the user towards their current situation

- - ¿Para qué usa normalmente su dispositivo móvil?
- - - Depending on the answer, this question could tell us about the attitude of the user towards their current situation 

- Tenure of online usage 

- - ¿Se considera una persona que utiliza con frecuencia su dispositivo móvil? 
- - ¿Qué tan seguido emplearía una aplicación o servicio en línea de ese estilo? Las siguientes cantidades de tiempo están pensadas para ser por día. 

- Type of usage

- - ¿Para qué usa normalmente su dispositivo móvil? 
- - ¿Alguna vez has empleado alguna aplicación o servicio en línea diseñado para ayudar a las personas a sentirse mejor emocionalmente? Por favor, responda si lo ha hecho y, en caso afirmativo, agradeceríamos que nos cuente su experiencia usándola (sea positiva o negativa). 

- Frustrations

- - ¿Cómo te ha afectado emocionalmente el distanciamiento social ocasionado por la pandemia? 
- - ¿Ha vivido alguna situación que le haya resultado especialmente frustrante o estresante durante el aislamiento social de la pandemia? Por favor, describa a su criterio cuáles han sido dichas ocasiones. 
- - ¿Por qué decidiste o no asistir a terapia? (Problemas económicos, falta de confianza, otros) Comparte tu opinión si es posible. 
- - ¿Alguna vez has empleado alguna aplicación o servicio en línea diseñado para ayudar a las personas a sentirse mejor emocionalmente? Por favor, responda si lo ha hecho y, en caso afirmativo, agradeceríamos que nos cuente su experiencia usándola (sea positiva o negativa). 
- - ¿Considera que las aplicaciones o servicios en línea anteriormente mencionados proporcionan algún tipo de ayuda real a sus usuarios? 
- - ¿Por qué considera lo anterior? 
- - ¿Qué debería tener una aplicación o servicio de este estilo para que te sea de lo más agradable de usar? 
- - - The opposite of the answers are factors to frustrate the users.

- Attitude toward technology used

- - ¿Se considera una persona que utiliza con frecuencia su dispositivo móvil? 
- - ¿Para qué usa normalmente su dispositivo móvil? 
- - ¿Alguna vez has empleado alguna aplicación o servicio en línea diseñado para ayudar a las personas a sentirse mejor emocionalmente? Por favor, responda si lo ha hecho y, en caso afirmativo, agradeceríamos que nos cuente su experiencia usándola (sea positiva o negativa).
- - - A positive answer shows a positive attitude towards the technology
- - ¿Usted le llegaría a dar una oportunidad a una aplicación de ese estilo? 
- - ¿Qué tan seguido emplearía una aplicación o servicio en línea de ese estilo? Las siguientes cantidades de tiempo están pensadas para ser por día. 

- How is value defined?

- - ¿Por qué decidiste o no asistir a terapia? (Problemas económicos, falta de confianza, otros) Comparte tu opinión si es posible.
- - - Depending on the answer we can extract the value for the user.
- - ¿Qué considera invaluable al emplear una aplicación o servicio en línea?
- - ¿Usted le llegaría a dar una oportunidad a una aplicación de ese estilo?
- - - If the answer is negative, we can imply that the user considers their time valuable.
- - ¿Qué debería tener una aplicación o servicio de este estilo para que te sea de lo más agradable de usar? 
- - ¿Cuáles son las consideraciones más importantes de privacidad que te gustaría que una aplicación de ese estilo emplee?

- Context of usage: Surrounding environment

- - ¿Dónde se sentiría más cómodo(a) empleando una aplicación de ese estilo? 
- - ¿Se considera una persona que utiliza con frecuencia su dispositivo móvil?
- - - In case the answer says high frequency of use, depending on the context, the convenience, the trust and other factors, the user can use the solution in other environments

- Context of usage: Confidentiality/privacy

- - ¿Por qué decidiste o no asistir a terapia? (Problemas económicos, falta de confianza, otros) Comparte tu opinión si es posible. 
- - ¿Qué considera invaluable al emplear una aplicación o servicio en línea? 
- - ¿Qué debería tener una aplicación o servicio de este estilo para que te sea de lo más agradable de usar? 
- - ¿Dónde se sentiría más cómodo(a) empleando una aplicación de ese estilo? 
- - - If a private place is chosen, we consider that the confidentiality or the privacy for the user is high
- - ¿Qué tan seguido emplearía una aplicación o servicio en línea de ese estilo? Las siguientes cantidades de tiempo están pensadas para ser por día.
- - - A very low frequency of use could indicate low trust, meaning that the users confidentiality is high
- - ¿Cuáles son las consideraciones más importantes de privacidad que te gustaría que una aplicación de ese estilo emplee? 

- Context of usage: Satisfaction

- - ¿Por qué decidiste o no asistir a terapia? (Problemas económicos, falta de confianza, otros) Comparte tu opinión si es posible.
- - - Depending on the answer we can know whether the user has tried alternative solutions thanks to current satisfaction.
- - ¿Qué considera invaluable al emplear una aplicación o servicio en línea? 
- - ¿Para qué usa normalmente su dispositivo móvil?
- - - Then the solution can mimic the types of apps the user normally uses so that they do not have to adapt to new things, and only focus on the content.
- - ¿Alguna vez has empleado alguna aplicación o servicio en línea diseñado para ayudar a las personas a sentirse mejor emocionalmente? Por favor, responda si lo ha hecho y, en caso afirmativo, agradeceríamos que nos cuente su experiencia usándola (sea positiva o negativa). 
- - ¿Considera que las aplicaciones o servicios en línea anteriormente mencionados proporcionan algún tipo de ayuda real a sus usuarios? 
- - ¿Por qué considera lo anterior?
- - ¿Qué debería tener una aplicación o servicio de este estilo para que te sea de lo más agradable de usar? 
- - ¿Qué tan seguido emplearía una aplicación o servicio en línea de ese estilo? Las siguientes cantidades de tiempo están pensadas para ser por día. 
- - - If the frequency of use is high, there is a predisposition to satisfaction
- - Si tienes alguna sugerencia para el proyecto, se agradecería mucho.  

- Interaction Characteristics of Usage: Frecuency of use 

- - ¿Se considera una persona que utiliza con frecuencia su dispositivo móvil? 
- - ¿Qué tan seguido emplearía una aplicación o servicio en línea de ese estilo? Las siguientes cantidades de tiempo están pensadas para ser por día. 

- Sensory/Immersive Characteristics of Use: Mood/Feeling 

- - ¿Cómo te ha afectado emocionalmente el distanciamiento social ocasionado por la pandemia? 
- - - Could present predisposition thanks to the current situation
- - ¿Ha vivido alguna situación que le haya resultado especialmente frustrante o estresante durante el aislamiento social de la pandemia? Por favor, describa a su criterio cuáles han sido dichas ocasiones.
- - - Could present predisposition thanks to the current situation
- - ¿Por qué decidiste o no asistir a terapia? (Problemas económicos, falta de confianza, otros) Comparte tu opinión si es posible. 
- - - Could present predisposition thanks to past experiences
- - ¿Alguna vez has empleado alguna aplicación o servicio en línea diseñado para ayudar a las personas a sentirse mejor emocionalmente? Por favor, responda si lo ha hecho y, en caso afirmativo, agradeceríamos que nos cuente su experiencia usándola (sea positiva o negativa).
- - - Could present predisposition thanks to past experiences
- - ¿Considera que las aplicaciones o servicios en línea anteriormente mencionados proporcionan algún tipo de ayuda real a sus usuarios?
- - ¿Por qué considera lo anterior?
- - ¿Usted le llegaría a dar una oportunidad a una aplicación de ese estilo?
- - - If the answer is positive, it could indicate predisposition to satisfaction
- - ¿Qué debería tener una aplicación o servicio de este estilo para que te sea de lo más agradable de usar?
- - - The opposite of the factors chosen could put the user in a bad mood

- Sensory/Immersive Characteristics of Use: Pleasurable
- - Durante este tiempo, ¿has llegado a intentar alguna de las siguientes estrategias como método para desestresarte? Si ninguna coincide con tus experiencias o te gustaría comentar alguna otra, siéntete libre de añadir una nueva opción. 
- - ¿Qué considera invaluable al emplear una aplicación o servicio en línea? 
- - ¿Qué debería tener una aplicación o servicio de este estilo para que te sea de lo más agradable de usar? 

### Results

Thanks to the survey now we can solve the required attributes  

- What do they expect from a solution?  
The users expect that the solution helps their users in a meaningful way. Users indicate functionality, security, privacy, ease of use, and efficiency as their top 5 expectations.

- When and how would they like to use the solution?  
The majority of users indicate that they would use their mobile device and that they would like to use the solution at their own room.

- How much important is privacy for them?  
Users value privacy normally. They do not wish to make public what should be private, and that they do not like data recollection unless its with their consent and anonymous.

- Age  
Majority of users are in the early adulthood, 18, 20 and 19 being the most common ages.

- Education  
All users are current university students.

- Attitudes  
The users feel hit by the current situation in a meaningful way, but not overwhelmed. They are open to trying new solutions that are outside their comfort if they are worth their time and money, and they are generally positive about the therapeutic applications that are seeking helping their users overcome their problems.

- Tenure of online usage  
50% of the surveyed users indicate that they use their mobile phone more than 5 hours a day, followed by a rough 40% indicating that they use it from 3 to 5 hours a day. The remaining 10% ranges from 1.5 to 3 hours.

- Type of usage  
100% of the surveyed users indicate that they use their mobile device for entertainment/recreative purposes.
Meanwhile a rough 80% indicate that they browse the internet, communicate with other people, and do academic-related work too.
Only 10% of the users indicate that they use their mobile phone for professional work.

- Frustrations  
Users have indicated a wide range of frustations.  
- - Personal:  
- - - Economic problems
- - - Unwillingess to deal with the current situation thanks to its absurdity or inability to change anything about it
- - - Isolation
- - - Important changes with their body, as in weight for example.
- - - Online classes
- - - Homework
- - - Returning to offline classes
- - - Anxiety
- - - Stress
- - - Feeling of wasting their youth or time
- - - Loneliness  

- - Related to solutions:  
- - - Too expensive
- - - Not effective
- - - Too slow
- - - Too ugly (interface)
- - - Not interested
- - - Not willing to try
- - - Not knowing which solution to try
- - - Adapting to the solution

- Attitude toward technology used  
Users are open to the technology used, but a rough 20% of them believe the current solutions do not help their users in a meaningful way.

- How is value defined?  
Users value functionality, security, privacy, ease of use, and efficiency as their top 5 expectations.
They also indicate that they want to be comforted as well as motivated and/or cheered up by the solution.
They value an inexpensive or free solution which they can use the least time possible and without requiring to adapt to it.

- Context of Usage  
- - Surrounding Environment  
Users would like to use the solution in the privacy of their own rooms.

- - Confidentiality/Privacy  
Users value privacy and they want a solution that does not recollect data without their consent, and as long as its anonymous. They want to trust the application so that its easier for them to open up and they want to use it in a private setting where it's only them and the solution

- - Satisfaction  
Generally, users agreed that a functional app that is cheap or free, that is easy and fun to use and efficient with its method, as long as its not collecting user data without consent would satisfy them.

- Interaction Characteristics of Usage   
- - Frequency of use  
Users indicate that they use their mobile devices up to 5 hours or more, but they are not going to use the solution for any longer than 1 hour. We have an even 30% divide between people who would try it for 1 hour and 30 minutes, and 20% indicating that they would use it for only 15 minutes or less. The rest indicates that they would use it longer than 2 hours, but that's a minority.

- Sensory/Immersive Characteristics of Use  
- - Mood/Feeling  
Users feel deeply hit thanks to the current situation but they try not to let it get to them.
Users want to feel safe and comforted while also being motivated and entertained by a cheap, easy to use app with an easy to read language and a fun set of activities so that they can have a good time. They want to be distracted from their problems while also bettering themselves.

- - Pleasurable  
Ease of use and understanding as well as fun or motivating can help the users feel more compliant to keep using the app for an extended period of time and not just a one-time ocassion.

[Final persona]

## Requirements definition

### Non-functional

- ...

> [👈 Go back.](./index.md)
