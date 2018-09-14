## Guidelines for future years

Please maintain the nested structure of the website repository. In particular, each year of the workshop should have its own subfolder that contains an index page `index.md` as well as a `slides` folder and a `papers` folder. The landing pages from previous years should be preserved (_i.e._, the existant subfolders `/201[0-9]` should remain unmodified in future years). However, future landing pages accessible at `metalearning.ml` may introduce a new webpage style as long as they maintain a visible link to all previous years of the workshop.

The original maintainer (Roberto Calandra) reserves the right to intervene to preserve the overall structure and previous editions of the website moving forward.

### Instructions for refreshing the website

To make the website ready for the year `20XX`:

1.  Create a folder `20XX`.
2.  Create a Markdown file at `20XX/index.md` with the webpage content. Feel free to copy the template from earlier years. Ensure that the header includes 

```
---
title: MetaLearn20XX
permalink: /20XX/index.html
weight: -1
redirect_from: /201XX/
---
```

3. Modify the root landing page at `index.html` to redirect to `http://metalearning.ml/20XX/`.
