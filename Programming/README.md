# Articles
In no particular order

[Avoid rewriting a legacy system from scratch, by strangling it](https://understandlegacycode.com/blog/avoid-rewriting-a-legacy-system-from-scratch-by-strangling-it/)<br/>
The best way to deal with legacy code IMO.

[3 tribes of programming](https://josephg.com/blog/3-tribes/)<br/>
This explains to me why so many programmers have different priorities in their work.
There are 3 types of programmers
- Ones that make useful tools from programs (code is useful)
- Ones who treat programs as art (code is beautiful)
- And those who care about the hardware underneath (code is fast)

[Bimodal programming – why design patterns fail](https://blog.cerebralab.com/Bimodal_programming_%E2%80%93_why_design_patterns_fail)<br/>
Explains why design patterns don't work for exploratory programming.

[Work Is Work - In which returns diminish.](https://codahale.com/work-is-work/) <br/>
Talks about the relationship between an organization's structure (breadth, depth, # of people, etc.) and how much work gets done.

[Paul Johson's essays](http://paulgraham.com/articles.html)<br/>
I recommend [Don't talk to Corp Dev](http://paulgraham.com/corpdev.html), [Life is Short](http://paulgraham.com/vb.html), and [Beating the Averages](http://paulgraham.com/avg.html).
- Life is Short goes over how to find and do the important things in life
- Don't talk to corp dev details when you should try to sell your company and when you shouldn't be talking to corp dev.
- Beating the averages is an example of why you should use the most powerful programming language at your disposal (Lisp in his case, and maybe yours too)

[The Rust Compilation Model Calamity](https://pingcap.com/blog/rust-compilation-model-calamity/)<br/>
Goes over why Rust's design decisions have given Rust long compilation times.

[Don’t Let Architecture Astronauts Scare You](https://www.joelonsoftware.com/2001/04/21/dont-let-architecture-astronauts-scare-you/)<br/>
This goes over how people at a certain level of abstraction no longer understand the proper solution to the problem you are actually dealing with.

[Monoliths are the future](https://changelog.com/posts/monoliths-are-the-future)<br/>
Details how microservices don't always solve the problem you are dealing with and how microservices are not a substitute for developer disciplines.

[No real numbers](http://beza1e1.tuxen.de/no_real_numbers.html)<br/>
How numbers are actually represented in a computer (if you already know about floating point truncation and precision, you probably don't need to read this).

[Don't use booleans](https://www.luu.io/posts/dont-use-booleans/)<br/>
Using enums is more readable and probably safer than using booleans.

[The Principles of Versioning in Go ](https://research.swtch.com/vgo-principles)<br/>
Why Go has one of the best package management algorithms.

[The Best and Worst GCC Compiler Flags For Embedded](https://interrupt.memfault.com/blog/best-and-worst-gcc-clang-compiler-flags)

[Programmer's critique of missing structure of operating systems](http://blog.rfox.eu/en/Programmer_s_critique_of_missing_structure_of_oper.html)
[Programs are a prison: Rethinking the fundamental building blocks of computing interfaces](https://djrobstep.com/posts/programs-are-a-prison)

# Quotes

>The most amazing achievement of the computer software industry is its continuing cancellation of the steady and staggering gains made by the computer hardware industry.

Henry Petroski

>There are only two kinds of languages: the ones people complain about and the ones nobody uses.

Bjarne Stroustrup, 

>Premature optimization is the root of all evil (or at least most of it) in programming.

Donald Knuth

>A complex system that works is invariably found to have evolved from a simple system that worked. The inverse proposition also appears to be true: A complex system designed from scratch never works and cannot be made to work.

John Gall

>Beware of bugs in the above code; I have only proven it correct, not tried it.

Donald Knuth

>The reality is that every developer on every keyboard is making a choice between doing things right and doing things right now?

Andrew Clay Shafer

# Videos
[CppCon 2019: Andrei Alexandrescu “Speed Is Found In The Minds of People](https://www.youtube.com/watch?v=FJJTYQYB1JQ&t=4711s)<br/>
A must watch IMO. He goes over how using big O does not accurately predict performance, only benchmarking does.

[CppCon 2019: Chandler Carruth “There Are No Zero-cost Abstractions”](https://www.youtube.com/watch?v=rHIkrotSwcc)

[CppCon 2014: Mike Acton Data-Oriented Design and C++](https://www.youtube.com/watch?v=rX0ItVEVjHc&t=2s)<br/>
How OO does not get performance, and how to get that performance back.

[Scale By The Bay 2019: Bryan Cantrill, Was He Wright All Along? Software After Moore's Law](https://www.youtube.com/watch?v=TM9h89Vo_Qo&t=338s)

[Principles of Technology Leadership | Bryan Cantrill | Monktoberfest 2017](https://www.youtube.com/watch?v=9QMGAtxUlAc&t=44s)


[Is It Time to Rewrite the Operating System in Rust?](https://www.youtube.com/watch?v=HgtRAbE1nBM)<br/>
Explains that Rust shares more values with the values of an operating system compared to C. Also, your values should be similar to the programming language you are using.

