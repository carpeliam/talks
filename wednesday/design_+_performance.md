# Design + Performance
* small, interdisciplinary teams
* define guiding principles
* Speed is more important than design embellishment
	* Users expect sites to render in under 2 seconds
* prototype early - try to get away from mock-ups
	* you might have people from design, product, and dev together, iterating in moments
* measure performance right from the start - define a performance budget
* show performance report (with passing/failing grade) right in the page - can be done with bookmarklet
* page load time (window.onload) is a web 1.0 metric
	* gmail finishes onload in 4 seconds, but that's just a loading screen- actually takes a while
	* amazon: 99% above the fold in 2 seconds, onload in 9.7 seconds
* WebPageTest:
	* start render, speed index: more important metrics than load time
		* speed index: time to render median above-the-fold pixel, in ms
	* cool feature: film strips
* Custom metrics: define most important elements on the page.
	* measure using User Timing
	* track with RUM *and* synthetic
	* twitter example: "time to first tweet"
* Image loading:
	* resource timing
	* image onload
	* offsetHeight Polling - when does 
	* inline script: `<script>performance.mark('image_stuff')</script>`
	* take max time of all of the above