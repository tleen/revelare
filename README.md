# Revelare

Starter site for creating slideshow presentations using [reveal.js](https://github.com/hakimel/reveal.js). Designed specifically to work in the context of [GitHub Pages](https://pages.github.com/) using [Jekyll](https://jekyllrb.com/).

This is a *starter* for a slideshow presentation, you can reasonably expect to have to modify the [configuration](_config.yml) and [styling](index.scss). Most of all you will have to author your own [slides](_slides), although there are a few example slides to get you started. 

## Slides

The slides may be written using [Markdown](https://guides.github.com/features/mastering-markdown/) and should all be in the [_slides](_slides) directory.

The slides use Jekyll [front matter](https://jekyllrb.com/docs/frontmatter/) to identify grouping and ordering.

Each slide belongs to a *group* which is a simple text slug you designate. This is used for ordering the main slides, the slide ordering you will define in the [configuration](_config.yml) file as a string value of comma separated slugs (no spaces).

If your slide has follow up slides they may use the same group slug. To control the display ordering of these sub-slides you may set the *order* in the slide's front matter. See this in action in the "introduction" [slides](_slides).
