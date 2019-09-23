# 4HC3 Human Compute Interaction

## Table of Contents
- [Elm Architecture](#elm-architecture)
- [Assignment 1](#assignment-1)
- [Communication](#communication)
- [Elm](#elm)
- [Design Thinking](#design-thinking)
- [Marking](#marking)
- [What is Design](#what-is-design)
- [Counter Example for Good Design](#counter-example-for-good-design)
- [Design Vocabulary](#design-vocabulary)
- [Tutorial Assignment 3](#tutorial-assignment-3)
- [The Psychology of Everyday Actions](#the-psychology-of-everyday-actions)

## Tutorial 1 - Sept 3, 2019

### Elm Architecture
- kinda works like react
- interact with the DOM

### Assignment 1
- create a button that clears the stopwatch timer app
- https://github.com/christopheranand/HC3_2019/blob/master/Assignments/Assignment1.elm

## Day 1 - Sept 4, 2019
- interface
    - between 2 faces
    - not the skin of the application
- interaction
    - dynamic
- task based inteface design
    - what does the user need
- book: The Design of Everyday Things by Don Norman

### Communication
- interaction is about communication
- simple information is harder to display since there is an expectatin to understand the information easily
- should design intuitively
- need to communicate to user what things they can do

#### Exercises
- chapter 1-6
- good to say that you know design thinking :hushed:
- default project: go find a user who has problems with math

### Elm
- compiles into javascript
- fully functional
- safe

### Design Thinking
- double diamond (insert diagram)
- there are 2 different kind of processes
- need a divergent phase where we generate different ideas
- some people like coming up with multiple ways of doing something and others want to find one right way
- it's good to be in a team that has both of the above
- need to research 
- understand things in others POV (empathy)

## Day 2 - Sept 5, 2019

### Marking
- 1% for tutorial assignment 1
- n = 9 tutorial assignments (2-5)
- 10 bonus, oct 2 - reflection
- midterm - one essay question - oct 21
- free tool - mural.co - for design thinking presentation (Oct 28) - 10%
- 14-n suprise avenue quizzes
- 30% for project pitch + backup report
- 20% for final exam + short essays
- finite state diagrams
    - https://macoutreach.rocks/paldraw/
    - http://www.cas.mcmaster.ca/~anand/ShapeCreate2.html
    - escape math game

## Day 3 - Sept 9, 2019

### What is Design
Design is people deciding how something should be

Instead of calling it philosophy he called it design of every day things. Users didn't understand what he book was about. the publisher told him to put design in the title but users don't want to read a book that says philosophy in the title. It gives them an appraoch to design their house, lives, etc

The Escape Math Island game uses this philosophy of design. The kids who develooped it followed a design thinking approach.

Sometimes you will wish you could just get started, if you are close to the deadline. But its almost guaranteed that you will deisgn something that will not work well if you dont iterate and think of many possibilities. It almost never works out the way you thought.

### Counter Example for Good Design
A counter example is CRUD - create read update destroy, a software interface, API operations. Lots of ways a user could get to a point and say 'I don't know what to do now'. It's bad because we're focusing on low-leve tasks, not the high-level tasks that the user needs to accomplish. It means we need to memorize all the commands. For a dev it's straight to the point.

Human entric design is about the experience, if it's easy to do and can we do it. It is highy subective and cannot tell if we are doing it right.

There are principles that people have come up with for this stuff. 
- the science of how the brain works
- the double diamond

### Design Vocabulary
- different languages have different definitions but it is esy to talk about things when there is one agreed upon definition
- a lot of our vocab will come from Norman
- he didn't invent these words, except maybe human centric design

#### Affordance
- a design vocab term from Norman
- taking 2 ideas and putting it into one term
- no one can talk about why something failed when there are 2 reasons
- affordance is the relationship between physical object and person
- eg handle on a coffee cup
- the chair affords sitting
- a high chair affords sitting for infants
- a cup handle is not an affordance
- relationship between handle and person creates an affordance
- an affordance doesn't have to be something you have to see, it is a relationship

#### Signifier
- comes from philosophy
- this is what many UI designers think an affordance is
- eg a sign on a web interface (something visible) is a signifier
- when you press a button at a crosswalk, the beep beep noise is a signifier for when you will be able to walk
- signifier is a percievable indicator (can be seen, heard, touched, etc)
- controls for adjusting a seat (that you can feel)
- the affordances that you fee can be more important to blind people
- buttons are the most common and obvious signifier
- eg a rectangle with words is commonly thought to be a button
- software bookmarks/physical bookmark

## Day 4 - Sept 11, 2019

- Norman doors lack signifiers
- things that aren't signifiers can be considered to be signiiers
- anti-affordances show where not to go
    - eg there is a barrier with gaps can be anti-affordances where cars can't go through but people can
    - grayed out button can be anti-affordance (means somtimes there is an affordance but there isn't one now)

#### Mapping
- function from one set to another
- natural mapping 
    - based on spatial relationship
    - means someone can come and look at your controls and not have to memorize them
- can't always use mapping if it doesn't exist

#### Feedback
- tell user what you are doing
- many users abandon tasks for lack of feedback
- if you give too much feedback you just overload 
- they will not know which signals are important and which can be ignored
- avoid giving feedback that you don't need
- kind of like the boy who cried wolf
- we can only process so many things at a time
- hospital rooms and cockpits are archetypical examples
    - many dials and buttons and things
    - if they all start beeping at once you will be panic

## Day 5 - Sept 12, 2019 

#### Conceptual Models
- example: files, folders, icons
- good: allows us to guess what will happen if we do something
- bad: using local storage model for cloud-based storage
    - weird to think that things are stored in clouds
- designers have to pay attention to the users conceptual model
- can be a cultural thing
- in a system
    - product + documentation
    - conceptual models are cognitive condtructions for prediction
    - user builds model as a result of their knowledge and interaction with the system
    - designer must communicate with user
- bayesian learning
    - prior probability - user is expecting the product to behave like their probable idea of the world around them
- paradox of technology
    - increase in tech is overwhelming
    - there are a lot of 'probable ideas' (ref: bayesian learning)
    - people propose more technology to make everything simpler
        - eg auditory interfaces
        - AI butlers
        - google glass
        - ubiquitous surface (AR/VR?)
    - these ideas could fail or take away human agency
    - can have acivity based interfaces or just not develop these things

##### The Design Challenge
- great design requires great teams and teams need great management
    - marketing
    - sales
    - hardware
    - manufacturing
    - software
    - designers

### Tutorial Assignment 3
- 7 points in backup report + presentation for 2 of the points (1 good 1 bad)
- due monday 
- feeback, mapping, affordance, signifier
- discoverability, conceptual model, constraints

## Day 6 - Sept 16, 2019

### The Psychology of Everyday Actions
- basic psychology is that our brain has a lil scientist that is doing experiments to figure out life
- when we can't open a jar we run the jar lid with hot water and the jar part with cold water
    - because we know materials expand when heated
1. form a model
2. make a hypothesis
3. take actions
4. observe results
5. revise model and start over

#### Gulfs of Execution and Evaluation
- we need reasons to run experiments
- most of the time we are just curious or want to achieve a goal

#### Seven Stages of Action
- this is how we analyze interfaces and errors
- components
    1. goal
    2. plan
    3. specify
    4. perform
    5. perceive
    6. interpret (perceived changes)
    7. compare (expectation vs actual changes)
- can be goal driven (based on internal goal) or event driven (reaction to environment)

## Day 7 - Sept 19, 2019

conscious | unconscious
----------|-------------
slow | fast
controlled | automatic
7 registers | multiple resources
for first times | skilled behaviour

- conscious
    - narrator of your life
    - one step at a time
- unconscius
    - internalized

### Learned Helplessness

### Positive Psychology
- make sure your app is giving user a sense of success
- reinforce success
- people learn from their mistakes
- turn failure into learning experience
    - IDEO: design company, slogan is fail often, fail fast