# Curriculum Vitae

## Personalia


**Name**: Maksim Nemisj

**Birthdate**: 23 october 1984

**Nationality**: Ukrainian

**Driving license**: A, B

**Marital status**: Married

**E-mail**: <maks@nemisj.com>

**Blog**: <http://nemisj.com>

**Github**: <https://github.com/nemisj>

## Languages

* Russian: native language
* Ukrainian: native language
* Netherlands: fluent (speaking, reading, writing)
* English: fluent (speaking, reading, writing)


## EDUCATION

### 2004 - 2008 : __The Hague The University of Applied Sciences__

( <http://www.thehagueuniversity.com> )

Bachelor of Computer Science, (2008).

Major: “Information and Communucation technoloty”. 
Minor: "Technical Computer Science".
	
At major education I was learning UML, RUP, ITIL, Java, SQL and Data warehousing ( using Oracle tools ). Also the part of the course was working with .NET platform, mostly ASP .NET and C# .NET 

Technical Computer Science gave C/C++, Assembly, Embedded systems and robotica, TCP/IP stack and all other cool low level stuff.
	

#### 2003 - 2004 : __InHolland The University of Applied Sciences__

( <http://www.inholland.nl/inhollandcom/> )

Major:"Business Informatics".
	
Have not finished it, since moved over to "The Hague The University of Applied Sciences". Education was focused mainly on Business processes and almost nothing on technical.

##### 1990 - 2000 : Highschool in Ukraine


## Courses

* 2011
: Profilering en Zelfmanagement voor ICT-ers ( bij Schouten & Nelissen )

* 2007
: MCP - “Analyzing Requirements 
	and Defining Microsoft .NET Solution Architectures”

* 2006
: Information Technology Infrastructure Library ( ITIL )

* 2005
: Cisco Certified Network Associate ( CCNA )

## Work experience

#### 2010 november - till now , Senior JavaScript developer,  Informaat IPE BV,  Baarn 

( <http://www.informaat-cxp.com/> )
	
__Department__ 	: R&D

__Achievements__ :	 
	
* Architecturing and implementing schema based persistence layer ( using node.js, mongo and websockets. )

This machinary helps Informaat to extend Domain Model of an application  without need to touch any part of the backend code and enables us to have immediate realtime persistence within the browser. While backend and schemas are relational, data on the client is Document based, which gives developers power and freedom to work with it. 


* Building single-page data-driven client framework for Customer Experience Platform ( CXP ) “Dialogica” ( using knockout.js )

This framework is using "model" to display single-page application in the browser. The application flow and data flow of the ui is fully drivven by the "model" itself. You can think of the model, like "configuration" of the single-page application. Model is drawn in Dialogica in a form of a data flow diagrams whih is interpreted by the client framework.   

* Establishing “Continuous Deployment” process ( using jenkins and bash-scripting )

Setting up jenknis jobs and pre-commit hooks in order to guarantee one click deployment mechanism

* Setting up UI testing framework ( using Selenium webdriver )

Before Protractor of angular came out, had to write test runner which could execute tests ( in javascript ) using selenium and report them to the Jenknis.
		
* Building selfcontained "Development environment” ( using vagrant, bash-scripting and python )

Because of use of some legacy systems which could not run on various platforms like OSX, introduced and implemented vagrant virtual machine with all the skeleton code and helpfull tools for fast bootstrap of development.

* Coach developers for "JavaScript best practices"

* Build ??? on top of "git"

__Keywords__: node.js, mongo, knockout.js, git, bash-scripting, python, angular.js, jenkins


#### 2008 february - 2010 october: , Senior JavaScript developer, Mendix BV, Rotterdam

( http://www.mendix.com/ )

After I have finished my final assesement I stayed working at Mendix and become main developer of the Mendix Client Framework.

__Department__ 	: R&D

__Achievements__ :

* JavaScript performance analysis, IE6 ( using memory profiler )

Created by the Mendix Platform apps became bigger and bigger. Logic inside it became more complex and screens became more full. Since our requirement was to support Internet Explorer 6, I had to dive deep into the memory analysis and memory leaks and fix that. At that time there was a tool : JavaScript Memory Validator ( http://www.softwareverify.com/ ) which gave a very low-level footprint of the browser's memory. Got really a lot of profiling experience and a lot of knowledge of the JavaScript internals, like how objects are created in memory, how they constructed and destroyed, how garbage collector actually works and another kind of js-engine aspects.

* Improving and stabilizing the previous version of the Mendix Client Framework

Besides memory leaks and fast rendering of the application inside Internet Explorer 6, customer satisfaction is depending on the stability of the Framework itself. Improving, refactoring, cleaning up, stabilazing and making product stone-solid was my task. It was a busy process, full of long days and nights, but result was above any expectations. We could deliever very stable and light and clean version ( 2.4 ) of the Mendix Client Framework.

* Creating architecture and implementing next version of the Mendix Client Framework ( v. 2.5 )

Improvement and stabilization was the fundamental part for the next version. In this version ( 2.5 ) one where I was leading architect. A lot of new feutures where added, but also a lot of work was done for future plans. Most of the stuff was even not visible yet, but gave a basic for the functionality which came in further releases. To build a high quality product, it's important to design and implement every layer, step by step, changing things today which will be needed "after tomorrow".

* Teaching and supervising junior JavaScript developer 

* Supervising student for his greduate project

__Keywords__: IE6 performance, memory analysis,  


#### 2007 september - 2008 february: Greduate student, Mendix, Rotterdam

( http://www.mendix.com/ )

At my last year of the education at The Hague The University of Applied Sciences, I had to do the final assesment and write process-report of it. My subject at that time was "Server-push technoogy".

__Department__ 	: R&D

__Achievements__ :

* Designing and implementing server-push technology in the Mendix Application Server and Mendix Client Framework

At this time I had to implement server-push technology on the backend but also on the fron-end, so end-2-end solution. There were a couple of different approaches at that time, but I stoped at Bayeux protocol defined by dojotoolkit, the main challange was to add support of it at the backend and connect both worlds together.

__Keywords__: Comet, Bayeux, Jetty Continuation

#### 2006 may - 2007 february : Dual student, Mendix, Rotterdam

After I finished my internship by Mendix I have decided to stay there. Because I was still studen I had to switch to the "Dual education" so that I could combine work and study together.

When working there as a dual student, I had to perform different tasks, not only related to the javascript and dojo, but also to the C# and Java.

__Department__ 	: R&D

__Achievements__ :

* Implmeneted Webservices module for backend system in Java ( using Apache Axis ) and implemented extra layer to handle DIME attachements.
	
One of my projects in that period of time was to implement Webservice layer inside Mendix Application Server, so that it could connect to the webservices. The one unusual aspect of that project was, that this module had to support also DIME attachements.

* Implemented "Planner" UI-module ( in JavaScript )
	
This was custom widget to have minimal ui for Gantt chart like planngins. A lot of Drag and Drop ( dnd ) logic was invloved and at that time it also had to perform on IE6, so that was a bit challange. The knowldge of the dnd and performance tricks of dnd I also reused in another project "Web-Portal" 

* Creating Planning module for Mendix Business Modeler ( in C# )

In order to use planner module in the client, it also had to be implemented inside Modeler tooling, so that it could be included in the builded app. All work was done inside Mendix Business Modeler using .Net C# and GDI+.

* Implementing portal ( in JavaScript )

iGoogle at that time was something very sweet to look at, all this configurable portlets with different information, customizable for every user. It was something what was attractive for a lot of people and Mendix decided to include such possibility inside their platform. Mostly I was creating set of custom widgets and creating infrastructure for configurable 'portlets'. Again, dnd was, on-fly save of configuration and other effects were the challenging parts


__Keywords__: WSDL, SOAP, Dime, .NET C#, IE6, DND

#### 2005 november - 2006 may: Junior JavaScript developer,  Mendix, Rotterdam

Started working at Mendix <http://mendix.com> as student ( Intern/Internship ).

This was the beginning of the Mendix history and my proffesional career. Their idea is very simple, to build, run and deploy app using Mendidx Platform. Mendix Platform includes Business Modeler, which is used to build an app ( using form builder ) and deploy it to the Mendix Application Server. Mendix Client Framework, single-page client framework which runs deployed app in the browser.

__Department__ 	: R&D

__Achievements__ :

* Creating widgets for web-based client framework ( using dojotoolkit )

At that time Mendix Client Framework was based on the dojotoolkit ( http://dojotoolkit.org/), and even though dojo had at that time already some stack of ui widgets, there was a lack for custom widgets which Mendix was planning to use. So my role as a student at this startup company was to code different custom widgets and other ui components.

* Thesis: Composition versus Inheritance in Java

As an intern student I also had to write a thesis. My subject was "Composition versus Inheritance in Java". The main idea of it was to see what does bring compision in place of inheritance. Does it solve problem of deep hyerarhical erlations.  Also I looked not only at the maintances problem of the inheritance but at the memory consumption when composition used and inheritance.

__Keywords__: Native javascript, dojotoolkit
 
## Technologies:

Languages: JavaScript ( including ECMAScript 6 ), CSS3,  HTML5, Python, Java/J2EE, bash-scipting, C# .NET, C ( basis ),  Assembly ( basis ), Clojure ( basis )

Methodolgies: SCRUM, ITIL, Rational Unified Process ( RUP ), Extreme Programming (XP)

Technologies: Node.js, REST, UML, SQL, XSD/XSLT/XML,  Web services (SOAP, WSDL)

OS: Intermidiate administration of Linux ( Debian based ), advanced usage of Windows XP and OSX

Additional: Design patterns, TCP/IP networks, Embedded systems

Keywords : DOJO, jQuery, Backbone, Sencha, Heroku, couchDB, mongoDB, REST, json, nodejs, npm, Selenium,  Jenkins, svn, git, mercurial ,vi/vim, eclipse, fabric, asynchronous code

## Hobbies

* Karate
* Motorcycling
