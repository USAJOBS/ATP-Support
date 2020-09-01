# ATP-Support

[![Build Status](https://travis-ci.org/USAJOBS/ATP-Support.svg?branch=master)](https://travis-ci.org/USAJOBS/ATP-Support)

Support content for the USAJOBS Agency Talent Portal. Currently includes the Job announcement playbook.

## Building the Site Locally

### Pre-requisites

* An appropriate of ruby for Jekyll development

### Building

* Pull the code
* Go to the root directory of the repository
* Run `bundle install` to install the dependencies
* Run `bundle exec jekyll build` to build the site (will put HTML files int the `_dist` folder)

### Serving the Site Locally during development

* The same steps as building, but run `bundle exec jekyll serve`. The site will be started at `http://localhost:4000`.
