# A Scalable CSS Reading List [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A list of things to read or watch that address these two questions: **What is scalable CSS?** and **How do we create scalable CSS?**

By *scalable CSS*, I mean CSS that is
- capable of remaining effective, coherent, extendable, and maintainable as projects grow over time
- capable of being understood and worked on by any number of different people in a consistent, systematic way

Included are resources that articulate key principles and practices. The list is restricted to the articles that I consider the most *important* to read -- that is, the best explanations (of which I'm aware) for different approaches to the problems.

**If you know of a resource that should be added, please share! File an issue or a pull request.**

(There are plenty of other problems related to CSS: understanding how it works, using specific properties, accomplishing specific styles, achieving responsive design, boosting performance, etc. This list is strictly focused on the problem of creating scalable CSS.)

*None of the sections present any kind of "ranking" or "suggested reading order." Just read them all.*

## Articles

Newest on top, oldest on bottom. (A note for you outside the US: my dates are month/day/year format.)

- [8 rules for a robust, scalable CSS architecture](https://github.com/jareware/css-architecture/blob/master/README.md), by Jarno Rantanen (10/16/2016)
- [More Meaningful CSS](http://snook.ca/archives/html_and_css/more-meaningful-css), by Jonathan Snook (5/17/16)
- [CSS and Scalability](http://mrmrs.io/writing/2016/03/24/scalable-css/), by Adam Morse (3/24/16)
- [Can CSS Be Too Modular?](http://csswizardry.com/2015/03/can-css-be-too-modular/), by Harry Roberts (3/8/15)
- [Side Effects in CSS](http://philipwalton.com/articles/side-effects-in-css/), by Philip Walton (3/3/15)
- [Used and Abused -- CSS Inheritance and Our Misuse of the Cascade](http://www.phase2technology.com/blog/used-and-abused-css-inheritance-and-our-misuse-of-the-cascade/?utm_source=CSS-Weekly&utm_campaign=Issue-127&utm_medium=RSS), by Micah Godbolt (8/25/14)
- [Enduring CSS: writing style sheets for rapidly changing, long-lived projects](http://benfrain.com/enduring-css-writing-style-sheets-rapidly-changing-long-lived-projects), by Ben Frain (8/7/14)
- [Challenging CSS Best Practices](http://www.smashingmagazine.com/2013/10/21/challenging-css-best-practices-atomic-approach/) -- suggesting a unique approach (all utility classes) the author calls Atomic CSS -- by Thierry Koblentz (10/21/13)
- [Atomic Design](http://bradfrostweb.com/blog/post/atomic-web-design/), by Brad Frost (6/10/13) -- which isn't really about *CSS code*, exactly; but so many people have found it a valuable way to think about frontend component architecture that it fits in well with this list.
- [MindBEMding - getting your head around BEM syntax](http://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/), by Harry Roberts (1/25/13)
- [CSS Architecture](http://philipwalton.com/articles/css-architecture/), by Philip Walton (11/16/12)
- [SOLID CSS](http://blog.millermedeiros.com/solid-css/), by Miller Medeiros (9/10/12)
- [Shoot to kill: CSS selector intent](http://csswizardry.com/2012/07/shoot-to-kill-css-selector-intent/), by Harry Roberts (7/17/12)
- [The open/closed principle applied to CSS](http://csswizardry.com/2012/06/the-open-closed-principle-applied-to-css/), by Harry Roberts (6/21/12)
- [Keep your CSS selectors short](http://csswizardry.com/2012/05/keep-your-css-selectors-short/), by Harry Roberts (5/15/12)
- [The single responsibility principle applied to CSS](http://csswizardry.com/2012/04/the-single-responsibility-principle-applied-to-css/), by Harry Roberts (4/28/12)
- [About HTML semantics and frontend architecture](http://nicolasgallagher.com/about-html-semantics-front-end-architecture/), by Nicolas Gallagher (3/15/12)
- [An Introduction to Object Oriented CSS (OOCSS)](http://www.smashingmagazine.com/2011/12/12/an-introduction-to-object-oriented-css-oocss/), by Louis Lazaris (12/12/11)

## Authoring Frameworks & Longer Readings

- [Atomic CSS](http://acss.io/), Yahoo! Inc.
- [CSS Modules](http://glenmaddern.com/articles/css-modules), by Glen Maddern
- [CSS Guidelines](http://cssguidelin.es/), by Harry Roberts
- [Scalable and Modular Architecture for CSS](https://smacss.com/), by Jonathan Snook
- [SUIT CSS Documentation](https://github.com/suitcss/suit/blob/master/doc/README.md), by Nicolas Gallagher
- [Multilayer CSS](http://operatino.github.io/MCSS/en/), by Robert Haritonov
- [Object Oriented CSS Wiki](https://github.com/stubbornella/oocss/wiki) by Nicole Sullivan

## CSS Styleguides

These styleguides articulate conventions and guidelines for authoring scalable CSS.

(I'm distinguishing *styleguides* from what I would call *pattern libraries*, which are references created to document and exemplify existing styles rather than guidelines for the authoring of the styles. Other people often use the term *styleguide* to refer to both or either of these reference types. I think pattern libraries are less specifically about scalable CSS, and more about a scalable frontend design and development workflow; so I'm not including resources related to pattern libraries.)

- [Trello](https://gist.github.com/bobbygrace/9e961e8982f42eb91b80)
- [Bootstrap](http://mdo.github.io/code-guide/#css)
- [SUIT](https://github.com/suitcss/suit/blob/master/doc/STYLE.md#4-css)
- [Github](https://github.com/styleguide/css)
- [Medium](https://gist.github.com/fat/a47b882eb5f84293c4ed)
- [Google](https://google.github.io/styleguide/htmlcssguide.xml#CSS_Style_Rules)

## Workflow Overviews

> How we do CSS at [blank] ...

Articles providing overviews of real-life CSS methodologies for production sites and apps of significant scale. Although these articles generally don't include principles that are not better explained in the articles and longer reads above, they are so pragmatic and concrete that they are important reads in their own right. Newest first.

- [Refining the Way We Structure Our CSS at Trello](http://blog.trello.com/refining-the-way-we-structure-our-css-at-trello/), by Bobby Grace (11/11/14)
- [How we do CSS at Ghost](http://dev.ghost.org/css-at-ghost), by Paul Davis (11/4/14)
- [Medium's CSS is actually pretty f\*\*\*ing good](https://medium.com/@fat/mediums-css-is-actually-pretty-fucking-good-b8e2a6c78b06), by Jacob Thornton (8/28/14)
- [Codepen's CSS](http://codepen.io/chriscoyier/blog/codepens-css), by Chris Coyier (7/30/14)
- [CSS at Lonely Planet](http://ianfeather.co.uk/css-at-lonely-planet/), by Ian Feather (7/24/14)
- [Github's CSS](http://markdotto.com/2014/07/23/githubs-css/), by Mark Otto (7/23/14)


## Talks

Newest first, I think.

- [Atomic CSS](https://www.youtube.com/watch?v=bokjM0ZaizQ) ([Slides](https://www.haikudeck.com/atomic-css-science-and-technology-presentation-dJ0xlFjhBQ)), Thierry Koblentz (2015)
- [Managing CSS Projects with ITCSS](https://speakerdeck.com/dafed/managing-css-projects-with-itcss), Harry Roberts (2014)
- [React: CSS in JS](http://blog.vjeux.com/2014/javascript/react-css-in-js-nationjs.html), Christopher Chedeau, a.k.a. Vjeux (2014)
- [Thinking Beyond "Scalable CSS"](http://www.thedotpost.com/2014/11/nicolas-gallagher-thinking-beyond-scalable-css), Nicolas Gallagher (2014)
- [Adaptation and Components](https://www.youtube.com/watch?v=m0oMHG6ZXvo) ([slides](https://speakerdeck.com/necolas/adaptation-and-components)), Nicolas Gallagher (2014)
- [CSS is a Mess](https://www.youtube.com/watch?v=C4z_9F6nfS8), Jonathan Snook (2013)
- [Architecting Scalable CSS](http://vimeo.com/67544231) ([slides](https://speakerdeck.com/csswizardry/architecting-scalable-css)), Harry Roberts (2013)
- [CSS for Grownups](https://www.youtube.com/watch?v=ZpFdyfs03Ug) ([slides](https://speakerdeck.com/andyhume/css-for-grown-ups-maturing-best-practises-sxsw-2012)), Andy Hume (2013)
- [CSS module system in Google+](https://github.com/davidtheclark/scalable-css-reading-list/issues/3) ([slides](https://docs.google.com/presentation/d/1_LpRI2_grOgTKyqodgg8yWGDhStgZHxnvjFOTJ6Jb3g/edit#slide=id.p)), Shubhie Panicker (2013)
- [Object-Oriented CSS](https://www.youtube.com/watch?v=BjAdHyA9nIY) ([slides](http://www.slideshare.net/stubbornella/object-oriented-css)), Nicole Sullivan (2009)
