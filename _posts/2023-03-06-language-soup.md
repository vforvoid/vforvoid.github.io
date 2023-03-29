---
layout: post
title: Programming language soup
date: 2023-03-05 17:00:00
description: List of the programming languages that I used so far
tags: languages programming
categories: languages programming
---

It may not sound like the best idea to learn and use several programming languages at the same time, especially from a career standpoint.
It's generally better to focus on one or a few similar languages and learn them in-depth.
However, as someone who is passionate about programming, I don't care as much.
I believe that learning multiple languages, even just a little, can have its own perks.
It can help you become aware of different approaches and concepts that you can employ to solve various problems.

I have seen on multiple occasions how people who only work within a single language and ecosystem can become trapped in a particular way of thinking.
In fact, this is a very natural process similar to how our brains work with natural languages:
If you spend too much time thinking in a particular language, it will inevitably carve neural highways in your brain that make it difficult for you to think outside of the framework this language provides.
Language creates the doors of perception for its user, not a breaking news.

You might hear people say things like "X is unidiomatic in my language," "X is discouraged in my language," "nobody does X this way in my language," "X feels weird in my language," or "X does not perform well in my language."
While all of these statements may be true in one language or ecosystem, they might not be the case in other ones.
It's hard to see these differences until you experience working in a different language yourself.
By doing so, you can gain a better understanding of the strengths and weaknesses of each language and how to use them effectively.
You can borrow ideas that you like from the other languages and use them in your primary one.

I strongly encourage anyone who is passionate about programming to learn at least the basics of a language that is **significantly** different from what they already know and use every day.
For example, if you're very familiar with Java, don't just learn Kotlin (well, ok, probably *do* learn Kotlin anyway).
Learn Python or Elm instead, which will challenge you to think differently and will probably be a paradigm shift for you.
Similarly, if you do a lot of JavaScript, don't go for Python, learn Haskell or Rust, otherwise you risk not to learn anything that is significantly new.
Taking a leap of faith and stepping out of your comfort zone and trying something new can be incredibly fascinating and useful!

Ok, enough of the foreword.
Here's a list of programming languages I've worked with throughout my life, roughly in the order they were introduced to me:

1. [Basic](#basic)
2. [Pascal](#pascal)
3. [Delphi](#delphi)
4. [C](#c)
5. [C++](#cpp)
6. [C#](#c-sharp)
7. [PHP](#php)
8. [Java](#java)
9. [Assembly](#asm)
10. [JavaScript](#javascript)
11. [Python](#python)
12. [R](#r)
13. [Scala](#scala)
14. [Lisp (Scheme)](#lisp)
15. [Kotlin](#kotlin)
16. [Elm](#elm)
17. [TypeScript](#typescript)
18. [Rust](#rust)

Note that:
- "Experience" reflects my subjective perception of how experienced I am with a particular language in comparison to other languages I've used, not how experienced and proficient I am in comparison to some other developer or you.
- The pros and cons I mention are based on the state of the language around the time I was using it and might not be true anymore. I wouldn't even pretend pros and const lists are comprehensive either. I could also easily miss some obvious solution for the downside of the language, as I'm just a human.
- For the sake of brevity, I won't include things like:
  - Data markup languages and formats like HTML, XML, JSON, etc
  - Query languages like SQL, GraphQL, GraphDB, mongo, elastic search queries
  - Style sheet languages like CSS, SCSS, Less
  - Different flavors of regular expression languages

---

## Basic

Used it in prod?
: ❌ No

Experience
: ⭐⭐⭐⭐⭐

Enjoyment
: ❤️❤️🖤🖤🖤

Comments
: Mostly used it before I turned sixteen.
  I wrote a lot of small games for myself and my cousin on an [old, dusty ZX machine](/blog/2023/walking-down-the-memory-lane/).
  Tetris and Sokoban was the most complex out of them.
  Also automated certain very repetitive parts of my math-y homework.
: **Pros**: Very easy to pick up as a kid.
: **Cons**: Basic is way too basic.
  The dialect I used was particularly limited, with only support for one big flat file, and manual line numbering required.
  Additionally, there was barely any function support (GOSUB) and pervasive use of GOTO.

---

## Pascal

Used it in prod?
: ❌ No

Experience
: ⭐⭐🌑🌑🌑

Enjoyment
: ❤️❤️❤️🖤🖤

Comments
: Learnt it in a high school, along with other basics like ADTs and high-level compiler theory.
: **Pros**: Decent language to learn about strict type system.
  Has a nice functions support.
: **Cons**: I don't think I can recall any cons for the language itself really.
  It's just the fact that it was out of use in production already when I learnt it.

---

## Delphi

Used it in prod?
: ❌ No

Experience
: ⭐🌑🌑🌑🌑

Comments
: Coded my first basic Windows GUI apps in it.
  It was a cool and refreshing experience to use a visual WYSIWYG UI editor for the first time in my life.
  However, I soon realized that C# was a better option for this purpose, as it was backed by Microsoft and had more support for modern programming practices.

---

## C

Used it in prod?
: ✅ Yes

Experience
: ⭐⭐🌑🌑🌑

Enjoyment
: ❤️❤️❤️🖤🖤

Comments
: Occasionally used it when I needed a performance boost. 
  Or didn't have other choice, such as when I needed to create bindings for a library that was written in C.
  10/10, would segfault again.
  I appreciate the power and low-level control that C gives the programmer.

---
<div id="cpp"></div>

## C++

Used it in prod?
: ✅ Yes

Experience
: ⭐⭐⭐🌑🌑

Enjoyment
: ❤️❤️🖤🖤🖤

Comments
: Worked with it quite a lot with OpenCV and Boost a while ago.
  Also did some desktop client development with WinAPI and QT.
  I mostly wrote pure-C-style though, avoiding objects as much as possible, and I haven't followed C++ news/standards.

---
<div id="c-sharp"></div>

## C#

Used it in prod?
: ✅ Yes

Experience
: ⭐⭐⭐⭐⭐

Enjoyment
: ❤️❤️❤️❤️🖤

Comments
: Picked it up while studying in university.
  Between 2013 and 2016, I did a lot of backend and Windows desktop client development using C#.
  I utilized it with various technologies such as WinForms, WPF, WCF, Entity Framework, ASP.NET, and SimpleInjector.
  I thought I'm going to specialize in C#, but I became increasingly concerned about the future of both Microsoft and myself.
  .NET Core was not really a thing back then and MS was not **that** involved in the opensource as it is now.
  This pushed me into exploring other languages as I was looking for the plan B for my career.
: **Pros**: Absolutely awesome [Haskell-inspired](https://stackoverflow.com/a/4683716/2782477) lazy collection processing semantics (LINQ) for an OOP language.
  Decent FFI. 
  Good multithreading and task API.
  C# also got async/await very early.
  Nice reflection with non-erasable generics.
  Extension methods.
: **Cons**: Dependence on the runtime, lack of cross-platform support and inability to compile to native (at least back then).
  Lack of proper [immutability](https://www.youtube.com/watch?v=O89-zG84QK4), or at least one had to try very hard to achieve it.
  EntityFramework gave me a slight ORM-phobia, because it makes it very easy for developer to write things that has terrible performance.
  Working with pure data is a bit awkward (anonymous objects make it a bit easier though).
  Dependence on Visual Studio projects and its build tools.
  Uncertain future of Microsoft (back then).

---

## PHP

Used it in prod?
: ❌ No, thanks

Experience
: 🌑🌑🌑🌑🌑

Enjoyment
: 🖤️🖤🖤🖤🖤

Comments
: In 2009, I was introduced to web development using this language. 
  Unfortunately, it gave me a deep disgust for anything related to web development for years.
I can't say for sure if it has improved since then, but even after all these years, I still have no desire to revisit it.

---

## Java

Used it in prod?
: ✅ Yes

Experience
: ⭐⭐⭐🌑🌑

Enjoyment
: ❤️❤️🖤🖤🖤

Comments
: Used it with ANTLR and CoreNLP on a backend mostly. 
  It was before Java 8 and there were no stream API.
  I always thought of Java as an older, more conservative brother of C#, who works in a big enterprise company with broader reach.
: **Pros**: Awesome ecosystem, decent tooling, and great deal of language stability.
  You still do need a runtime, but it's more ubiquitous than .NET and more cross-platform.
: **Cons**: The main issue I had with Java is its verbosity and amount of ceremony one needs to accomplish even the most basic tasks.
  This was compounded by the absence of the stream API back then, and I was already spoiled by C#'s LINQ, so it further degraded my experience.

---
<div id="asm"></div>

## Assembly language, Turbo Assembler specifically

Used it in prod?
: ❌ No

Experience
: 🌑🌑🌑🌑🌑

Enjoyment
: ❤️❤️❤️🖤🖤

Comments
: Although I've only used it for university course assignments, I found it surprisingly enjoyable to work with.
  Despite the tedium of controlling the machine on such a low level, there was something weirdly satisfying about having complete control over almost every aspect of the program's execution.
  While I wouldn't want to spend my entire career writing Assembly code, it's definitely a language worth learning for those interested in understanding computers guts.

---

## JavaScript

Used it in prod?
: ✅ Yes

Experience
: ⭐⭐⭐🌑🌑

Enjoyment
: ❤️❤️🖤🖤🖤

Comments
: JavaScript has long been the "vendor lock" for browsers, with only recently the introduction of the WASM being its closest, immature competitor.
  I first started using JavaScript in production in 2016 to build simple front-ends with the help of packages like Bootstrap, React, and Angular.
  More recently, in 2019, I also used it on the backend for a data ingestion pipeline.
  While JavaScript is frustrating at times, especially with its endless quirks and inconsistencies, its ubiquity and versatility make it an essential tool in any web developer's toolkit.
  No matter if you like it or not, it's the [most popular language](https://survey.stackoverflow.co/2022/#most-popular-technologies-language) right now and often used as a lingua franca in the programming community.
: **Pros**: Surprisingly ubiquitous and very accessible.
  Popularized JSON.
  Ceremony-free way to declare and manipulate dictionary-like data records ("objects").
  Nice arrow style for functions.
  You barely need any tools to start working with it, just open your browser.
: **Cons**: But if you want to work with it more than few days, boy oh boy, you will need to learn about all the tools in the observable universe and then some.
  And these tools will surely change every few months.
  NPM is the language's biggest blessing and curse.
  `is-even` and `left-pad` became proper nouns.
  Language designed in 10 days, prank got out of control, and now it's design by committee.
  Absolutely rudimentary core lib which gives you a `Set` class without methods to intersect or union sets out of the box.
  2GB of `node_modules` in a barebone autogenerated project template.
  JS folks are generally lenient towards taking on extra dependencies for their projects.
  Multithreading is hard.
  Coerces everything to a string.
  `this` acts differently depending on a context.
  I can go on and on and on.

---

## Python

Used it in prod?
: ✅ Yes

Experience
: ⭐⭐⭐⭐🌑

Enjoyment
: ❤️❤️❤️❤️🖤

Comments
: In 2019, I utilized Python to build a data ingestion pipeline on the backend and created simple back- and frontends using Django and Django REST.
  Currently, I'm actively utilizing Python for machine learning projects with things like scikit, TensorFlow, Torch, and few gradient boosting packages to train, fine-tune and deploy language models to AWS SageMaker.
  Python is undeniably good choice for ML tasks and an excellent language for small projects and scripts.
  It's very easy to get something running with it really fast.
: **Pros**: The best ecosystem for ML. 
  A lot of the packages are written in "faster system languages" which gives the whole ecosystem extra edge in performance department.
  Nice list / dict / iterable comprehension syntax.
  Ability to manipulate pure data structures like dictionaries without necessity to create a class for every possible structure.
: **Cons**: `pip` package manager is somewhat unergonomic, but this can be solved by using something like `poetry`.
  I still get into trouble importing code from the local packages sometimes. 
  Certain ML-related workloads require creating a little dependency hell on your machine.
  Multithreading is rather hard, thanks to GIL.
  It's necessary to use `venv` to isolate dependencies of projects.
  Lambda syntax is cumbersome.
  Async/await was added rather late.
  Type annotations is a great effort, but it's very late to the party.

---

## R

Used it in prod?
: ✅ Yes, barely

Experience
: ⭐🌑🌑🌑🌑

Enjoyment
: ❤️❤️❤️❤️🖤

Comments
: I used it around 2015 with [Shiny](https://www.shinyapps.io) to visualize energy consumption statistical predictive model's work.
  I didn't spend a lot of time with it, but I found the experience to be quite pleasant.
  It was my first foray into building a truly reactive web UI, and I must say, it felt much purer than the "pure components" of React.

---

## Scala

Used it in prod?
: ✅ Yes, barely

Experience
: ⭐🌑🌑🌑🌑

Comments
: In 2017, I had the opportunity to use Scala to create an Akka Rest API wrapper around an information extraction library.
  While I didn't form a concrete opinion on it, I did notice that it still had the Java-like verbosity that I found somewhat cumbersome.
  It also seems like it tries to be both good at OOP and FP at the same time, with its costs and benefits.
  Dotty (aka Scala 3) looks interesting as well, but I'm afraid Java-centric community will be repulsed by the language instability.


---
<div id="lisp"></div>

## Lisp (Scheme)

Used it in prod?
: ❌ No

Experience
: 🌑🌑🌑🌑🌑

Enjoyment
: ❤️❤️️❤️❤️🖤

Comments
: That's pretty much an honorable mention here.
  I learnt it while going through [SICP](https://en.wikipedia.org/wiki/Structure_and_Interpretation_of_Computer_Programs).
  Very fun and extremely minimalistic language.
  Certainly a good gymnastics for one's brain.
  After watching a fair amount of [Rich Hickey's lectures](https://www.youtube.com/watch?v=kGlVcSMgtV4) I wanted to try out Clojure, but unfortunately I haven't yet. 

---

## Kotlin

Used it in prod?
: ✅ Yes

Experience
: ⭐⭐🌑🌑🌑

Enjoyment
: ❤️❤️❤️❤️🖤

Comments
: I got to work with Kotlin in 2020 when I was developing a pet project of mine.
  And then I commercially made a simple kiosk-mode Android application with it.
  While I didn't enjoy working on the Android app part, I was pleasantly surprised by the language itself.
  It felt much better than C# and Java, and I think it will make a decent "Java++".
  It has taken many of the things I loved about C#.
: **Pros**: Functions are finally feel like first-class citizens in an otherwise OOP language, you no longer have to stuff them into static classes.
  Another notable experimental feature is the ability to compile to native code. 
  Kotlin also has explicit nullability, ensuring that null values are handled appropriately.
  The language has good 2-way interoperability with Java, allowing developers to use existing Java code. 
  Composition over inheritance is baked into the language in the form of delegation.
  Kotlin's core library has excellent collection processing capabilities.
  Suspended functions are also available, allowing for asynchronous programming.
  Additionally, Kotlin's convention of specifying the last lambda outside of parameter parentheses is a neat feature.
  And the most important feature: no need for semicolons.
: **Cons**: Relatively slow compilation time.
  Some verbose ceremony required still to declare arrays and anonymous objects.
  Surprisingly, I don't remember any other issues that I had.


---

## Elm

Used it in prod?
: ✅ Yes, barely

Experience
: ⭐⭐🌑🌑🌑

Enjoyment
: ❤️❤️❤️❤️❤️

Comments
: I started using around 2020, built a few small SPAs with it, and quickly fell in love.
  It's just illegal how good it is.
  As mostly a backend developer, I never expected I will be enjoying developing web applications so much.
  It simply has the best developer experience I ever witnessed.
  I learnt a lot from this language.
  If you're curious about Elm and its potential use cases, I highly recommend checking out [this](https://engineering.rakuten.today/post/elm-at-rakuten/) article.
: **Pros**: There's no concept of Exceptions in the language at all, errors are represented as data.
  The language is trying its best to make sure you've exhaustively handled all the obviously possible errors and cases.
  Elm also doesn't have `null` nor `undefined`, plus everything is strictly immutable.
  As a result it's very unlikely you will ever meet crashes in a runtime.
  One good long-term effect for me from using Elm is that I started to take care of more of the "unhappy paths" than I did before when I was working in other languages.
  State is concentrated and updated in one place and the language takes care of that.
  Functions are curried by default.
  Type system is sound and will infer the minimum sufficient type for any valid code if you don't add any annotations, but it's customary to write type annotation anyway.
  Error messages are best in class, compiler is really helpful.
  Compilation is very fast in comparison to the other compile-to-js languages, bundle sizes are relatively small (in comparison to React and Angular)
  Batteries included: core library is pretty amazing.
  Also, it's not customary to have a big list of dependencies for an Elm project.
  It's a very small language, I feel that I got productive with it in half a week from the absolute zero.
  I liked its task API more than JS Promises.
: **Cons**: First main problem with Elm is it's not popular. It's [2nd most popular](https://2022.stateofjs.com/en-US/other-tools/#javascript_flavors) JS-based language as of 2022, but it's a huuuge drop from TypeScript.
  It's not a problem of language, more of a problem of a language per se, it's just that its future is quite unclear.
  The second problem I've experienced with Elm is it gets you on the hook.
  Switching from Elm to JS/TS is an excruciating experience. I was desperately trying to find some language for a backend development that is distantly as good as Elm is and still haven't found it.
  Some people don't like the fact that Elm don't have higher kinded types or ability to create custom infix operators. It's true, but it makes it easier for newcomers to pick it up though.
  FFI with JS is deliberately cumbersome and tedious, as you need to pass the JS values through the "Elm customs" that ensures the data has exactly the format you expect, which further decreasing the chances you will crash.
  Things you're used like random number generation, logging, chaining effectful code can be tricky all of a sudden. 

---

## TypeScript

Used it in prod?
: ✅ Yes

Experience
: ⭐⭐⭐⭐🌑

Enjoyment
: ❤️❤️️❤️🖤🖤

Comments
: I started using it around mid 2021, mostly for a backend.
  I quickly realized it's not really a language, but rather a family of languages depending on tsconfig you have, which I instantly set to the strictest level possible.
  When you search for type-related help on StackOverflow, chances other people's config is different.
  Overall, it's just a JS with types (not to downplay types significance), and thus TS inherits a lot of its virtues and vices.
: **Pros**: I've noticed it got easier for me to work on a codebases when it gets to a certain size, at least around 5k-10k lines of code.
  All because types information enables better hints in IDE and you get more relaxed as you at least get some level of certainty of what the data format will be at each point of execution.
  If you set `tsconfig` strict enough; if you will be disciplined not to use type casts and other dirty tricks pervasively; if you will parse & validate all your input data from the outside world the moment you received it, then you might get a remotely good developer experience with TS.
  I also liked the fact that syntax for the curried function is very succinct in comparison to other typed imperative languages.
  I liked the tagless union types support, which is very handy at explicitly declaring all possible failure modes of your function execution results.
  Oftentimes you can make things `readonly` and `eslint` will check it for you, but it's hard for 3rd party code. 
  I absolutely love to deal with the structural types, not the nominal types.
  Literal types is another cool feature I like.
: **Cons**: Compilation / transpilation / webpacking / running unit tests may be brutally slow.
  Type errors can be hard to read, at least until you get used to them and know where to look.
  Sometimes you get an impression that "Type" in TypeScript really means "to type more stuff for a false sense of security", as underlying foundation is still an untyped JS: sooner rather than later you will find a type mismatch.
  There's no escape from Chaos.
  You will inevitably find out that type definition for certain built-in core library functions is plain wrong, 3rd party packages won't have type definitions, or they will be wrong, webpack will mess your code and your value will be `undefined` when it shouldn't, and so on.
  Deliberately unsound type system will exhibit weird behaviors occasionally, with non-informative error message.
  Type assignability is not transitive sometimes: if any arbitrary type A is assignable to type B, and type B assignable to type C, there can be cases where assigning type A to type C will cause an error.
  Type inference is frustratingly wrong sometimes, it's also rather bad with generics and too eager to make your type concrete `unknown`.

---

## Rust

Used it in prod?
: ❌ No

Experience
: 🌑🌑🌑🌑🌑

Enjoyment
: ❤️❤️️❤️❤️🖤

Comments
: Rust is a great language with powerful low-level capabilities and a nice core library that includes excellent collection processing functions.
  Although I haven't had a lot of experience with it, I've enjoyed experimenting with Rust and fighting with its infamous borrow checker.
  I also wrote some proof-of-concept projects to demonstrate to my company how we could potentially replace certain parts of our TypeScript data processing with Rust, which according to my benchmarks could yield a 10x-100x performance boost in computation-intensive areas.
