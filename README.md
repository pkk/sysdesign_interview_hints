# System Design

## Overview

I would like to breakdown the solution into the following

1. Requirments ( Scope )
2. Estimation ( Scale )
3. Interfaces / APIs
4. Entities & Relationships
5. Architecture / Design
6. Misc: Scaling, Monintoring / Observability, Handling Failures etc... 

### Requirement ( Scope )

Try to scope down the problem. These interviews last for about 30 to 45 minutes and it is implicit that the solution being sought is for a specific feature set or a feature. 

For e.g. 

1. posting and viewing pics on instagram may be a well scoped problem i.e. one doesn't have to deal with features like search, tags etc ...
2. Posting and Viewing tweets would be a well scoped problem and one may ignore following, adding friends etc ...

### Estimation ( Scale )

This is eseentailly about rough estimates about size of the system (number of tweet, transactions per second, etc ...), storage and bandwidth requirements

1. Size of the System: Esitmate around number of message/files etc ...
2. Storage : storage required estimate. Different types of files and their size ( e.g. text files vs photos vs audio/video)
3. Network : bandwidth required

## System Interface: 

It is a good ideal to break down the problem into a set of API's ( restrict it to 2 or 3 APIs if feasible )
e.g. 

1. API to Send A Survey 
2. API to Post Survey Answers
3. API to analyze a Survey


## Entities & Relationships

Simply put, try to oversimily the application into few tables ( Entities ) and relationships between them

One doesn't  needs relationship in DB as it can be managed via code 

Also, talk about what needs to be encrypted ( if any e.g. PCI related data)

This discussion should come up with some suggestions on DBMS one would like to use RDBMS, Document store, Time series db etc ...

*Entertain a dicussions here, as it helps you understand thought process*


## Architecture / Design

Start out with block diagrams ensure a flow is established i.e. where inputs is received, processed and stored.

e.g. Application Server, DB , Blob Store, Webserver etc...

Check which part of the said design one wants to discuss more and then go in details of design ( could be OOP, frameworks, tools, etc ...)


## Scaling

Disclaimer : I find this very subjective and most time the methods one applies are pretty much standardizes unless some commpany uses some inhouse mechanisms ( and they typically turn out to be poor immitations of best practices or Open source tools)

I will provide links to some documents. This is highly subjective but I personally look for / talk about how to mointor the system. 
## Prerequisite
### Online 

#### Test your technology ( Zoom, Hangout, etc)
__Very elementary but one would be surprisied to know how often we, as a community, fail at basics__ 

* Ensure microphone is working
* Ensure Video ( if required ) is working 
* Bandwidth is sufficient for A/V + Screenshare
* A test call with a friend / family, to ensure the above is working fine.
* Avoid any sofware updates before the interview

#### Handy tools

* https://excalidraw.com
* https://app.diagrams.net

### Onsite

