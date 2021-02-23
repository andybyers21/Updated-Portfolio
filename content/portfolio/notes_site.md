+++
title = "notes.ajb.app"
draft = false
image = "img/notes/notes_head.png"
showonlyimage = false
weight = 1
+++

A personal note taking site I developed to create, share and manage my ongoing
notes.

Built using Jekyll, the JTD framework and Lunr.JS for search. Deployed with
Netlify.

<!--more-->

- [View Site](https://notes.ajb.app)
- [View Source Code](https://github.com/andybyers21/notes.ajb.app)

This site is my personal research environment and an experiment in learning in
public. It evolved from a vault I created to store for my ongoing note and a
frustrstion with the tools (and cost of) avaliable at the time.

![notes](/img/notes/notes_home.png)

The topics are broad and cover things like self-education, Computer Science &
Web Concepts personal knowledge management (PKM), Productivity,
entrepreneurship, strategy, marketing, Wealth Creation, and whatever other
rabbit holes I find myself in. I’ve committed to sharing my findings with the
world. If you’re willing to let people access your life, they’ll find what they
need to help you succeed.

Note categorization is loosely based on the zettelkasten system. Whenever you
add a new note, the zettelkasten method forces you to look for already existing
notes you can link to. That broadens your thinking by foring you to consider how
new ideas relate to others you’ve encountered before. If you start with an
initial idea you cannot help but filter everything you encounter. However, the
zettelklasten system has no preconceptions of what it is fed over the long term,
it builds on your thoughts over a period of time that could possibly span years.
New ideas and insights will form just by comparing notes side by side. In turn,
questions will emerge from the work, rather than being imposed on it.

NOTE: As these are my personal notes some of them may not make any sense to you
or be part complete. My intent for is to use them for developing ideas over
time.

## Features

Notes are catogarised and tagged using YAML Tags

Top level navigation structure and a flat file structure for easier note
retrieval. File sysytem is organised in such a waty that it can easily be
integrated with [Obsidian](https://obsidian.md),
[VimWiki](http://vimwiki.github.io/) and other markdown based note taking tools.

Code-block syntax highlighting:

```py
def fizzy(y):
    for a in range(1, (y + 1)):
        if a % 3 == 0 and a % 5 == 0:
            print("FIZZBUZZ")
        elif a % 3 == 0:
            print("FIZZ")
        elif a % 5 == 0:
            print("BUZZ")
        else:
            print(a)


y = int(input('how many fizzbuzzes? '))

fizzy(y)
```

Compatable with various environments, Chrome, Safari and Firefox among others

Notes can be created in plain text or markdown in your editor of choice and
backlinks and wikilinks are automatically generated on save. Notes are
automatically transformed by [Jekyll](https://jekyllrb.com/) into a static site
whenever I push this repo to GitHub and deployed to the web by
[Netlify](https://app.netlify.com/).

Site wide search is implemented on all pages by default.

![Example of search](/img/notes/notes_search.png)

It's hosted at [notes.ajb.app](https://notes.ajb.app/).
![jekyll implementation](/img/notes/notes_jekyll.png)

It's built on the excellent [Just the
Docs](https://pmarsceill.github.io/just-the-docs/) framework by [Patrick
Marsceill](https://github.com/pmarsceill). Search is made possible by
[Lunr.js](https://lunrjs.com/).

Backlinks are maintained with a modified version of Andy Matuschak's
[note-link-janitor](https://github.com/andymatuschak/note-link-janitor). This
script reads in a folder of Markdown files, notes all the wiki-style links
between them, then adds a special “backlinks” section which lists passages which
reference a given file. Links are formatted using `[[double square brackets]]`.
Note titles are inferred from the first line of each note, which is assumed to
be formatted as a `#heading`, Note title.  

All .md files are siblings; the script does not currently
recursively traverse subtrees. The backlinks “section” is defined as the AST
span between backlinks and the next heading tag (or `<!-- -->` tag). Any text
you might add to this section will be clobbered. Don’t append text after the
backlinks list without a heading in between! (I like to leave my backlinks list
at the end of the file)

![Example of backlinks output](/img/notes/notes_backlinks.png)

Feel free to use the source code as you like. Its hosted under [the MIT
license](https://opensource.org/licenses/MIT). If you do use it, let me know
what you come up with.

