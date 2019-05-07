---
layout: post
title: "Getting started: Running the site locally!"
---

This is my first post, and I can't think of anything more appropriate than to
document how to run the site locally in order to preview changes before pushing
them externally.

### Running locally

To run locally, execute the following command in the root directory of your
repository:
```bash
bundle exec jekyll serve --incremental
```

This should regenerate your site files and you should be able to access the
local instance of your site at `http://localhost:4000`

### Drafts

There's another trick here that you can use to write draft posts i.e. posts that
are not shown on your site, unless you run the site with draft-publishing
enabled.

As you probably already know, posts that you would like to be published go into
a specially named directory: `_posts`.

Any draft writings go into a specially named directory: `_drafts`
Then, run locally using the following command
```bash
bundle exec jekyll serve --incremental --drafts
```
