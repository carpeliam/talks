# Welcoming the Web
## Estelle Weyl
* don't limit to white male milennials - ninjas, rockstars, cowboys
* recruiting based on cultural fit creates a homogeneous team
* 50% of women in STEM leave due to hostile work environments
* use same language for everyone
* use merit, not potential, as a benchmark
* assume devs are as skilled as you; their code is as good as yours; they're correct
* listen, don't interrupt
* stand up when others are silenced
* give directives, instead of constructive criticism
* incorporated improv principles
* onboard, include everyone (not just the devs)
* formalize processes
* use `git blame` when you find an EXCELLENT line of code, not just a bad one

# Erin McKean
## The Linguistics of JavaScript
* all languages used by humans are used to persuade
* most language rules are built around things that are possible to do, but are not liked
* "raise your hand if you wrote a style guide in the last month"
* if a word can be misunderstood, it will be
* "i haven't slept for ten days, because that would be too long" - "if you have an expression in JavaScript that ends this way, you are a jerk."
* semi-colon appreciation society!!

# Eric Meyer
## This Web App Best Viewed By Someone Else
* "Oh hey this website doesn't load properly and the back button is kind of broken. \*view source\* Of course it is."
* "JavaScript is part of the web platform; you don't get to take it away and expect the web to work" - the only things you can't take away are HTTP, HTML, and a browser/client
* the web is NOT a platform: the web is explicitly designed to be cross-platform, designed to be independent
* the web is not for the people who have the fastest connection and have JS running
* ubiquity over consistency
* three takeaways of living with slow internet (medium)
	* some sites never loaded
	* on some sites, text was invisible for a frustratingly long time
	* well-designed apps worked wonderfully

# Kimberly Blessing
## The Web (Browser) We Forgot
* line mode browser was open-sourced (maybe the first OSS proj) because CERN didn't want to pay licensing fees
* line-mode.cern.ch
* built out of modern technologies
* many new websites don't work so well - github does
* reminder that progressive enhancement is a good thing

# JavaScript: The Musical
* The web took off not because of tools, but because it enabled us to find each other

# Julien Verlaguet
## Deep-dive: Facebook’s programming language, Hack
* Hack is THE server-side language at facebook
* "gradually typed": dynamic vs static typing is optional, at very fine grain
* HHVM: Hack JIT virtual machine
* what's cool about hack:
	* runs type checker as daemon, in the background - this allows for static checking, without compiler/linter delay
	* it not only tells you what went wrong, but all parts of the code that contribute to what went wrong
* async/await: expression in the language of blocking code, but is async
* Nullable: you can say that something can be null (at type checking time), and see all places in code where you need to deal with null
* xhp: similar to React's JSX