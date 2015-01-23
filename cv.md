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

### 2004 - 2008 : __The Hague University of Applied Sciences__

( <http://www.thehagueuniversity.com> )

Bachelor of Computer Science, (2008).

__Major__: “Information and Communucation technology”

__Minor__: "Technical Computer Science"

At the The Hague University of Applied Sciences I've got two directions of the education - major and minor. Both educations were centered around Computer Science, though each got its own level of responsibility.

Major education was concentrated on high level software development. I was learning modeling languages e.g., UML, different software methodologies, e.g., RUP, XP, testing principles, e.g., ITIL or PRINCE2, object oriented programming based on Java. Also databases and data warehousing were part of the education using Oracle tools and SQL. As an extra addition course of .NET platform with ASP.NET and C#.NET were included in this education.

Minor education "Technical Computer Science" gave me C/C++ and assembly languages, embedded systems (including embedded software and robotica), TCP/IP stack and all other cool low level aspects of software/hardware.

This cooperation of high-level Java, OO together with design patterns and software develpoment methodolgies combined with low level C/C++ and networks helps me to review problems from different perspectives and solve them on correct levels.


### 2003 - 2004 : __The InHolland University of Applied Sciences__

( <http://www.inholland.nl/inhollandcom/> )

__Major__: "Business Informatics".
	
Education at "The InHolland University of Applied Sciences" was mainly focused on Business processes and there was almost nothing technical involved. Since I preffer to dive deep into the technologies and software, this education was a bad match for me. As a result I haven't finished this study and moved to "The Hague University of Applied Sciences" to do the real software development.

### 1990 - 2000 : High-school in Ukraine

Just the usual High-school in the usual city with the usual subjects.


## Courses

* 2011
: Profilering en Zelfmanagement voor ICT-ers ( at Schouten & Nelissen )

( <http://www.sn.nl/> )

"Profilering en Zelfmanagement voor ICT-ers" offers communication skills training that teaches how to deal with critics and how to define more conrcete aims while beening an IT person.

* 2007
: MCP - “Analyzing Requirements 
	and Defining Microsoft .NET Solution Architectures”

* 2006
: Information Technology Infrastructure Library ( ITIL )

* 2005
: Cisco Certified Network Associate ( CCNA )

## Work experience

#### 2010 November - Now : Informaat CXP, Baarn 

( http://www.informaat.com/ )

>Informaat is a design and consultancy agency for digital services, who supports organizations in the development and implementation of their digital strategy.

__Role__ : Developers architect

__Department__ 	: R&D

After five years of working at Mendix ( see below ) I've moved on to the new challenges, possibilities and a fresh start. I moved to Informaat, a company with a deep focus on User Experience ( UX ).

Around this time, Informaat started to develop its own platform called Customer Experience Platform ( CXP ) and tooling (Dialogica). It's was a starting point for this company into the R&D branch. A lot had to happen, researched and tried out to bring the platform in production state. This was the moment where I started to work with Node.js, MongoDB, AngularJS, grunt and other cutting-edge technologies.

__Achievements__ :	 
	
* Creating architecture and implementing schema based persistence layer ( using NodeJS, MongoDB and SocketIO. )

One of my primary ideas are that a product in a start-up company is exposed to rapid changes. In order to be able to deal with fast changes, our architecture should be scalable enough to allow any changes to happen fast and seamless. This mean that changing one part of the architecture should be as flexible as possible and should not trigger "falling domino effect".

There are always parts in the architecture which are static and another ones which change frequently. The Domain Model of the start-up application is something that changes frequently. For that reason I have implemented schema based persistence layer, which allows us to make changes to our Domain Model quickly without any further modifications to the back-end landscape. This is a seamless process that works not only for our back-end machinery, but also changes are instantly available in the front-end.

The main differences of this system from other schema-based persistence layers is that it is totally relational at the backend, but Document Based on the front-end. A very powerful hybrid form which allows JSON manipulation on the front-end with the relational integrity checking at the back-end.

Another important aspect is that the data changes are real-time, and changing a data inside browser of one client, will be broadcast to all of the connected clients.

* Building single-page data-driven client framework ( using Knockout.js )

Our platform delivers a lot of different artifacts and one of this artifacts is the touchpoint bundle. This bundle is a completely standalone HTML5 app which can run as a single-page website or embedded into another portal/web-site.

Client engine underneath this app is responsible for rendering the page fragments, passing data from one view to another. Session management, history management and other facilities of the stand-alone webpage are intergated into the engine. You can think of it as an Angular framework. Only this engine is fully adopted to the Informaat CXP concepts and rules and uses application configuration ( generated by the dialogica ) to drive the whole front-end app.

My responsibility was to setup and implement the initial architecture of it.

* Establishing “Continuous Testing” process ( using jenkins and bash-scripting )

Another aspect of software development is the continious testing and one click deployment. Setting up jenknis jobs and pre-commit hooks in order to guarantee one click deployment mechanism was one of my responsibilites. In this way every commit which developer made started testing process on a remote CI environment. Also releasing our software to acceptance was one click move.

* Setting up UI testing framework ( using Selenium webdriver )

Because we have to support different browsers there was a need in setting up testing framework. There were no Karma, Protractor and SauceLabs  available on the market, so we've developed our own layer to test our code usiing Selenium webdriver. Nowdays, it's all rewritten to the standard technologies, to keep the nonstandard legacy code as small as possible, but it was a tough experience.

* Building selfcontained "Development environment” ( using vagrant, bash-scripting and python )

Because of the use of some legacy systems which could not run on various platforms like OSX, I have introduced  virtual machines with all the skeleton code and helpful tools for fast bootstrap of development process. Our VMS were build on top of the vagrant tooling.

* A lot more

In the time that I worked and working at Informaat CXP I've been busy on a different fields of software development, so there is even more, from small to bigger things, which I haven't covered in my CV.

__Keywords__: node.js, mongo, knockout.js, git, bash-scripting, python, angular.js, jenkins, vagrant, regular-expressions, mocha, socket.io

#### 2008 February - 2010 October: Mendix BV, Rotterdam

( http://www.mendix.com/ )

>Mendix is the app platform company for the enterprise. The Mendix App Platform enables companies to build, integrate and deploy web and mobile applications faster and with better results, effectively driving ROI in days, not months.

__Role__ : Senior JavaScript developer

__Department__ 	: R&D

After I've finished my final university assessment, I've stayed working at Mendix at the position "Lead developer of the Mendix Client Framework". This was the moment when focus was on a stabilization of the Mendix Platform.

__Achievements__ :

* JavaScript performance analysis, IE6 ( using memory profiler )

Most apps which were ceated by the Mendix Platform grew into complex applications - screens became more full of complex data and a lot of conditinal rendering was applied in them. It were not simple forms anymore but complex nested multi-tab interfaces. All this made generated apps runs slower not only in old browsers, like IE but also in newer ones. 

Since our requirement was to support Internet Explorer 6, I had to dive deep into the memory analysis in order to optimize rendering of the apps. At that time there was a tool called "JavaScript Memory Validator ( http://www.softwareverify.com/ )", which gave a very low-level footprint of the browser's memory. Using this information helped me really a lot of in getting better understanding of the internals of the JavaScript engine e.g., how objects are created in the browsers memory, the way garbage collector actually works, where memory leaks can reside and other js-engine's aspects. After couple of weeks of profiling I achieved user accaptable rendering of the applications.

* Improving and stabilizing the previous version of the Mendix Client Framework

Besides memory leaks and fast rendering of the application inside Internet Explorer 6, customer satisfaction is depending on the stability of the Framework itself. Improving, refactoring, cleaning up, stabilazing and making product stone-solid was my task. It was a busy process, full of long days and nights, but result was above any expectations. We could deliver very stable and light and clean version ( 2.4 ) of the Mendix Client Framework.

* Creating architecture and implementing next version of the Mendix Client Framework ( v. 2.5 )

Improvement and stabilization was the fundamental part of the next version. In this version ( 2.5 ) I took responsibility to become lead developer. A lot of new features had be added, but also a lot of work had to be done for future plans. Most of the stuff was even not visible to the user yet, but gave a fundament for the functionality which came in further releases. To build a high quality product, it's important to design and implement every layer, step by step, changing parts "today", which will be needed only "tomorrow".

* Teaching and supervising junior JavaScript developer

Not only programming was part of my daily tasks, but also supervising a new junior JavaScript developer. Teaching him all the corners of our architecture and giving him different assessments. Explaining all the details to him made things more clear to me, so it was a very useful period of my work at Mendix. Collaboration in work makes people closer and we became not only good colleges, but also a good friends after all.

* Supervising student for his graduate project

Besides suprevising a junior JavaScript developer I also was supervise one student on his final University assessment.

__Keywords__: IE6 performance, memory analysis,  supervising junior, architecture 

#### 2007 September - 2008 February: , Mendix, Rotterdam

( http://www.mendix.com/ )

__Role__ : Student ( graduation assesment )

__Department__ 	: R&D

At my last year of the education at The Hague University of Applied Sciences, I had to do the final assesment. My subject of the assesment was "Server-push technoogy and it's implementation inside HTML web apps". I had to investigate in all the possible solutions at that time, find a suited one for Mendix platform and implement it on the server and in the client. There were two deliverablse of this assesment. Working system for the Mendix and process-report for the University.

__Achievements__ :

* Designing and implementing server-push technology in the Mendix Application Server and Mendix Client Framework

While investigating in different server-push technologies I've choosen a Bayeux protocol. It was defined by dojotoolkit group and was ongoing project of them, which later resulted in CometD ( http://cometd.org/ ). Even though the protocol was defined and some support was already build into dojotoolkit, the main challange was to add support of it into at the Mendix backend and connect client and server together. It was an interesting project, whereby I ( not only me, but the whole dojo community ) was trying to solve the limitations of the HTTP protocol in non standard way. My achievement of this project is the 8.5 grade which I recieved for my final report. 

__Keywords__: Comet, Bayeux, Jetty Continuation

#### 2006 May - 2007 February: Mendix, Rotterdam

( http://www.mendix.com/ )  

__Role__ : Dual student

__Department__ 	: R&D

After I've finished my internship I've decided to stay at Mendix. Despite I was was a student, I've switched to the "Dual education" so that I could combine work and my study together.

When working there as a dual student, I had to perform different tasks, not only related to the JavaScript and dojo, but also to C# and Java.

__Achievements__ :

* Implmeneted Webservices module for backend system in Java ( using Apache Axis ) and implemented extra layer to handle DIME attachements

My task was to implement webservice support inside Mendix Application Server, so that it could connect to the webservices and interchange data between them. The one unusual aspect of that project was, the fact that this module had to support also DIME attachements, which were not included in the Apache Axis library at that time. Armed with DIME specs I've devide into the XML, WDSL, SOAP and other aspects of webservices.

* Implemented "Planner" UI-module ( in JavaScript )

One of the requirements for one of our customer was to have support for planning widget, similair to Gantt charts. A lot of Drag and Drop ( dnd ) logic was invloved in there. And ofcourse because we had to support IE6, it was challanging to get it perform well in this browser. This project gave me a good starting point to start collecting knowldge in how to write efficient DragNDrop code.

* Creating Planning module for Mendix Business Modeler ( in C# )

In order to use planner widget inside the client, it also had to be implemented inside the Mendix Busnisse Modeler. All work was done using .Net C# and GDI+.

* Implementing portal ( in JavaScript )

iGoogle at that time was something very sweet to look at: all these configurable portlets with different information, customizable for every user, a lot of drad-n-drop, animation, etc. It was something what was attractive for a lot of people and Mendix decided to include such possibility inside their platform. My task was to create a set of custom widgets and create infrastructure for configurable 'portlets'.


__Keywords__: WSDL, SOAP, Dime, .NET C#, IE6, DnD

#### 2005 November - 2006 May: Mendix, Rotterdam

( http://www.mendix.com/ )

__Role__ : Junior JavaScript developer

__Department__ 	: R&D

Started working at Mendix as student ( Intern/Internship ) as Junior JavaScript developer. This was the beginning of the Mendix history and my proffesional career. Their idea was and is still is very simple: "Build, run and deploy app using Mendidx Platform". Mendix Platform includes Business Modeler, which is used to build an app ( using form-builder ) and deploy it to the Mendix Application Server. Deployed apps run in a browser as single-page applications using Mendix Client Framework. The main difference between Mendix and others was that Mendix generated only configuration of the app totally and no code, which they later called Model Driven Development.

My knowledge base of JavaScript was almost equal to nothing.

__Achievements__ :

* Creating widgets for web-based client framework ( using dojotoolkit )

At that time Mendix Client Framework was based on the dojotoolkit ( http://dojotoolkit.org/), and even though dojo had already stack of satndard ui widgets at that time, there was a lack for custom widgets which Mendix was planning to use. So my role as a student at this startup company was to write code for different custom widgets.

* Thesis: Composition versus Inheritance in Java

As an intern student I also had to write a thesis. My subject was "Composition versus Inheritance in Java". The main idea of it was to see what does bring compision in place of inheritance. Does it solve a problem of deep hyerarhical relations. And what are the tradeoffs using composition instead of inheritance. Questions like maintances problem of the inheritance and the memory consumption where also covered in there.

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

## Etc

**Keyboard**: dvorak
**Editor**: ViM
**envn**: terminal, gnu screen
