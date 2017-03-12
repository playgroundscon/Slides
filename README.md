# Playgrounds
## A Conference for Swift and Apple Developers
### 2017 Talk Slides

### Adam Bell, [@b3ll](https://www.twitter.com/bell)

##### Taming Touches and Taps
As we enter a new decade of iOS, apps are transitioning from looking pretty to being highly interactive. Building apps where everything feels interactive and interruptible is crucial to making things feel magical, but pulling it off can be rather difficult. We'll go into a deep dive on some advanced techniques on how to build apps that use lots of motion, animations, and gestures to make them stand out as first class citizens on iOS.

---

### Alan Zeino, [@alanzeino](https://www.twitter.com/alanzeino)
##### Swift at Scale; Rewriting the Uber app
In September Uber debuted a complete rewrite of its iOS app. In addition to a whole redesign we shipped a new architecture, powered by Swift. Along the way we learned a lot about ourselves, and we’d love to share some of our stories and insights with you. In this talk we’ll talk about how we undertook such a large rewrite while grappling with growing compilation times, Xcode performance, and hundreds of engineers in one codebase.

---

### Ash Furrow, [@ashfurrow](https://www.twitter.com/ashfurrow)
##### Comparative Asynchronous Programming

Different programming commununities have different approaches to how they handle asynchronous programming. Some use callbacks, others use promises, and they all seem to have really strong opinions. This talk will focus on popular approaches to async programming used outside the Swift community, exploring how those approaches could fit in with the Swift language. Some paradigms are encapsulated in existing libraries, while others would need changes to the Swift compiler.

- [Slides](https://speakerdeck.com/ashfurrow/comparative-asynchronous-programming)
- [Blog post](https://ashfurrow.com/blog/comparative-asynchronous-programming/)

---

### Harlan Haskins, [@harlanhaskins](https://www.twitter.com/harlanhaskins)
##### How to Clang Your Dragon 🐉: Building Compilers with LLVM
Compilers are treated with a fearful reverence that betrays how fascinating and approachable they really are. In this talk, we'll discuss LLVM and how it works by building a real compiler for a toy language called Kaleidoscope. We'll implement many of the fundamental building blocks of compilers and see how certain Swift features make it a great compiler language.

- [Slides](https://speakerdeck.com/harlanhaskins/how-to-clang-your-dragon-building-a-compiler-with-llvm)
- [Demo Source Code](https://github.com/trill-lang/Kaleidoscope)
- In Depth Blog Posts
  - [Part 1: Introduction and the Lexer](https://harlanhaskins.com/2017/01/08/building-a-compiler-with-swift-in-llvm-part-1-introduction-and-the-lexer.html)
  - [Part 2: AST and the Parser](https://harlanhaskins.com/2017/01/09/building-a-compiler-with-swift-in-llvm-part-2-ast-and-the-parser.html)
  - [Part 3: Code Generation to LLVM IR](https://harlanhaskins.com/2017/01/11/building-a-compiler-with-swift-in-llvm-part-3-code-generation-to-llvm-ir.html)

---

### Chris Bailey, [@chris__bailey](https://www.twitter.com/chris__bailey)
##### Swift On The Server

- [Slides](https://www.slideshare.net/cnbailey/playgrounds-mobile-swift-bff)

---

### Chris Eidhof, [@chriseidhof](https://www.twitter.com/chriseidhof)
##### How I Learned To Stop Worrying And Love Mutation

In this talk, we’ll look at mutation in Swift. Mutation gets a bad rap, but together, we’ll look at the reasons behind that and debunk some myths surrounding mutation.

_<P>Note: This was a live demo, there are no slides for this talk_

- [Source code](https://gist.github.com/chriseidhof/5e07c5bbcbe79602ee9dcaff5cae8777)

---

### Dennis Pilarinos, [@dennispilarinos](https://www.twitter.com/dennispilarinos)
##### Putting Together The Best CI Workflow For Swift Apps
A Swift developer's time is valuable. Ideally, it should be spent crafting an application that their users will love -  not focused on the tedious tasks involved in setting up and maintaining infrastructure. Two years ago, in the process of building an iOS app, a couple of friends realized that they were spending more time fighting with their build and deployment system than actually building their app. They put that iOS project on hold to try and build a better CI / CD platform for mobile developers. 

Today, buddybuild provides the platform that thousands of mobile teams use to build apps that their users love. Its continuous integration, continuous delivery and user insight platform streamlines the process of building mobile apps. It also eliminates the friction development teams often face when involving their end users as part of their development workflow.

This talk will dive into what's involved in designing, building, scaling and operating one of the most popular CI/CD platforms for mobile developers. We'll also share some the best practices and trends we've gathered in the process.

After this talk, the audience will be equipped with of a set of best practices to improve their Swift development, and some fun stories of building and operating a high scale, highly available distributed build system.

- [Slides](https://speakerdeck.com/dennispilarinos/putting-together-the-best-continuous-integration-and-deployment-workflow-for-ios-apps)

---

### Erica Sadun, [@ericasadun](https://www.twitter.com/ericasadun)
##### Opinionated Code

Style rules aren't enforced by the compiler. They aren't mandated by any specification. They're not official. Style rules are personal or organisational opinion on specific styling choices that make your code Swiftier. Here's why you should adopt style guidelines to support better and more maintainable code.

---

### Felix Krause, [@krausefx](https://www.twitter.com/krausefx)
##### Scaling Open Source Communities

I'll be talking about the different stages of open source projects, how handling PRs and support change with scale and how to keep innovating with a bigger user base. With that in mind, I'll go into detail on how developers can solve those problems, in particular automating workflows, staying in closer contact with contributors and improving your product and documentation.

- [Blog post](https://krausefx.com/blog/scaling-open-source-communities)

---

### Greg Heo, [@gregheo](https://www.twitter.com/gregheo)
##### Five Unbelievable Secrets Of Reactive Programming The Experts Don’t Want You To Know!

Object-oriented, functional, procedural…do we really need another programming paradigm to take up space in our brains? In this talk, you’ll learn the basic concepts of reactive programming and why they’re useful. As a motivating example, you’ll see a traditional Cocoa app transformed into its reactive counterpart.  <P>More importantly you’ll come away with some new patterns and paradigms to expand your programming toolbox, whether you make a complete conversion to RxSwift or borrow some ideas to use in your existing object-oriented project.

- [Blog post](https://gregheo.com/blog/reactive-programming-basics/)
- [Slides](https://speakerdeck.com/gregheo/five-unbelievable-secrets-of-reactive-programming-the-experts-dont-want-you-to-know)
- [Example project](https://github.com/gregheo/NoughtsAndCrosses)

---

### Hector Matos, [@allonsykraken](https://www.twitter.com/allonsykraken)
##### SpriteKit

- [Source code](https://github.com/KrakenDev/SuperMarioWorld)

---

### Jason Brennan, [@jasonbrennan](https://www.twitter.com/jasonbrennan)
##### Playgrounds

Everybody knows of Swift Playgrounds, Apple's interactive programming environment for learning Swift, now on the iPad. But did you know Apple had an interactive programming environment 30 years ago, also called Playgrounds?   <P>This talk explores Apple's Playgrounds, an interactive graphical programming environment, designed by Alan Kay and his team, for young children to learn programming and complex systems. We'll look at the design principles that went into this 1980s environment and see what it was capable of.   <P>Playgrounds of the 1980s were capable of realtime, interactive, live-programmed objects (for example, in an underwater ecosystem simulation). We'll look at how things have changed from the Playgrounds of yesteryear to the Swift Playgrounds of today.

- [Blog post](https://ashfurrow.com/blog/comparative-asynchronous-programming/)
- [Slides](https://github.com/jbrennan/presentations/tree/master/February_23_2017_Playgrounds)

---

### Marin Usalj, [@_supermarin](https://www.twitter.com/_supermarin)
##### Code signing demystified: certificates, private keys, profiles. 
Every iOS developer has hit the wall of trying to publish an iOS app. 
Code signing is one of the most hated topics in the field: it's obscure,
complicated and not well understood.

The talk clarifies all the components in the code signing process, and it should save you some time in the future.
The talk goes over private keys, .p12 export, certificates, certificate requests, provisioning profiles, teams, and shows how it all fits together.

- [Slides](https://speakerdeck.com/supermarin/osx)

---

### Matt Comi, [@mattcomi](https://www.twitter.com/mattcomi)
##### Cooperative Path Finding
Big Bucket's game Space Age can be described as a mashup of an Real-time strategy and an adventure game. Space Age has units and missions, but also inventory and dialogue. When a unit needs to navigate between map locations, it uses the A* pathfinding algorithm. As well as A*, Space Age employs some novel techniques to ensure that units don't bump each other while also ensuring that their navigation appear natural and ad-hoc, not coordinated or precognitive. I will be discussing some of these techniques.

- [Slides](https://speakerdeck.com/mattcomi/cooperative-path-finding)
- [Source code](http://bigbucketgames.com/playgroundscon)
- [Video](http://bigbucketgames.com/playgroundsconvideo)

---

### Matt Gallagher, [@cocoawithlove](https://www.twitter.com/cocoawithlove)
##### Swift Performance
By default, Swift aims to be a simple-to-use language that protects the programmer from the details of memory management, type implementations and function invocation strategies. However, when we need high performance, we need to understand the details of what Swift does at a low level so we can use that knowledge to help Swift produce code that performs optimally.

<P>This talk will look at how Swift implements generics, protocols, modules, reference counting, closures, copy-on-write and inheritance and look at how each of these features can have performance that varies by as much as a factor of 10, depending on how you use them. I will look at how to read profiling information in Instruments to identify which of these features is the source of performance problems and how to restructure code to solve these problems. I'll talk about which Swift features can be used at different scales from 10,000 iterations per second through to 1 billion iterations per second.

- [Slides](https://speakerdeck.com/mattgallagher/playgrounds-2017-high-performance-swift)
- [Source code](https://github.com/mattgallagher/Playgrounds2017)

---

### Rachel Bobbins, [@bobbins](https://www.twitter.com/bobbins)
##### Refactoring Strategies

Refactoring existing code can be hard. You can recognize your existing pain points, and might have an idea for how to solve them. But, that journey from point A to point B can be fraught with compilation errors. These compilation errors can stop you from making incremental progress.

<P>In this talk, I'll talk about some of the strategies you can use for incrementally refactoring your Swift code, by leaning heavily on the compiler. You'll be able to keep your app functioning and your tests passing, even while gutting your app from the inside out!
- [Slides](https://speakerdeck.com/rbobbins/your-refactoring-toolbox)

---

### Samuel Giddins, [@segiddins](https://www.twitter.com/segiddins)
##### Understanding Why Strings Are Evil

Strings are usually the first or second data type we learn to work with as programmers. Despite appearing deceptively simple, misunderstanding and misuse of strings abound in the code we write every day. From performance problems to unicode correctness issues to complex APIs and the challenges of displaying strings on screen (and storing them on disk), we'll look at ways to wrangle our favorite data type. Swift forced many of us to question how strings really worked for the first time, so we'll use Swift's String interface to understand what makes strings so slow and difficult, and explore some ways to make working with them fast and easy.

- [Slides](https://speakerdeck.com/segiddins/why-strings-are-evil)

---

### Soroush Khanlou, [@soroush](https://www.twitter.com/soroush)
##### Everything You Ever Wanted To Know About Sequence and Collection

Sequence and Collection are two of the deepest and most interesting and deepest protocols in the Swift standard library.  We’ll take a deep dive into these protocols and their related protocols and types, like Index, Sliceable, and RangeReplaceableCollection, and how they each interplay.. We'll build a `LinkedList` implementation to explore Sequences and how Iterators interact with them. We'll talk about Collection, and build a few extensions using the abstractions that Collection gives us. By the end, you'll know everything you ever wanted to know about Sequence and Collection.

- [Slides](https://speakerdeck.com/playgroundscon/everything-you-ever-wanted-to-know-aboutsequence-and-collection)

---

### Tamar Nachmany, [@tamarshmallows](https://www.twitter.com/tamarshmallows)
##### Unit Testing for Designers

Unit testing is a driving force in the way many iOS engineers architect codebases. It is a vehicle for change, opening up opportunities to make changes without breaking everything. It also pushes codebases to be more modular. But modularity presents tradeoffs, sometimes making it more challenging to introduce new functionalities to an app.

<P>In this talk, I will discuss why even though unit tests are not user facing in any way, they are the perfect technical topic to teach the designers on your team about. I will highlight engineering concepts that support unit testing, like state and dependency injection, and share lightweight ways of bringing designers into the unit testing process, like running and sharing snapshot tests.

<P>I hope this will be a talk iOS engineers can share with the designers and product folks they work with to break down barriers and start a conversation about architecting apps that support both unit testing and bold design iteration.

- [Slides](https://speakerdeck.com/tamarnachmany/unit-testing-for-designers?slide=2)

---

### Wendy Lu, [@wendyluwho](https://www.twitter.com/wendyluwho)
##### Once Upon a Rewrite

At Pinterest, we recently completed a rewrite our iOS app for a faster, cleaner experience. Speed is something that has always been very important to us. I’ll share some techniques we used to achieve large gains in app startup time and scroll performance. Another of the goals of our re-architecture was to move to a completely immutable model layer. I'll discuss the motivation behind our migration, and explore how our new system handles updating models, loading new information from the API and other data integrity concerns.

