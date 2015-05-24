A docker image based on debian jessie containing Pelican, Markdown and a couple extensions of mine.

Image specs:

* the blog root should be mounted at `/blog`
* Default command: `make html` to build the html output
* Call with `serve` to start a dev server (on port `8000`)