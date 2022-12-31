# hugo-bulma-kiss

This theme is forked from [Mike Watkins'](https://mikewatkins.ca) 
[Smorg](https://github.com/solutionroute/hugo-smorg) which is no longer
maintained.

Bulma KISS is intended to be a clean and minimal theme using the 
[Bulma](https://bulma.io/) CSS framework to provide a simple personal website
for Derek Kozel's site. The original values from Smorg of being responsive and
mobile-friendly remain, as does the intent of allowing simple and flexible 
adaptation of the theme.

The theme is not specifically intended for general use, but small fixes and 
improvements are welcome if anyone does use it. Just like Bulma, this theme 
intends to "just work" rather than being clever or ideal.

Keep It Simple and Stupid

**Current release**: v1.0, December 31, 2022 - Officially breaking from Smorg 
in order to do a variety of updates and to remove missing dependencies.

Check the CHANGELOG.md for details about the changes made.

## Objectives

* Remain easy to understand while also being easy to extend.
* Keep pace with current [Hugo](https://gohugo.io) features and practicies.
* Avoid relying on config.yaml for too much customization.
* Keep HTML customizability effort low using template blocks and partials and
  CSS customizability options open via SASS / CSS.
* Produce output that will validate and load quickly by default.

## Features

Bulma KISS is:

* Mobile first thanks to [Bulma](https://bulma.io/), a SASS CSS framework alternative to
  Bootstrap.
* Themable itself via [Bulmaswatch](https://jenil.github.io/bulmaswatch/).
* Minimalistic in nature. 

And offers:

* Responsive site-wide drop-down capable navigation menu
* Simple "Subsection" pages possible with layout:subsection in front-matter.
* Breadcrumb-menu in subsection layout, available to others.
* Produces Atom syndication format with option to disable RSS.
* JSON-LD microdata
* Category and Tag taxonomies (partial page-meta)
* Themed mobile-friendly pagination.

## Installation

1. Clone the repo:

	git clone --recursive https://github.com/dkozel/hugo-bulma-kiss.git

2. To view the theme:

	cd exampleSite
	hugo server

[Hugo]: https://gohugo.io/
[Bulma]: https://bulma.io/ 
[Bulmaswatch]: https://jenil.github.io/bulmaswatch/
