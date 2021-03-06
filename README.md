# NGM-ai2html

This is a fork of the NYTimes' ai2html. For installation and full documentation go to [ai2html](http://ai2html.org). This modified script works nicely with [trudy, the Nat Geo Magazine graphics generator and preview tool](https://github.com/natgeo/ngm-trudy). A project using trudy will provide an [.ai template](https://github.com/natgeo/ngm-trudy/tree/master/project-files/ai2html) thats optimized to support natgeo.com.

## Installation

Ensure that this project is up to date. 

In the Terminal, navigate to the ai2html directory on your computer (e.g.: `cd ngm-ai2html`).

Pull the latest version: `git pull`

Double click on `_INSTALL.command`. If that fails, manually copy `ai2html.js` into your Illustrator scripts folder, likely `/Applications/Adobe Illustrator [version]/Presets/en_US/Scripts/`.

## Enhancements

- Generates font-face definitions for map fonts, supports Verlag and Neue Haas
- Generates font-smoothing css
- Letter tracking within the browser more closely matches Illustrator
- Leading uses ems instead of px


---

# [ai2html](http://ai2html.org)

> ai2html is an open-source script for Adobe Illustrator that converts your Illustrator documents into html and css.

Here are [examples of how we’ve used the script](https://delicious.com/archietse/ai2html,nyt) at The New York Times and [examples of how others](https://delicious.com/archietse/ai2html,others) have used it. Share your ai2html projects on Twitter, Delicious, etc. using #ai2html.

For documentation and examples on [how to use ai2html](http://ai2html.org), please visit [ai2html.org](http://ai2html.org).


## Contributing to this project

The Github repository for this site is available at [newsdev/ai2html](https://github.com/newsdev/ai2html).


## Thanks

Many thanks to [Gregor Aisch](https://twitter.com/driven_by_data), [Derek Watkins](https://twitter.com/dwtkns), [Josh Katz](https://twitter.com/jshkatz), [K.K. Rebecca Lai](https://twitter.com/kkrebeccalai), [Tom Giratikanon](https://twitter.com/giratikanon), [Matt Ericson](https://twitter.com/mericson), [Jeremy Ashkenas](https://twitter.com/jashkenas) and [Alan McLean](https://twitter.com/alanmclean) for their incredible contributions to this project, as well as to my colleagues in The New York Times [Graphics Department](https://twitter.com/nytgraphics) for their patient guidance.

If you’re learning to write Javascript for Adobe Illustrator, [John Wundes](http://www.wundes.com/JS4AI/), has many wonderful scripts. [explore.js](http://www.wundes.com/JS4AI/explore.js) is particularly helpful for understanding what attributes are attached to Illustrator objects.

---

<p style="font-size:.8em;opacity:0.5;">Created by <a href="https://twitter.com/archietse">Archie Tse</a> / <a href="https://github.com/newsdev">The New York Times</a></p>

<p style="font-size:.8em;opacity:0.7;">Copyright (c) 2011-2015 The New York Times Company</p>



