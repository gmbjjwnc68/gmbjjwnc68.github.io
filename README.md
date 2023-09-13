# Gustavo Machado Brazilian Jiu-Jitsu 68

Visit us at [our website](http://www.gmbjjwnc68.com)!

## Questions? Comments? Concerns?

Please reach out to us at gmbjjwnc68@yahoo.com with any questions, etc. This repository was created and is maintained by [Momosimo](https://github.com/Momosimo).

### Technical setup details

#### Useful setup inputs

- This portion of the readme was adapted in part from [the official Jekyll setup guide.](https://jekyllrb.com/docs/step-by-step/01-setup/)

- With [Ruby and all system-based dependencies](https://jekyllrb.com/docs/installation/) installed:

`gem install jekyll bundler`

- Create a new Gemfile to list your project’s dependencies:

`bundle init`

- Edit the Gemfile in a text editor and add jekyll as a dependency (this step may already be done, but check the Gemfile in any case):

`gem "jekyll"`

- Run bundle to install jekyll for your project:

`bundle`

- nb. You can now prefix all jekyll commands listed in this tutorial with bundle exec to make sure you use the jekyll version defined in your Gemfile.

#### Useful build inputs

- Build the site and outputs a static site to a directory called "_site":

`bundle exec jekyll build`

- Do jekyll build and run it on a local web server at http://localhost:4000, rebuilding the site any time you make a change:

`bundle exec jekyll serve`

- Optional flags: "--livereload" "--host" "--port"

- eg. `bundle exec jekyll serve --livereload`
