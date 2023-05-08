# Instant-AI-SW-Engineering-Tasks

# Instant Tasks Software Engineering

## Task1 V-model
it is an SDLC model. and it is shaped as the letter V.similar to waterfall model it executes in a sequential manner.  It is based on the association of a testing phase for each corresponding development model meaning for every single phase in the development cycle there is directly an associated testing phase. It is also known as Verification and validation model.

### when to use? 
* when the requirements are clearly defined and fixed.Example Medical Development Field.
### advantages: 
* simple and easy to understand 
* easy to manage since each phase is completed one at a time
### disadvantages
* not a good choice for long projects
* the production of a working software is late 

## Task2 DevOps Tools for each phase

### Planning
* Jira and others like Trac
### Development
* Apache Maven, Apache Ant, Gulp.
* Jira, Git
### Integration
* Jenkins 
* version control system
### Deployment
* Docker, Anisble
### Monitoring
* New Relic
* Prometheus
### Feedback
* Jira Service Management
* Parlor
### Operation
* Opsgenie: Opsgenie is a DevOps tool used to prepare for, predict, and resolve service disruptions

## Task3
UML? is a modern approach to modeling and documenting software
diagrammatic representation of software components. so that we can understand possible flaws or errors in software. 
Types of UML? 
* Behavioral (describe the behavior of the system, its actors and its building components)
    - Activity Diagram: used to describe the flow of different activities and actions.
    - Use Case Diagram: used to analyze the system’s high level requirements.
       main components: Functional Requirements, Actors, Relationships
    - Interaction Overview Diagram: we have a subset made of four diagrams, called Interaction Diagrams:
      Interaction Overview Diagram  is an activity diagram made of different interaction diagrams.
         - Timing Diagram is used to represent how objects and actors act along a linear time axis.
         - state Machine used to describe the different states of a component within a system.
         - sequence describes the sequence of messages and interactions that happen between actors and objects.
* Structural (analyze and depict the structure of a system)
    - Class Diagram: contain classes, alongside with their attributes (also referred to as data fields) and their behaviors (also referred to as member functions).
    - Object Diagram
    - component Diagram: help break down the system into smaller components.
    - Composite Structure represents the internal structure of a class and the relations between different class components.
    - Deployment Diagram: visualize the relation between software and hardware. 
    - Package Diagram:  show the relations between the different large components that make up a complex system.


## Task4 Software Archetichture
* Layered Pattern: the software is divided into units and each layer provides services to a next higher layer.
and it has 4 main layers: 
Presentation => Application => Business Logic => Data Access
UI => Service => Domain => Persistence 
usage:Desktop Applications

* Pipe and Filter: has independent entities called filters which perform transformations on data and process the input they receive => pipes which serve as connectors for the stream data being transformed
usage: Compilers

* Client-Server: 2 parties server and multiple clients 
   - server provides services to clients 
   - clients request services from the server
   usage:Online applications => email. document sharing and banking
  
* MVC divides application to 3 parts:
   - model (has the functionality and data)
   - view (display the information to the user)
   - controller (handles the input_
   usage: WWW applications in major programming languages

* Event-Bus: has 4 components:
  - event source: publish messages to particular channel on an event bus
  - event listener: subscribe to a channel and are notified of messages that are published to a channel to which they have subscribed before
  - channel 
  - event bus
  usage:Android development and notification services

* Peer-to-Peer: has individual components known as peers which they both function as a client or a server or as both. and it can change its role dynamically with time.
  usage: File-Sharing Like Gnutella





# Rana (2023)
