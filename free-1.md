# Free project 1

## The user and a language

This section describes who the project would serve and why a language might be a
good way to meet their needs.

People trying to balance their worklife and personal life - on their phones and laptops. Notifications are an important way of keeping track of things, but they are also very destracting and often even anxiety inducing. And the toggles given to manage notifications do not provide personalisation. Being able to program your phone's notif system and/or make a personalised applet would be really great.

You could code in what times and which apps are allowed to send pop ups. You can code in specific users from within an app (say, I want text messages from my boss to come through, but do not want text messages from colleagues or companies.) You could group together apps which can be turned on and off in a single click (For instance, I have Whatsapp, Messenger, Telegram and Signal - which all do the same thing and I hate having to individually turn all of them on or off. And I can't turn ALL my notificitions off because some are important.). There is just a lack of flexibility, and having way too many notificitions and way too less notifications are both problematic. Being able to go in and program your notifications would be a lot of help. Doing so would be wayy too much work via a general purpose PL. 

### What's the need?

_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help
them?_

Problem :  There is a lack of flexibility when it comes to notifications, and having way too many notificitions and way too less notifications are both problematic. Way too many, and you get distracted/anxious and way too few notifications and you miss out on important things. 

If you could provide finer control, I would feel a lot more comfortable.

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

The programming language provides some easy functions to give finer control over notifications. PLs have a lot of control and flexibility. You could code in new timings, new toggles, etc. 


### Operation (semantics)

_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

Makes applets with personalised notification management.

The applet will have toggles that are more personalized. You can have a toggle for "Chris", you can have a toggle for "Instagram+Snapchat+Facebook". 

The programming language provides some easy functions to give finer control over notifications. Auto set times. Create new modes (right now, most modes on an iPhone either turn all notifications off or keep all of them on). You could have a school mode, an introvert mode, a family mode, etc. etc. You could create new toggles which allow you to turn on or off smaller/bigger groups. You could turn off all social media with one toggle, or turn off just a single person from a single social media with one toggle. Now, you can only toggle individual apps - nothing bigger, nothing smaller. 

So essentially, there will be two aspects of the DSL. One with immediate deployment. I could program (turn off whatsapp from 9am to 5pm) and hit run, and it will do that everyday on my phone. And one is a deployment that shows up in a new applet. I could program (CREATE button WITH Instagram, Snapchat) and it will show up in an applet and you can now control those two through one button whenever you want. Any functions with "CREATE" will show up in the applet, and any other functions will deploy as soon as you hit run. 




### Expressiveness

_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

Easy : Notif managements

The language will have if/then (to allow things like {if xyz then block notifications from abc}, so you will be able to do some other coding.

Difficult : The language most likely won't have loops or recursion - which will make it hard to do anything super advanced. And the program's output is in the form of notification management which makes it hard to do anything else.

### Related work

_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

There is apps for notification management, but most do not provide systems level control. They just allow you to set quiet periods and things like that. 
There probably is no DSL, to my knowledge, because DSLs seem to be aimed at professions, and apps aim at users - but in this case, I would benifit greatly from a DSL to manage my notifs.

## The Project

This section examines whether the idea makes for a good CS 111 project.

Maybe? It is too narrow a focus though.

### Suitability

_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

I feel like the systems side of this might be hard because I don't know how to interact with all the apps on a phone and control their notifications. Design is important too though, since it needs to be intuitive and easy to use.

### Scope

_How big an idea is this? How ambitious is this project?_

I think it is a pretty small idea. It doesn't do much outside block and allow notifications. Nothing groundbreaking.

### Benefits and drawbacks

_Why might this be a good idea for a project? Why might this not be a good idea
project?_

Good idea: I myself will use such a DSL. It feels useful for anyone that wants to hardcode their notifications instead of relying on sleep mode and do not disturb mode.

Bad idea: It feels very small and meaningless. I don't know how much more functionality I can add compared to an app. 
