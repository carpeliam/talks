#Paul Irish Keynote

* Speed is relative
* What metric matters?
* ~~What is slow?~~ What does the user feel?
	* Jakob Neilson:
	* 100ms gives feeling of instantaneous response
	* 1000ms keeps the user's flow of thought seamless
	* 10s : you've lost the user's attention
* Break down into actions
	* User Response - responding to touch, tap, drag - < 100ms (from tap to paint)
	* Animation/Scrolling - 60fps, < 16ms
	* Idle - user isn't active... but could be. work completes in 50ms chunks
	* Page load
		* user loads the page and sees critical path content
		* starts interacting
		* ready to use in 1000ms, also satisfy response goals during full load
	* **RAIL** : **R**esponse, **A**nimation, **I**dle, **L**oad

	
# Andreas Gal Keynote
## Dirty Performance Secrets of HTML5

* 16ms is based on 60fps
* browser actions are serial
* most code is NOT on the critical path
* don't try to analyze code to find performance issues, they're not obvious - analyze benchmarks
* Firefox - JIT Coach - Sample Based JIT Profiler

# Bill Scott
## Kraken - PayPal JS framework
* JavaScript has enabled PayPal to move faster
* The UI layer is the experimentation layer

# Brendan Eich
## Compilers
* JS Solar System
	* it started with the core, ES3
	* ES6: ES2015; ES7: 2017
	* On top of JS: transpilers, linters
	* On top of that: Type-safe JS
	* Babel - turns your ES6+ code into ES5-friendly code, works with JSX
* Thread support in the future (kind of), will enable integration with C++ threads
* demos - games embedded in webpage, in Unity
* "Always bet on JS"

# Stewart Nickolas
## Conversational Computing
* Watson services, built-out for the cloud, internet of things

# Kathy Sierra
* What do you need to know? This is the wrong question.
* What do you need to learn quickly?

Am I doing things that make people unnecessarily burn their cognitive resources?

**Three stages**

* A: Can't do, but need to do
* B: Can do, but with effort
* C: Mastered (reliable, automatic)

* Pile Up on B - too many things taking resources so we can't master
	* Split it up into subskills, take subskills into C
	* half-a-skill beats a half-assed skill - practice makes permanent
	* it needs to be small enough to be mastered within three 45-90 minute sessions
* Half-assed skills on C
	* continually recheck things you've learned, does it need to be refined?
* Need to bypass B when possible