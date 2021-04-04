---
layout: post
title: "Introduction"  
---
## Intruduction

### General Info

1. Name: Patrick McCabe
2. Year: Senior 
3. Major: Computer Science
4. Minors: Data Science, History

### Favorite Programming Languages:

* Python 3
* Bash
* Java
* GO
* C/C++

### Cyber Security:

COFC Cyber Security club 2017-2021

COFC Cyber Defence Team 2017-2021

Published author for outward facing network penetration testing

Member of ASIS International
Attended the following Security BSides Conferences:
* BSides Charleston 2019
* BSides Charlotte 2019
* BSides Charleston 2018

---
layout: post
title: "Reflections on FOSS"  
---

# Reflections on FOSS

## Introduction

FOSS and H/FOSS projects are a very interesting topic for discussion. The shift in **Open Source Software** has put the Software as a Service (SaaS). There are both benefits and disadvantages to both development models. The selected reading, The Cathedral and the Bazaar, illustrates the process of developing FOSS for the masses and the downsides of this method of deployment. **Open Source Software** has been a blessing and a curse depending on which side of the market one lies on, opinions will differ on the matter.

## Open Source Benefits
If you are a consumer then **Open Source Software** benefits you, since there is little to no cost associated, unless the user is willing to donate to the project or contribute in their spare time. This model of software development/deployment benefits both the creator and the users, as the users can suggest/implement features for the entirety of the project or can create a local version for themselves (without offering the project for a fee as that would violate some of the many different licenses that are currently employed by Open Source projects). 

A great example of this model’s success is Linus Torvalds and Linux. The project itself, seemed like it would devolve into utter chaos, but somehow, someway, the project has thrived and is currently in release 20.10 (with major feature updates released in both April and October as well as Long Term Support (LTS) releases for multiple years for enterprise systems). Why has this been so successful? The answer lies in the relationship between the users and the developer. Linus Torvalds embraced the ideas that the community brought forth and was able to listen and integrate the ideas into the operating system very easily through version control. 
Another benefit of **Open Source Software** is the added security that is enabled through discourse within the communities and the ability to audit projects that are on the open web. The ability for security researchers to look directly at source code and discover vulnerabilities, can lead to early fixes rather than distributing a vulnerable package to multiple enterprises. This also goes hand in hand with Requests For Comments (RFCs) as they allow for input on new protocols or applications that need extra input before implementation.

## Open Source Disadvantages
A blaring disadvantage of Open Source are that there are some projects that are taken advantage of and they are not properly funded, and without funds (or even interest/lack of time from the developer) the projects are neglected and die out. This is not beneficial to the users, since they rely upon the project for a critical function of their enterprise and can be sitting ducks for hackers if no security updates have been pushed to the project.
Another disadvantage of **Open Source Software** is that with a great project, comes the responsibility to understand what they are developing. In the article, the developer describes a new protocol, *SendMail*, that would deprecate SMTP and POP3 delivery methods into one protocol that involves forwarding all email protocols to a common protocol. With this implementation, email clients would need to adapt to the new protocol as well as the email servers that hosted the email users (since protocol translation would need to be implemented), which is cost-ineffective. 

A final disadvantage that goes hand in hand with the first reason is security considerations. Without putting in the proper time and research, **Open Source Software** can become weaponized if security vulnerabilities are discovered and not patched in a timely manner. Two examples would be [VSFTPD 2.3.4](https://nvd.nist.gov/vuln/detail/CVE-2011-2523#vulnCurrentDescriptionTitle) and [LibSSH 0.7.1-0.8.3](https://nvd.nist.gov/vuln/detail/CVE-2018-10933). Both could have been patched sooner if more research and time had gone into the development of these **Open Source Softwares**.

## Conclusion
Generally speaking, **Open Source Software** is beneficial to the community with many new and innovative ideas becoming implemented in real world applications. But with every new idea, comes the possibility of deprecating old technologies or even putting a wide user base at risk with untimely patches and updates.

---
layout: post
title: "Reflections on Open Source in Today's World"  
---

# Reflections on Open Source in Today's World

## Articles

[Article 1](https://opensource.com/article/21/1/ifconfig-ip-linux)

[Article 2](https://opensource.com/article/20/6/modern-linux-command-line-tools)

## Introduction

The articles that I have selected are `Linux` specific and are describing the newer methods for gathering information and upgrading workflows with `bash`. Most commands that are built into `bash` have been around since the early days of `Unix` and `*nix` and need some additional updates for efficiency, streamlining, and over user-friendliness. The tools found in the articles below are some tools I use on a daily basis and some that I never used before and am glad I have discovered them

## Why you need to drop ifconfig for ip

The first article I selected was for networking within the `bash` interface in a terminal. While learning `Linux` and the `CLI`, `ifconfig` was the main networking command that worked across multiple distributions of `Linux` and was very user friendly. The article selected, mentions this as `ifconfig` has served `Linux` well, but it is time to move on from the old and outdated utility.

Although `ip` is the new tool on the block, it is still available in most distributions installed by defualt or the `net-tools` package is available to download from the package manager. Also, with a new tool, the total move to the new standard cannot happen overnight due to the learning curve associated with the new standard. `ifconfig` is a pretty straightforward command and the article does a great job of comparing and noting the `ifconfig` and `ip` equivalents to showcase the differences between the two tools. Though I must say from my perspective, `ipconfig` is great for beginners, but `ip` has come along and fully updated the command and has allowed for more verbose options for the simple operations, albeit with a learning curve.

## 5 modern alternatives to essential Linux command-line tools

The second article I selected runs along the same lines as the first article but with more tools with their modern equivalents. The author selected the following tools

- `ncdu`
- `htop`
- `tldr`
- `jq`
- `fd`

The first two tools I have used their older equivalents `top` (for dynamically checking system processes) and `du`, with `du` getting the following alias in my `.bash_aliases` file: `alias allocate="du -sh"`. The only noticible difference between `top` and `htop` are the aesthetics, they both work fine and both are installed on my distributiuon of choice, [Parrot OS](parrot.sh). I have not heard of `tldr` but upon installing it on my desktop, it seems like a cool tool, but in the end it appears that `man` is still better suited for what `tldr` is looking to replace: additional information and options for running a tool. When I look for help, I want to have as many options as well as much information on the options as possible. `tldr` does not accomplish this and `man` is installed out of the box for majority of the dirtributions of `Linux` that are one the market. The final two tools, `jq` and `fd`, I have not used, nor have I had the opprotunity to install them, especially `fd` since there seem to be some dependemcies that are not available for `Parrot OS` at this moment (this also includes trying to install the package with the `--fix-missing` flag for `apt`). `jq` is `JSON` specific, and I have not had the opporotunity to use `JSON` files for any projects that I have worked on, but look to learn more about them in the future.

## Conclusion

In general, both articles have really good intentions, but their arguments may not have been as convincing as they intended. Both explained why the new tools were better, but I found that both articles showed the old and new equivalent of the same commands, but the first article only focused on one specific use case and two tools rather than a `tldr` on 5 different tools. When push comes to shove, both articles communicated their points well and I learned about a few more tools for bash that I had never heard of before and will look to apply these tools to my workflow and toolchain.

---
layout: post
title: "This bugs me"  
---

# This bugs me

[Source](https://quaid.fedorapeople.org/TOS/Practical_Open_Source_Software_Exploration/html/ch-Debugging_the_Code.html)

Selected Project: [SugarLabs](https://github.com/sugarlabs)

## TOS 6.4: Exercise - Find the Oldest Bug

[Oldest Bug](https://github.com/sugarlabs/Pippy/issues/49)

## TOS 6.5: Figure out how to create a new account on the bug tracker of your chosen project. You'll need that account very soon.

[GitHub](github.com/pmccabe5)

## TOS 6.6: The Anatomy of a Good Bug Report

### Bug Report

Bug: Button Sensitivty

- **Description**: The undo/redo buttons are very sensitive when pressed in the GUI window
- **Environment**: `VMWare ESXi`, `Ubuntu 18.04 Focal Fossa`, `Fedora 32`
- **Resolution**: It appears that on line 667 of `pippy_app.py` the following code is present, where there is a typo on the variable `butston` which should be `button`.:

```
def __undobutton_cb(self, butston):
        text_buffer = self._source_tabs.get_text_buffer()
        if text_buffer.can_undo():
            text_buffer.undo()
```

## TOS 6.7: Bug Triage

1. [Undo Button Sensitivity](https://github.com/sugarlabs/Pippy/issues/69)
2. [Redo Button Sensitivity](https://github.com/sugarlabs/Pippy/issues/68)
3. [Example Failure](https://github.com/sugarlabs/Pippy/issues/66)
4. [Automated Testing Framework](https://github.com/sugarlabs/Pippy/issues/84)
5. [Auto Indenting](https://github.com/sugarlabs/Pippy/issues/74)

---
layout: post
title: "What's Happening?"  
---

# What's Happening?

## 7.2.2 Exercise - Compare diff formats

```
diff 2021-2-4-HW3.md 2021-2-11-HW4.md 
3c3
< title: "This bugs me"  
---
> title: "What's Happening?"  
6c6
< # This bugs me
---
> # What's Happening?
8,43c8
< [Source](https://quaid.fedorapeople.org/TOS/Practical_Open_Source_Software_Exploration/html/ch-Debugging_the_Code.html)
< 
< Selected Project: [SugarLabs](https://github.com/sugarlabs)
< 
< ## TOS 6.4: Exercise - Find the Oldest Bug
< 
< [Oldest Bug](https://github.com/sugarlabs/Pippy/issues/49)
< 
< ## TOS 6.5: Figure out how to create a new account on the bug tracker of your chosen project. You'll need that account very soon.
< 
< [GitHub](github.com/pmccabe5)
< 
< ## TOS 6.6: The Anatomy of a Good Bug Report
< 
< ### Bug Report
< 
< Bug: Button Sensitivty
< 
< - **Description**: The undo/redo buttons are very sensitive when pressed in the GUI window
< - **Environment**: `VMWare ESXi`, `Ubuntu 18.04 Focal Fossa`, `Fedora 32`
< - **Resolution**: It appears that on line 667 of `pippy_app.py` the following code is present, where there is a typo on the variable `butston` which should be `button`.:
< 
< ```
< def __undobutton_cb(self, butston):
<         text_buffer = self._source_tabs.get_text_buffer()
<         if text_buffer.can_undo():
<             text_buffer.undo()
< ```
< 
< ## TOS 6.7: Bug Triage
< 
< 1. [Undo Button Sensitivity](https://github.com/sugarlabs/Pippy/issues/69)
< 2. [Redo Button Sensitivity](https://github.com/sugarlabs/Pippy/issues/68)
< 3. [Example Failure](https://github.com/sugarlabs/Pippy/issues/66)
< 4. [Automated Testing Framework](https://github.com/sugarlabs/Pippy/issues/84)
< 5. [Auto Indenting](https://github.com/sugarlabs/Pippy/issues/74)
\ No newline at end of file
---
> ## 7.2.2 Exercise - Compare diff formats
\ No newline at end of file
```

```
diff 2021-2-4-HW3.md 2021-2-11-HW4.md 
3c3
< title: "This bugs me"  
---
> title: "What's Happening?"  
6c6
< # This bugs me
---
> # What's Happening?
8,43c8
< [Source](https://quaid.fedorapeople.org/TOS/Practical_Open_Source_Software_Exploration/html/ch-Debugging_the_Code.html)
< 
< Selected Project: [SugarLabs](https://github.com/sugarlabs)
< 
< ## TOS 6.4: Exercise - Find the Oldest Bug
< 
< [Oldest Bug](https://github.com/sugarlabs/Pippy/issues/49)
< 
< ## TOS 6.5: Figure out how to create a new account on the bug tracker of your chosen project. You'll need that account very soon.
< 
< [GitHub](github.com/pmccabe5)
< 
< ## TOS 6.6: The Anatomy of a Good Bug Report
< 
< ### Bug Report
< 
< Bug: Button Sensitivty
< 
< - **Description**: The undo/redo buttons are very sensitive when pressed in the GUI window
< - **Environment**: `VMWare ESXi`, `Ubuntu 18.04 Focal Fossa`, `Fedora 32`
< - **Resolution**: It appears that on line 667 of `pippy_app.py` the following code is present, where there is a typo on the variable `butston` which should be `button`.:
< 
< ```
< def __undobutton_cb(self, butston):
<         text_buffer = self._source_tabs.get_text_buffer()
<         if text_buffer.can_undo():
<             text_buffer.undo()
< ```
< 
< ## TOS 6.7: Bug Triage
< 
< 1. [Undo Button Sensitivity](https://github.com/sugarlabs/Pippy/issues/69)
< 2. [Redo Button Sensitivity](https://github.com/sugarlabs/Pippy/issues/68)
< 3. [Example Failure](https://github.com/sugarlabs/Pippy/issues/66)
< 4. [Automated Testing Framework](https://github.com/sugarlabs/Pippy/issues/84)
< 5. [Auto Indenting](https://github.com/sugarlabs/Pippy/issues/74)
\ No newline at end of file
---
> ## 7.2.2 Exercise - Compare diff formats
\ No newline at end of file
```

## 7.8 Exercise - Create a Patch for a New File

Contents of `foo`:
```
cat foo
bar
```

## Exercise - Patch echo

No output is recorded for the original and reverse

---
layout: post
title: "Stupid or Solid?"  
---

# Stupid or Solid?

## What is S.O.L.I.D.?

- S: Singleton
- T: Tight Coupling
- U: Untestable
- P: Premature Optimization
- I: Indescriptive Naming
- D: Duplication

## Use Cases of S.T.U.P.I.D.

### Singleton

When the singleton trait is present, that means that there is one class of code for the entire project. This trait can be useful when the following conditions are present:

- Making sure there is one instance of a class
- Ensuring accessability of a class
- Controlling instantiation
- Instance restriction
- Global variable accessibility

The main drawbacks of this desing pattern is that this does not allow for `test driven development`, no inheritance, creation control is restricted, and requires all dependencies to be changed for each instance

### Tight Coupling

Tight coupling is not much better than singleton development, due to the over reliance of code throughout a project. By implementing this strategy of development, there could be a trickle down effect on the project if one dependency breaks any file that uses it. Thus, multiple files need to be changed. Additional drawbacks include difficult code reuse in the future and inhibits the ability to test the project.

### Untestability

Testability in a code base should be easily implemented and should be an integral part of the development cycle. Most times, if a project is too tightly coupled, then the ability to test your code base is inhibited. Thus, testing should be implemented along the way, rather than at the end of development when time and capitol for the project could be running low.

### Premature Optimization

In this pattern, the cost of the project outweighs the ability for benefits. In this day and age, is detrimental to product development and especially to product security. If cost is an issue, then features, testing, and security will be cut rather than implemented. As such, with cost becoming a factor the code will take a step back in both performance and readability for future improvements or reuse.

### Indescriptive Naming

This is pretty self explanitory, using descriptive names for variables reduces the need for comments and is appreciated further down the road for maitenance, feature implementation, and code reuse.

### Duplication

This is on the same wavelength as indescriptive naming, if there are duplicated functions then time is wasted and coupling is affected by the multiple ways of doing the same task.

## S.O.L.I.D.

S.O.L.I.D. is the complete opposite of S.T.U.P.I.D. and covers the following design priniciples:

- S: Single responisibility
- O: Open/Closed Principle
- L: Liskov Substitution Principle
- I: Interface Segregation
- D: Dependency Inversion Principle

## Use Cases for S.O.L.I.D.

### Single Responsibility Principle

This design pattern involves only having one purpose per class. This allows for both low coupling and high cohesion in a project or code base. The rule of thumb to check for this principle is the following: *Is there more than one reason to change this class?* If there is more than one reason, then the single class can be split into multiple classes.

### Open/Closed Principle

- Open: open for extension, this applies to adding `data structures` and fields to the functions contained within the class.

- Closed: closed for modification, this applies to internal variables which should be private and accessed by `getter` and `setter` methods for the class. 

### Liskov Substitution Principle

The Liskov Substitution Principle (LSP) applies to classes where a class can be replaced with an instance of their subtype without losing functionality or correctness of the class.

### Interface Segregation Principle

This design principle refers to not having a generic interface for multiple use cases. This principle specifically outlines `low coupling` and `high cohesion` among classes within a project and minimizes the dependencies among the classes

### Dependency Inversion Principle

The Dependency Inversion Principle has two main attributes:

- Abstractions should not depend upon details
- Details should depend upon abstractions

By applying this design principle, a code base or project will have reduced dependencies within the project and allows for future code reuse.

## My Thoughts

After looking through the following design principles, S.O.L.I.D. is more modern and I have attempted to add these principles to my code projects and they are a a night and day improvement over S.T.U.P.I.D. Hopefully going forward, I can use these principles throughout my projects and applications that I develop.

---
layout: post
title: "Release Early and Often"  
---

# Release Early and Often

## Chapter 8

Chapter 8 provided a great insight into documentation and why it is extremely important in the documentation process. From personal experience, proper and detailed documentation is a great bonus for getting started in **Free Open Source Software**(`FOSS`) or **Humanitarian Free Open Source Software**(`H/FOSS`) projects. One problem I have run into, is if there is documentation, there may be a possibility that it is outdated and makes getting a project built properly for either testing or contributing for the project. Some of the steps that are involved with documentation are:

- Planning
- Content
- Writing
- Internationalism/Localisation
- Review

This process begins with the when the project is being brainstormed and presented to decision makers within the orgainzation or code project. Also, it is not hard to add documentation, as it can be implemented by the following:

- Within the code as comments
- A `README` within the project and subsequent directories about how the code works
- Through an online wiki

An added benefit of code documentation is that it is also an easy way to get involved with a `FOSS` or `H/FOSS` project as documentation can always be added/updated.

## Chapter 9

With `FOSS` and `H/FOSS`, realeasing early and often is always encouraged, as sometimes there may be bugs or unforseen errors in the code. By constantly releasing updates, the users are happy for three reasons:

- The code is being updated
- The maintainers are listening to the users
- The maintainers care about the success of the project

Thus, constant releases are always appreciated no matter what level you are at or stage of development your project is currently in.

---
layout: post
title: "Chapter 5"  
---

# Chapter 5

Chapter 5 centers around the idea of **Domain Class Development**. Throughout developing code, the following three topics are present:

- Coding
- Unit testing
- System testing

## Reusing Legacy Code

One of the first steps to coding **Domain Classes** is looking internally within the codebase for any code that can be repurposed. When looking internally, well commented and documented code and meaningful variable names will make the process run as smooth as possible. By commenting and documenting the processes that it took to deveop the original code, reuse can be determined quickly and save time when considering whether or not to create a new class from scratch. If the legacy code meets the above criteria, it can be moved into the next three phases:

- Downloading the legacy code
- Identify and retain the necessary code for reuse
- Declare/add new instance variables to the legacy code

One the code has been refactored with the added functionality, the only additional steps are to ensure the constructor works or add the necessary functionality for the new class and add the necessary `getter` functions for the new private variables.

## Testing

Now that the code has been refactored and improved with the necessary private variables, testing should begin to ensure that the code is functional before full deployment into the production environment. Depending on the programming language that the project has been implemneted with, the following `unit testing` frameworks can be used:

- `JUnit` (Java)
- `PHPUnit` (PHP)
- `Pytest` (Python)
- `testing` (GO)
- `cmoka` (C)

Once a testing framework has been selected, the test cases should have the following traits:

- Tests should be grouped into `test suites`
- `Unit Tests` should test all of the class's functions, including the constructor
- Test calls should be asserted to either `true` for a pass or `false` for a failure/unexpected test oracle
- Tests should aim for 100% code coverage and 100% use case coverage with every line of code being tested in the class

Once `Unit Testing` has concluded, `Integration Testing` can begin with the following concepts being implemented:

- Classes and modules should be tested separately
- Each of the tested modules of the classes, modules, and unit tests should be `pushed` and `merged` to the main codebase
- The merged code should be `pulled` into the developer's version of the codebase

## Debugging and Refactoring

### Debugging

Debugging code is neccessary, but GitHub makes the process easier and centralized with the `issue` tracker within a repository. 

### Refactoring

Refactoring code is always a plus, since it requires looking over the code again and allows for functions to be reviewed and classified as the following:

- Necessary: the function is used and is necessary for the class
- Redundant: the function's purpose is fulfilled by another function or functions within the class or project
- Useless: the function is not used within the project and is taking up extra lines of code

Also included in refactoring are the following:

- Renaming
- Extracting function(s)
- Reorganizing
- Removing useless code
- Removing layering violations
- Merging functions/modules
- Separating Model, View, and Controller code

## Client Review and Issue Tracking

For client review, the code should be refined and thoroughly tested and deployed in a sandbox for the client or users to test within their workflow. In conjunction, `issue tracking` should be done to ensure that bugs can be addressed for the project for the specific client's use case of the software. The process in reporting an issue can be done by the following:

- By the developer/client during review
- The issue is posted as open with the followin 
    - Title
    - Description
    - Example/replication of the issue
- Open issues are reviewed by the project lead and traiges the issue's priority and whether it overlaps with another issue within the project
- The issue is assigned to developers by the lead
- Once corrected and reviewed, the patch can be approved and once it is approved, the issue is marked as closed

---
layout: post
title: "Chapter 6"  
---

# Chapter 6

## Database Development

Database development is a key factor of developing multiple types applications. Some applications include:
- Website
- Wordpress
- OrangeHRM
- Learning Management Systems (LMS)
- E-Commerce
- Email server
- APIs
- Anything built on a `LAMP Stack` or `WAMP Stack`

A `LAMP Stack` includes the following technologies:
- Linux
- Apache (webserver)
- MySQL or MariaDB
- PHP

A `WAMP Stack` includes everything listed above but swaps `Linux` for `Windows`

## Why are Databases Important?

### Database functions

Databases provide developers a structured data storage solution that is easily accessible and able to be queried for information matching specific criteria that is stored within the database. One of the features of databases that make it an ideal storage solution for data is that it can handle multiple requests at to the database. This is done by locking data per request and unlocks the data for the next request. 

Although `MySQL` is one of the most well known database applications, some other database applications are the following:

- `PostgreSQL`
- `SQLite`
- `MongoDB`
- And many others

`MySQL`, `PostgreSQL`, and `SQLite` all have different ways of connecting and querying to their respective databases. Some include:

- `ssh` connection and querying from a `cli`
- Graphical applications with connections
- Code libraries for the following languages:
    - Java
    - PHP
    - Python
    - Ruby

### Database Security

Depending on the production environment, a database is one of the prized possesions of an adversary. (**Aside**: the only assets I view as higher bounties for adversaries are the following: *Active Directory* (LDAP for Windows/Microsoft authentication for users) and *Domain Controler* access). With databases, there can be multitudes of data data that is stored, including but not limited to:
- Usernames
- Passwords (plain text or hashed (with the `Message Digest 5 (MD5)` encryption algorithm))
- Personal indformation
- Domain specific/highly sensitive information (See the Office of Personnel Management Breach [here](https://www.csoonline.com/article/3318238/the-opm-hack-explained-bad-security-practices-meet-chinas-captain-america.html)) 

When securing a database, the following steps should be implemented:
- Use prepared (sanitized) inputs when accessing a database
- Exercise least privilege for accounts and commands that can be executed by all users
- Prevent unauthorized access
- Limit data manipulation/exfiltration/deletion
- Ensure data integrity within the database's data
- Backups of the database should be completed regularly and restoration from a backup should be practiced in case of a breach or database compromise

Securing a database should be a top priority of a developer as the top vulnerability of the **Open Web Application Security Project (OWASP) Top 10** is [command injection](https://owasp.org/www-project-top-ten/), which includes `SQL Injection`. With `SQLite` specifically, the following commands are present to assist with implementing secure database policy:
- Server level (all databases)
- Database level (table permissions)
- Table level (specific table)
- Column level (column of a table)

With regards to the database integrity, a database application should be available to the following actions:
- Open connections
- Query
- Close connections
- Return query result


## Conclusion

In conclusion, databases are an integral part to application development and must be treated as such. Until `command injection` is removed from the `OWASP Top 10`, there should be an added emphasis on properly securing and maintaining databases so that security incidents do not happen.

---
layout: post
title: "Chapter 9"  
---

# Chapter 9

## Support

As applications grow and scale, there will be a point in time where professional support is necessary to accomodate the user base of the product. With the scaling, and depnding on the type of project, obtaining support will be placed on the user rather than the maintainers, unless the project is closed source and not an application for a specific use case developed by a third party. Some tools that can help with supporting and maintaining an open source project are the following:
- GitHub
- GitLab
- Bitbucket
- Source Forge

A good metric to determine the maturity of a project is the **Open Source Maturity Model (OMM)**:
- Basic
- Intermediate
- Advanced

The basic level includes:
- Documentation
- Adoption of established standards
- Quality test plan
- Licenses
- Technical platform
- Commits and bug reports
- Mantainence and stability
- Configuration management
- Project planning
- Requirement management
- Product roadmap

With all these attributes present, a project can begin to scale and advance to higher levels of the **OMM**. But as an open source project hosted on one services listed above, maitanence becomes even easier, since any user of the platform can contribute to the project and post issues that need to be addressed by the community. Open source projects add a layer of security, since the code is public and can be audited for abnormalities or security risks by the community or even be patched via a pull request to the project. Users within a community can be classified as one of the three categories:
- User: know and use the project on a regular basis
- Contributor: users that have also implement bug fixes and add minor features
- Committers: all of the responsibilities of the contributor, with the added responisbilities of the following:
    - Code review of bug fixes
    - Merges pull requests to the main code base

Within the committer role, the following positions are present:
- Project Lead
- Exper User: maintains actors, use cases, requirements, and user roles within the project
- Lead Developer
- Developers: maintain the following:
    - User interface
    - Domain Classes
    - Database administration
    - Codebase
    - Testing (unit tests)
    - Packaging
    - Build schedule
- Testers: maintain the following:
    - Bug reports
    - Forum(s)
- Writers: online assistance and documentation
- Bug Marshall(s): triage open bugs within the project
- Release Managers: oversee packaging and release of new versions

Finally, within the whole structure of the project there may be constraints that are domain specific such as:
- Internet access
- Bandwidth
- Power source
- Natural disaster (especially for a centralized data center)
- Learning curve for new systems
- System customization
- Local developers and the learning curve associated with the new software
- Legacy systems
- Data granularity, validity, and redundancy

---
layout: post
title: "Meeting Charleston"  
---

# Meeting Charleston

## Details

- Organization: [ASIS International: Charleston Chapter](http://charlestonasis.org/)
- Date: 3/27/2021
- Topic: Change Management and Successful Strategies to Implement Change

## Meeting Notes

- Change is hard to implement 
- Change is necessary
- If the selected process/software is not broken, don't change
- Successful change is based on employee morale, if the change is not effective, then morale will plummet
- There are many different models for implementing change

## Example

As an example, let us consider **Company X** and **Company Y** who both allow their developers to use a text editor of choice on their `Linux` machines when working on code such as:
- `nano`
- `vim`
- `sublime`
- `notepad++`
- `vscode`
- `leafpad`
- `micro` (Really cool and minimal cli text editor that has syntax higlighting which can be found [here](https://micro-editor.github.io/))
- `pluma`
- `IDEs` (for this example, Company X has built their product with `python3`)

As listed above, there are many different editors in place to edit the codebase. As a bad example of change management, Company X's Lead Developer has recently heard about `vscode`, has began to use it in their workflow, and wants to implement `vscode` team wide. The Lead Developer wants to implement this overnight, with only their approval, and not give their team any time to adjust to the new product into their toolchain or ask for input from their team. This would be an example of a bad change management, since a sudden change would tank the morale of their team and inhibit productivity due to the new learning curve for the new environment. With this sudden change, team members would be more likely to revert back to their previous text editor

On the contrary, Company Y wants to implement the same change as Company X and unify their developers under one text editor to edit the codebase. Company Y's Lead Developer holds a meeting with their team members and guages their opinions on the change and what the pros and cons of each text editor that is used by each of the developers. The Lead then takes that information and does their own research, and narrows their choices down to `nano` and `vscode` due to the minimal learning curve and they were the most popular. The Lead then re-polls their team and `nano` wins. Once `nano` wins, it can be installed on the team's `Linux` machines. This can be done easily, since Company Y has implemented `ansible` across their machines and can deploy the necessary software with the following playbook:

```
---
name: install nano
become: true # become sudo to install nano
hosts: linux # all linux machines in the environment
tasks:
  - name: update repositories
    - apt:
      update_cache: yes
  - name: install nano
    - apt:
      name: nano
      state: present
```

This was a very naive example, but once this scales to network components or even changing direction on a project, it is very important to make sure that the change can occur properly and minimize potential employee morale within the team.