# WMPA project page

Project page for **World-Model Policy Arbiter for Goal-Conditioned Reinforcement Learning**
(Junwei Quan, Evgenii Opryshko, Nicholas Rhinehart, Igor Gilitschenski), served with GitHub Pages at
https://junwei0102.github.io/wmpa-webpage/.

The page uses the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template)
(Bulma). It is fully static: edit `index.html` and push; there is no build step.

```
index.html              the page (the results chart is inline SVG)
static/css/             bulma.min.css and index.css from the template
static/js/index.js      BibTeX copy button and scroll-to-top
static/images/          overview figure, cube-double-play episode figure, favicon
```

## After the arXiv announcement

Search `index.html` for `ARXIV_ID`:

- add a Paper button that links to `https://arxiv.org/pdf/ARXIV_ID`;
- turn the "arXiv (coming soon)" button into a link to `https://arxiv.org/abs/ARXIV_ID`
  (remove `disabled`, `aria-disabled`, and "(coming soon)");
- in the BibTeX block, change `journal = {arXiv preprint}` to `journal = {arXiv preprint arXiv:ARXIV_ID}`.
