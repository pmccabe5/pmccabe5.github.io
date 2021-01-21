---
layout: post
title: "HW0: Introduction"  
---

## Intruduction

### General Info

1. Name: Patrick McCabe
2. Year: Senior 
3. Major: Computer Science
4. Minors: Data Science, History

### Cyber Security:

COFC Cyber Security club 2017-2021
COFC Cyber Defence Team 2017-2021

Published author for outward facing network penetration testing

Member of ASIS International
Attended the following Security BSides Competitions:
* BSides Charleston 2019
* BSides Charlotte 2019
* BSides Charleston 2018
---
layout: post
title: "HW1: Chapter 1"  
---


## Chapter 1

### 1.3:  What are the four important attributes that all professional software should possess? Suggest four other attributes that may sometimes be significant.

The 4 important attributes of professionally developed software should possess are:

1. Acceptability
2. Maintainability
3. Dependability and Security
4. Efficiency

Aside from that, four other attributes that may be significant are:

1. Heterogenity
2. Business and Social change
3. Security and Trust
4. Software Scalability

### 1.8: Discuss whether professional software engineers should be licensed in the same way as doctors or lawyers.

I believe that there should be some level of certification for Software Engineers. Seeing as many network professionals are strongly encouraged to gain certifications so that there is a common understanding of the tools and environments they could encounter, Software Engineers should have the ability to take certification tests to allow employers to establish a baseline for the profession. An example would be the Certified Ethical Hacker (CEH) certification and an equivalent would be something along the lines of a Certified Ethical Coder or some other name that is appropriate.

### 1.9: For each of the clauses in the ACM/IEEE Code of Ethics shown in Figure 1.4, propose an appropriate example that illustrates that clause.

1. Public: Code an program that users will use to solve a problem
2. Client and Employer: Coders should code a prgram that their employer and client has contracted and meets the specifications provided.  
3. Product: A program should be patched if there is a security vulnerablity is discovered and the vulnerability disclosed.
4. Judgment: Programmers must make decisions on a program that would benefit the end user the best.
5. Management: Maintanence procedures on a program will come from the top down and a culture will be formed around the procedures. 
6. Profession: Programmers should look to involve themselves with the youger generations and pass down knowledge gained.
7. Colleagues: A programmer should take interest in their coworkers' projects and listen to suggestions, as well as support their career decisions.
8. Self: Programmers should continue learning about current technologies and learn how to implement them into current or future projects.

### 1.10: To help counter terrorism, many countries are planning or have developed computer systems that track large numbers of their citizens and their actions. Clearly, this has privacy implications. Discuss the ethics of working on the development of this type of system.

The positives of this systems are outweighed by the negatives of this system. The first negative includes the ability for data sniffing for governments, as they will be able to collect data unbeknownst to the user. The next negative is if a backdoor is developed, what is stopping a nation-state from discovering the vulnerability and sniffing for data that could be used in a social engineering campaign that can occur during an election. The final negative is the loss of trust in the governments if it was disclosed that spying on their own citizens broke to the news. There would be another case of the Edward Snowden saga, trust in the government would decline, and public opinion would change as well. The only benefit would be more data for government agencies, but there is a slim chance within that data set that there would be an attack that would be thwarted. There also would not be much media coverage if bulk data collection was the reason for a raid on a potential terrorist.---
layout: post
title: "HW2: Reflections on software engineering practices"  
---

## Reflection on Software Engineering practices

Software Engineers in this day and age are faced with adversity as it relates to their working environments and workflows. They are faced with ever evolving workflows, programming languages, and technology to develop their applications for. This constant evolution in development is hard to put into perspective, but software engineers have stepped up to the plate and have adapted to their surroundings.
The first concern that software engineers face today is the fact that they are developing for technologies that are constantly changing, especially with the languages that also change with the development of software products. An example of this would be the move that is occurring from Object-Oriented Programming to a focus on development on Artificial Intelligence. This shift is due in large part to the technological advances and the versatility of the software that is in development. One of the other problems facing software developers is the fact that technology is ever evolving and a new requirement for development is how well the product scales from a localized instance to how well the product scales to the cloud. Although it has not been a problem to scale to the cloud, it is another set of skills that software engineers need to add to their toolboxes for future development.
Next, workflows that software developers utilize continue to evolve and the process to implement changes to software can differ slightly from company to company and product to product. To confuse matters even more, some teams and team leads will differ in the ways that they want to remediate bugs and the ways that bugs are labeled can differ greatly. Software engineers are faced with constant critique of their abilities to fix bugs from supervisors. There needs to be a level of trust between manager and developer, although there also needs to be a relationship between developers to help test patches for bugs. Though according to George V. Neville-Neil, there should be different levels and classifications of bug remediation. They are: bug analyzed, patched |, and bug fixed. These classifications offer some guidance for remediation in a way that can become common across the industry, along with a proven or disproven quantifier for test cases that prove or disprove the implemented patch.
Finally, there is also a concern for the toolchains that software developers use on a daily basis. In Google’s case, they have a central code repository rather than individualized or specialized repositories for their products. This can be both beneficial and at the same time confusing. The toolchains and methods that are used in Google’s case, they have implemented a branching model that only takes the best features of the main code branch and deploys them to the release branch. This differs from other models since their main repository contains the bulk of their code and their releases are branches off of the main branch, rather than test branches off of the main branch and then merged.
In conclusion, there are concerns that software engineers face in this day and age. Although they may seem minimal, they can become problematic once development teams are scaled to build more robust applications. But, software developers are ever evolving and are willing to take up the challenge to adapt to the evolving environment that is software development
---
layout: post
title: "HW3: Chapters 11 & 12"  
---

## Chapter 11

### 11.4 What is the common characteristic of all architectural styles that are geared to supporting software fault tolerance?

One characteristic that all architectural styles incorporate a fail safe module or system to protect against a failed input. This can be seen in many applications, especially in equipment that puts lives at stake, such as flight control systems and medical monitoring devices.

### 11.7 It has been suggested that the control software for a radiation therapy machine, used to treat patients with cancer, should be implemented using N-version programming. Comment on whether or not you think this is a good suggestion.

The use of N-Version programming would not be a welcome addition to a radiation therapy machine. The benefit to the implementation would be an extra layer of data checking to ensure the therapy machine dispenses the correct amount of radiation. The drawbacks to implementing this system are that N-Version programming relies on hardware failure rather than a software failure, and if the wrong dosage is given then it will be fatal for the patient. The other drawback to the added system to the therapy machine is that the additional system would also be subject to the same regulations and standards and those could be ignored for sake of profit.

### 11.9 Explain why you should explicitly handle all exceptions in a system that is intended to have a high level of availability.

If exceptions are handled explicitly, it allows for the continuation of the software to continue running. If exceptions are not handled, then the program will crash or produce incorrect outputs for the user. If the exception results in the former, that will result in a financial loss for the company that produces the

### 12.5 A train protection system automatically applies the brakes of a train if the speed limit for a segment of track is exceeded, or if the train enters a track segment that is currently signaled with a red light (i.e., the segment should not be entered). There are two critical-safety requirements for this train protection system:
* The train shall not enter a segment of track that is signaled with a red light.
* The train shall not exceed the specified speed limit for a section of track.
### Assuming that the signal status and the speed limit for the track segment are transmitted to on-board software on the train before it enters the track segment, propose five possible functional system requirements for the onboard software that may be generated from the system safety requirements.

    Five possible Functional Requirements for the Train system are:
    1. The train system needs to be able to communicate over a centralized network
    2. The system needs to calculate the current speed of the train at any given time
    3. A signal must be handled for the color of the light at a section of a track
    4. The system needs to handle errors for possible decouplements (ex: the speed drastically increases after losing a car)
    5. The system needs to communicate to the engineer of any issues with any mechanical equipment on the train---
layout: post
title: "HW4: Reflections on software failures"  
---

## HW4: Reflections on software failures

Software failures have been a problem in development since software engineering has become a profession. Although there have been advances in the field in increased success, there are aspects of software development that are playing catch up for the industry. Examples of this would be through security implementation and security assessments for projects and the ever changing technology that is being developed to deploy applications in a secure way.

With regards to security, it has been an afterthought for development for years and that the process to implement security through development has only been added to the development cycle through DevOPs and Sec DevOPs. Security is an ever evolving field and attack vectors and signatures are ever changing. Implementing security in a product takes time, and most times it's time that a project does not have on their timeline for deployment of the product. Project timelines are one of the major road bumps for implementing a full blown secure application.

The first step to implementing security would be to perform a full risk assessment of the systems that are involved in the development of a product and ensure that the systems are indeed secure before development begins. Once the systems are secured, then development should begin and if network connections are present, they must be secured and monitored so that outside threats cannot disturb development, steal code or data, and disallow for uploading remote access trojans (RATs) to disturb and compromise the entire company. There also has to be training for all the users in the company and on especially on the development team, because the threat of phishing and other user-oriented attacks. By falling for these attacks, as simple as they may sound, can be catastrophic if one employee's information is leaked and not properly attended to, can be used for leverage and blackmail of the employee for more access to the company.

There was a specific software project that crossed into both software engineering and security became intertwined when the FBI began to move from paper records to virtual case files (VCFs). The idea was simple in nature, the FBI wanted to move their case records online so that they could begin to modernize and access records in the field. Issues with the project started to show up immediately, mainly due in part to building security into the product from the ground up. As time progressed with the project, the overall cost to feature/usability implementation was not balanced, leaning favorably in the direction of the costs outweighing the performance. Overall the project ran over budget by millions of dollars and it took the project roughly seven years to make it to full deployment to the field for the FBI.

In conclusion, security is a hard topic to grasp and integrate into a product from the ground up. In order to deploy a secure product to a working environment. In order to deploy a product securely, a development team needs to think like a hacker and ensure that the proper secure libraries are used and use the tools and methodologies white hat (good guys) hackers use to ensure that environments are secure and safe for real world deployment. If the product is not secure before deployment, the small flaw that exists could lead to a massive ransomware attack where cities and hospitals grind to a halt and will not be able to operate. 
---
layout: post
title: "HW5: Chapter 4 and reflections"  
---

## 4.5: Using the technique suggested here, where natural language descriptions are presented in a standard format, write plausible user requirements for the following functions:

* An unattended gas pump system that includes a credit card reader. The customer swipes
the card through the reader, then specifies the amount of fuel required. The fuel is
delivered and the customer's account debited.
* The cash-dispensing function in a bank ATM.
* In an internet banking system, a facility that allows customers to transfer funds from one
account held with the bank to another account with the same bank.

### Gas Pump

**1.1** The system will be able to dispense gas

**1.2** The system will be able to accept payments from credit and debit cards

**1.3** The system will be able to accept a pin for a payment

**1.4** The system will be able to select the fuel grade that the user selects

**1.5** The system will be able to dispense fuel

**1.6** The system will be able to calculate the price of the fuel in real time based on the amount dispensed

**1.7** The system will detect if the fuel tank is full

**1.8** The system will charge the card that was accepted at requirement 1.3

**1.9** The system will be able to return a receipt for the transaction if the user asks for it

### Bank ATM

**2.1** The ATM will accept a card

**2.2** The ATM will able to accept a pin as authentication

**2.3** The ATM will not allow cash to be withdrawn if the pint that was entered is wrong

**2.4** The ATM will provide "quick cash" options for dispersement ($20, $40, $60, $80, $100)

**2.5** The ATM will accept a custom amount to be dispersed

**2.6** The ATM will check to make sure that there are suffiecient funds before dispersing money

**2.7** The ATM will disperse the amount specified

**2.8** The ATM will ensure that the transaction is done

**2.9** The ATM will return the card

### Internet Banking

**3.1** The system will be accept a login for authentication

**3.2** The system will ensure the user's number is legal and not an illegal value

**3.3** The system will check the database of accounts to make sure the second account exists

**3.4** The system will accept an amount to be transfered

**3.5** The system will ensure there funds available to transfer

**3.6** The system will be able to securely transfer funds 

**3.7** The system will ask if the user is done

**3.8** The system will log out once done

## 4.6 Suggest how an engineer responsible for drawing up a system requirements specification might keep track of the relationships between functional and non-functional requirements.

A way that an engineer can draw up system requirements is to create a list of the requirements that are asked of by the client themselves. Anything that the engineer would see as worth including in the final package as well as features that would be an add on or improvement to the product that the client would welcome to the application.

## Using your knowledge of how an ATM is used, develop a set of use cases that could serve as a basis for understanding the requirements for an ATM system.

**UC1:** The user will be able to withdraw money from the ATM

**UC2:** The user will be able to deposit money

**UC3:** The user will be able to accept user input for a pin authentication and amount of money tp be tendered

**UC4:** The user will be able to view their current bank information

## Readings Reflection

After reading the provided readings about secure car systems, it only provides further evidence for the current development and legal environment we face: the asymmetric advantage of red hat hackers is years ahead of governments. The overall sentiment is that with simple testing, Software Defined Radio (SDR) tools with injection are only a few hundred dollars, the development team would have had a better grasp on the technology that they were using.With the ever evolving technology, laws for the systems and protocols are lagging behind and proactivity on the legal side of the matter is paramount. The law that prevents the SDR exploit to be patched upon assembly took 5 years to be introduced to congress, way too late to patch and also would incur a financial loss for all car manufaturers with cars with the exploit, since new systems would need to be installed or money for software patches would need to be spent. Thus, the need for a specific Cyber Security comittee in congress, and a government agency for oversight, needs to be created to proactively defend and research security flaws in the real world.---
layout: post
title: "HW6: Chapter 2"  
---

## Exercise 2.1

1. A system to control the antilock brake in a car

* Incrimental development: the system will want to use the incrimental development since the system will have multiple iterations and will need to be calibrated over the years of the product cycle

2. A virtual reality system to support software maintenance

* Waterfall: the waterfall method would be best suited since the product is being developed from the ground up and there will be an end of life period for the product as technology changes

3. A university accounting system that replaces an existing system

* Integration and configuration: this methodology would be best suited because there is a product in place that will need to be scaled and migrated to the new platform

4. An interactive healthcare system that helps users plan journeyswith the lowest environmental impact

* Incrimental development: Incrimental would be best suited since security must be built in from the ground up with handling health data. Also, the features need to be up to the client's standards before being incorporated into the final product.---
layout: post
title: "HW7: Chapters 5 and 6"  
---

## Chapter 5

### 5.3 Activity Diagram for Booking an Event

[5.3](https://github.com/pmccabe5/pmccabe5.github.io/blob/master/5-3.png)

### 5.5 Sequence Diagram for registering for courses

[5.5](https://github.com/pmccabe5/pmccabe5.github.io/blob/master/5-5.png)

### 5.7 Activity Diagram for withdrawing cash from an ATM

[5.7](https://github.com/pmccabe5/pmccabe5.github.io/blob/master/5-7.png)

### 5.8 Sequence Diagram for an ATM

[5.8](https://github.com/pmccabe5/pmccabe5.github.io/blob/master/5-8.png)

## Chapter 6.4

### Ticket Machine

[Ticket Machine](https://github.com/pmccabe5/pmccabe5.github.io/blob/master/ticket-conceptual.png)

### Video Conferencing

[Video Conferencing](https://github.com/pmccabe5/pmccabe5.github.io/blob/master/video-conceptual.png)---
layout: post
title: "HW9: Chapter 8 and reflections on testing"  
---

8.7 Write a scenario that could be used to help design tests for the wilderness weather station system.

Billy works for a wilderness weather station out in Lander, WY. He spends a lot of time at work because he often gets snowed in and has to spend the night. This gives him plenty of time to test the weather station software. First, he has to log onto the system using his weatherman username and password. 

Billy usually first checks the status of the satellitle communcations (SatComm) and the regular communications (Commslink) link to ensure that the summary is being collected from up-to-date data. He then will request a weather data summary report from satellite communications and receive an acknowledgement of this request. 

Billy knows the weather station will send him a report if it is unable to collect data via the Commslink and it will also acknowledge that he requested a report. Always alone and drinking coffee, Billy looks forward to receiving the summary report of the weather data to give him something to do on long snowy days at work. 

8.10 > A common approach to system testing is to test the system until the testing budget is exhausted and then deliver the system to the customers. Discuss the ethics of this approach for systems that are delivered to external customers. 

This is not a very ethical approach. Testing is time-intensive and often leads to changes in software as the tests reveal issues. The testing period should have plenty of time devoted to it to ensure that a customer is getting, if not a totally bug-free product, at least a product that has undergone extensive testing before it was deemed appropriate to receive money for. A testing budget should also be a little bit larger because of its importance to a project. 

If a software company develops and delivers software to an external customer without putting in significant testing time, then how can the software company be sure that they will get that customer back? A company can only ensure returning customers if they have put the time and effort into making their product the best it can be for the requirements asked for and tested it effectively to the best of their abilities.---
layout: post
title: "HW10: Chapter 15"  
---

15.10: The reuse of software raises a number of copyright and intellectual property issues. If a customer pays the software contractor to develop a system, who has the right to reuse the developed code? Does the software contractor have the right to use that code as a basis for a generic component? What payment mechanisms might be used to reimburse providers of reusable components? Discuss these issues and other ethical issues associated with the reuse of software.

---
layout: post
title: "HW13: Chapter 17"  
---

Risks of moving desktop apps to remote

1. There could be issues with the default configurations for the desktop apps once they move to remote. There would need to be a benchmark set so that the virtual environment is the same as the local desktop environment.

2. Another issue that occurs once the desktop applications move remote is the multi-tenacy of the users, since the environments need to be as close as possible to the local environment. From work experience, virtualization through a third party client that is able to page or call the application and use remote resources to allow the user to temporarily run the app.

3. One of the final problems with moving to a remote model for local desktop applications is the ability to scale as a company either grows or shrinks. Some tools that can be used are a combination of Docker, Kubernetes or Redhat Openshift, and a automation tool such as Ansible or Puppet. These tools can make scaling to fit the needs of the company at any given time.---
layout: post
title: "HW14: Chapter 18"  
---

## RESTful API for Simple Interest Calculator

1. Create (POST): The SimpleInterestCalculator will create an instance of the SimpleInterest calculator and then send a Create or (GET) request

2. Read (GET): The Read request will return the value calculated by the SimpleInterestCalculator or an error, if error handling is present in the application for invalid arguments or 

3. Update (PUT): This request will be sent if the user needs to change a value in the calculation of the SimpleInterestCalculator

4. Delete (DELETE): THis request will be executed once the user closes or quits the program and the instance will be deleted.---
layout: post
title: "HW17: Team Progress I"  
---

## Team Progress

This project has been a very interesting roller coaster, but is trending in the right direction. We started out trying to run the `sugar-labs` desktop environment to testing the `calculate-activity`. The progress on the testing framework has run smoothly, with very few hiccups along the way. We look to have completed test cases within the next week or so.---
layout: post
title: "HW17: Team Progress I"  
---

## Team Progress II

The project has been running very well and we have not run into any hiccups.
