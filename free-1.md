# Free project 1

## The user and a language

This section describes who the project would serve and why a language might be a
good way to meet their needs.

People trying to balance their worklife and personal life - on their phones and laptops. Notifications are an important way of keeping track of things, but they are also very destracting and often even anxiety inducing. And the toggles given to manage notifications do not provide personalisation. Being able to program 

You could code in what times and which apps are allowed to send pop ups. You can code in specific users from within an app (say, I want text messages from my boss to come through, but do not want text messages from colleagues or companies.) You could group together apps which can be turned on and off in a single click (For instance, I have Whatsapp, Messenger, Telegram and Signal - which all do the same thing and I hate having to individually turn all of them on or off. And I can't turn ALL my notificitions off because some are important.). There is just a lack of flexibility, and having way too many notificitions and way too less notifications are both problematic. Being able to go in and program your notifications would be a lot of help. Doing so would be wayy too much work via a general purpose PL. 

### What's the need?

_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help
them?_

Problem : 

### Why a language?

_Why is a DSL appropriate for your user(s)? How does it address the need?_

Why not an app: There exist ways to manage notifications on phones and laptops, but these have very limited functionality.

Why not a general purpose language: Managing notifications and producing a companion applet would require some communication with the Operating System itself which has a big learning curve and might be hard to pull off. 

A DSL allows you abstract away the internal complications, and allows the user of the language to use simpler commands to group apps, group people, set time based on and off, and control the notifications within each app. 

### Why you?

_What excites you about this idea? How did you come up with it?_

This idea excites me for two reasons. First, because it seems like something I could use. Second, not only does it seem useful to myself - our interviewees complained about notifications too when we interviewed them about their relationship with computers. 

### Domain

_Describe the project's domain in five words._
Notification management applets and personalisation. 

### Interface (syntax)

_How might the user interact with the language? What does programming look
like? Why is this the right way to interact with the problem domain?_



### Operation (semantics)

_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

Makes applets with personalised notification management.

The applet will have toggles that are more personalized. You can have a toggle for "Chris", you can have a toggle for "Instagram+Snapchat+Facebook". 

### Expressiveness

_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

Easy : Notif managements

The language will have if/then (to allow things like {if xyz then block notifications from abc}

Difficult : The language most likely won't have loops or recursion - which will make it hard to 

### Related work

_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

## The Project

This section examines whether the idea makes for a good CS 111 project.

### Suitability

_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

### Scope

_How big an idea is this? How ambitious is this project?_

### Benefits and drawbacks

_Why might this be a good idea for a project? Why might this not be a good idea
project?_
