# Automation

(we didn't really get a chance to work through this, plus it is far beyond where we expect people to actually reach in the tutorial. But in any case, a few links on advanced stuff)

- [ ] Enable travis on a repo
- [ ] Hooks, (e.g., a bash/python/R script triggered by a Git action)
- [ ] Github pages


## Continuous Integration

We cannot yet use continuous integration services with repos in the USEPA Github organization, but perhaps of interest.

* [Travis Getting Started guide](https://docs.travis-ci.com/user/getting-started/)
* [Building an R package on Travis](https://docs.travis-ci.com/user/languages/r/)


## Git Hooks

Git hooks allow scripts to be triggered by Git actions. For example, the way CI frequently works is that every time a new commit is pushed to Github, the CI build is triggered. Other applications include checks that your files have been updated, or automatically incrementing versions.

[hooks in the Pro Git book](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks)


## Enabling Github pages so your repo can have a website:

* [Github instructions](https://guides.github.com/features/pages/) for enabling Github pages
* Jenny Bryan's recommendations [about making your repo browsable](http://happygitwithr.com/repo-browsability.html)
* For R users, [pkgdown](http://pkgdown.r-lib.org/) is a reason you might use github-pages.
* Also, Terry used it for [his presentation](https://github.com/tbnorth/GitRDDES)!
