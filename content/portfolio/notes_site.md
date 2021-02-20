+++
title = "notes.ajb.app"
draft = false
image = "img/notes/notes_head.png"
showonlyimage = false
weight = 1
+++

A personal note taking site I developed to create, share and manage my ongoing notes. Built using
Jekyll, the JTD framework and Lunr.JS for search. Deployed with Netlify.

<!--more-->

- [View Site](https://notes.ajb.app)
- [View Source Code](https://github.com/andybyers21/notes.ajb.app)

## Tech Stack

- Jekyll 3.something

This site is my personal research environment and an experiment in learning in public. I built it as
a vault for my ongoing note taking. The topics are broad and cover things like self-education,
computer science & web concepts, personal knowledge management (PKM), productivity,
entrepreneurship, strategy, marketing, wealth creation, note taking and whatever other rabbit holes
I find myself in.

![notes](/img/notes/notes_home.png)

Notes can be created in plain text or markdown in your editor of choice and backlinks and wikilinks
are automatically generated on save. Notes are automatically transformed by Jekyll into a static
site whenever I push the repo to GitHub and deployed to the web by Netlify. Site wide search is
implemented on all pages by default.

![Example of search](/img/notes/notes_search.png)

It's hosted at [notes.ajb.app](https://notes.ajb.app/). It is automatically transformed
by [Jekyll](https://jekyllrb.com/) into a static site whenever I push this repo to GitHub and
deployed to the web by [Netlify](https://app.netlify.com/).

![jekyll implementation](/img/notes/notes_jekyll.png)

It's built on the excellent [Just the Docs](https://pmarsceill.github.io/just-the-docs/) framework
by [Patrick Marsceill](https://github.com/pmarsceill). Search is made possible by
[Lunr.js](https://lunrjs.com/).

Backlinks maintained with a modified version of Andy Matuschak's
[note-link-janitor](https://github.com/andymatuschak/note-link-janitor)

![Example of backlinks output](/img/notes/notes_backlinks.png)

Feel free to use the source code as you like. Its hosted under [the MIT
license](https://opensource.org/licenses/MIT). If you do use it, let me know what you come up with.
