# Free project 2

## The user and a language

This section describes who the project would serve and why a language might be a
good way to meet their needs.

Artists, that could use AI like DallE2 to assist them. 

DallE2 is a software that takes a natural language description input, and produces a piece of art using the provided description. This is cool - but it is really hard to express an artistic idea precisely using a natlang. That makes DallE often useless to help if you already have a very specific idea in your head. 

### What's the need?

_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help
them?_

Artists and AI art are viewed as antagonistic to one and another. When In fact AI could help artists speed up their workflow and be MORE creative and have more time for perfection. Artists could use AI to produce creative templates. A DSL could help produce intricate templates using AI, which artists could then also further work on.

Creating an art DSL, much like ContextFree, that also allows artists to incorporate the AI smarts of DallE would be a really powerful tool. 

LOOP(Draw, 25)

Draw { 

  main ( Dolphin, n1)
  
  strongWith ( Wings, n2 )
  
  n2.color (grey)
  
  weakWith (Ramen Noodles)
  
  widthBorder( 10 pixels ) 
  
  backgroundColor (green) 
  
  imageShape ( Polygon (12) )
  
  style (Van Gogh)
  
}


By creating a DSL like this, you get the simplicity of Context Free and the power of AI like DallE2. The code here looks a lot like ContextFree, but it is a lot more powerful. In just a few lines, you could make 25 drawings of dolphins with grey wings having ramen inside a dodecagon, in the style of Van Gogh. 

------

Dalle either creates something weird or requires a lot of step by step instructions and nudging. It also only produces one output each time, requiring users to repeat the process multiple times until they get an artwork that they can work with. The loop (LOOP) feature inside the DSL can help produce multiple outputs in one instance. You can also change the code very easily, and add or remove instructions as you please. The functions aim to reduce ambiguity and provide as many instructions as you can. 

An example, here, "dolphin with wings, and with ramen" to us obviously means a Dolphin that has wings on its back. And it is holding ramen next to it. We know this even though we say "with wings" and "with ramen". But AI is not smart and cannot disambiguate. It will produce a Dolphin that has hair made of Ramen with a pair of wings lying next to it. Code can allow clear, predecided instructions.  

### Why a language?

_Why is a DSL appropriate for your user(s)? How does it address the need?_

LOOP(Draw, 25)
Draw { 
  main ( Dolphin, n1)
  strongWith ( Wings, n2 )
  n2.color (grey)
  weakWith (Ramen Noodles)
  widthBorder( 10 pixels ) 
  backgroundColor (green) 
  imageShape ( Polygon (12) )
  style (Van Gogh)
}

Dalle either creates something weird or requires a lot of step by step instructions and nudging. It also only produces one output each time, requiring users to repeat the process multiple times until they get an artwork that they can work with. The loop (LOOP) feature inside the DSL can help produce multiple outputs in one instance. You can also change the code very easily, and add or remove instructions as you please. The functions aim to reduce ambiguity and provide as many instructions as you can. 

An example, here, "dolphin with wings, and with ramen" to us obviously means a Dolphin that has wings on its back. And it is holding ramen next to it. We know this even though we say "with wings" and "with ramen". But AI is not smart and cannot disambiguate. It will produce a Dolphin that has hair made of Ramen with a pair of wings lying next to it. Code can allow clear, predecided instructions.

Here, "strongWith" and "weakWith" functions act differently. The DSL abstracts a lot of the inner workings while also being more unambiguous and "featureful" than a natural language.


### Why you?

_What excites you about this idea? How did you come up with it?_

I have used DallE a lot. I know where it can be useful, and where it can be very time consuming and frustrating. I’m also part of an art community, and an artistic tech community. So I feel I know the ins and outs of what people need and what I need and how to solve it. 

This excites me because it’s a DSL that uses some really ground breaking technology to power it.  

### Domain

_Describe the project's domain in five words._

AI Art and Image generation.

### Interface (syntax)

_How might the user interact with the language? What does programming look
like? Why is this the right way to interact with the problem domain?_

I have pasted an example of what code would look like in previous prompts : 

LOOP(Draw, 25)
Draw { 
  main ( Dolphin, n1)
  strongWith ( Wings, n2 )
  n2.color (grey)
  weakWith (Ramen Noodles)
  widthBorder( 10 pixels ) 
  backgroundColor (green) 
  imageShape ( Polygon (12) )
  style (Van Gogh)
}

It looks somewhat like a programming language, with functions and loops. It has some resemblance with ContextFree and HTML/CSS. Both allow you to toggle around such parameters to produce visual outputs. But this DSL acts as an interface with an AI while doing so. The "LOOP... 25" indicates that this program will produce 25 different images with the same input, and the artist can pick one.  

### Operation (semantics)

_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

It produces as many outputs as many times the art functions are run. It does so by interacting with an AI multiple times. AI tends to often produces varying outputs, even though the input might be the same. Errors include incorrect function calls and wrong parameters. The required parameters, although obvious, can be viewed through the documentation.

### Expressiveness

_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

Explain art and get an AI to generate it. Anything else would basically be impossible since the DSL largly relies on art outputs. 

### Related work

_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

Not that I can find. Probably because OpenAI just recently became so popular. 

## The Project

This section examines whether the idea makes for a good CS 111 project.

I don't know if it does, I think it might be a useful tool but it isn't quite a typical DSL, and is dependant on outside AI APIs.

### Suitability

_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

I think there is a mix of both, but there is probably more design decisions. It is very important to make sure the function names are intuitive, and the layout is simple.

### Scope

_How big an idea is this? How ambitious is this project?_

It is quite ambitious because it uses AI to power it. On the other hand though, a lot of it is already ready to use and the language designer does not need to build something like DallE themselves. 

### Benefits and drawbacks

_Why might this be a good idea for a project? Why might this not be a good idea
project?_

Good idea : I think it could be a useful tool to use AI to its fullest to actually generate usable artwork

Not good idea : It isn't a pressing issue on this planet. Software like DallE gets more usable by the day. The DSL is also dependant on other outside software to run on, and this software is constantly changing. 
