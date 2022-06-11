# ccf

Source code for the Computing Connections Fellowship website.

## To build the site locally

Inside this directory, run
```bash
bundle install
bundle exec github-pages --help
bundle exec github-pages build
```

This builds the site to `_site/`. The `github-pages` gem doesn't have a serve option, so to serve locally one is suppose to use [Jekyll](https://jekyllrb.com/) directly: `bundle exec jekyll serve`. However Jeykll isn't working for me at the moment on my M1 mac so I just view the files under `_site/` instead and publish when I need to see the changes live.

## Source

This uses a modification of the `minimal` theme from GitHub pages. [Source on Pages](https://github.com/pages-themes/minimal/blob/master/_layouts/default.html); [Upstream source from orderedlist](https://github.com/orderedlist/minimal/blob/master/index.html)
