# Building HTML Email Doesn't Have To Suck
## Current State of email
* tool: litmus
	* lists client share
* different (30+) clients have very different rendering engines (including MS Word)
* don't rely on DIV (floating, position)
* can't rely on stylesheets, css3, html5, JS, images
* what we *can* use:
	* tables; "<td> or GTFO (get to fixing Outlook)"
	* inline CSS
	* target Outlook `<!--[if mso 12]>...`
	* target Webkit with media query (also used for responsive design)
	* progressive enhancement
		* lack of images shouldn't render email useless

## Building HTML email
* handcoding is not scalable
* modules, not pages; using building blocks instead of one-off pages
* static site generators can help
* "premailer" gem
* compress images, using `imagemin`

## Automating HTML email
* Grunt, Gulp
* tasks for compiling SASS, assembling html templates, imagemin, inlining CSS
* make plain text version as well
* send email to litmus, or mailchimp
* send templates to codebase
* https://github.com/leemunroe/grunt-email-workflow
