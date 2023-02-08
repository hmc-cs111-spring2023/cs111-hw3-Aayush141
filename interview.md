# Interview project

## The user and a language

This section describes who the project would serve and why a language might be a
good way to meet their needs.

Anyone studying climate change data. A language would help perform manupulations on climate specific datasets, and visualize it in a manner that is specific to weather and climate visualisation. 

### What's the need?

_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help
them?_

Right now, people looking to present and understand climate change data and try out different possibilities of future need to use a lot of tools, or use a more general PL which doesn't have helpful abstractions for climate change. Understanding RCP scenarios, location based scenarios and domino effect impacts are really hard and cumbersome to do via apps or General PLs. Making the output interactive is very hard too. But this is often necessary within this field.

### Why a language?

_Why is a DSL appropriate for your user(s)? How does it address the need?_

A DSL would provide abstractions that would be really useful to do something as specific as this. This would bring in several people into the fold who have ideas or care about the climate but cannot participate because of the high barrier to entry. It also helps people currently studying or presenting it.

### Why you?

_What excites you about this idea? How did you come up with it?_

I am passionate about climate change. In fact I, and the person I interviewed, are doing a "minor" in it. This combines my two passions of Environment and Coding. Climate Change is the problem, and this is part of the solution to it. Or at least facilitating solutions. Climate change is an existential crisis and any software that helps is always exciting to me.

### Domain

_Describe the project's domain in five words._

Studying and Presenting Climate Data.

### Interface (syntax)

_How might the user interact with the language? What does programming look
like? Why is this the right way to interact with the problem domain?_

It would look a lot like R, but with further abstractions to hone down on the issues being studied in climate science. It's output would be in the form of applets, graphs, maps and so on. This is an important way to interact with the domain because understanding the data we already have is very important, and very hard to do.

### Operation (semantics)

_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

It provides a visual, interactive output based on what you ask it to do and what data you give it.

Errors: May include incorrect syntax. Providing incorrect data may lead to misleading outputs which is also very dangerous but inevitable.

### Expressiveness

_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

Since a lot of abstractions are provided, performing tasks that are not graphical or topographical would be very hard. On the flip side though, these abstractions make it easy to do climate and weather related studying.

### Related work

_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

I couldn't find anything specifically like this, but multiple tools do exist that either do parts of it, or do too much (general PLs) and thus make it hard to specialize.

## The Project

This section examines whether the idea makes for a good CS 111 project.

### Suitability

_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

Systems would take up a major portion of the time. Making interactive maps and datasets is not easy. The style aspect of it is pretty straightfoward, but still important as it needs to be intuitive and needs to be able to grow as we get more data and more ways of understanding that data in this rapidly evolving field.

### Scope

_How big an idea is this? How ambitious is this project?_

It is very ambitious. It is basically R but for weather. A ton of features would be necessary for it to be useful. It requires a lot of data processing and visualization. 

### Benefits and drawbacks

_Why might this be a good idea for a project? Why might this not be a good idea
project?_

Good idea: Climate Change is an existential crisis and this helps study something really important

Bad idea: You can always use other software, which is more cumbersome but it exists. It also very hard to build. I prefer my two free-form ideas compared to this because I was more creative there whereas this was more dependant on the interview.
