
<!-- badges: start -->
[![Netlify Status](https://api.netlify.com/api/v1/badges/8aeb0e37-d981-47ce-8689-591ecb3acc3d/deploy-status)](https://app.netlify.com/sites/rladies-jozi-r-pkg-dev/deploys)
[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
<!-- badges: end -->

# Become an R package developer!

## Workshop for R-Ladies Jozi| 2022-04-04

This repo contains the materials for a 2 hour workshop on R package development. <br>
Visit [https://rladies-jozi-r-pkg-dev.netlify.app/](https://rladies-jozi-r-pkg-dev.netlify.app/) to see the live version!

### Instructor (+ Content)
Maelle Salmon | ([@maelle](//github.com/maelle)) | [masalmon.eu](https://masalmon.eu) | [@ma_salmon](//twitter.com/ma_salmon)


### Organizers
- [R-Ladies Johannesburg](https://www.meetup.com/rladies-johannesburg/events/284974968/) | [@RLadiesELansing](//twitter.com/RLadiesJozi)

Source of the website of a short course.

It is powered by [Hugo](https://gohugo.io/) and the following themes:

* [Hugo theme learn](https://github.com/matcornic/hugo-theme-learn)
* [Hugo theme reveal-hugo](https://github.com/dzello/reveal-hugo)

Slides for each section are listed in the menu and opened in a new tab (thanks to a [custom menu layout](/blob/master/layouts/partials/menu.html), compared to the original Hugo learn theme).

Some Markdown content is generated with [R Markdown](https://rmarkdown.rstudio.com/), using [hugodown](https://github.com/r-lib/hugodown/).

The website is deployed by [Netlify](https://www.netlify.com/).

Slides could be printed to PDF using Decktape which I [have done in a concept](https://github.com/maelle/test-course-site) but I am not pursuing it further.

### Why these tools?

Why use Hugo for both the website and slidedecks, and not, say Hugo+hugodown for pages and xaringan for slides?
This way the source of slides is html produced by Hugo from Markdown content.
It allows me to use:

* downlit syntax highlighting for slides created from R Markdown with hugodown output format;
* Chroma syntax highlighting for other languages;
* emojis! `:grin:` works in slides;
* Shortcodes in slides, should I choose to.

Also, because slides are in the content, they are indexed by the Hugo learn theme so searchable!

