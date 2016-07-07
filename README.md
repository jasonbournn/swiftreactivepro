> There is no royal road to Swift. —Euclid

##### [Key](#emoji-key)

## **Index**

- [Programming](#programming)
    + [Functional Programming](#functional-programming)
    + [Functional Reactive Programming](#functional-reactive-programming)
- [iOS Programming with Swift](#ios-programming-with-swift)
    + [Architecture](#architecture)
    + [Core Data and Realm](#core-data-and-realm)
    + [iOS](#ios)
    + [JavaScript](#javascript)
    + [JSON](#json)
    + [UI](#ui)
    + [Web Services, Routing, and Networking](#web-services-routing-and-networking)
- [Mac Programming with Swift](#mac-programming-with-swift)
- [watchOS Programming with Swift](#watchos-programming-with-swift)
- [tvOS Programming with Swift](#tvos-programming-with-swift)


[:arrow_up:](#index)

### **Functional Programming**
- Declarative Programming
    - Modern Declarative Programming in Swift [:page_facing_up:](https://wiki.mq.edu.au/display/plrg/James+Moss%3A+Modern+Declarative+Programming+in+Swift)
    - What is Functional Programming in Swift? [:floppy_disk:](http://media.monkey-robot.com/docs/thoughtworks-swift.pdf) [:page_facing_up:](http://harlankellaway.com/blog/2015/08/10/swift-functional-programming-intro) [:page_facing_up:](http://jamesonquave.com/blog/functional-programming-in-swift/) [:floppy_disk:](https://speakerdeck.com/saloievgen/think-functionally-in-swift) [:microphone:](https://realm.io/news/pragma-hannes-verlinde-statelessness-react-native/)
    - Functional Programming By Example [:pencil:](http://caiorss.github.io/Functional-Programming/haskell/Functional_Programming_Concepts.html)
    - Make Swift More Functional [:floppy_disk:](http://www.slideshare.net/jarsen7/7-habits-for-a-more-functional-swift?qid=8a7611e7-4c08-4e2f-9f81-99b67c6f4390&v=default&b=&from_search=3)
    - Introduction to Functional Programming in Swift [:page_facing_up:](http://www.raywenderlich.com/114456/introduction-functional-programming-swift)  [:floppy_disk:](http://www.slideshare.net/alexis_gallagher/swift-functional-programming-and-the-future-of-obj-c?qid=8a7611e7-4c08-4e2f-9f81-99b67c6f4390&v=default&b=&from_search=1)
    - Functional Programming in Swift Talks [:microphone:](https://vimeo.com/107419503) [:microphone:](https://realm.io/news/altconf-chris-eidhof-functional-programming-in-swift/) [:floppy_disk:](http://www.slideshare.net/natashatherobot/funcitonal-swift-conference-the-functional-way?qid=8a7611e7-4c08-4e2f-9f81-99b67c6f4390&v=default&b=&from_search=4) [:microphone:](https://www.youtube.com/watch?v=rJosPrqBqrA) [:microphone:](https://www.youtube.com/watch?v=estNbh2TF3E)
    + Proof in Functions [:page_facing_up:](http://www.fewbutripe.com/swift/math/2015/01/06/proof-in-functions.html) [:page_facing_up:](https://www.reddit.com/r/programming/comments/2rjnou/proof_in_functions_curryhoward_explained_through/) [:page_facing_up:](https://jeremywsherman.com/blog/2015/10/02/when-is-proof-not-proof/)
    + Functional Thinking [:floppy_disk:](https://prezi.com/pgqshla_nuoe/functional-thinking/)
    + 6 Killer Functional Swift Features [:page_facing_up:](http://ericasadun.com/2015/05/21/swift-six-killer-features/)
    + Functional Programming in the Swift Language [:page_facing_up:](https://medium.com/swift-programming/2-functional-swift-c98be9533183)
    + Writing Compelling Functional Code with BananaKit [:microphone:](https://realm.io/news/compelling-code/)
    - Practical Declarative [:floppy_disk:](https://speakerdeck.com/kylef/practical-declarative-programming-360-idev-2015) and Functional [:floppy_disk:](https://speakerdeck.com/kylef/practical-functional-programming-dotswift-2015) Swift
    + 7 Habits for more functional Swift [:floppy_disk:](http://www.slideshare.net/jarsen7/7-habits-for-a-more-functional-swift) [:pencil:](https://gist.github.com/sketchytech/0ba6dfe2b197f188c64b)
    - Writing Pipe operators in Swift [:page_facing_up:](http://gilesvangruisen.com/writing-a-pipeline-operator-in-swift/)
    - Reccomended Functional Operators in Swift [:pencil:](https://github.com/typelift/Operadics) [:page_facing_up:](http://sketchytech.blogspot.com/2015/06/functional-programming-understanding.html) [:pencil:](https://gist.github.com/sketchytech/c02adc1b68fb1080ffc3)
    - Point-Free Style Swift [:page_facing_up:](https://www.quora.com/Why-should-or-shouldnt-I-use-Swift-to-write-OS-X-or-iOS-apps-the-Functional-Programming-way)
- Immutable State
    - Embrace Immutability [:microphone:](https://realm.io/news/slug-keith-smiley-embrace-immutability/)
    + Immutable Swift [:page_facing_up:](http://nomothetis.svbtle.com/immutable-swift)
    - Dodging State [:page_facing_up:](https://jeremywsherman.com/blog/2015/07/15/dodging-state/)
    - Separating data from logic with Immutable State [:page_facing_up:](http://www.marisibrothers.com/2015/12/separating-data-from-logic-in-swift.html)
- Map / Filter / Reduce
    - Reduce all the things [:page_facing_up:](http://appventure.me/2015/11/30/reduce-all-the-things/)
    + Map and FlatMap demystified [:page_facing_up:](http://www.uraimo.com/2015/10/08/Swift2-map-flatmap-demystified/) [:page_facing_up:](http://robnapier.net/maps)
    + Understanding Reduce in Swift [:page_facing_up:](http://ijoshsmith.com/2014/06/25/understanding-swifts-reduce-method/)
    + Deriving higher order functions in Swift [:page_facing_up:](http://ijoshsmith.com/2015/12/09/higher-order-functions-in-swift/)
    - Reduction in Force [:page_facing_up:](http://robnapier.net/reduction-in-force)
- Recursion and Infinite Streams
    - Tail Call Optimization
        - Does Swift implement tail call optimization? and in mutual recursion case? [:link:](http://stackoverflow.com/questions/24023580/does-swift-implement-tail-call-optimization-and-in-mutual-recursion-case) [:link:](https://devforums.apple.com/thread/247371?start=0&tstart=0)
        - (Tail)Recursion with nested functions in Swift 2.0 [:page_facing_up:](http://danielnagy.hu/?p=119) [:page_facing_up:](http://natashatherobot.com/functional-swift-tail-recursion/) [:pencil:](https://gist.github.com/marcelofabri/4b41adb87a09ce86ff40)
    + Thunks
        + Thunks in Swift [:page_facing_up:](https://plus.google.com/+ShriramKrishnamurthi/posts/dXd71hueSvH) [:page_facing_up:](https://www.reddit.com/r/swift/comments/2umog0/what_does_an_abstraction_thunk_helper_do/) [:pencil:](https://github.com/apple/swift/blob/master/test/DebugInfo/thunks.swift)
        - Wnat is an abstraction thunk helper? [:link:](https://www.reddit.com/r/swift/comments/2umog0/what_does_an_abstraction_thunk_helper_do/)
    + CPS
        + Continuation Passing Style in Swift [:page_facing_up:](https://github.com/mbrandonw/mbrandonw.github.io/blob/master/_drafts/continuation-passing-in-swift.markdown) [:page_facing_up:](https://medium.com/swift-programming/continuation-passing-style-in-swift-e4d825962803#.o41p6fw4j)
        + Tying the Knot in Swift [:link:](http://stackoverflow.com/a/24026196/2855836
        - Chaining with Continuations [:page_facing_up:](http://www.overtakenbyevents.com/Swift-continuations/)
    + Infinite
        + FizzBuzz with infinite streams [:page_facing_up:](http://cutting.io/posts/completely-overengineering-fizzbuzz-with-infinite-streams/)
        + Aquifier Functional streaming abstractions in Swift [:pencil2:](https://github.com/typelift/Aquifer)
        + Lazy infinite streams [:pencil2:](https://github.com/antitypical/Stream)
        + Better Recursion with Swift [:microphone:](https://vimeo.com/138092644) [:floppy_disk:](https://speakerdeck.com/ontherocks/better-recursion-with-swift)
        - Does swift have a protocol for writing a stream of bytes? [:page_facing_up:](http://stackoverflow.com/questions/24184429/does-swift-have-a-protocol-for-writing-a-stream-of-bytes)
        - Infinite array [:pencil:](https://gist.github.com/kristopherjohnson/516b24ca19f6b9d247c3)
        - Recursive structures in Swift without Box classes [:pencil:](https://gist.github.com/zats/c39dbd9b0017fb3b77dd37be744cf474)
- Memoizations
    - Memoization in Swift [:link:](http://stackoverflow.com/questions/31129211/need-detailed-explanation-for-memoize-implementation-in-swift-wwdc-14-session)
    + Functional Memoization in Swift [:page_facing_up:](http://blog.scottlogic.com/2014/09/22/swift-memoization.html) [:page_facing_up:](http://www.matthewsessions.com/memoize-in-swift/) [:pencil:](http://stackoverflow.com/questions/31129211/need-detailed-explanation-for-memoize-implementation-in-swift-wwdc-14-session)
- Lambda Calculus
    + Church Encoding [:pencil:](https://gist.github.com/CodaFi/b9ca5bcee6d7ea9ff158)
    + Lambda Calculus in Swift 2 [:pencil:](https://gist.github.com/bellbind/6ffb0add23990eb5bef4) [:pencil:](https://gist.github.com/dankogai/d80ab3befe81de7ea7e0)
    - Programming is Mathematics [:page_facing_up:](http://xn--wxak1a.com/blog/FP-In-Swift-Intro.html)
    + Llama Calculus [:floppy_disk:](https://github.com/rnapier/llama-calculus)
- Functors and Applicatives
    + Functor and Monad in Swift [:page_facing_up:](http://www.javiersoto.me/post/106875422394) [:pencil:](https://gist.github.com/harlanhaskins/dd31095330b4889a741c) [:pencil:](https://gist.github.com/mbrandonw/42651182eddf53ca3991)
    - Various Functors in Swift [:page_facing_up:](http://qiita.com/335g/items/81af12f9be8f7f8112c7)
    - Are true functors possible in Swift? [:link:](https://www.reddit.com/r/swift/comments/2d6mpo/are_functors_possible_in_swift/) [:link:](http://stackoverflow.com/questions/25233594/recreating-the-functor-type-in-swift)
    + Functors, Applicatives, and Monads in Swift [:page_facing_up:](http://www.mokacoding.com/blog/functor-applicative-monads-in-pictures/) [:link:](https://lists.swift.org/pipermail/swift-evolution/Week-of-Mon-20151214/002739.html) [:page_facing_up:](http://www.russbishop.net/monoids-monads-and-functors)
    + Functional JSON Parsing [:page_facing_up:](http://chris.eidhof.nl/posts/json-parsing-in-swift.html)  [:page_facing_up:](http://radex.io/swift/json/)
    - No Real Functors [:page_facing_up:](http://nomothetis.svbtle.com/smashing-swift)
    - Functor & Friends: Protocol + Tests [:page_facing_up:](https://jeremywsherman.com/blog/2015/03/08/functors-and-friends-interface-plus-tests/)
    - How I learned to stop worrying and love the functor [:microphone:](https://vimeo.com/132657092) [:floppy_disk:](https://github.com/gfontenot/talks/tree/master/Functors)
    - The Missing Apply Function in Swift [:page_facing_up:](https://www.drivenbycode.com/the-missing-apply-function-in-swift/)
    - Avoid consecutive “if let” declarations in Swift [:link:](http://stackoverflow.com/questions/26671833/avoid-consecutive-if-let-declarations-in-swift/26673847#26673847)
- Arrows
    + Arrows in Swift [:pencil:](https://github.com/typelift/Swiftz/blob/master/Swiftz/Arrow.swift)
- Monads
    - About
        - What is a Monad? [:page_facing_up:](http://codeplease.io/2015/08/05/monads/) [:pencil:](https://gist.github.com/RuiAAPeres/0b317796f810839fe706)
        + What are Monads [:page_facing_up:](http://xn--wxak1a.com/blog/Monards.html) [:pencil:](https://gist.github.com/Ben-G/542982cc102aaa1a4d4b)  [:microphone:](https://realm.io/news/slug-andy-bartholomew-understand-monads-one-weird-trick/)
        + Applicatives in Swift [:pencil:](https://github.com/typelift/Swiftz/blob/master/Swiftz/Applicative.swift) [:pencil2:](https://github.com/koher/ApplicativeSwift) [:page_facing_up:](https://www.objc.io/blog/2014/11/17/functional-snippet-7-applicative-functors/)
        - Monad laws [:page_facing_up:](http://nomothetis.svbtle.com/third-monad-law-derivation)
        + infix Operators for Monadic Functions in Swift [:pencil2:](https://github.com/thoughtbot/Runes)
        + Monads & C# Tasks in Swift [:page_facing_up:](https://realm.io/news/swift-tasks-nevyn-bengtsson/)
        - What the heck is a monad? [:floppy_disk:](https://speakerdeck.com/swiftsummit/al-skipp-the-monad-among-us) [:page_facing_up:](http://khanlou.com/2015/09/what-the-heck-is-a-monad/)
        + Swift Adventures in Monad Land [:pencil2:](https://github.com/alskipp/Swift-Adventures-In-Monad-Land)
        + Paragons Of Perfunctory Programs [:page_facing_up:](http://xn--wxak1a.com/blog/Monadic-Computering.html)
        - Networking with Monads and into to Transformers [:microphone:](https://www.youtube.com/watch?v=LqwrUmuodyY)
        - "var" is the State monad [:page_facing_up:](https://twitter.com/jckarter/status/510582940158291969)
    - Reader
        + Reader Monad in Swift [:pencil:](https://gist.github.com/tLewisII/bfee33f69ddb8e03b379) [:pencil:](https://github.com/typelift/Swiftz/blob/master/Swiftz/Reader.swift)
    - Writer
        + Writer Monad in Swift [:pencil:](https://gist.github.com/tLewisII/987d7c0f4ecd873b89a7) [:pencil:](https://github.com/typelift/Swiftz/blob/master/Swiftz/Writer.swift)
    - State
        + State Monads in Swift [:pencil2:](https://github.com/sharplet/State?files=1)
    - Continuation
        - Continuation Monad [:pencil:](https://gist.github.com/CodaFi/2186a73bdfb9fff79c26) [:pencil:](https://gist.github.com/robrix/dd2a65bbc8b44d7a670b) [:pencil:](https://gist.github.com/sjoerdvisscher/a56a286ccfabce40e424)
- Monoids
    + Simple Monoid Example [:pencil:](https://gist.github.com/drexin/e3022674f6ddf6fdb65f) [:pencil:](https://gist.github.com/jhaberstro/9aa326e3762f91abbe8f)
    - Monoid Library [:pencil2:](https://github.com/alskipp/Monoid)
    - Swift's lack of Monoids [:page_facing_up:](https://www.reddit.com/r/swift/comments/2xm80a/swifts_lack_of_monads/)
    - Monoid with Dual and Writer [:pencil:](https://gist.github.com/tLewisII/c44a70a560488edea29a)
- Folds and Lazy Lists
    + Folds in Swift [:page_facing_up:](http://thepurecoder.com/functional-swift-fold-it-baby/) [:page_facing_up:](http://thepurecoder.com/more-on-fold/) [:pencil:](https://gist.github.com/HenningBrandt/fd9a46d5abbc3b39a35e) [:pencil:](https://gist.github.com/HenningBrandt/f44a0f59c716e7fe4689) [:pencil:](https://gist.github.com/davidpdrsn/3afcee0327285be77fbd) [:pencil:](https://gist.github.com/sonsongithub/fde90049cda3c4a2d05c) [:pencil:](https://gist.github.com/curtclifton/2ac04e88e186f52f2239)
    - Lazy Haskell like Lists [:page_facing_up:](https://github.com/dankogai/swift-lazylist) [:page_facing_up:](http://matt.might.net/articles/implementing-laziness/)
    - Making flatMap lazy [:page_facing_up:](https://bigonotetaking.wordpress.com/2015/07/19/making-flatmap-lazy/)
    - How are swift lazy collections implemented [:page_facing_up:](https://medium.com/@NSomar/lazy-collection-cb4903a36ff7#.7izheiih6)
    - Lazy Collections [:pencil:](https://gist.github.com/oarrabi/df877678161976b9e553)
- Zipper
    - Implementing zip and zipWith recursively [:page_facing_up:](http://www.luby.info/2015/03/15/swift-zip-zipWith-recursion.html)
    - Custom Zip Function [:page_facing_up:](http://flexmonkey.blogspot.com/2015/05/a-test-driven-custom-swift-zip-function.html)
    - zipWith [:pencil:](https://gist.github.com/kristopherjohnson/7419ed4444a0ad9bb2ea) [:pencil:](https://gist.github.com/kristopherjohnson/7419ed4444a0ad9bb2ea)
    + Array to Zipper [:pencil2:](https://github.com/rnapier/array-zipper)
    - zip(), zip3(), unzip(), and unzip3() for Swift [:pencil:](https://gist.github.com/kristopherjohnson/04dbc470e17f67f836a2)
- Promises / Futures
    - FutureKit Repository [:pencil2:](https://github.com/FutureKit/FutureKit)
    - You're missing the point of promises [:pencil:](https://gist.github.com/domenic/3889970)
    - A simple Promise in Swift [:pencil:](https://gist.github.com/robrix/5f3dc201988fb0f5f584)
    - PromiseKit Promise Library [:pencil2:](https://github.com/mxcl/PromiseKit) [:link:](http://promisekit.org/)
    - BrightFutures Repository [:pencil2:](https://github.com/Thomvis/BrightFutures) [:microphone:](http://www.thomasvisser.me/2015/11/08/swiftsummit-execution-context/)
    + Back to the Futures with Swift [:microphone:](https://realm.io/news/swift-summit-javier-soto-futures/) [:floppy_disk:](https://speakerdeck.com/javisoto/back-to-the-futures)
    + Futures and Latency as an effect in Swift [:page_facing_up:](https://sideeffects.xyz/2015/latency-as-effect-in-swift/) [:floppy_disk:](http://www.bubblefoundry.com/blog/2014/10/future-shock/)
    - Binds and Promises with Forbind [:page_facing_up:](http://ulrikdamm.logdown.com/posts/277995) [:pencil2:](https://github.com/ulrikdamm/Forbind)
    - Futures and monads [:link:](https://lists.swift.org/pipermail/swift-evolution/Week-of-Mon-20151214/002995.html)
    - Promise + progress + pause + cancel + retry [:pencil2:](https://github.com/ReactKit/SwiftTask)
- Combinators
    - Parser Combinators in Swift [:microphone:](https://realm.io/news/tryswift-yasuhiro-inami-parser-combinator/)
    + Y Combinators in Swift [:pencil:](https://gist.github.com/kongtomorrow/e95bea13162ca0e29d4b#file-gistfile1-swift) [:pencil:](https://gist.github.com/kongtomorrow/e95bea13162ca0e29d4b)  [:page_facing_up:](https://medium.com/@ayanonagon/the-y-combinator-no-not-that-one-7268d8d9c46#.7z8p7rbu7)
    + Combinators [:page_facing_up:](http://xn--wxak1a.com/blog/Combinators.html) [:pencil:](https://gist.github.com/CodaFi/10afdd77e42bb8ad18ab)
    + Parser combinators, for Swift [:page_facing_up:](http://blog.nottoobadsoftware.com/footlessparser/) [:pencil2:](https://github.com/kareman/FootlessParser) [:pencil2:](https://github.com/hlian/jiffy)
    - Monadic Parser Combinator [:pencil2:](https://github.com/inamiy/TryParsec)
    - Swift recursive descendent parser combinator [:pencil2:](https://github.com/jadengeller/Parsley)
    - Fixed point combinators and recursive closures [:link:](http://stackoverflow.com/a/34566264/2855836)
- Lenses, Transducers, Reducers
    + Lenses in Swift [:page_facing_up:](http://chris.eidhof.nl/posts/lenses-in-swift.html) [:pencil:](https://gist.github.com/mbrandonw/4acd26ab01bb6140af69) [:pencil2:](https://github.com/robb/Monocle/blob/master/Monocle/Lens.swift) [:pencil:](https://gist.github.com/mbrandonw/48ea2b3de9dc308907d9)
    + Lenses, Prisms, Isos in Swift 2 [:pencil2:](https://github.com/typelift/Focus)
    - Creating a Lens to Provide a New Public Interface [:page_facing_up:](https://christiantietze.de/posts/2016/02/lens-data-interface/)
    - Functional Programming with Bananas, Lenses, Envelopes, and Barbed Wire [:pencil:](https://gist.github.com/CodaFi/bbedc25a318a1565e4c1)
    + Transducers and Reducers in Swift 2 [:pencil2:](https://gist.github.com/rjchatfield/14e2869b0c572696ea3c) [:page_facing_up:](http://stackoverflow.com/questions/32082320/transducers-in-swift) [:link:](http://stackoverflow.com/questions/32082320/transducers-in-swift) [:link:](http://stackoverflow.com/questions/26311327/transducers-and-swift-porting-javascript-code-to-swift-code) [:pencil:](https://gist.github.com/mbrandonw/429f84f46b2818338f8e)
    - Lenses in Swift, or how to change parts of immutable objects [:page_facing_up:](http://narf.pl/posts/lenses-in-swift)
    - Lenso [:pencil2:](https://github.com/narfdotpl/lenso)
    - Lens Parser [:pencil2:](https://github.com/KarlHarnois/LensParser)
- Categories
    + From Category Theory to Swift [:pencil2:](https://github.com/mbrandonw/naturally-swift)
    + Categories in Swift [:pencil:](https://gist.github.com/CodaFi/4d0ce6a3cc0cb1085720)
    - Yoneda Embedding [:pencil:](https://gist.github.com/CodaFi/d4efd98697130bd35f5c)
    - Top, Any, and Bottom Type [:link:](http://stackoverflow.com/questions/34150907/bottom-type-in-swift)
    + Covariance and Contravariance in Swift 2.1 [:page_facing_up:](http://www.uraimo.com/2015/09/29/Swift2.1-Function-Types-Conversion-Covariance-Contravariance/) [:page_facing_up:](https://mikeash.com/pyblog/friday-qa-2015-11-20-covariance-and-contravariance.html)
    - Category Theory Practice [:pencil2:](https://github.com/ashfurrow/category-theory-exercises)
- Functional Frameworks
    + Swiftz Functional Programming Library [:pencil2:](http://www.stackbuilders.com/news/swiftz-the-power-of-liftz)
    + Second Bridge Swift Functional Framework [:pencil2:](https://github.com/47deg/second-bridge)
    + Swiftx Functional Data Types [:pencil2:](https://github.com/typelift/Swiftx)
    + Basis Pure Declarative Programming in Swift [:pencil2:](https://github.com/typelift/Basis)
    + Functional Concurrency Primitives [:pencil2:](https://github.com/typelift/Concurrent)
    + Prelude Library [:page_facing_up:](https://github.com/robrix/Prelude)
    + Funky Functional Programming Tools and Experiements [:pencil2:](https://github.com/brynbellomy/Funky)
    + Dollar.Swift Functional Toolkit like Lodash and Underscore [:pencil2:](https://github.com/ankurp/Dollar.swift)
    - SwiftLand MicroFramework [:pencil2:](https://github.com/AlexanderKaraberov/SwiftLand)

[:arrow_up:](#index)

#### **Functional Reactive Programming**
### FRP
   * WhatI wished younger me knew about FRP [:page_facing_up:](http://codeplease.io/2016/04/04/what-i-wished-younger-me-knew/)
   * Why FRP [:page_facing_up:](http://codeplease.io/2016/01/08/why-frp/)
   * FRP in Swift 2.0 [:microphone:](https://realm.io/news/agnes-vasarhelyi-beer-app-frp-swift-2/)
   * Functional Reactive Programming in an Imperative World [:microphone:](https://realm.io/news/nacho-soto-functional-reactive-programming/)
   * FRP is a forbidden term [:page_facing_up:](https://medium.com/@andrestaltz/why-i-cannot-say-frp-but-i-just-did-d5ffaa23973b#.te52wjpxq) [:page_facing_up:](https://sideeffects.xyz/2015/the-functional-reactive-misconception/)
   * What is FRP? On StackOverflow [:page_facing_up:](http://stackoverflow.com/questions/1028250/what-is-functional-reactive-programming/1030631#1030631)
   * State, Promises, and Reactive Programming [:microphone:](https://realm.io/news/state-promises-reactive-programming/) [:pencil2:](https://github.com/ReactKit/ReactKit)
   * Functional Reactive Programming on iOS [:floppy_disk:](https://speakerdeck.com/benjamin_encz/functional-reactive-programming-on-ios)
   * Delta Library for managing state [:page_facing_up:](https://github.com/thoughtbot/Delta)
   * Functional Reactive Intuition [:page_facing_up:](http://itchingpixels.com/blog/functional-reactive-intuition-swift/)
   * What is Functional Reactive Programming? [:link:](http://stackoverflow.com/questions/1028250/what-is-functional-reactive-programming/1030631#1030631)
   * The Non-Reactive Solution [:page_facing_up:](http://inessential.com/2016/04/04/the_non-reactive_solution)
   * Simple Reactive Programming [:pencil:](https://gist.github.com/monyschuk/07be2c45c2a7157522f7)

### MVVM
   * MVVM + FRP [:page_facing_up:](http://www.sprynthesis.com/2014/12/06/reactivecocoa-mvvm-introduction/)
   * Modern application architectures (Reactive programming, MVVM and beyond) [:page_facing_up:](https://slack-files.com/T051G5Y6D-F0HABHKDK-8e9141e191)
   * MVVM in Practice [:page_facing_up:](http://bartjacobs.com/swift-and-model-view-viewmodel-in-practice/) [:page_facing_up:](http://bartjacobs.com/more-swift-and-model-view-viewmodel-in-practice/)
   * Reactive Learning Curve [:page_facing_up:](https://medium.com/@clozach/climbing-the-reactive-learning-curve-4a03fa8d17ae#.uy89014wo)
   * Reddit MVVM Benchmark [:pencil2:](https://github.com/ivanbruel/Reddit-MVVM-Benchmark)

### RAC
   * Introduction [:page_facing_up:](http://nomothetis.svbtle.com/an-introduction-to-reactivecocoa)
   * Reacting to Events [:page_facing_up:](http://nomothetis.svbtle.com/reactivecocoa-ii-reacting-to-signals)
   * ReactiveCocoa 4.0 Info [:link:](https://blog.alltheflow.com/reactivecocoa-4-0-with-swift-2-0/)
   * RAC 3 with Ash Furrow [:floppy_disk:](http://www.slideshare.net/colineberhardt/reactivecocoa-and-swift-better-together?qid=8a7611e7-4c08-4e2f-9f81-99b67c6f4390&v=default&b=&from_search=10), and some other nice [:floppy_disk:](https://speakerdeck.com/romainpouclet/taking-a-peak-at-reactivecocoa-3-dot-0)
   * FRP with RAC in Swift [:floppy_disk:](https://speakerdeck.com/ashfurrow/functional-reactive-programming-in-swift)
   * MVVM + Rac 4 [:pencil2:](https://github.com/richeterre/SwiftGoal)
   * RAC Schedulers [:page_facing_up:](http://codeplease.io/2015/11/30/schedulers/)
   * RACNest: RAC + MVVM Examples [:pencil2:](https://github.com/RuiAAPeres/RACNest)
   * Reactive Command Pattern [:pencil2:](https://github.com/pepibumur/ReactiveCommander)

### Rx
   * Simple RxSwift [:page_facing_up:](https://littlebitesofcocoa.com/162-reacting-with-rxswift) [:page_facing_up:](https://littlebitesofcocoa.com/163-creating-observables-with-rxswift)
   * Functional Rective Programming with RxSwift [:floppy_disk:](https://speakerdeck.com/realm/functional-reactive-programming-with-rxswift)
   * MVVM + RxSwift [:microphone:](https://realm.io/news/slug-max-alexander-functional-reactive-rxswift/) [:pencil2:](https://github.com/RxSwiftCommunity/RxViewModel), [:page_facing_up:](https://medium.com/@marinbenc/implementing-mvvm-in-ios-with-rxswift-458a2d47c33d#.k901myr5x), [:page_facing_up:](http://tailec.com/blog/reactive-recipe-2)
   * The Difference between RxSwift and ReactiveCocoa [:page_facing_up:](http://stackoverflow.com/questions/32542846/reactivecocoa-vs-rxswift-pros-and-cons) [:page_facing_up:](https://ashfurrow.com/blog/reactivecocoa-vs-rxswift/) [:page_facing_up:](https://sideeffects.xyz/2015/from-rac-to-rxswift-the-survival-guide/)
   * Learning RxSwift [:link:](https://github.com/pepaslabs/LearningRxSwift)
   * Upgrading to RxSwift [:page_facing_up:](http://artsy.github.io/blog/2015/12/08/reactive-cocoa-to-rxswift/)
   * RxSwift Community Webpage [:link:](http://community.rxswift.org/)
   * Split laps timer with RxSwift and RxCocoa [:page_facing_up:](http://rx-marin.com/post/rxswift-rxcocoa-sample-split-laps-timer/) [:page_facing_up:](http://rx-marin.com/)
   * Introduction to Rx [:link:](http://reactivex.io/documentation/operators.html)

[:arrow_up:](#index)

### **Generics**
- About
    + Generics in Swift, Part 1 [:page_facing_up:](http://austinzheng.com/2015/01/02/swift-generics-pt-1/), Part 2 [:page_facing_up:](http://austinzheng.com/2015/09/29/swift-generics-pt-2/)
    + Official Docs [:pencil:](https://github.com/apple/swift/blob/master/docs/Generics.rst)
    - A Sanatorium for Swift Generics [:page_facing_up:](http://natecook.com/blog/2015/03/a-sanatorium-for-swift-generics/)
- Covariance
    + Covariant and contravariant generic type parameters [:link:](https://forums.developer.apple.com/thread/5056)
- Protocol Generics
    + The shortcomings of generic protocols [:page_facing_up:](http://krakendev.io/blog/generic-protocols-and-their-shortcomings)
    + Generic Protocols [:page_facing_up:](http://milen.me/writings/swift-generic-protocols/)
    - Protocol Generics Self [:pencil:](https://gist.github.com/AliSoftware/e6b931c1731f016e41fb)
    - Generic Protocols in Swift [:link:](http://stackoverflow.com/questions/24469913/how-to-create-generic-protocols-in-swift-ios)
    - Extending Swift Generic Types [:link:](http://www.marisibrothers.com/2016/03/extending-swift-generic-types.html)
    - Generic Typealias in Swift [:page_facing_up:](http://stackoverflow.com/questions/27084586/generic-typealias-in-swift)
    - [What are Generic Protocols good for?](https://dzone.com/articles/swift-generic-protocols-what-are-they-good-for)
- Where keyword
    - Swift “where” keyword [:link:](http://stackoverflow.com/questions/25336079/swift-where-key-word/25336571#25336571)
    - Multiple Type constraints with where [:link:](http://stackoverflow.com/questions/24089145/multiple-type-constraints-in-swift)
- Patterns
    + Generic Constructors [:link:](http://stackoverflow.com/a/30857172/2855836) and factories [:link:](http://stackoverflow.com/questions/24341061/how-to-write-generic-factory-method-in-swift)
- Parametric Polymorphism
    + Parametric Polymorphism in Swift [:page_facing_up:](http://nsomar.com/parametric-compile-time-polymorphism-in-swift/) [:page_facing_up:](http://rosettacode.org/wiki/Parametric_polymorphism) [:page_facing_up:](http://cs.stackexchange.com/questions/26389/why-isnt-the-swift-programming-language-type-inference-more-aggressive)
+ Generic Arrays in Swift 2.0 [:page_facing_up:](http://blog.krzyzanowskim.com/2015/10/07/generic-array-uint8/)
+ Partial Function Application with Generics [:link:](http://stackoverflow.com/questions/28353539/swift-partial-function-application-with-generics)
- Template Metaprogramming Swift [:page_facing_up:](http://stackoverflow.com/questions/26939354/metaprogramming-in-swift)
- Generic Functions for Incompatible Types [:page_facing_up:](http://natecook.com/blog/2014/08/generic-functions-for-incompatible-types/)

[:arrow_up:](#index)

#### **Initialization, Properties, and Dependency Injection**
+ Initialization
    - Initialization in Swift 2 part series [:page_facing_up:](https://www.raywenderlich.com/119922/swift-tutorial-initialization-part-1) [:page_facing_up:](https://www.raywenderlich.com/121603/swift-tutorial-initialization-part-2)
    + Swift Initializers [:page_facing_up:](http://ashfurrow.com/blog/swift-initializers/)
    + Be Mindful of Your Filters [:page_facing_up:](http://owensd.io/blog/be-mindful-of-your-filters/)
    + Swift Initialization and the Pain of Optionals [:page_facing_up:](http://blog.scottlogic.com/2014/11/20/swift-initialisation.html)
    + Initializers for Structs [:page_facing_up:](http://www.codingexplorer.com/structures-swift/)
    + Swift init() [:page_facing_up:](http://merowing.info/2015/11/swift-init/)
    + Public Getter, Private Setter [:page_facing_up:](https://www.natashatherobot.com/swift-magic-public-getter-private-setter/)
    - What are get and set? [:page_facing_up:](http://stackoverflow.com/questions/24699327/swift-what-are-get-and-set)
    - Why is the convenience keyword needed in Swift? [:link:](http://stackoverflow.com/questions/30896231/why-convenience-keyword-is-even-needed-in-swift)
    - When should I use deinit? [:link:](http://stackoverflow.com/questions/24018758/when-should-i-use-deinit)
    - Designated and Convenience initializers in Swift [:page_facing_up:](http://www.codingexplorer.com/designated-initializers-convenience-initializers-swift/)
    - Writing Class Initalizers [:page_facing_up:](http://www.codingexplorer.com/class-initializers/)
    + Swift Failiable Initializers [:page_facing_up:](http://www.jessesquires.com/swift-failable-initializers-revisited/)
    - Designated Initializer Basics [:page_facing_up:](https://littlebitesofcocoa.com/204-swift-designated-initializer-basics)
    - Dynamic Init [:pencil:](https://gist.github.com/Ben-G/cb1708b1068d2bc5916f)
    + Definitive Variable Initialization [:page_facing_up:](https://medium.com/the-traveled-ios-developers-guide/on-definitive-initialization-54284ef5c96f#.5wdzuyrev)
    - Lazy initialization [:page_facing_up:](http://mikebuss.com/2014/06/22/lazy-initialization-swift/)
    - Default initializer [:link:](http://stackoverflow.com/questions/25327168/default-initializer-in-swift?rq=1)
+ Properties
    + Type Properties
        + Instance property vs static type property vs computed type property [:page_facing_up:](http://stackoverflow.com/questions/24087936/how-do-i-make-class-methods-properties-in-swift)
        - About Type properties [:page_facing_up:](http://stackoverflow.com/a/24138580/2855836)
    + Stored Properties
        + Stored Properties [:page_facing_up:](https://www.quora.com/Apple-Swift-programming-language/What-is-a-stored-property)
        - List of class' properties [:link:](http://stackoverflow.com/questions/24844681/list-of-classs-properties-in-swift?lq=1)
    - Named Parameters
        - Named Parameters [:page_facing_up:](http://owensd.io/blog/named-parameters/)
        - Intuition behind the Swift external/local parameter system [:page_facing_up:](https://jeremywsherman.com/blog/2014/06/05/intuition-behind-swift-external-local-parameter-system/)
        - Swift named parameters [:page_facing_up:](http://useyourloaf.com/blog/swift-named-parameters.html)
    - Property Observers
        - Property Observers and Lazy Properties [:page_facing_up:](https://littlebitesofcocoa.com/179-swift-tricks-properties)
        + Property Observers [:page_facing_up:](https://www.quora.com/Apple-Swift-programming-language/What-is-a-property-observer)
        - Swift Property Observers [:page_facing_up:](http://www.codingexplorer.com/swift-property-observers/)
    - IBOutlets
        - Outlets: Strong! Or Weak? [:page_facing_up:](http://scottberrevoets.com/2016/03/21/outlets-strong-or-weak/)
        + IBOutlet Style in Swift [:page_facing_up:](http://natashatherobot.com/ios-a-beautiful-way-of-styling-iboutlets-in-swift/)
    - Computed Properties
        - Beware of Computed Properties [:page_facing_up:](https://www.natashatherobot.com/swift-computed-properties/)
        - How to use swift computed properties [:page_facing_up:](http://adamdelong.com/how-to-use-swift-computed-properties-to-create-a-simple-goal-tracker-class/)
        - Computed Properties and Initializers [](http://www.codingexplorer.com/swift-extensions/)
        - Static Vars are Lazy in Swift [:link:](https://developer.apple.com/swift/blog/?id=7)
        + Lazy Properties in Structs [:page_facing_up:](http://oleb.net/blog/2015/12/lazy-properties-in-structs-swift/)
        - Turn Computed Property into Lazy Property [:page_facing_up:](http://kostiakoval.github.io/posts/turn-computed-property-into-lazy-roperty)
    + Static Properties
        - Static Properties [:page_facing_up:](https://www.hackingwithswift.com/read/0/18/static-properties-and-methods)
        - Does Swift have class level static variables [:page_facing_up:](http://stackoverflow.com/questions/26804066/does-swift-have-class-level-static-variables?lq=1)
        - Static vs class functions/variables in Swift classes? [:link:](http://stackoverflow.com/questions/29636633/static-vs-class-functions-variables-in-swift-classes)
    + Read-only
        - Read-only and non-computed variable properties [:link:](http://stackoverflow.com/questions/24081194/read-only-and-non-computed-variable-properties-in-swift)
+ Dependency Injection
    + You Used To Inject Me In Your Constructor [:floppy_disk:](https://speakerdeck.com/mathonsunday/you-used-to-inject-me-in-your-constructor)
    - How to Dependency Inject on iOS [:microphone:](https://www.youtube.com/watch?v=384rumYOs-g)
    - Dependency Injection in Swift [:page_facing_up:](https://medium.com/ios-os-x-development/dependency-injection-in-swift-a959c6eee0ab#.r2gq9cjv7) [:page_facing_up:](http://natashatherobot.com/ios-unit-testing-dependency-injection-with-structs-in-swift/) [:page_facing_up:](https://medium.com/ios-os-x-development/dependency-injection-in-view-controllers-9fd7d2c77e55#.wxwnwtqmo)
    + Dependency Injection with a Custom Initializer [:page_facing_up:](https://www.natashatherobot.com/swift-dependency-injection-with-a-custom-initializer/)
    - Dependency Injection Container [:pencil2:](https://github.com/AliSoftware/Dip) [:pencil2:](https://github.com/AliSoftware/Dip-UI)
    - Nuts and Bolts of Dependency Injection in Swift [:page_facing_up:](http://bartjacobs.com/dependency-injection-in-swift/)
    - Inversion of Control and Dependency Injection [:pencil2:](https://github.com/jgretz/CoreMeta)
    - Swift Dependency Injection Framework [:pencil2:](https://github.com/knightswhosaynil/Apodidae) [:pencil2:](https://github.com/Swinject/Swinject)
    - Swift Injection Wesite [:link:](https://yoichitgy.github.io/)
    - Property Injection [:page_facing_up:](https://sharpfivesoftware.com/2015/02/17/testing-singletons-in-swift-property-injection/)
    - Constructor Injection [:page_facing_up:](https://sharpfivesoftware.com/2015/02/03/testing-singletons-in-swift/)
    - DIY: Build Your Own Dependency Injection Library [:microphone:](https://realm.io/news/android-pierre-yves-ricau-build-own-dependency-injection/)

[:arrow_up:](#index)

#### **Interpolability**
- C
    - Swift And C: Everything You Need to Know [:page_facing_up:](https://www.uraimo.com/2016/04/07/swift-and-c-everything-you-need-to-know/)
    + Swift and C [:microphone:](https://realm.io/news/pragma-chris-eidhof-swift-c/)
    - Why C is not always safe Swift [:page_facing_up:](http://www.cocoawithlove.com/blog/2016/02/16/use_it_or_lose_it_why_safe_c_is_sometimes_unsafe_swift.html)
    + Wrapping a C library in a Swift Framework [:page_facing_up:](http://colindrake.me/2015/10/05/wrapping-a-c-library-in-a-swift-framework/)
    + Mapping Swift Types to C Pointers [:page_facing_up:](https://tetontech.wordpress.com/2014/10/22/swift-c-libraries-and-mapping-swift-types-to-c-pointer-types/)
    - Swift Interop [:microphone:](https://www.skilled.io/chriseidhof/swift-interop)
    - char ** in Swift [:page_facing_up:](http://dduan.net/post/2015/11/char-star-star-in-swift/)
    - C Pointer Memory [:page_facing_up:](http://en.swifter.tips/pointer-memory/)
    - C Callbacks in Swift [:page_facing_up:](http://oleb.net/blog/2015/06/c-callbacks-in-swift/)
    - A Swift wrapper around libcurl that works with Linux [:pencil2:](https://github.com/SwiftOnTheServer/CCurl)
    - Swift Wrappers Around CommonMark [:pencil2:](https://github.com/chriseidhof/commonmark-swift)
    - Swift Substring on a C String [:page_facing_up:](http://dev.iachieved.it/iachievedit/swift-substring-on-a-c-string/)
    - Swift can now partially import C aggregate [:link:](http://stackoverflow.com/questions/24622475/using-glkmath-from-glkit-in-swift/24622846#24622846)
    - Compiling and Interpolating C with the spm [:page_facing_up:](http://ankit.im/swift/2016/04/06/compiling-and-interpolating-C-using-swift-package-manager/)
- Objective-C
    + Swift & the ObjC Runtime [:page_facing_up:](http://nshipster.com/swift-objc-runtime/)
    + How are NSDictionaries implemented in-memory? [:page_facing_up:](http://ciechanowski.me/blog/2014/04/08/exposing-nsdictionary/#comment-1345004966)
    + Exposing NSMutableArray [:page_facing_up:](http://ciechanowski.me/blog/2014/03/05/exposing-nsmutablearray/)
    + Source-Code for the Objective-C Runtime [:pencil2:](http://opensource.apple.com/source/objc4/objc4-551.1/)
    - Wrapping Objc Frameworks in Swift [:floppy_disk:](https://speakerdeck.com/jpsim/wrapping-objective-c-frameworks-in-swift)
    - Casting Swift objects to Objective-C types [:page_facing_up:](https://plus.google.com/+AndreyTarantsov/posts/AZmU5c3nJwc)
    - How to call Objective C code from Swift [:page_facing_up:](http://stackoverflow.com/questions/24002369/how-to-call-objective-c-code-from-swift?rq=1)
    + Method Swizzling in Swift [:page_facing_up:](http://www.uraimo.com/2015/10/23/effective-method-swizzling-with-swift/)
    + How to Method Swizzle in Swift [:page_facing_up:](http://kostiakoval.github.io/posts/methods-swizzling-in-swift) [:page_facing_up:](http://en.swifter.tips/)
    + Conform to Objective C Protocols in Swift [:page_facing_up:](http://cocoa.tumblr.com/post/128293810968/conforming-to-objective-c-protocols-with-custom?is_related_post=1)
    - Swift extensions on Objective-C classes still need to be prefixed [:page_facing_up:](https://pspdfkit.com/blog/2016/surprises-with-swift-extensions/)

[:arrow_up:](#index)

#### **Internals**
- ARC
    - ARC + Swift [:page_facing_up:](https://medium.com/the-traveled-ios-developers-guide/arc-swift-d323535baecb#.td8gy7jid)
    + Swift Manual Retain/Release [:page_facing_up:](http://www.russbishop.net/swift-manual-retain-release)
    - ARC in depth [:page_facing_up:](https://sectionfive.net/blog/2015/03/31/arc-in-depth-part-i/) [:page_facing_up:](https://sectionfive.net/blog/2015/06/12/arc-in-depth-part-ii/)
    - ARC Exploration and pitfalls [:page_facing_up:](https://sectionfive.net/blog/2014/11/24/arc-exploration-and-pitfalls/)
    - Static vs Dynamic Linking [:page_facing_up:](http://www.thedotpost.com/2015/02/marius-rackwitz-static-vs-dynamic-linking)
    - ARC vs Garbage Collection [:page_facing_up:](http://typedarray.org/swift-arc-vs-flash-gc/)
    - Why Swift should drop ARC [:page_facing_up:](https://digitalleaves.com/blog/2014/07/memory-management-in-swift-a-lost-opportunity/)
    - Call By Name [:page_facing_up:](http://www.russbishop.net/swift-call-by-name)
    - Are Swift variables atomic? [:page_facing_up:](http://stackoverflow.com/questions/24157834/are-swift-variables-atomic)
    - Is there a reason that Swift array assignment is inconsistent (neither a reference nor a deep copy)? [:link:](http://stackoverflow.com/questions/24081009/is-there-a-reason-that-swift-array-assignment-is-inconsistent-neither-a-referen)
    - How does Swift implement ARC in property attributes? [:link:](http://stackoverflow.com/questions/24387634/how-does-swift-implement-arc-in-property-attributes)
    - Will ARC always make Swift slower than a language without any type of garbage collector like C++ or C? [:page_facing_up:](https://www.quora.com/Will-ARC-always-make-Swift-slower-than-a-language-without-any-type-of-garbage-collector-like-C++-or-C?srid=xrLC&share=e61ad115)
- Assembly
    - IR is better than assembly [:page_facing_up:](https://idea.popcount.org/2013-07-24-ir-is-better-than-assembly/)
    - iOS Assembly Tutorial: Understanding ARM [:page_facing_up:](https://www.raywenderlich.com/37181/ios-assembly-tutorial)
    - An ARM Build Farm with Jenkins [:page_facing_up:](http://dev.iachieved.it/iachievedit/an-arm-build-farm-with-jenkins/)
    - Swift for ARM Systems [:page_facing_up:](http://dev.iachieved.it/iachievedit/swift-for-arm-systems/)
- Build
    - Steps of a Swift Application Build [:link:](http://stackoverflow.com/a/25965909/2855836)
    - Build Configuration Management [:page_facing_up:](http://dev.iachieved.it/iachievedit/build-configuration-management-with-swift/)
    - Swift Byte Packing [:page_facing_up:](http://www.russbishop.net/packing-bytes-in-swift)
    - Swift Compilation Reporting at Tumblr [:page_facing_up:](https://engineering.tumblr.com/post/144151794436/swift-compilation-reporting-at-tumblr)
- Clang
    - Clang documentation [:link:](http://clang.llvm.org/docs/index.html)
    - Clang format for Xcode [:pencil:](https://github.com/travisjeffery/ClangFormat-Xcode)
    - fucking clang warnings [:link:](http://fuckingclangwarnings.com/)
    - Clang vs Other Open Source Compilers [:page_facing_up:](http://clang.llvm.org/comparison.html)
    - What is the difference between LLVM and Clang? [:page_facing_up:](https://www.quora.com/What-is-the-difference-between-LLVM-and-Clang)
- Grammar
  - Implicit Member Expression [:link:](http://stackoverflow.com/a/35387593/2855836)
- LLVM Compiler
    - WWDC 2014: What's new in LLVM [:microphone:](http://devstreaming.apple.com/videos/wwdc/2014/417xx2zsyyp8zcs/417/417_whats_new_in_llvm.pdf) [:floppy_disk:](http://devstreaming.apple.com/videos/wwdc/2014/417xx2zsyyp8zcs/417/417_whats_new_in_llvm.pdf)
    + LLVM by Chris Lattner [:page_facing_up:](http://aosabook.org/en/llvm.html)
    + Swift Intermediate Language [:floppy_disk:](http://llvm.org/devmtg/2015-10/slides/GroffLattner-SILHighLevelIR.pdf)
    + Using the LLVM API With Swift [:page_facing_up:](http://lowlevelbits.org/how-to-use-llvm-api-with-swift/)
    - LLVM and Swift [:microphone:](https://www.youtube.com/watch?v=Ntj8ab-5cvE)
    - LLVM in Swift: Setup [:page_facing_up:](http://dduan.net/post/2015/10/lets-play-llvm-in-swift-setup/)
    - Kaleidoscope: Implementing a Parser and AST in LLVM [:page_facing_up:](http://llvm.org/docs/tutorial/LangImpl1.html) [:pencil2:](https://github.com/matthewcheok/Kaleidoscope)
    - Swift Object Name De-mangling [:page_facing_up:](https://www.securify.nl/blog/SFY20150302/hooking_swift_methods_for_fun_and_profit.html)
    - How to use LLVM API with Swift [:page_facing_up:](http://lowlevelbits.org/how-to-use-llvm-api-with-swift/) [:page_facing_up:](http://lowlevelbits.org/how-to-use-llvm-api-with-swift-addendum/)
    - Swift Compiler [:page_facing_up:](https://www.accelebrate.com/blog/thinking-swift-part-ii/)
    - Parsing Mach-O files [:page_facing_up:](http://lowlevelbits.org/parse-mach-o-files/)
    - How to use LLVM C API with Swift [:page_facing_up:](https://fosdem.org/2016/schedule/event/llvm_c_swift/) [:page_facing_up:](https://github.com/AlexDenisov/swift_llvm)
    - Creating a Virtual Machine/Register VM [:page_facing_up:](https://en.wikibooks.org/wiki/Creating_a_Virtual_Machine/Register_VM_in_Swift)
    - What is LLVM and how does it differ from GCC? [:page_facing_up:](https://www.quora.com/What-is-LLVM-and-how-it-is-different-from-GCC)
    - Swift wrapper around LLVM [:pencil2:](https://github.com/bencochran/LLVM.swift)
    - Simple programming language written in Swift and compiled with LLVM [:pencil2:](https://github.com/bencochran/Kaleidoscope)
- Memory
    - Exploring Swift's Dictionary Implementation [:page_facing_up:](http://ankit.im/swift/2016/01/20/exploring-swift-dictionary-implementation/)
    - Swift Memory Layout [:page_facing_up:](https://www.mikeash.com/pyblog/friday-qa-2014-07-18-exploring-swift-memory-layout.html)
    - Swift Struct Storage [:page_facing_up:](https://www.mikeash.com/pyblog/friday-qa-2016-01-29-swift-struct-storage.html)
    - Bitcode Demystified [:page_facing_up:](http://lowlevelbits.org/bitcode-demystified/)
    - Memory management using Swift and Objective-C [:page_facing_up:](http://www.ibm.com/developerworks/library/mo-ios-memory/)
    - Swift Memory and Concurrency Model [:page_facing_up:](http://fossies.org/linux/misc/swift-swift-2.2-SNAPSHOT-2015-12-01-b.tar.gz/swift-swift-2.2-SNAPSHOT-2015-12-01-b/docs/proposals/archive/Memory%20and%20Concurrency%20Model.rst)
    - Where is my variable being stored? [:link:](http://stackoverflow.com/questions/31987566/where-is-my-variable-being-stored-swift)
- Optimizations
    - The Importance of Being Final [:page_facing_up:](http://blog.human-friendly.com/the-importance-of-being-final)
    - Switch Statement Optimizations [:link:](http://stackoverflow.com/questions/25284522/switch-statement-optimization-swift)
    - Swift Whole Module Optimization [:page_facing_up:](http://useyourloaf.com/blog/swift-whole-module-optimization/)
    - Increasing Performance by Reducing Dynamic Dispatch [:microphone:](https://developer.apple.com/swift/blog/?id=27)
    - Dynamic Dispatch and Whole Module Optimization [:page_facing_up:](http://useyourloaf.com/blog/dynamic-dispatch-and-whole-module-optimization/)
    - How Swift uses introSort [:page_facing_up:](http://stackoverflow.com/questions/27677026/swift-sorting-algorithm-implementation)
    - Optimizing Swift Performance [:microphone:](https://developer.apple.com/videos/play/wwdc2015-409/)
    - Functional Style - 50x Speed boost from changing 1 Keyword [:page_facing_up:](http://blog.human-friendly.com/optimising-swift-with-functional-style-50x-speed-boost-from-changing-1-keyword)
    - Launch time performance optimization [:page_facing_up:](http://www.avanderlee.com/optimization/launch-time-performance-optimization/)
    - Meaning of the LLVM Optimization Levels [:link:](http://stackoverflow.com/questions/21447377/meaning-of-the-llvm-optimization-levels)
    - ARC Optimization for Swift [:pencil:](https://github.com/apple/swift/blob/master/docs/ARCOptimization.rst)
    - High Level SIL Optimizations [:pencil:](https://github.com/apple/swift/blob/master/docs/HighLevelSILOptimizations.rst)
    - The Effect of Dependency Structure on iOS Launch Times [:page_facing_up:](https://engineering.tumblr.com/post/144507330193/peeking-into-a-black-box-the-effect-of)
- Performance
    - Swift Performance [:floppy_disk:](http://blog.human-friendly.com/swift-performance-iosdevuk) [:page_facing_up:](http://www.swift-studies.com/blog/2014/7/8/learning-about-swift-performance)[:pencil:](https://github.com/koher/swift-performance-experiment)
    - Swift 2 Under the Hood [:floppy_disk:](https://speakerdeck.com/alblue/swift-2-under-the-hood-gotober-2015)
    - Swift Compiler Diagnostics [:page_facing_up:](http://oleb.net/blog/2015/08/swift-compiler-diagnostics/)
    - Swift: Performance of Inline Code versus Instance Methods versus Class Methods [:page_facing_up:](http://flexmonkey.blogspot.com/2014/09/swift-performance-of-inline-code-versus.html)
    - Simple Swift.String Performance Test [:pencil2:](https://github.com/bnickel/Simple-Swift.String-Performance-Test)
    - Secret of Swift Performance [:page_facing_up:](https://medium.com/swift-programming/secret-of-swift-performance-fcc5d2a437a8#.q0cnnqxat) [:page_facing_up:](https://medium.com/swift-programming/secret-of-swift-performance-a8ee86060843#.i6p6554gk)
    - Writing High Performance Swift Code [:link:](https://github.com/apple/swift/blob/master/docs/OptimizationTips.rst)
    - Swift Single Soutce [:pencil:](https://github.com/apple/swift/tree/master/benchmark/single-source)
    - 10 thousand times faster Swift [:page_facing_up:](https://medium.com/@icex33/10-thousand-times-faster-swift-737b1accd973#.92zevwqyq)
- Preprocessing
    - Preprocessing in Swift [:link:](http://stackoverflow.com/questions/24369272/swift-ios-deployment-target-command-line-flag)
    - Preprocessor Macros [:link:](http://stackoverflow.com/questions/24111854/in-absence-of-preprocessor-macros-is-there-a-way-to-define-practical-scheme-spe)
    - Parsing Mach-O Files [:page_facing_up:](http://lowlevelbits.org/parse-mach-o-files/)
    - -Xfront [:page_facing_up:](http://www.robertvojta.com/2015/06/30/swift-hidden-options/)
    - Change your API endpoint/environment using Xcode Configurations in Swift [:page_facing_up:](https://medium.com/@danielgalasko/change-your-api-endpoint-environment-using-xcode-configurations-in-swift-c1ad2722200e#.a1lggp7pb)
- SIL and swiftc
    - Official SIL Page [:pencil:](https://github.com/apple/swift/blob/master/docs/SIL.rst)
    - - 🖇Introduction to Swift Intermediate Language [:video_camera:](https://www.youtube.com/watch?feature=youtu.be&utm_medium=email&v=NH-qIKOoKgA)
    - Exploring SIL and swiftc [:page_facing_up:](http://swiftc.io/)
    - swift vs swiftc [:page_facing_up:](http://owensd.io/2015/01/14/swift-vs-swiftc.html)
    - SIMD (Single Instruction Multiple Data) [:page_facing_up:](http://www.russbishop.net/swift-2-simd)
    - @convention [:page_facing_up:](http://stackoverflow.com/questions/30740560/new-conventionc-in-swift-2-how-can-i-use-it)
    - Introspecting Swift [:floppy_disk:](https://speakerdeck.com/jpsim/introspecting-swift)
    - Unsafe Swift [:floppy_disk:](https://speakerdeck.com/realm/unsafe-swift)
    + Type Introspection and demangling [:page_facing_up:](http://ericasadun.com/2014/06/16/swift-more-than-you-probably-want-to-know-about-type-introspection/)
    - The mysterious builtin module [:page_facing_up:](http://ankit.im/swift/2016/01/12/swift-mysterious-builtin-module/)
    - SIL Optimizations [:pencil:](https://github.com/apple/swift/blob/master/docs/HighLevelSILOptimizations.rst)

[:arrow_up:](#index)

#### **Language Comparisons**
+ Language Comparisons
    - Haskell
        - Haskell Overlords [:page_facing_up:](http://robnapier.net/haskell-overlords)
        - Learning Swift from Haskell [:floppy_disk:](https://speakerdeck.com/abizern/what-haskell-teaches-me-about-writing-swift) and corresponding [:microphone:](https://realm.io/news/altconf-abizer-nasir-what-haskell-teaches-me-about-swift/)
        - Functional Programming like Haskell [:floppy_disk:](https://speakerdeck.com/mchakravarty/functional-programming-in-a-stateful-world) [:microphone:](https://yow.eventer.com/yow-lambda-jam-2015-1305/functional-programming-in-a-stateful-world-by-manuel-chakravarty-1883)
        + What do Haskell developers think of Swift? [:link:](https://www.quora.com/What-do-Haskell-developers-think-of-Swift)
        + A Swift intoduction to Haskell [:floppy_disk:](https://speakerdeck.com/johannesweiss/swift-london-meetup-introduction-to-haskell)
        - Hindley-Milner languages [:link:](http://qr.ae/Rg3rFd)
        - Quicksort in swift with haskell style [:link:](http://stackoverflow.com/questions/26310136/quicksort-in-swift-with-haskell-style/26310566#26310566)
    - Javascript
        + Comparing Swift and Javascript [:page_facing_up:](http://www.mircozeiss.com/swift-for-javascript-developers)
        - From JS to Swift [:page_facing_up:](http://www.folio3.com/blog/swiftly-javascript-from-javascript-to-apples-swift/)
        - Swift vs React Native [:page_facing_up:](https://medium.com/ios-os-x-development/an-ios-developer-on-react-native-1f24786c29f0#.h7kbylshm)
    - C
        - Swift vs C speed test [:page_facing_up:](http://stackoverflow.com/questions/24101718/swift-performance-sorting-arrays) [:page_facing_up:](https://www.quora.com/Is-Swift-programming-language-faster-than-C-or-C++-and-if-yes-why) [:page_facing_up:](https://medium.com/swift-programming/swifth-vs-c-5be7d0398f4f#.6ume737mt)
    - C++
        - Swift vs C++ Benchmarks [:page_facing_up:](http://www.primatelabs.com/blog/2014/12/swift-performance/) [:pencil:](https://github.com/primatelabs/geekbench-swift)
        + C++ Advice to Swift Devs [:page_facing_up:](http://airspeedvelocity.net/2014/06/10/rundown-of-how-each-effective-c-item-relates-to-swift/)
        - Is Swift a viable alternative to C++ for performance critical code? [:page_facing_up:](https://www.quora.com/Is-Swift-a-viable-alternative-to-C++-for-performance-critical-code?srid=xrLC&share=abc6caeb)
        - Swift vs Modern C++ [:link:](https://www.youtube.com/watch?v=VxevGjZ8RuE)
        - Use a C++ Library from Swift [:page_facing_up:](http://www.swiftprogrammer.info/swift_call_cpp.html)
    - C#
        - Swift for C# Developers [:page_facing_up:](https://developer.ibm.com/swift/2016/02/25/swift-for-c-developers/)
        - Swift is a lot like C# [:link:](http://swiftcomparsion.qiniudn.com/)
        - Swift vs C# [:page_facing_up:](http://www.sitharus.com/2014/06/swift-vs-csharp.html)
        - Swift vc C# reference guide [:link:](http://download.microsoft.com/download/4/6/9/469501F4-5F6B-4E51-897C-9A216CFB30A3/SwiftCSharpPoster.pdf)
        - Is something in Swift like LINQ in C# [:link:](http://stackoverflow.com/questions/29655304/is-something-in-swift-like-linq-in-c-sharp)
        - Are the Tuples in Swift complete alternative to Anonymous types as in C# [:link:](http://stackoverflow.com/questions/24080591/are-the-tuples-in-swift-complete-alternative-to-anonymous-types-as-in-c-sharp)
        - Swift Protocol Extensions and C# Abstract Classes [:page_facing_up:](https://www.andrewcbancroft.com/2015/08/06/analyzing-swift-protocol-extensions-and-c-abstract-classes/)
        - C# like async in Swift [:page_facing_up:](https://alastairs-place.net/blog/2014/06/09/c-number-like-async-in-swift/)
    - Java
        + Swift Protocols vs Java 8 Interfaces [:page_facing_up:](http://stackoverflow.com/questions/30859334/compare-protocol-in-swift-vs-interface-in-java)
        - Swift 2.0 Protocol Extensions vs Java Abstract Classes [:link:](http://stackoverflow.com/questions/30943209/is-there-a-difference-between-swift-2-0-protocol-extensions-and-java-c-abstract)
        - Swift vs Java Performance [:page_facing_up:](https://www.quora.com/In-terms-of-performance-speed-is-Swift-faster-than-Java)
        - Making Abstract Classes in Swift [:page_facing_up:](http://bartjacobs.com/how-to-create-an-abstract-class-in-swift/) [:page_facing_up:](http://stackoverflow.com/questions/24110396/abstract-classes-in-swift-language)
        - Why doesn't Apple Swift adopt the memory management method of garbage collection like in Java? [:page_facing_up:](https://www.quora.com/Why-doesnt-Apple-Swift-adopt-the-memory-management-method-of-garbage-collection-like-in-Java)
        - Class level or struct level method in swift like static method in Java? [:link:](http://stackoverflow.com/questions/24107833/class-level-or-struct-level-method-in-swift-like-static-method-in-java)
        - Difference between Swift 2.0 protocol extensions and Java/C# abstract classes? [:page_facing_up:](http://stackoverflow.com/questions/30943209/is-there-a-difference-between-swift-2-0-protocol-extensions-and-java-c-abstract/30945263#30945263)
    - Kotlin
        - Swift is like Kotlin [:page_facing_up:](https://nilhcem.github.io/swift-is-like-kotlin/)
    - Android
        - How to Start Android Development with an iOS Background [:page_facing_up:](http://savvyapps.com/blog/how-to-start-android-development-with-an-ios-background)
    - Go
        - Swift vs Golang [:floppy_disk:](http://go-talks.appspot.com/github.com/wangkuiyi/swiftgo/swiftgo.slide#1)
        - Loops Go vs Swift [:page_facing_up:](http://lithium3141.com/blog/2015/11/26/variable-capture-in-go-vs-swift/)
    - Rust
        - Go vs Node vs Rust vs Swift [:page_facing_up:](https://grigio.org/go-vs-node-vs-rust-vs-swift/)
        - Rust from Swift [:page_facing_up:](http://faq.sealedabstract.com/rust/#a-word-on-design-philosophy)
        - Rust and Swift [:page_facing_up:](http://www.chriskrycho.com/2015/rust-and-swift-i.html)
        - Observations from Rust’s original designer [:page_facing_up:](http://graydon.livejournal.com/191100.html)
        - Differences between Rust and Swift [:page_facing_up:](https://www.quora.com/Programming-Languages/What-are-the-differences-between-Rust-and-Swift)
    - Ruby
        + Swift For Rubyists [:microphone:](https://realm.io/news/swift-for-rubyists/)
    - Scala
        + Swift vs Scala [:floppy_disk:](https://www.reddit.com/r/programming/comments/27dmsb/swift_vs_scala/) [:page_facing_up:](http://www.cultivatehq.com/swift-design-influences/)
        - Swift is a lot like Scala [:link:](https://leverich.github.io/swiftislikescala/)
    - Ocaml
        + OCaml's Deferred in Swift [:page_facing_up:](https://github.com/bignerdranch/Deferred)
    - Python
        - Pythonic Swift [:pencil2:](https://github.com/practicalswift/Pythonic.swift)
    - Elixir
        - Comparing Protocols and Extensions in Swift and Elixir [:page_facing_up:](http://blog.plataformatec.com.br/2014/06/comparing-protocols-and-extensions-in-swift-and-elixir/)
    + ObjC
        + How is Swift Faster than Objective-C? [:page_facing_up:](https://www.quora.com/How-is-Swift-faster-than-Objective-C)
        - A Eulogy for Objective C [:microphone:](https://realm.io/news/altconf-aaron-hillegass-eulogy-for-objective-c/)
        - The best of Obj-C to Swift [:microphone:](https://realm.io/news/altconf-jaim-zuber-the-stylish-objective-c-developer-s-guide-to-swift/) [:page_facing_up:](https://www.quora.com/What-are-the-best-code-examples-to-illustrate-the-benefits-of-Swift)
        - Swift vs Objective-C Fibonacci Sequence Speed Comparison [:link:](http://stackoverflow.com/questions/28161197/swift-vs-objective-c-fibonacci-sequence-speed-comparison)

[:arrow_up:](#index)

#### **Linux**
- Intro to Swift Dev on Linux [:page_facing_up:](http://www.raywenderlich.com/122189/introduction-to-open-source-swift-on-linux) [:page_facing_up:](https://www.twilio.com/blog/2015/12/getting-started-with-swift-on-linux.html)
- Dynamic Swift Framework Without Xcode [:page_facing_up:](http://dduan.net/post/2015/07/dynamic-swift-framework-without-xcode/)
- Foundation on Linux [:page_facing_up:](http://dev.iachieved.it/iachievedit/foundation-on-linux/)
- NSLinux Strings [:pencil2:](https://github.com/johnno1962/NSLinux)
- interact with Linux GPIO/SPI on ARM [:pencil2:](https://github.com/uraimo/SwiftyGPIO)
- Concurrency on Linux [:page_facing_up:](https://developer.ibm.com/swift/2016/02/22/talking-about-swift-concurrency-on-linux/)
- Power Linux [:page_facing_up:](https://developer.ibm.com/swift/2016/02/01/swift-on-power-linux/)
- Foundation on Linux [:page_facing_up:](http://dev.iachieved.it/iachievedit/foundation-on-linux/)
- Practical Cross-Platform Swift [:microphone:](https://realm.io/news/tryswift-jp-simard-practical-cross-platform-swift/)

[:arrow_up:](#index)

#### **Optionals**
+ How I handle Optionals in Swift [:page_facing_up:](http://blog.human-friendly.com/how-i-handle-optionals-in-swift)
+ How to unwrap an optional in 9 different ways [:page_facing_up:](https://twitter.com/Kametrixom/status/636187970509406209)
+ Optional Protocol Methods in Pure Swift [:page_facing_up:](http://blog.stablekernel.com/optional-protocol-methods-in-pure-swift)
+ Swift Optionals Made Simple [:page_facing_up:](http://appventure.me/2014/06/13/swift-optionals-made-simple/)
+ Every Kind of Optional [:page_facing_up:](http://www.fantageek.com/blog/2015/12/04/optional-in-swift/)  
- Pervasive use of Optional in Swift is penance for nil [:page_facing_up:](https://jeremywsherman.com/blog/2014/07/09/pervasive-use-of-optional-in-swift-is-penance-for-nil/)
- Optionals under the hood [:page_facing_up:](https://littlebitesofcocoa.com/173-swift-optionals-under-the-hood)
- Nil coalescing operator [:page_facing_up:](http://www.codingexplorer.com/nil-coalescing-swift/)
+ Understanding Optional Chaining [:page_facing_up:](http://nomothetis.svbtle.com/understanding-optional-chaining)

[:arrow_up:](#index)

#### **Problem Solving**
- Problems
    - Swift Rosetta Code [:link:](https://rosettacode.org/wiki/Category:Swift)
    - FizzBuzz on steroids with Swift [:floppy_disk:](https://speakerdeck.com/abizern/fizz-buzz-in-swift)
    - Learning Swift the Euler Way [:microphone:](https://vimeo.com/136059613)
    + Swift in Practice [:microphone:](https://developer.apple.com/videos/wwdc/2015/?id=411)
    + Make a DSL in Swift [:page_facing_up:](http://colindrake.me/2015/10/28/implementing-a-small-dsl-in-swift/) [:floppy_disk:](https://speakerdeck.com/kylef/dsls-in-swift) [:floppy_disk:](https://speakerdeck.com/luisobo/techniques-to-write-dsls-in-swift) [:microphone:](https://www.youtube.com/watch?v=a3rR5XVA22w)
    + Implementing goto in Swift [:page_facing_up:](https://harlanhaskins.com/2016/01/09/goto-in-swift.html)
    + Functional ASCII Art [:page_facing_up:](https://github.com/ijoshsmith/swift-ascii-art)
    + Writing 2048 in Swift [:page_facing_up:](https://realm.io/news/swift-2048/)
    - FlappySwift [:pencil2:](https://github.com/fullstackio/FlappySwift)
    - Parallel Mandelbrot Set in Swift [:page_facing_up:](http://blog.scottlogic.com/2014/10/29/concurrent-functional-swift.html)
    - Game of Life in Swift [:page_facing_up:](http://blog.scottlogic.com/2014/09/10/game-of-life-in-functional-swift.html)
- Interview Questions
    + Ray Wenderlich [:clipboard:](http://www.raywenderlich.com/110982/swift-interview-questions-answers)
    + Toptal [:clipboard:](http://www.toptal.com/swift/interview-questions)
    + LeetCode [:clipboard:](https://github.com/diwu/LeetCode-Solutions-in-Swift) [:link:](https://www.guiguan.net/swift/)
    + Coding Questions [:clipboard:](https://github.com/CameronBanga/iOS-Developer-and-Designer-Interview-Questions#code)
    + :fire: Awesome Swift Interview Questions [:clipboard:](https://github.com/MaximAbramchuck/awesome-interviews#swift)
    + :fire: Awesome iOS Interview Questions [:clipboard:](https://github.com/MaximAbramchuck/awesome-interviews#ios)
    - Swift Computer Science Problems [:pencil2:](https://github.com/Cananito/SwiftComputerScience)

[:arrow_up:](#index)

#### **Production**
- Dependency Managers
    - Carthage
        - How Carthage works [:floppy_disk:](https://speakerdeck.com/jspahrsummers/ruthlessly-simple-dependency-management-with-carthage) [:floppy_disk:]((https://speakerdeck.com/abizern/carthage))
    - Cocoapods
        - Make a Cocoapods Framework [:microphone:](https://realm.io/news/altconf-billy-tobon-brew-your-own-cocoa-framework/)
        - Swift, Frameworks & Modules, Learnings from CocoaPods [:page_facing_up:](https://speakerdeck.com/realm/swift-frameworks-and-modules-learnings-from-cocoapods)
    - SPM
        - Using the Swift Package Manager [:page_facing_up:](http://kostiakoval.github.io/posts/swift-package-manager) [:page_facing_up:](https://honzadvorsky.com/articles/2016-02-25-14-00-3_steps_to_marry_xcode_with_swift_package_manager/) [:page_facing_up:](http://cjwirth.com/2016/03/07/using-xcode-and-spm-together/)
        - IBM Swift Package Catalog [:link:](https://swiftpkgs.ng.bluemix.net/)
        - Exclude folders in the SPM [:page_facing_up:](http://kostiakoval.github.io/posts/exclude-folders-new-feature-in-swift-package-manager)
        - Swift, Frameworks & Modules, Learnings from CocoaPods [:page_facing_up:](https://speakerdeck.com/realm/swift-frameworks-and-modules-learnings-from-cocoapods)
        - Swift Package Manager [:floppy_disk:](https://speakerdeck.com/neonichu/swift-package-manager)
- Modules and frameworks
    - Modules and Precompiled Headers [:page_facing_up:](http://useyourloaf.com/blog/modules-and-precompiled-headers/)
    - Building a Swift Framework [:microphone:](https://realm.io/news/marius-rackwitz-challenges-building-swift-framework/)
- Docker
    - Deploy and run Swift Kitura Applications with Docker [:page_facing_up:](http://heidloff.net/article/swift-kitura-docker-bluemix)
    - Docker image that contains all dependencies for building and running the Kitura sample application [:pencil2:](https://github.com/IBM-Swift/kitura-ubuntu-docker)
    - Docker for iOS Development [:pencil2:](https://github.com/jkingyens/docker4xcode)
    - How I'm dockerizing Swift web apps [:page_facing_up:](https://blog.kida.io/dockerizing-swift-web-apps/)
    - Docker containers used for spinning up different Swift web frameworks [:page_facing_up:](https://github.com/joshdholtz/swift-webframeworks-docker)
    - Easy Server Side Swift with Docker [:page_facing_up:](https://medium.com/@LarsJK/easy-server-side-swift-with-docker-4c297feeeeb5#.p4xdbad2i)
    - Swift example to run on Kubernetes [:pencil2:](https://github.com/fabric8io/swift)
    - Run Linux Swift on your Mac or PC with Docker [:page_facing_up:](https://medium.com/@LarsJK/run-linux-swift-on-your-mac-or-pc-c2ea3ffba80b#.8wtaudarb)
- Other
    - Naming assets [:pencil:](https://github.com/dkhamsing/ios-asset-names)
    - Xcode Snippets [:pencil2:](https://github.com/burczyk/XcodeSwiftSnippets)
    - Bottom Up Programming in Swift [:microphone:](https://realm.io/news/altconf-airspeed-velocity-bottom-up-programming-in-swift/)
    - Lessons from Production Swift [:floppy_disk:](https://speakerdeck.com/ashfurrow/lessons-from-production-swift)
    - An Ansible playbook for Swift [:page_facing_up:](https://akrabat.com/an-ansible-playbook-for-swift/)
    - Ansible role to install Swift programming language in Ubuntu [:page_facing_up:](https://galaxy.ansible.com/alexcoppe/swift/)

[:arrow_up:](#index)

#### **Protocols**
- Swift Literal Convertibles [:page_facing_up:](http://nshipster.com/swift-literal-convertible/) [:page_facing_up:](http://en.swifter.tips/literal/) [:page_facing_up:](http://iosdevstuff.blogspot.com/2015/11/swift-literal-convertible-protocols.html) [:page_facing_up:](http://lithium3141.com/blog/2014/12/14/learning-swift-convertibles/)
- 55 Standard Library Swift Protocols [:floppy_disk:](https://speakerdeck.com/gregheo/what-i-learned-from-55-star-swift-standard-library-protocols) [:page_facing_up:](http://swiftunboxed.com/protocols/swift-standard-library-protocols-lessons/) [:microphone:](http://www.skilled.io/gregheo/what-the-55-swift-standard-library-protocols-taught-me)
+ Protocols in Swift [:page_facing_up:](http://austinzheng.com/2014/12/24/protocols-in-swift/)
- The Genius of Protocols [:page_facing_up:](https://www.wooji-juice.com/blog/swift-genius-of-protocols.html)
+ Swift Comparison Protocols [:page_facing_up:](http://nshipster.com/swift-comparison-protocols/)
- Protocols in Swift [:page_facing_up:](http://www.codingexplorer.com/protocols-swift/)
- Raw​Option​Set​Type [:page_facing_up:](http://nshipster.com/rawoptionsettype/)
+ Standard Template Protocols [:pencil2:](https://github.com/cconeil/Standard-Template-Protocols)
+ Properties of Types Conforming to Protocols [:page_facing_up:](http://ilya.puchka.me/properties-of-types-conforming-to-protocols-in-swift/)
+ Swift Default Protocol Implementations [:page_facing_up:](http://nshipster.com/swift-default-protocol-implementations/)
+ Optional Protocol Methods [:page_facing_up:](http://useyourloaf.com/blog/swift-optional-protocol-methods.html)
- Using the Hashable Protocol [:page_facing_up:](http://samuelmullen.com/2014/10/implementing_swifts_hashable_protocol/) [:page_facing_up:](http://stackoverflow.com/questions/31438210/how-to-implement-the-hashable-protocol-in-swift-for-an-int-array-a-custom-strin)
- Swift Protocol Naming Conventions [:page_facing_up:](http://programmers.stackexchange.com/questions/263521/swift-protocol-naming-conventions)
- A default CustomStringConvertible implementation for Swift types [:page_facing_up:](https://github.com/jessesquires/DefaultStringConvertible)
- A protocol that allows any class to be printed as if it were a struct [:page_facing_up:](https://github.com/mattcomi/ReflectedStringConvertible)

[:arrow_up:](#index)

#### **Protocol Oriented Programming**
+ :raised_hands: Protocol-Oriented Programming in Swift [:microphone:](https://developer.apple.com/videos/wwdc/2015/?id=408) [:floppy_disk:](http://devstreaming.apple.com/videos/wwdc/2015/408509vyudbqvts/408/408_protocoloriented_programming_in_swift.pdf?dl=1) [:pencil:](https://gist.github.com/rbobbins/de5c75cf709f0109ee95) [:page_facing_up:](https://medium.com/swift-programming/protocol-oriented-programming-a3e192f6e8f2#.b3vmjxbzy)
+ Beyond Crusty [:microphone:](http://www.thedotpost.com/2016/01/rob-napier-beyond-crusty-real-world-protocols) [:pencil:](https://gist.github.com/rnapier/e64e3938a787d789c2d4)
+ POP is OOP Thesis [:page_facing_up:](http://blog.metaobject.com/2015/06/protocol-oriented-programming-is-object.html)
+ Protocol Oriented MVVM [:page_facing_up:](http://natashatherobot.com/swift-2-0-protocol-oriented-mvvm/), [:floppy_disk:](http://www.slideshare.net/natashatherobot/protocoloriented-mvvm-extended-edition) [:microphone:](https://realm.io/news/doios-natasha-murashev-protocol-oriented-mvvm/)
+ Functional thinking via Protocol Extensions [:page_facing_up:](http://kelan.io/2015/approachable-functional-thinking-using-protocol-extensions/)
+ Protocol Extensions vs Type Extensions [:page_facing_up:](https://gist.github.com/hsavit1/3337f80d9fe1396c44ce)
+ What are the advantages? [:page_facing_up:](http://www.infoq.com/news/2015/06/protocol-oriented-swift)
+ Another look into the concept of P.O.P.  [:page_facing_up:](http://willowtreeapps.com/blog/protocol-oriented-programming/)
+ If you're subclassing, you're doing it wrong. POP and VOP explained [:page_facing_up:](http://krakendev.io/blog/subclassing-can-suck-and-heres-why)
+ Protocol Oriented Programming through UIKit [:page_facing_up:](http://www.captechconsulting.com/blogs/ios-9-tutorial-series-protocol-oriented-programming-with-uikit)
+ Protocols in Swift [:page_facing_up:](http://ashfurrow.com/blog/protocols-and-swift/)
+ Ray Wenderlich intro to POP [:page_facing_up:](http://www.raywenderlich.com/109156/introducing-protocol-oriented-programming-in-swift-2)
+ Protocol Extensions and the death of the Pipe forward operator [:page_facing_up:](http://airspeedvelocity.net/2015/06/23/protocol-extensions-and-the-death-of-the-pipe-forward-operator/)
+ How Protocol Oriented Programming could still improve [:page_facing_up:](https://bigonotetaking.wordpress.com/2015/07/17/swift-protocols-a-strategy/)
+ The Swift Protocol Proposal [:page_facing_up:](http://kickingbear.com/blog/archives/521)
+ :raised_hands: Mixins and Traits in Swift 2.0 [:page_facing_up:](http://matthijshollemans.com/2015/07/22/mixins-and-traits-in-swift-2/)
+ Minimal Swift 2.1 Protocol Coformance [:page_facing_up:](http://softwaredesign.jeffverkoeyen.com/minimal-swift-protocol-conformance/)
+ Favor Mixins over inheritance [:page_facing_up:](http://alisoftware.github.io/swift/protocol/2015/11/08/mixins-over-inheritance/)
- Stateful mixins in Swift [:page_facing_up:](http://cutting.io/posts/stateful-mixins-in-swift/)
+ Use Protocol Composition [:page_facing_up:](http://natashatherobot.com/swift-protocol-composition/)
- Current Recommended Protocol Usage [:page_facing_up:](http://owensd.io/2015/08/06/protocols.html)
- POP in Swift vs ObjC and C++ [:page_facing_up:](http://owensd.io/2015/06/16/protocol-oriented-programming.html)
- POP Utility Belt [:pencil2:](https://github.com/tptee/Oriole)
- Typesafe and Composable Data Sources in Swift [:page_facing_up:](http://www.jessesquires.com/building-data-sources-in-swift/)
- Protocol Extension Method Dispatch [:page_facing_up:](https://medium.com/ios-os-x-development/swift-protocol-extension-method-dispatch-6a6bf270ba94#.xsrtw75qp)
- Weird things you can do with protocol extension [:page_facing_up:](http://cjwirth.com/2016/01/20/swift-protocol-extension-weirdness/) [:page_facing_up:](http://allblue.me/swift/2016/01/24/two-weird-things-about-extension-subclass-in-swift/)
- Improved Protocol-Oriented Programming with Untyped Type Aliases [:page_facing_up:](https://medium.com/capital-one-developers/improved-protocol-oriented-programming-with-untyped-type-aliases-part-1-625484ca1f9d#.g0i8pfjvj) [:page_facing_up:](https://medium.com/@michikono/3f0e2eadee73#.dvk6ubezg)
- Protocol-Oriented Problems and the Immutable 'self' Error [:page_facing_up:](https://www.bignerdranch.com/blog/protocol-oriented-problems-and-the-immutable-self-error/)
- Multiple Inheritance vs. Traits or Protocol Extensions [:page_facing_up:](https://www.dzombak.com/blog/2015/06/Multiple-Inheritance-vs--Traits-or-Protocol-Extensions.html)
- Protocol Oriented Networking [:page_facing_up:](http://khanlou.com/2016/05/protocol-oriented-programming/) [:page_facing_up:](https://www.natashatherobot.com/protocol-oriented-networking-in-swift/) [:floppy_disk:](https://speakerdeck.com/ishkawa/protocol-oriented-programming-in-networking)
- Protocol-Oriented Views in Swift [:page_facing_up:](https://www.natashatherobot.com/protocol-oriented-views-in-swift/)

[:arrow_up:](#index)

#### **REPL**
- Introduction to the Swift REPL [:page_facing_up:](https://developer.apple.com/swift/blog/?id=18)
- Swift REPL Docker Image [:link:](https://hub.docker.com/r/jlehikoinen/swift-repl/)

#### **Security**
- Cryptography with Swift [:microphone:](https://realm.io/news/swift-summit-marcin-krzyzanowski-cryptoswift-cryptography/) [:pencil2:](https://github.com/krzyzanowskim/CryptoSwift)
- Encryptor / Decryptor Data Format [:pencil2:](https://github.com/RNCryptor/RNCryptor)
- CommonCrypto in Swift [:microphone:](https://realm.io/news/danny-keogan-swift-cryptography/)
- Ceaser Cipher in Swift [:page_facing_up:](https://www.objc.io/blog/2015/01/26/functional-snippet-17-caesar-ciphers/) [:page_facing_up:](http://ijoshsmith.com/2015/04/14/caesar-cipher-in-swift/)
- Swift-ly secure [:microphone:](https://realm.io/news/seth-law-swift-security/)
- Common Crypto [:page_facing_up:](http://sketchytech.blogspot.com/2016/02/resurrecting-commoncrypto-in-swift-for.html) [:pencil2:](https://github.com/iosdevzone/IDZSwiftCommonCrypto)
- Reverse Engineering iOS Apps [:microphone:](https://realm.io/news/conrad-kramer-reverse-engineering-ios-apps-lyft/)
- Security and Your Apps [:microphone:](https://developer.apple.com/videos/play/wwdc2015/706/)
- Make iOS apps more secure with SSL pinning [:page_facing_up:](https://infinum.co/the-capsized-eight/articles/how-to-make-your-ios-apps-more-secure-with-ssl-pinning)
- Security Framework Wrapper [:pencil2:](https://github.com/henrinormak/Heimdall)
- SwCrypt [:pencil2:](https://github.com/soyersoyer/SwCrypt)

[:arrow_up:](#index)

#### **Server Side Swift**
- Hello Server Side Swift [:page_facing_up:](https://medium.com/@LogMaestro/server-side-swift-c965b7ebe6e7#.vitoriti4)
- The case for bringing Swift to the server [:page_facing_up:](https://qconlondon.com/system/files/presentation-slides/patrickbohrerchrisbailey.pdf)
- IBM's Swift on the Server [:microphone:](http://www.infoq.com/articles/Ibm-swift)
- Vapor Swift Web Framework [:pencil2:](https://github.com/tannernelson/vapor)
- Kitura Web Framework and HTTP Server [:page_facing_up:](https://developer.ibm.com/swift/2016/02/22/building-end-end-cloud-apps-using-swift-kitura/) [:pencil2:](https://github.com/IBM-Swift/Kitura) [:pencil2:](https://github.com/IBM-Swift/Kitura-BluePic)
- Swift Redis [:pencil2:](https://github.com/swizzlr/swift-redis)
- Swift Sockets: TCP, UDP; Client, Server [:pencil2:](https://github.com/czechboy0/Socks) [:page_facing_up:](http://dev.iachieved.it/iachievedit/tcp-sockets-with-swift-on-linux/)
- Zevo Server Side Swift Community [:link:](https://github.com/Zewo)
- Swift HTTP Servers [:page_facing_up:](https://izeeshan.wordpress.com/2014/08/25/local-http-server-for-ios/) [:pencil2:](https://github.com/crossroadlabs/Express) [:pencil2:](https://github.com/paulofaria/SwiftHTTPServer) [:pencil2:](https://github.com/kylef/Curassow) [:pencil2:](https://github.com/glock45/swifter) [:pencil2:](https://github.com/elliottminns/blackfish) [:pencil2:](https://github.com/Zewo/Epoch) [:pencil2:](https://github.com/LoganWright/swift-server-io)
- Swift on Rails [:pencil2:](https://github.com/necolt/Swifton)
- Swift Website Example [:pencil2:](https://github.com/kylef/Curassow-example-helloworld)
- Write Web Server in Swift [:pencil2:](https://github.com/tryswift/trySwiftServer/blob/master/Slides/Deckset/Soaring%20Swiftly.md)
- Swift and Perfect Server on Linux with Vagrant [:pencil2:](https://github.com/mpclarkson/perfect-swift-linux)
- Caramel brings powerful, expressive I/O to Server Side Swift [:microphone:](https://realm.io/news/steve-streza-caramel-for-swift/)

[:arrow_up:](#index)

#### **Strings and Regular Expressions**
+ Strings
    + Swift String Cheat Sheet [:page_facing_up:](http://useyourloaf.com/blog/swift-string-cheat-sheet.html) [:pencil:](https://gist.github.com/kharrison/08d1db4169d70a88b194)
    + How is the String type implemented? [:page_facing_up:](https://www.quora.com/Apple-Swift-programming-language/How-is-the-String-type-implemented)
    + Useful String Library [:pencil2:](https://github.com/erica/SwiftString)
    - Symbology in Swift [:page_facing_up:](http://ericasadun.com/2016/01/13/a-few-thoughts-on-swift-symbologygist/)
    - Functional String Ranges [:page_facing_up:](https://www.natashatherobot.com/swift-string-ranges-the-functional/)
    - ICU Text Transforms in Cocoa [:page_facing_up:](http://oleb.net/blog/2016/01/icu-text-transforms/)
    - Swift Substrings [:page_facing_up:](http://vluxe.io/swift-sub-strings.html)
    - DSL for Attributed Strings [:pencil2:](https://github.com/delba/TextAttributes)
+ Lexing and Parsing
    - Abstract Syntax Tree [:page_facing_up:](http://ankit.im/swift/2016/02/29/swift-abstract-syntax-tree/)
    + Creating a Lexer in Swift [:page_facing_up:](http://blog.matthewcheok.com/writing-a-lexer-in-swift/)
    + Creating an Abstract Syntax Tree Parser in Swift [:page_facing_up:](http://blog.matthewcheok.com/writing-a-parser-in-swift/) [:page_facing_up:](http://blog.matthewcheok.com/writing-a-parser-in-swift-part-2/)
    + String to Number Parser [:pencil2:](https://github.com/davedelong/DDMathParser)
    + Madness: Parsing strings in simple context-free grammars [:pencil2:](https://github.com/robrix/Madness)
    - Swift version of the Coco/R Compiler Generator [:pencil2:](https://github.com/mgriebling/Coco)
    - CSV Parser [:page_facing_up:](https://github.com/Daniel1of1/CSwiftV)
+ Regular Expressions
    + RegularExpressions in Swift [:page_facing_up:](https://littlebitesofcocoa.com/121-swiftier-regular-expressions-with-regex) [:page_facing_up:](http://en.swifter.tips/regex/) [:page_facing_up:](http://benscheirman.com/2014/06/regex-in-swift/)
    + NSRegularExpression Cheat Sheet [:page_facing_up:](http://www.raywenderlich.com/86205/nsregularexpression-swift-tutorial)
    + Clean Regular Expressions in Swift [:page_facing_up:](http://nomothetis.svbtle.com/clean-regular-expressions-using-conversions)
    + Simple Regex [:pencil:](https://gist.github.com/mattt/3f12f56d72b8d2ebbe62)
    + Verbal Expressions style RegEx [:pencil2:](https://github.com/VerbalExpressions/SwiftVerbalExpressions)

[:arrow_up:](#index)

#### **Testing**
- Unit Testing
    - Testing in Xcode 6 [:microphone:](https://developer.apple.com/videos/play/wwdc2014/414/)
    - Better Unit Testing with Swift [:page_facing_up:](http://masilotti.com/better-swift-unit-testing/)
    - Unit Testing in Swift [:page_facing_up:](https://bendyworks.com/unit-testing-in-swift/) [:page_facing_up:](http://nshipster.com/xctestcase/)
    - The Philosophy [:page_facing_up:](https://medium.com/cobe-mobile/unit-testing-in-swift-part-1-the-philosophy-9bc85ed5001b#.dl2rnvpkt)
    - Unit Testing with @testable in Xcode 7 [:page_facing_up:](http://natashatherobot.com/swift-2-xcode-7-unit-testing-access/) [:page_facing_up:](http://mr-v.github.io/xcode-7-swift-2-unit-testing-setup)
    - Understanding testability in Swift 2 [:page_facing_up:](http://www.captechconsulting.com/blogs/ios-9-tutorial-series-testability-by-example-making-unit-testing-easier-in-swift-20-and-xcode-7)
    - The good parts of XCTest [:page_facing_up:](http://modocache.io/xctest-the-good-parts)
    - QuickCheck made in Swift [:page_facing_up:](http://chris.eidhof.nl/posts/quickcheck-in-swift.html)
    - Test callbacks with XCTests [:page_facing_up:](http://www.mokacoding.com/blog/testing-callbacks-in-swift-with-xctest/)
    - What's the difference between unit, functional, acceptance, and integration tests? [:link:](http://stackoverflow.com/questions/4904096/whats-the-difference-between-unit-functional-acceptance-and-integration-test)
    - Testing with Swift – Approaches & Useful Libraries [:page_facing_up:](https://spin.atomicobject.com/2016/05/02/testing-swift-code/#.VydVY-RcsWY.hackernews)
- Mocking
    - Real world mocking in Swift [:microphone:](https://realm.io/news/tryswift-veronica-ray-real-world-mocking-swift/)
- Stubbing
    - Stub driven mobile app development [:page_facing_up:](https://medium.com/cobe-mobile/stub-driven-mobile-app-development-8dea10459621#.svhif3269)
- TDD
    - TDD with Swift [:page_facing_up:](http://swiftandpainless.com/category/tdd/)
    - TDD By Controlling Dependencies in Swift [:microphone:](https://www.youtube.com/watch?v=qYpURmZcCKs&index=47&list=PLEx5khR4g7PL0fDNJkI2dHhqeckQTAbes), [:microphone:](http://gotocon.com/dl/goto-cph-2015/slides/JorgeD.OrtizFuentes_TestDrivenDevelopmentbyControllingDependencies.pdf)
    - TDD on iOS [:microphone:](https://realm.io/news/altconf-glen-tregoning-paul-zabelin-successful-test-driven-development-on-ios/)
    - How to TDD in Swift [:page_facing_up:](http://roadfiresoftware.com/2015/09/how-you-can-do-tdd-with-swift/) [:page_facing_up:](http://qualitycoding.org/files/BowlingGame-Swift.pdf)
    - TDD Swift Playground [:page_facing_up:](http://initwithstyle.net/2015/11/tdd-in-swift-playgrounds/)
    - Swift version of Graham Lee's "Test-Driven iOS Development" [:pencil2:](https://github.com/SixFiveSoftware/BrowseOverflowSwift)
- BDD
    - BDD Testing with Swift [:page_facing_up:](http://railsware.com/blog/2014/07/04/bdd-style-testing-in-swift-with-sleipnir/)
    - SwiftTest BDD Testing Framework [:pencil2:](https://github.com/bppr/Swiftest)
    - Intro to Quick and Nimble [:page_facing_up:](http://theiostimes.com/advent-calendar/quick-nimble.html)
    - Testing in Swift with Quick [:microphone:](https://realm.io/news/testing-in-swift/) [:microphone:](https://realm.io/news/rachel-bobbins-testing-view-controllers-quick/)
    - Quick Testing Framework [:pencil2:](https://github.com/Quick/Quick) [:page_facing_up:](http://blog.benjamin-encz.de/how-i-write-swift-specs-with-quick/)
    - Nimble Matcher Framework [:pencil2:](https://github.com/Quick/Nimble)
- UI Testing
    - UI Testing Cheat Sheet [:page_facing_up:](http://masilotti.com/ui-testing-cheat-sheet/) [:page_facing_up:](http://www.runtimecrash.com/tag/xcuielementquery/)
    + UI Testing in Xcode [:microphone:](https://developer.apple.com/videos/wwdc/2015/?id=406) [:page_facing_up:](http://www.runtimecrash.com/tag/xcuielementquery/) [:page_facing_up:](http://www.mokacoding.com/blog/xcode-7-ui-testing/) [:page_facing_up:](https://www.bignerdranch.com/blog/ui-testing-in-xcode-7-part-1-ui-testing-gotchas/) [:page_facing_up:](http://masilotti.com/ui-testing-xcode-7/) [:pencil:](https://gist.github.com/rbobbins/f8f23916c741379bbd66)
    - Replacing KIF with XCUI Tests [:page_facing_up:](http://www.catehuston.com/blog/2015/11/11/replacing-kif-tests-with-xcui-tests/)
    - Three Ways UI Testing Just Made TDD Better [:page_facing_up:](http://masilotti.com/ui-testing-tdd/)
    - Unit and UI tests with code coverage [:page_facing_up:](https://speakerdeck.com/ugocastro/unit-and-ui-tests-with-code-coverage-on-xcode-7-using-swift-2)
    - UI or Unit tests? [:page_facing_up:](http://christiantietze.de/posts/2016/02/unit-or-integrated-tests/)
- Network Testing
    - Network Testing in Swift and DVR [:microphone:](https://realm.io/news/soffes-swift-network-testing-dvr/) [:page_facing_up:](https://blog.soff.es/network-testing-in-swift-with-dvr)
    - Unit Testing Core Data Model Layers [:page_facing_up:](http://www.andrewcbancroft.com/2015/01/13/unit-testing-model-layer-core-data-swift/)
    - Mocking Objects in Swift [:page_facing_up:](http://www.raywenderlich.com/101306/unit-testing-tutorial-mocking-objects)
- Snapshot Testing
    - iOS Snapshot Test Cases [:pencil2:](https://github.com/facebook/ios-snapshot-test-case)
- Profiling
    - Profiling in Depth [:microphone:](https://developer.apple.com/videos/play/wwdc2015-412) [:floppy_disk:](http://devstreaming.apple.com/videos/wwdc/2015/412rhea5amj6iaf/412/412_profiling_in_depth.pdf?dl=1)
    - WWDC 2014: Improving you app with instruments [:microphone:](https://developer.apple.com/videos/play/wwdc2014-418/) [:floppy_disk:](http://devstreaming.apple.com/videos/wwdc/2014/418xxtihju1a7v4/418/418_improving_your_app_with_instruments.pdf)
    - Finding memory leaks with instruments [:page_facing_up:](http://spin.atomicobject.com/2016/01/25/ios-memory-leak-xcode/#.VqaGcF_w1AE.hackernews)
    - Automatic memory leak detection on iOS [:page_facing_up:](https://code.facebook.com/posts/583946315094347/automatic-memory-leak-detection-on-ios/)
    - What every iOS Developer should be doing with Instruments [:page_facing_up:](https://medium.com/@kazmiekr/what-every-ios-developer-should-be-doing-with-instruments-d1661eeaf64f#.961cmlvx3)
    - Xcode Instruments Documentation [:link:](https://developer.apple.com/library/prerelease/ios/documentation/DeveloperTools/Conceptual/InstrumentsUserGuide/index.html#//apple_ref/doc/uid/TP40004652-CH3-SW1)
    - Instruments Tutorial [:page_facing_up:](https://www.raywenderlich.com/97886/instruments-tutorial-with-swift-getting-started)
- Functional Testing
    - SwiftCheck: QuickCheck for Swift [:pencil2:](https://github.com/typelift/SwiftCheck)
    - More functional testing [:page_facing_up:](http://www.thinkandbuild.it/ios-functional-testing-with-user-stories-uitest-and-local-server/)
- iOS Testing
    - The state of iOS testing in 2015 [:page_facing_up:](http://www.mokacoding.com/blog/ios-testing-in-2015/)
    - Framerate testing [:pencil2:](https://github.com/tapwork/WatchdogInspector)
    - Setting up KIF for iOS Acceptance Testing [:page_facing_up:](http://www.mokacoding.com/blog/setting-up-kif-for-ios-acceptance-testing/)
    - How to configure Travis CI for iOS Testing [:page_facing_up:](http://www.mokacoding.com/blog/travis-ci-ios-testing/)
    - Heap Inspector [:pencil2:](https://github.com/tapwork/HeapInspector-for-iOS)
    - Using Xcode's Schemes to run a subset of your tests [:page_facing_up:](http://artsy.github.io/blog/2016/04/06/Testing-Schemes/)
- Code Coverage
    - Xcode code coverage [:page_facing_up:](http://useyourloaf.com/blog/xcode-code-coverage/)
- Code Injection
    - Code injection for Xcode [:page_facing_up:](http://artsy.github.io/blog/2016/03/05/iOS-Code-Injection/)
    - Code Injection Vulnerabilities [:link:](http://stackoverflow.com/questions/28548248/is-swift-vulnerable-to-code-injection/28549095#28549095)

[:arrow_up:](#index)

#### **Tools**
- Analyzers
    - Use the static analyzer sith Swift [:page_facing_up:](http://stackoverflow.com/questions/29326036/is-it-not-possible-to-use-analyze-with-swift)
    - Can you use Clang static analyzer with Swift [:page_facing_up:](http://stackoverflow.com/questions/30712090/can-clang-static-analyzer-be-used-with-swift)
- Benchmarking
    - Practicing Swift Benchmarks [:pencil2:](https://github.com/vsco/swift-benchmarks)
- Continuous Integration
    - Using Xcode Bots [:page_facing_up:](http://mjtsai.com/blog/2016/02/11/using-xcode-bots/)
    - Continuous Integration for Xcode 6 [:microphone:](https://developer.apple.com/videos/play/wwdc2014/415/)
    - Continuous Integration With Xcode Server [:page_facing_up:](http://useyourloaf.com/blog/continuous-integration-with-xcode-server/)
    - BuddyBuild Continuous Integration [:link:](http://buddybuild.com/)
    - Xcode CI, the missing manual [:page_facing_up:](http://faq.sealedabstract.com/xcodeCI/)
    - Self-hosted CI [:page_facing_up:](https://medium.com/@hello_paja/self-hosted-ci-for-ios-mac-development-f273606ca767#.jd7up9ujd)
    - Build a Swift Pipeline with Jenkins Workflow [:page_facing_up:](https://dzone.com/articles/build-a-swift-pipeline-with-jenkins-workflow) [:page_facing_up:](http://mmorejon.github.io/en/blog/continuous-integration-jenkins-ios9-xcode/)
    - Continuous Integrations for iOS Apps [:video_camera:](https://vimeo.com/158290425)
- Code Coverage
    - Swift Code Coverage [:pencil2:](https://github.com/realm/SwiftCov)
    - Continuous Integration and Code Coverage In Xcode [:pencil:](https://gist.github.com/rbobbins/92e2fd3736f842d4ccee)
    - Code Coverage Xcode 7 [:page_facing_up:](http://mgrebenets.github.io/mobile%20ci/2015/09/21/code-coverage-for-ios-xcode-7)
    - Slather Code Coverage [:pencil2:](https://github.com/SlatherOrg/slather)
- Debugging Tools
    - Profiling Swift Tool [:page_facing_up:](http://irace.me/swift-profiling)
    - Profiler formatter xcpretty [:pencil2:](https://github.com/larslockefeer/xcpretty-profiler-formatter)
    - Atom Swift Debugger [:pencil2:](https://github.com/aciidb0mb3r/atom-swift-debugger)
    - Debugger Optimizers [:page_facing_up:](http://indiestack.com/2016/05/a-tale-of-two-optimizers/)
    - Cocoalumberjack [:pencil2:](https://github.com/CocoaLumberjack/CocoaLumberjack)
- Delivery Tools
    - Continuous Delivery with Fastlane [:microphone:](https://vimeo.com/146505670)
    - Using Fastlane [:page_facing_up:](https://github.com/jacobvanorder/FastlaneCocoaConf2016/blob/master/Speeding_Up_Your_iOS_Development_With_Fastlane.pdf)
    - Ship C code with Swift packages using Swift package manager [:page_facing_up:](http://ankit.im/swift/2015/12/27/ship-c-code-with-swift-packages-using-swift-package-manager/)
    - Codeship iOS [:pencil2:](https://github.com/beanieboi/codeship-ios)
- Development Tools
    - Jazzy Docs [:page_facing_up:](https://github.com/realm/jazzy) [:floppy_disk:](https://speakerdeck.com/jpsim/overview-of-jazzy-soulful-docs-for-swift)
- Docker Tools
    - How to run Swift within a Docker container [:page_facing_up:](https://developer.ibm.com/swift/2015/12/15/running-swift-within-docker/)
    - Docker Swift [:pencil2:](https://github.com/swiftdocker/docker-swift)
- Server Tools
    - Heroku Buildpack for Swift [:pencil2:](https://github.com/kylef/heroku-buildpack-swift)
- Swift Tools
    - Exploring Graph Theory with OmniGraffle and Swift [:page_facing_up:](http://www.mattrajca.com/2015/05/22/exploring-graph-theory-with-omnigraffle-and-swift.html)
    - Swift Environment [:pencil2:](https://github.com/kylef/swiftenv)
- Xcode Tools
    - Alcatraz Master Repository [:pencil2:](https://github.com/alcatraz/Alcatraz)
    - Cocoa Layout Instrument [:page_facing_up:](https://www.bignerdranch.com/blog/inpecting-auto-layout-with-the-cocoa-layout-instrument/)
    - IBAnimatable [:pencil2:](https://github.com/JakeLin/IBAnimatable)
    - Draw in Interface Builder [:pencil2:](https://github.com/ipraba/EPShapes)
    - VVDocumenter [:pencil2:](https://github.com/onevcat/VVDocumenter-Xcode)
    - Analytics workflow in Swift [:pencil2:](https://github.com/brianmichel/Swift-Analysis-Workflow)
    - Anarchy Swift Build Tools [:pencil2:](https://github.com/AnarchyTools)
    - Refractor Swift Code with Refractorer [:pencil2:](https://github.com/johnno1962/Refactorator)
    - xcbuild Build Tool [:pencil2:](https://github.com/facebook/xcbuild)
    - Speeding Up Slow Swift Build Times [:page_facing_up:](https://medium.com/swift-programming/speeding-up-slow-swift-build-times-922feeba5780#.96anpx7tq)
    - SwiftCompilationPerformanceReporter [:pencil2:](https://github.com/tumblr/SwiftCompilationPerformanceReporter)

[:arrow_up:](#index)

#### **Types**
- Category and Type Theory
    - Key terms in Category Theory [:page_facing_up:](https://www.quora.com/What-are-the-key-terms-of-category-theory)
    - Category Theory for Programmers [:book:](http://bartoszmilewski.com/2014/10/28/category-theory-for-programmers-the-preface/)
    + Cheat Sheet For Typeclasses and Monads in Haskell [:scroll:](https://github.com/rudymatela/ultimate-cheat-sheets/releases/download/haskell-tc-v0.2/haskell-tc-ucs-0.2.pdf) [:scroll:](http://fundeps.com/tables/FromSemigroupToMonads.pdf) [:page_facing_up:](https://wiki.haskell.org/Typeclassopedia)
    + Category Theory For Beginners [:floppy_disk:](http://www.slideshare.net/kenbot/your-data-structures-are-made-of-maths?related=1) [:floppy_disk:](http://www.slideshare.net/kenbot/category-theory-for-beginners)
    + Category Theory and Programming [:microphone:](http://yogsototh.github.io/Category-Theory-Presentation/categories.html)
    + Awesome Math/Category Theory [:pencil:](https://github.com/rossant/awesome-math#category-theory)
    + Category Theory in Haskell [:page_facing_up:](https://en.wikibooks.org/wiki/Haskell/Category_theory)
    + The Category Design Pattern [:page_facing_up:](http://www.haskellforall.com/2012/08/the-category-design-pattern.html)
    + Type Theory vs Category Theory [:page_facing_up:](https://ncatlab.org/nlab/show/relation+between+type+theory+and+category+theory)  [:page_facing_up:](http://cs.stackexchange.com/questions/3028/is-category-theory-useful-for-learning-functional-programming/3256#3256)
    + MIT Category Theory Class [:link:](http://ocw.mit.edu/courses/mathematics/18-s996-category-theory-for-scientists-spring-2013/)
    - Functional Programming, Abstraction, and Naming Things [:page_facing_up:](http://www.stephendiehl.com/posts/abstraction.html)
    - Monads defined [:link:](http://stackoverflow.com/questions/3870088/a-monad-is-just-a-monoid-in-the-category-of-endofunctors-whats-the-problem?rq=1)
    - Fantasy Land Specification [:pencil2:](https://github.com/fantasyland/fantasy-land)
    - List of Functional Programming Topics [:link:](https://en.wikipedia.org/wiki/List_of_functional_programming_topics)
    - Using types to keep yourself honest [:page_facing_up:](http://matthijshollemans.com/2016/03/25/using-types-to-keep-yourself-honest/)
+ Reference Types (Classes)
    + Class or Struct? [:page_facing_up:](http://faq.sealedabstract.com/structs_or_classes/) [:page_facing_up:](http://owensd.io/2015/07/05/re-struct-or-class.html) [:page_facing_up:](https://www.mikeash.com/pyblog/friday-qa-2015-07-17-when-to-use-swift-structs-and-classes.html)
    + let vs var [:page_facing_up:](http://stackoverflow.com/questions/24002092/what-is-the-difference-between-let-and-var-in-swift)
    - Weak, Strong, Unowned [:floppy_disk:](https://speakerdeck.com/realm/weak-strong-unowned-hector-matos)
    - Is Swift Pass By Value or Pass By Reference [:link:](http://stackoverflow.com/questions/27364117/is-swift-pass-by-value-or-pass-by-reference/27366050#27366050)
    - How can I make a weak protocol reference in 'pure' Swift (w/o @objc) [:link:](http://stackoverflow.com/questions/24066304/how-can-i-make-a-weak-protocol-reference-in-pure-swift-w-o-objc)
    - When to use weak pointers with delgates [:link:](http://stackoverflow.com/questions/30056526/swift-delegation-when-to-use-weak-pointer-on-delegate)
    - Instance methods and type methods in Swift [:page_facing_up:](http://www.codingexplorer.com/instance-methods-and-type-methods-in-swift/)
+ Value Types (Structs)
    + Every Swift Value Type Should be Equatable [:microphone:](https://developer.apple.com/videos/wwdc/2015/?id=414) [:page_facing_up:](https://www.andrewcbancroft.com/2015/07/01/every-swift-value-type-should-be-equatable/)
    + Structs are 900x faster than classes [:link:](http://stackoverflow.com/questions/24232799/why-choose-struct-over-class/24243626#24243626)
    - How can I make a container with copy-on-write semantics? [:page_facing_up:](http://stackoverflow.com/questions/32984258/how-can-i-make-a-container-with-copy-on-write-semantics-swift)
    - When to use mutating functions in swift structs [:page_facing_up:](https://www.natashatherobot.com/when-to-use-mutating-functions-in-swift-structs/)
    - Mutating Funcs in Swift Structs [:page_facing_up:](http://natashatherobot.com/mutating-functions-swift-structs/)
    - Making Friends with Value Types [:microphone:](https://realm.io/news/andy-matuschak-controlling-complexity/)
    + Safer Swift Code With Value Types [:microphone:](https://realm.io/news/altconf-benjamin-encz-safer-swift-code-with-value-types/) [:page_facing_up:](https://gist.github.com/rbobbins/596bb6896141dca5934d)
    - Swift copy-on-write behavior for a struct using HeapBuffer [:pencil:](https://gist.github.com/airspeedswift/71f15d1eb866be9e5ac7)
    - Swift pass struct by reference? [:page_facing_up:](http://stackoverflow.com/questions/31495431/swift-pass-struct-by-reference)
    - Value Types [:page_facing_up:](http://cjwirth.com/2016/02/09/value-types/)
    - Fully Value-Typed Arrays in Swift [:page_facing_up:](http://natecook.com/blog/2014/07/fully-value-typed-arrays-in-swift/)
    + Structs as Data Models [:page_facing_up:](https://medium.com/swift-programming/swift-caveats-for-structs-as-data-models-8299d84b49dc#.rf1agoadg)
    - Swift and mutating struct [:link:](http://stackoverflow.com/questions/24035648/swift-and-mutating-struct)
+ Algebraic Types
    + Sum Types
        + See [Enums](#enums-and-pattern-matching)
    + Product Types
        - Tuples [:page_facing_up:](https://medium.com/swift-programming/swift-tuple-328aecff50e7#.apsfyt2ky)
+ Compose Types
    + Composing Types [:pencil:](https://gist.github.com/Ben-G/aa080de6d61f46bdc842)
    - Named Types and Compound Types [:page_facing_up:](https://www.andrewcbancroft.com/2016/03/18/swift-functions-as-types/)
+ Abstract Types
    - Understanding Swift’s Abstract Types (Swift 2.2 & above) [:page_facing_up:](http://blog.davidungar.net/2016/02/29/understanding-swifts-abstract-types-swift-2-2-above/)
    - Understanding Abstract Types [:page_facing_up:](http://blog.davidungar.net/2016/01/10/understanding-swifts-abstract-types-2#fn6)
+ Wrapper Types
    + Wrapper Types [:page_facing_up:](https://www.objc.io/blog/2014/11/24/functional-snippet-8-wrapper-types/)
    + Type-Erased Wrappers in Swift [:microphone:](https://realm.io/news/type-erased-wrappers-in-swift/)
+ Phantom Types
    - What are Phantom Types good for? [:page_facing_up:](https://angelovillegas.com/swift-phantom-types/)
    + Phantom Types in Swift [:page_facing_up:](https://www.objc.io/blog/2014/12/29/functional-snippet-13-phantom-types/) [:microphone:](https://realm.io/news/swift-summit-johannes-weiss-leveraging-the-type-system/)
    - Money with Phantom Types [:page_facing_up:](https://www.natashatherobot.com/swift-money-phantom-types/#) [:pencil:](https://gist.github.com/oisdk/569de8286f9f706749b7d0668836706a)
+ Dependent Types
    + Dependent Types in Swift [:page_facing_up:](https://sectionfive.net/blog/2015/08/11/building-almost-dependent-types-in-swift/) and why they matter [:page_facing_up:](https://jeremywsherman.com/blog/2015/08/26/read-why-dependent-types-matter/)
    + Can Swift have Dependent Types? [:pencil:](https://github.com/oisdk/ConstArray/blob/master/Playground.playground/Contents.swift) [:page_facing_up:](https://github.com/oisdk/PretendDependSwift)
    + More Misunderstanding of Dependent Types [:page_facing_up:](https://bigonotetaking.wordpress.com/2015/09/06/yet-more-misunderstanding-of-dependent-types/)
    - An implementation of a dependently-typed intermediate language [:pencil2:](https://github.com/antitypical/Manifold) [:pencil2:](https://github.com/oisdk/PretendDependSwift)
    - Dependent Types: I'm missing something [:page_facing_up:](http://owensd.io/blog/dependent-types-im-missing-something/)
    - Backwards Dependent Types [:page_facing_up:](https://jeremywsherman.com/blog/2015/10/02/what-if-you-get-your-dependent-type-backwards/)
    - Type-Level Assertions (or, almost-dependent types) [:pencil:](https://gist.github.com/JadenGeller/f39130616846f9bf9879)
    - Validated: A Swift μ-Library for Somewhat Dependent Types [:page_facing_up:](http://blog.benjamin-encz.de/validated-a-swift-m-library-for-somewhat-dependent-types/)
+ Dynamic Types
    - DynamicType and MultiMethods [:page_facing_up:](http://en.swifter.tips/multi-method/)
    - DynamicTypes and Metatypes [:page_facing_up:](https://medium.com/@NSomar/types-and-meta-types-in-swift-9cd59ba92295#.ucwjngqy5)
+ Nested Types
    - Lazy Nested Types [:page_facing_up:](https://littlebitesofcocoa.com/)
    - Using a nested type in Swift [:page_facing_up:](http://www.codingexplorer.com/using-nested-type-swift/)
+ Type Reflection and Casting
    + Simple Reflection in Swift [:page_facing_up:](http://freecake.angelodipaolo.org/simple-reflection-in-swift/)
    + Understanding Reflection in Swift and how to use it [:page_facing_up:](http://appventure.me/2015/10/24/swift-reflection-api-what-you-can-do/) [:page_facing_up:](http://stackoverflow.com/questions/24060667/does-swift-support-reflection)
    - Basic Reflection in Swift [:pencil:](https://gist.github.com/mchambers/fb9da554898dae3e54f2)
    - Swift class introspection & generics [:page_facing_up:](http://stackoverflow.com/questions/24049673/swift-class-introspection-generics?lq=1)
    + Typecasting and the Swift Runtime [:page_facing_up:](https://github.com/vandadnp/swift-weekly/blob/master/issue08/README.md)
    - Advanced Type Safety in Swift [:floppy_disk:](https://github.com/jspahrsummers/correct-behavior-through-type-safety/blob/master/Correct%20Behavior%20Through%20Type%20Safety.pdf), and corresponding [:microphone:](https://realm.io/news/altconf-justin-spahr-summers-type-safety/)
    + Why doesn't Swift have implicit type conversion? [:page_facing_up:](https://www.quora.com/Why-does-Swift-not-allow-implicit-type-conversion)
    + as? vs as! [:page_facing_up:](http://stackoverflow.com/questions/25708649/downcasting-optionals-in-swift-as-type-or-as-type)  
    + Understanding Downcasting Operators in Swift [:page_facing_up:](http://stackoverflow.com/questions/25708649/downcasting-optionals-in-swift-as-type-or-as-type)
    - Type check with switch statements [:page_facing_up:](http://www.tekramer.com/using-switch-statements-for-type-checking-in-swift/)
+ Associated Types
    + Protocols with Associated Types and how they got that way [:floppy_disk:](https://speakerdeck.com/algal/protocols-with-associated-types-and-how-they-got-that-way) [:microphone:](https://www.youtube.com/watch?v=XWoNjiSPqI8)
    + Associated Types in Swift Explained [:page_facing_up:](http://www.russbishop.net/swift-associated-types) [:page_facing_up:](http://www.natashatherobot.com/swift-protocols-with-associated-types/)
    + Illuminating Forum Post [:page_facing_up:](https://forums.developer.apple.com/message/18038)
    + How to make Generic Protocols in Swift [:page_facing_up:](http://milen.me/writings/swift-generic-protocols/)
    + Associated Enum Data As Types [:page_facing_up:](http://owensd.io/2015/09/15/associated-enum-cases-as-types.html)
    + Typesafe Associated Objects [:pencil2:](https://github.com/kballard/swift-tsao)
    - Associated Types Considered Weird [:page_facing_up:](https://schani.wordpress.com/2014/06/11/associated-types-considered-weird/)
    - Swift Associated Types, cont [:page_facing_up:](http://www.russbishop.net/swift-associated-types-cont)
+ Type Aliases
    - Generic Typealiases [:page_facing_up:](http://ericasadun.com/2016/03/08/generic-typealiases-are-a-thing/)
+ Metatypes
    + Types and Metatypes in Swift [:page_facing_up:](https://medium.com/@NSomar/types-and-meta-types-in-swift-9cd59ba92295#.1o9z1ikpc)
    + Higher Kinded Types [:pencil:](https://gist.github.com/adamkuipers/bb7bdb9cc425de8905c7) [:page_facing_up:](https://lists.swift.org/pipermail/swift-evolution/Week-of-Mon-20151214/003122.html) [:page_facing_up:](https://www.quora.com/What-language-features-can-make-Swift-even-better) [:link:](https://github.com/typelift/swift/issues/1)
    + Swift MetaTypes [:page_facing_up:](http://jasdev.me/lets-get-meta)
    + Typeclasses in Swift and Scala [:page_facing_up:](http://brainyandbrawny.com/article/Typeclass_in_Swift_and_Scala)
    + Creating new Types in Swift [:page_facing_up:](https://developer.apple.com/swift/blog/?id=8)
    - What is ExistentialMetatype in Swift [:page_facing_up:](http://stackoverflow.com/questions/25342832/what-is-existentialmetatype-in-swift)
+ MirrorTypes
  - Using a Mirror Struct to get an object's type [:link:](http://stackoverflow.com/a/33001534/2855836)
+ Typeclasses
    + Typeclasses in Swift, Haskell and Scala [:page_facing_up:](http://siejkowski.net/typeclasses-in-swift/)
+ Type Inference
    - Implicit Member Expression [:page_facing_up:](http://ericasadun.com/2015/04/21/swift-occams-code-razor/)
    - Referential Transparency [:link:](https://www.reddit.com/r/swift/comments/2ffk7z/what_is_swift_imperative_functional/)
+ Type Variance
    - Type Variance in Swift [:page_facing_up:](http://nomothetis.svbtle.com/type-variance-in-swift)
+ Type Erasures
    - Type Erasures [:microphone:](https://realm.io/news/tryswift-gwendolyn-weston-type-erasure/)
+ Other
    + Swift's Type System [:page_facing_up:](http://oleb.net/blog/2015/07/swift-type-system/)
    + The Natural Numbers Encoded as Types [:page_facing_up:](https://forums.developer.apple.com/thread/19942)
    + Return Type Polymorphism in Swift [:page_facing_up:](http://www.figure.ink/blog/2015/1/25/polymorphism-with-return-types) [:link:](https://news.ycombinator.com/item?id=8826422)

[:arrow_up:](#index)

#### **Weird Swift**
- Pointers
    - Dereference an UnsafeMutablePointer [:page_facing_up:](http://useyourloaf.com/blog/how-to-dereference-an-unsafe-mutable-pointer-in-swift/)
    - UnsafePointer [:page_facing_up:](http://en.swifter.tips/unsafe/)
    - UnsafeMutablePointer [:page_facing_up:](http://sketchytech.blogspot.com/2014/10/becoming-less-afraid-of-unsafe-mutable.html)
    - COPaquePointer and CFunctionPointer [:page_facing_up:](http://en.swifter.tips/opaque-function-pointer/)
    - How to Dereference an Unsafe Mutable Pointer in Swift [:page_facing_up:](http://useyourloaf.com/blog/how-to-dereference-an-unsafe-mutable-pointer-in-swift/)
    - Pointers, Pointer Arithmetic, and Raw Data in Swift [:page_facing_up:](http://stackoverflow.com/questions/24067085/pointers-pointer-arithmetic-and-raw-data-in-swift)
    - If a function returns an UnsafeMutablePointer is it our responsibility to destroy and dealloc? [:link:](http://stackoverflow.com/questions/25605658/if-a-function-returns-an-unsafemutablepointer-is-it-our-responsibility-to-destro)
- Advanced
    - WWDC 2014: Advanced Swift [:microphone:](https://developer.apple.com/videos/play/wwdc2014-404/) [:floppy_disk:](http://devstreaming.apple.com/videos/wwdc/2014/404xxdxsstkaqjb/404/404_advanced_swift.pdf)
    + Other Swift Attributes you may not have heard of [:page_facing_up:](http://www.russbishop.net/more-swift-attributes)
    - Hipster Swift [:page_facing_up:](http://krakendev.io/blog/hipster-swift) [:microphone:](https://realm.io/news/tryswift-hector-matos-hipster-swift/)
    - Namespaces in Swift [:page_facing_up:](http://andybargh.com/2016/01/21/lifetime-scope-and-namespaces-in-swift/) [:page_facing_up:](http://andybargh.com/lifetime-scope-and-namespaces-in-swift/) [:page_facing_up:](http://stackoverflow.com/questions/24002821/how-to-use-namespaces-in-swift/24012981)
    - Swift Enums as namespace [:page_facing_up:](https://medium.com/swift-programming/swift-enums-as-namespace-7df63a17f36f#.u656hot7j)
    - Swift Method Dispatching [:page_facing_up:](http://allegro.tech/2014/12/swift-method-dispatching.html)
    - Global variables in Swift are not variables [:page_facing_up:](http://railsware.com/blog/2014/06/11/global-variables-in-swift-are-not-variables/)
    - @convention(c) [:page_facing_up:](http://stackoverflow.com/questions/30740560/new-conventionc-in-swift-2-how-can-i-use-it)
    - Infix [:page_facing_up:](https://swifting.io/blog/2016/02/03/3-infix-operator/)
    - CVArgType [:page_facing_up:](http://stackoverflow.com/questions/28639154/what-are-the-difference-and-use-cases-for-va-list-cvalistpointer-anyobject)
    - Hidden Gems in Swift [:microphone:](https://netguru.co/blog/hidden-gems-swift)
    - A Look At Swift's Elusive ~> Operator [:page_facing_up:](http://natecook.com/blog/2014/11/swifts-elusive-tilde-gt-operator/)
    - ObjectiveCBridgeable [:page_facing_up:](http://www.russbishop.net/bridges-of-siracusa-county)

[:arrow_up:](#index)

## **iOS Programming with Swift**

#### **Application Structure / Architecture**
- Extinct
    - Dropped Patterns [:page_facing_up:](http://artsy.github.io/blog/2015/09/01/Cocoa-Architecture-Dropped-Design-Patterns/)
- Elm Like Architecture
    - Elmification of Swift [:page_facing_up:](https://medium.com/design-x-code/elmification-of-swift-af14b7f92b30#.k1njpy7sn)
    - Simple model for elm-like composable programs [:pencil2:](https://github.com/davidcairns/AppComponents)
    - Swift Elm [:pencil2:](https://github.com/momentumworks/swift-elm)
- Functional
    + Functional View Controllers [:page_facing_up:](http://chris.eidhof.nl/posts/functional-view-controllers.html) [:pencil:](https://gist.github.com/chriseidhof/244f1a9c8a39a4c809f9)
- Massive View Controllers
    - Refractor the Mega Controller [:microphone:](https://realm.io/news/andy-matuschak-refactor-mega-controller/)
    - Preventing Massive View Controllers [:microphone:](https://www.youtube.com/watch?v=dgOdsh1Bq10&feature=youtu.be&list=PLy2fR8K1ngurocVMEL0qHn0ik2MDYewLJ)
    - Destroying Massive View Controllers [:page_facing_up:](http://khanlou.com/2015/12/massive-view-controller/) with patterns [:page_facing_up:](https://medium.com/ios-os-x-development/humble-object-pattern-in-swift-de5efe8fe05a#.iyh62t857)
    - Lighter View Controllers in Swift [:page_facing_up:](https://www.codefellows.org/blog/tech-tip-clean-up-your-code-with-lighter-view-controllers-in-swift) [:pencil:](https://gist.github.com/lostincode/38e6b0a612a3b33f6f7b)
    - View Controller Thinning [:page_facing_up:](http://puchka.me/view-controller-thinning/) via Dependency Injection [:page_facing_up:](http://puchka.me/view-controller-thinning-dependency-injection/)
    - Consistent, Thin, & Dumb: Redesigning the Spotify iOS App [:microphone:](https://realm.io/news/mbltdev-hector-zarate-consistent-thin-dumb-spotify/)
    - 3 Strategies for Skinny VCs [:page_facing_up:](http://bartjacobs.com/three-strategies-to-keep-view-controllers-skinny/)
    - Clean Swift iOS Architecture for Fixing Massive View Controller [:pencil2:](http://clean-swift.com/clean-swift-ios-architecture/)  [:pencil2:](https://github.com/Clean-Swift)
- Model Layer and Caching
    - How to cache view controllers in iOS [:page_facing_up:](https://medium.com/@gitter/how-to-cache-view-controllers-in-ios-854be6734062#.lownd94t5)
    - Awesome Cache [:pencil2:](https://github.com/aschuch/AwesomeCache)
    - SwiftyDB [:pencil2:](https://github.com/Oyvindkg/swiftydb)
    - A Structy Model Layer [:page_facing_up:](http://khanlou.com/2015/12/a-structy-model-layer/)
    - Cache [:pencil2:](https://github.com/hyperoslo/Cache)
- Model View Whatever
    - iOS Architecture Patterns [:page_facing_up:](https://medium.com/the-traveled-ios-developers-guide/architecture-patterns-in-ios-part-1-8d4ad146c266#.wexkb2ofi) [:page_facing_up:](https://medium.com/the-traveled-ios-developers-guide/architecture-patterns-in-ios-part-2-fac1180e0251#.f0ckrnpxp) [:page_facing_up:](https://medium.com/the-traveled-ios-developers-guide/architecture-patterns-in-ios-part-3-231f82cbb781#.kbuhsnk3t)
    - Clean Architecture in Swift [:pencil2:](https://github.com/marcinkuptel/clean-architecture)
    - Demystifying iOS Architecture Patterns [:page_facing_up:](https://medium.com/ios-os-x-development/ios-architecture-patterns-ecba4c38de52#.5zn7t5oh2)
    + MVVM in Swift [:page_facing_up:](http://artsy.github.io/blog/2015/09/24/mvvm-in-swift/) [:page_facing_up:](http://khanlou.com/2015/12/mvvm-is-not-very-good/) [:page_facing_up:](https://ashfurrow.com/blog/mvvm-is-exceptionally-ok/) [:page_facing_up:](http://gilesvangruisen.com/mvvm-swift/) [:page_facing_up:](https://medium.com/faber-dev/mvvm-benchmark-in-an-mvc-world-part-1-dab952617395#.nhandvll2) [:page_facing_up:](https://github.com/ivanbruel/MVVM-Benchmark)
    - MVVM-C [:floppy_disk:](https://speakerdeck.com/macdevnet/mvvm-c-in-practice) [:pencil2:](https://github.com/macdevnet/mvvmc-demo)
    - Stateful View Controller [:pencil2:](https://github.com/aschuch/StatefulViewController)
    - An MVP Framework [:pencil2:](https://github.com/Karumi/BothamUI)
    - Designing App Infrastructure [:page_facing_up:](https://medium.com/@gitdoapp/gitdo-designing-the-app-infrastructure-3b7710c0fd81#.mf5kc58vj)
    - Model-View-Binding in Swift [:page_facing_up:](http://blog.asynchrony.com/2016/02/model-view-binding-swift/)
    - Service Oriented Archiecture in Swift with MVVM [:microphone:](https://realm.io/news/modular-ios-apps/)
    - Pitfalls of MVVM [:page_facing_up:](http://bartjacobs.com/what-is-wrong-with-model-view-controller/)
    - Bindings, Generics, Swift and MVVM [:page_facing_up:](http://rasic.info/bindings-generics-swift-and-mvvm/)
    - Cloud based View Models [:pencil2:](https://github.com/hyperoslo/Spots#origin-story) [:page_facing_up:](https://medium.com/@zenangst/hitting-the-sweet-spot-of-inspiration-637d387bc629#.tkm4b9s6p)
    - React-Like Views [:pencil2:](https://github.com/sahandnayebaziz/StateView)
- Viper
    - Using VIPER Architecture with Swift [:microphone:](https://realm.io/news/altconf-brice-pollock-250-days-shipping-with-swift-and-viper/) [:page_facing_up:](https://swifting.io/blog/2016/03/07/8-viper-to-be-or-not-to-be/)
    - Safer with VIPER [:page_facing_up:](https://medium.com/ios-os-x-development/safer-uiviewcontroller-creation-when-using-storyboards-1915ac2b2c80#.bynj7y4gd)
- Unidirectional Data Flow
    - Ziggurat iOS App Architecture [:page_facing_up:](https://corner.squareup.com/2015/12/ziggurat-ios-app-architecture.html)
    - One Way Data Flow Architecture in Swift [:microphone:](https://www.youtube.com/watch?v=4cP1p5VOrSI)
    - Unidirectional Dataflow Architecture with Swift-Flow [:microphone:](https://realm.io/news/benji-encz-unidirectional-data-flow-swift/) [:pencil2:](https://github.com/Swift-Flow/Swift-Flow) [:floppy_disk:](https://speakerdeck.com/benjamin_encz/unidirectional-data-flow-in-swift)
    - ReSwift Unidirectional Data Flow [:pencil2:](https://github.com/ReSwift) [:page_facing_up:](http://christiantietze.de/posts/2016/01/reswift-level-indirection/)
    - CocoaFlow Architecture [:page_facing_up:](http://www.skilled.io/paulyoung/cocoaflow)
    - Improve your iOS Architecture with FlowControllers [:page_facing_up:](http://merowing.info/2016/01/improve-your-ios-architecture-with-flowcontrollers/)
    - Explaining Flux data flow in Swift [:pencil:](https://gist.github.com/rjchatfield/d78cca1bf7b02323bad9)
    - ReduxKit is a predictable state container for Swift apps [:page_facing_up:](https://github.com/ReduxKit/ReduxKit) [:pencil:](https://gist.github.com/rjchatfield/27e3d8ef2249a4298046#file-statereduce-swift) [:pencil2:](https://github.com/ReduxKit)
    + Uber Jetstream [:pencil2:](https://github.com/uber/jetstream-ios)
    - Building a Unidirectional Data Flow app with Realm [:page_facing_up:](https://realm.io/news/unidirectional-data-flow-in-swift/)
    + Swift Flow + RxSwift [:pencil:](https://gist.github.com/Ben-G/c33486169d68a6f3d12f)
- State Machines
    - State Machines in Swift [:pencil2:](https://github.com/ReactKit/SwiftState) [:floppy_disk:](https://github.com/tangphillip/state-machine-talk) [:pencil:](https://gist.github.com/monyschuk/e2c5609599195a30cc66)
    - How to build a FSM with Swift [:page_facing_up:](http://everythingel.se/blog/how-to-build-a-finite-state-machine-with-swift/) [:page_facing_up:](http://everythingel.se/blog/how-to-build-a-finite-state-machine-fsm-with-swift-pt-2/)
    - Transporter is a modern finite-state machine implemented in pure Swift [:pencil2:](https://github.com/DenHeadless/Transporter)
    - FSMs in Swift and the State Pattern [:page_facing_up:](http://ctarda.com/2015/06/introducing-turnstile-finite-state-machines-in-swift/) [:pencil2:](https://github.com/ctarda/Turnstile) [:pencil2:](https://github.com/cipriancaba/SwiftFSM)
    - Generic State Machine in Swift [:page_facing_up:](http://curtclifton.net/generic-state-machine-in-swift)
    - Building Swift State Machine Series [:page_facing_up:](http://www.figure.ink/blog/2015/1/31/swift-state-machines-part-1) [:page_facing_up:](http://www.figure.ink/blog/2015/2/1/swift-state-machines-part-2) [:page_facing_up:](http://www.figure.ink/blog/2015/2/8/swift-state-machines-part-3-follow-up) [:page_facing_up:](http://www.figure.ink/blog/2015/2/9/swift-state-machines-part-4-redirect) [:pencil:](https://gist.github.com/jemmons/f30f1de292751da0f1b7)
    - Swift implementation of Robert C. Martin's turnstile state-machine example [:pencil:](https://gist.github.com/kristopherjohnson/4bcb89e07a5ece10e305)
    - Simple State Machine in Swift [:pencil2:](https://github.com/egeniq/EFStateMachine)

[:arrow_up:](#index)

#### **Core Data and Realm**
- Core Data
    - Official Apple Guide [:link:](https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/CoreData/index.html#//apple_ref/doc/uid/TP40001075-CH2-SW1)
    - What's New in Core Data [:microphone:](https://developer.apple.com/videos/play/wwdc2015-220) [:floppy_disk:](http://devstreaming.apple.com/videos/wwdc/2015/220lgx5lvphj2/220/220_whats_new_in_core_data.pdf?dl=1)
    - Pragmatic Core Data [:microphone:](https://vimeo.com/146505672)
    - Getting Started with Core Data [:page_facing_up:](http://www.raywenderlich.com/115695/getting-started-with-core-data-tutorial) [:pencil2:](https://github.com/iascchen/SwiftCoreDataSimpleDemo) [:microphone:](https://realm.io/news/jesse-squires-core-data-swift/)
    - Core Competencies [:page_facing_up:](https://developer.apple.com/library/ios/documentation/DataManagement/Devpedia-CoreData/coreDataStack.html#//apple_ref/doc/uid/TP40010398-CH25-SW1)
    + A Swift Into To Core Data [:page_facing_up:](https://github.com/andyshep/CoreDataPlayground)
    + Moving from ObjC to Swift with Core Data [:page_facing_up:](http://martiancraft.com/blog/2015/07/objective-c-swift-core-data/)
    + What, if any, ACID gurantees does Core Data Make? [:page_facing_up:](http://stackoverflow.com/questions/6634731/what-if-any-acid-guarantees-can-core-data-provide-on-ios)
    + Core Data Libraries and NSKeyedArchiver [:page_facing_up:](http://nshipster.com/core-data-libraries-and-utilities/)
    - Ditching Core Data for Something else [:page_facing_up:](https://medium.com/the-way-north/ditching-core-data-865c1bb5564c#.24t5a9t8t)
    - Comparing Core Data Stacks [:page_facing_up:](http://floriankugler.com/2013/04/29/concurrent-core-data-stack-performance-shootout/)
    - Better Core Data Models with Swift [:page_facing_up:](http://www.jessesquires.com/better-coredata-models-in-swift/)
    - Core Data Threading Demystified [:microphone:](https://realm.io/news/marcus-zarra-core-data-threading/)
    - My Core Data Stack [:page_facing_up:](http://martiancraft.com/blog/2015/03/core-data-stack/) [:pencil:](https://gist.github.com/Ben-G/54f363482303b984574b)
    - Core Data Tutorial Series [:link:](http://code.tutsplus.com/series/core-data-and-swift)
    - Core Data Fundamentals: Exploring the Core Data Stack [:page_facing_up:](http://bartjacobs.com/core-data-fundamentals-core-data-stack/)
    - Pragmatic Core Data [:microphone:](https://realm.io/news/cocoaheads-florian-kugler-pragmatic-core-data/)
    - Core Data Migrations Tutorial [:page_facing_up:](http://www.raywenderlich.com/114084/core-data-migrations-tutorial-lightweight-migrations) [:page_facing_up:](https://izeeshan.wordpress.com/2014/11/10/core-data-migration/)
    - Multiple Managed Object Contexts [:page_facing_up:](http://www.raywenderlich.com/113489/core-data-tutorial-multiple-managed-object-contexts)
    - Getting Started with Moya [:page_facing_up:](http://marginalfutility.net/2015/10/04/moya/)
- Realm
    - Super simple Realm Intro [:page_facing_up:](https://littlebitesofcocoa.com/49-realm-basics) [:floppy_disk:](https://speakerdeck.com/jpsim/realm-in-swift) [:page_facing_up:](http://theiostimes.com/advent-calendar/realm.html)
    - A look into Realm's Core DB Engine [:microphone:](https://realm.io/news/jp-simard-realm-core-database-engine/)
    - Designing a Database: Realm Threading Deep Dive [:page_facing_up:](https://realm.io/news/threading-deep-dive/)
    - Why Realm over Core Data? [:page_facing_up:](https://www.quora.com/Why-would-you-use-Realm-over-Core-Data) [:floppy_disk:](https://speakerdeck.com/realm/why-realm) [:page_facing_up:](http://cjwirth.com/2015/05/13/why-realm/) [:page_facing_up:](http://szulctomasz.com/ios-realm-instead-of-coredata/)
    - Official Realm Introduction [:page_facing_up:](https://realm.io/news/introducing-realm/)
    - Realm Tutorial [:page_facing_up:](http://www.raywenderlich.com/81615/introduction-to-realm)
    - Realm Best Practices [:page_facing_up:](http://stackoverflow.com/questions/31590717/proper-realm-usage-patterns-best-practices)
    - Realm Repo [:page_facing_up:](https://github.com/realm/realm-cocoa)
    - Reddit Thread [:page_facing_up:](https://www.reddit.com/r/iOSProgramming/comments/2vmbv2/realm_or_coredata/)
    - Working with Realm [:page_facing_up:](http://blog.matthewcheok.com/working-with-realm/)
    - Testing Realm Apps [:page_facing_up:](http://www.mokacoding.com/blog/testing-realm-apps/)
    - Looking at Realm's Core DB Engine [:floppy_disk:](https://speakerdeck.com/jpsim/a-look-into-realms-core-db-engine)
    - Realm Incremental Store [:pencil2:](https://github.com/eure/RealmIncrementalStore)
    - Migrations in Realm [:page_facing_up:](http://stackoverflow.com/questions/30384884/adding-and-removing-realm-object-during-a-migration)
    - Migrating an app from Core Data to Realm [:page_facing_up:](https://realm.io/news/migrating-from-core-data-to-realm/)
    - Realm + Alamofire + VIPER [:page_facing_up:](https://blog.hyphe.me/realm-and-alamofire-in-a-effective-harmony/)
    - How Realm kills C++ STL Binary Search [:page_facing_up:](https://realm.io/news/how-we-beat-cpp-stl-binary-search/)
    - App state with Realm and RxSwift [:page_facing_up:](http://rx-marin.com/post/rxswift-realm-reactive-app-settings/)
    - Migrating to Realm on iOS [:microphone:](https://realm.io/news/alex-leffelman-migrating-to-realm-ios/)
    - RxRealm [:microphone:](https://realm.io/news/marin-todorov-realm-rxswift/)

[:arrow_up:](#index)

#### **Core Image**
- Core Image [:books:](https://itunes.apple.com/us/book/core-image-for-swift/id1073029980)
- GPU Image Library in Swift [:pencil2:](https://github.com/BradLarson/GPUImage2)
- Introducing GPUImage 2, redesigned in Swift [:page_facing_up:](http://sunsetlakesoftware.com/2016/04/16/introducing-gpuimage-2-redesigned-swift)

[:arrow_up:](#index)

#### **iOS**
- All of the Apple Device Frameworks [:link:](https://developer.apple.com/library/ios/documentation/Miscellaneous/Conceptual/iPhoneOSTechOverview/iPhoneOSFrameworks/iPhoneOSFrameworks.html)
- Apple Example Code [:link:](https://developer.apple.com/library/ios/navigation/#section=Topics&topic=Swift)
- iOS 9 Programming Fundamentals with Swift [:link:](http://www.apeth.com/swiftBook/index.html)

[:arrow_up:](#index)

#### **JSON**
- Functional Parsing
    - Functional JSON Parsing [:page_facing_up:](http://owensd.io/2014/08/06/functional-json.html) [:pencil:](https://gist.github.com/chriseidhof/48243eb549481bc38d58)
    - Functional JSON Parsing with Tyro [:pencil2:](https://github.com/typelift/Tyro)
    + Efficient JSON Parsing with Functional Concepts [:page_facing_up:](https://robots.thoughtbot.com/efficient-json-in-swift-with-functional-concepts-and-generics)
- { JSON, Swift, and Type Safety } [:floppy_disk:](https://speakerdeck.com/swiftsummit/anthony-levings-json-swift-and-type-safety-its-a-wrap)
- JSON in Swift [:page_facing_up:](http://blog.matthewcheok.com/json-and-swift/)
+ Swift and JSON: Are we doing it right? [:microphone:](https://skillsmatter.com/skillscasts/6202-swift-and-json-are-we-doing-it-right)
+ Calling APIs and Parsing JSON with Swift [:page_facing_up:](https://www.topcoder.com/blog/calling-apis-parsing-json-with-swift/) [:page_facing_up:](http://www.raywenderlich.com/82706/working-with-json-in-swift-tutorial)
+ Parsing Embedded JSON and Arrays in Swift [:page_facing_up:](https://robots.thoughtbot.com/parsing-embedded-json-and-arrays-in-swift)
+ Real World JSON Parsing [:page_facing_up:](https://robots.thoughtbot.com/real-world-json-parsing-with-swift)
- Operator Overloading and JSON Parsing in Swift [:page_facing_up:](https://realm.io/news/swift-thinking/)
- Swift JSON [:pencil2:](https://github.com/dankogai/swift-json)
- Beyond JSON in Swift [:microphone:](http://www.thedotpost.com/2016/01/maxim-zaks-beyond-json)
- Generate JSON from Swift Structs [:page_facing_up:](http://tomlokhorst.tumblr.com/post/119966903324/json-swift-with-code-generation)
- Flat Buffers (an efficient cross platform serialization library) in Swift [:pencil2:](https://github.com/mzaks/FlatBuffersSwift) [:floppy_disk:](http://www.slideshare.net/maximzaks/beyond-json-mobilewarsaw)
- Unpacking JSON with Swift [:video_camera:](https://vimeo.com/165920052)

[:arrow_up:](#index)

#### **Persistence**
- NSCoding and UserDefaults [:page_facing_up:](http://stackoverflow.com/questions/26469457/saving-custom-swift-class-with-nscoding-to-userdefaults)
- NSCoding And Swift Structs [:page_facing_up:](http://swiftandpainless.com/nscoding-and-swift-structs/)
- NSCoder and NSKeyedArchiver [:page_facing_up:](http://mhorga.org/2015/08/31/ios-persistence-with-core-data.html)
- NSCoder initialization [:page_facing_up:](http://napora.org/nscoder-and-swift-initialization/)
- Simple persistent storage [:page_facing_up:](http://stackoverflow.com/questions/26233067/simple-persistent-storage-in-swift/26233274#26233274)
- How to cache data using NSCache [:page_facing_up:](https://www.hackingwithswift.com/example-code/system/how-to-cache-data-using-nscache) [:page_facing_up:](http://nshipster.com/nscache/)
- Access SQLite DB in Swift [:link:](http://stackoverflow.com/questions/24102775/accessing-an-sqlite-database-in-swift)
- Simple Object Persistence [:pencil2:](https://github.com/mattcomi/PersistentObject)

[:arrow_up:](#index)

#### **UI**
- Animations
    - AdaptiveUI Animations [:microphone:](https://realm.io/news/gotocph-sam-davies-adaptive-ui-ios/)
    - Animating VCs [:page_facing_up:](http://www.raywenderlich.com/110536/custom-uiviewcontroller-transitions)
    - Transition Treasury Lib [:pencil2:](http://transitiontreasury.com/)
    - Animations with CAReplicationLayer [:page_facing_up:](http://www.ios-animations-by-emails.com/posts/2015-march)
    - Building a hamburger button transition [:page_facing_up:](http://robb.is/working-on/a-hamburger-button-transition/)
    - Advanced Graphics and Animations for iOS Apps [:page_facing_up:](https://developer.apple.com/videos/play/enterprise-419/)
- Autolayout
    - iOS Animations with AutoLayout [:microphone:](https://realm.io/news/gotocph-marin-todorov-auto-layout-animations-ios/) and [:pencil2:](https://github.com/sammyd/AdaptiveUI-GOTOConf) [:page_facing_up:](https://littlebitesofcocoa.com/9-animating-constraints)
    - Cartography Autolayout DSL [:pencil2:](https://github.com/robb/Cartography)
    - How to configure a UIScrollView with Auto Layout in Interface Builder [:page_facing_up:](http://mokagio.github.io/tech-journal/2015/06/24/ios-scroll-view-and-interface-builder.html)
- CollectionViews
    - What's new in Table and Collection Views [:microphone:](https://developer.apple.com/videos/play/enterprise-226/)
    - Advanced Collection Views [:microphone:](http://devstreaming.apple.com/videos/wwdc/2014/232xxz8gxpbstio/232/232_advanced_user_interfaces_with_collection_views.pdf)
- Core Animation
    - Advanced Graphics with Core Animation [:microphone:](https://realm.io/news/tryswift-tim-oliver-advanced-graphics-with-core-animation/)
- Core Graphics
    - Core Graphics Tutorial [:page_facing_up:](http://www.raywenderlich.com/90690/modern-core-graphics-with-swift-part-1)
- Core Image
    - Core Image Blog [:notebook:](http://flexmonkey.blogspot.com/)
- Presenting
    - Swifty View Controller Presenters [:microphone:](https://realm.io/news/slug-jesse-squires-swifty-view-controller-presenters/)
- TableViews
    - Table View Controllers in Swift [:microphone:](https://realm.io/news/tryswift-chris-eidhof-table-view-controllers-swift/)
    - Advanced UITableViews [:microphone:](https://realm.io/news/altconf-mason-glidden-advanced-uitableviews-for-fun-and-profit/) [:page_facing_up:](http://www.martinrichter.net/blog/2015/12/30/animating-table-row-changes-using-changesets-with-mvvm/)
    - UITableView Configuration Values [:page_facing_up:](https://www.objc.io/blog/2015/02/16/functional-snippet-20-configuration-values/)
    - Typed TableViewControllers [:page_facing_up:](https://www.objc.io/blog/2015/02/23/functional-snippet-21-typed-table-view-controllers/) [:page_facing_up:](https://www.objc.io/blog/2015/03/02/functional-snippet-22-typed-table-view-controllers-redux/) [:pencil:](https://gist.github.com/chriseidhof/892c1a574d1f3975c697) [:page_facing_up:](http://holko.pl/2016/01/05/typed-table-view-controller/)
    - Using Generators for UITableView Pagination Purposes [:page_facing_up:](http://blog.krzyzanowskim.com/2015/06/26/paging/)
    - Upgrade your TableViews with Loading State in Swift [:page_facing_up:](https://medium.com/swift-programming/upgrade-your-tableviews-with-loading-state-in-swift-1fdce34ada77#.bg6wbtkzc)
- SpriteKit and Metal
    + Mixing SpriteKit with UIKit in iOS 9 [:page_facing_up:](https://littlebitesofcocoa.com/8-mixing-spritekit-into-uikit)
    - SpriteKit as an intro to SceneKit [:floppy_disk:](https://speakerdeck.com/bklnswift/joseph-mcmahon-spritekit-as-an-intro-to-scenekit-and-metal)
    - Metal and Swift [:microphone:](https://realm.io/news/swift-summit-simon-gladman-metal/)
    - Why use SpriteKit? [:page_facing_up:](https://www.quora.com/Which-tools-are-you-using-with-SpriteKit)
    - 3D Graphics with Metal in Swift [:microphone:](https://realm.io/news/3d-graphics-metal-swift/)
- UIKit
    - UIKit for the Mac, rewritten in Swift [:pencil2:](https://github.com/unifiedh/Chameleon-Swift)
    - Did Apple implement UIKit and Cocoa classes "Obj-C on Swift" [:page_facing_up:](https://www.quora.com/Did-Apple-implement-UIKit-and-Cocoa-classes-Obj-C-on-Swift-or-Swift-on-Obj-C-or-did-they-write-the-whole-thing-twice?srid=xrLC&share=59c4c728)
    - Cocoa Touch Best Practices [:pencil:](https://gist.github.com/rbobbins/236b2160ab9621f3f8e7)
    - How Do You Do UIView<SomeProtocol> in Swift? [:page_facing_up:](http://nearthespeedoflight.com/article/2016_02_18_how_do_you_do_uiview_someprotocol__in_swift_)

[:arrow_up:](#index)

#### **Web Services, Routing, and Networking**
+ Networking
    - AlamoFire Tutorial [:page_facing_up:](http://www.raywenderlich.com/121540/alamofire-tutorial-getting-started)
    + SwiftHTTPStatusCodes [:pencil:](https://github.com/rhodgkins/SwiftHTTPStatusCodes)
    + Calling a REST Api in Swift [:page_facing_up:](http://stackoverflow.com/questions/24321165/make-rest-api-call-in-swift)
    + How to Make REST API Calls and Parse JSON with Swift [:page_facing_up:](http://devdactic.com/rest-api-parse-json-swift/)  [:page_facing_up:](http://stackoverflow.com/questions/24162051/best-architectural-approaches-for-building-ios-networking-applications-rest-cli)
    + HTTP in Swift [:page_facing_up:](https://medium.com/swift-programming/http-in-swift-693b3a7bf086) [:link:](http://stackoverflow.com/questions/24016142/how-to-make-an-http-request-in-swift)
    + Reachability Library [:page_facing_up:](https://github.com/ashleymills/Reachability.swift)
    - NSURLSession Basics [:page_facing_up:](https://littlebitesofcocoa.com/78-nsurlsession-basics) [:page_facing_up:](http://www.splinter.com.au/2015/06/12/swift-nsurlsession-wrapper/) [:page_facing_up:](http://www.raywenderlich.com/110458/nsurlsession-tutorial-getting-started)
    - Background Downloads [:page_facing_up:](https://littlebitesofcocoa.com/77-background-downloads)
    - Background Transfer Services [:microphone:](https://realm.io/news/gwendolyn-weston-ios-background-networking/)
    - An introduction to using Alamofire [:page_facing_up:](http://nshipster.com/alamofire/)
    - Moya: Network Abstraction Layer written in Swift [:pencil2:](https://github.com/Moya/Moya)
    - Network data as a Struct [:page_facing_up:](http://chris.eidhof.nl/posts/struct-semantics-in-swift.html)
    - Your app and next generation networks [:microphone:](https://developer.apple.com/videos/play/wwdc2015/719/)
    - Tiny Networking [:microphone:](http://www.thedotpost.com/2016/01/chris-eidhof-tiny-networking-in-swift)
+ Routing
    - Understanding Routing with Swift [:page_facing_up:](https://karlbowden.com/featherweight-router-tldr/)
    - An AlamoFire Router [:page_facing_up:](https://littlebitesofcocoa.com/93-creating-a-router-for-alamofire) [:page_facing_up:](https://grokswift.com/router/)
    - Write Your Own API Clients [:page_facing_up:](https://thatthinginswift.com/write-your-own-api-clients-swift/)
+ Web Services
    + CloudKit Introduction [:page_facing_up:](http://szulctomasz.com/2015/10/27/cloudkit-introduction-and-lets-build-an-app.html)
    + Create a Data Access Layer with SQLite.swift and Swift 2 [:page_facing_up:](http://masteringswift.blogspot.com/2015/09/create-data-access-layer-with.html)
    + Using YapDatabase [:page_facing_up:](https://github.com/yapstudios/YapDatabase)
    - MagicalRecord loves Swift [:microphone:](http://gotocon.com/dl/goto-cph-2015/slides/SaulMora_CoreDataIn2015andMagicalRecordMeetsSwift.pdf)
    - Swift-MongoDB [:pencil2:](https://github.com/Danappelxx/SwiftMongoDB)

[:arrow_up:](#index)

## **Mac Programming with Swift**

## **WatchOS Programming with Swift**
- IBM Wearables SDK [:pencil2:](https://github.com/ibm-wearables-sdk-for-mobile/ibm-wearables-swift-sdk)

## **tvOS Programming With Swift**
- Creating a Client Server tvOS app [:link:](https://developer.apple.com/library/tvos/documentation/General/Conceptual/AppleTV_PG/YourFirstAppleTVApp.html)

[:arrow_up:](#index)
