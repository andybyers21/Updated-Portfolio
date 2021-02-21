+++
title = "notes.ajb.app"
draft = false
image = "img/notes/notes_head.png"
showonlyimage = false
weight = 1
+++

Version History
0.3
0.3.0,
Added automatic back-linking to notes
Moved to a flat file structure for easier note retrieval
Updated YAML Tags
(Updated current notes to new YAML format)
Updated navigation system
Created tagging system for notes
Top level navigation structure
General navigation styling updates
Removed deep links with Obsidian
0.2
0.2.4, 14th September 2020
Add syntax highlighting to code-blocks
Added more fonts for use with various systems
Update color schemes for readability
0.2.3, 23rd August 2020
Refactor code and remove unnecessary plugins
Public launch via netlify
0.2.2, 10th August 2020
Styling updates
0.2.1, 29th July 2020
Update navigation structure (folder based note sorting)
0.2.0, 27th June 2020
File system updated for better oganization and integration with Obsidian.mdr

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

I built this site as a vault for my ongoing note taking. The topics are broad and cover things like self-education, Computer Science & Web Concepts personal knowledge management (PKM), Productivity, entrepreneurship, strategy, marketing, Wealth Creation, and whatever other rabbit holes I find myself in. I’ve committed to sharing my findings with the world. If you’re willing to let people access your life, they’ll find what they need to help you succeed.

This page is my personal research environment and an experiment in learning in public.
Note categorization is loosely based on the zettelkasten system. Whenever you add a new note, the zettelkasten method forces you to look for already existing notes you can link to. That broadens your thinking by foring you to consider how new ideas relate to others you’ve encountered before. If you start with an initial idea you cannot help but filter everything you encounter. However, the zettelklasten system has no preconceptions of what it is fed over the long term, it builds on your thoughts over a period of time that could possibly span years. New ideas and insights will form just by comparing notes side by side. In turn, questions will emerge from the work, rather than being imposed on it.

One important notion, there will be very few straight lines within this platform. It should be dominated by curves and offshoots.

If you want to view the code you can do so here. You can see my TO-DO list for the site. If you want to get in touch with me or have any comments, you can do so by emailing me at a@ajb.app

P.S. As these are my personal notes some of them may not make any sense to you or be part complete. My intent for is to use them for developing ideas over time.

If you happen to stumble across my notes on learning to code please be aware that they are written on an Apple developer environment.c

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

Backlinks maintained using Andy Matuschak’s note link janitor

This script reads in a folder of Markdown files, notes all the wiki-style links between them, then adds a special “backlinks” section which lists passages which reference a given file.

Assumptions/warnings
Links are formatted <a href="">like this</a>.
Note titles are inferred from the first line of each note, which is assumed to be formatted as a heading, i.e. # Note title.
All .md files are siblings; the script does not currently recursively traverse subtrees (though that would be a simple modification if you need it; see lib/readAllNotes.ts)
The backlinks “section” is defined as the AST span between ## Backlinks and the next heading tag (or <!-- --> tag). Any text you might add to this section will be clobbered. Don’t append text after the backlinks list without a heading in between! (I like to leave my backlinks list at the end >of the file)>

![Example of backlinks output](/img/notes/notes_backlinks.png)

Feel free to use the source code as you like. Its hosted under [the MIT
license](https://opensource.org/licenses/MIT). If you do use it, let me know what you come up with.
