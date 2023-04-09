# Website
This is the code behind Jeanine Pollard's personal website. It uses Jekyll and Github Pages to generate the pages and is based on an open-source Minimal Mistakes theme. Jekyll generates webpages via a mixture of Markdown files (content) and config files for assembling the content. Most of the logic for the site can be found in the [original theme](https://github.com/mmistakes/minimal-mistakes) and the files in this repository just override certain configurations etc.

## Updating
There are a few update patterns:
- Adding new posts: add a new markdown file to the `_posts` directory like [any of these examples](https://github.com/mmistakes/minimal-mistakes/tree/master/docs/_posts).
- Changing basic config (layout; sidebar content; etc.): directly edit the `_config.yml` file. For supported keys, check [default configuration](https://github.com/mmistakes/minimal-mistakes/blob/master/_config.yml) or [docs](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/).
- Changing more advanced config (styling etc.): copy the relevant files from the [original theme](https://github.com/mmistakes/minimal-mistakes) (into the exact same file path) and edit them locally. They will override the originals.

## Resources
- [Original repository generator](https://github.com/mmistakes/mm-github-pages-starter)
- [Theme documentation](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)
- [Github pages](https://pages.github.com/)
- [Jekyll](https://jekyllrb.com/)
- [Markdown](https://kramdown.gettalong.org/quickref.html)