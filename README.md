# Website for waikato-datamining

Generates the website at [https://waikato-datamining.github.io/](https://waikato-datamining.github.io/) using [Nikola](https://getnikola.com/). 

This website is available through the custom domain [data-mining.co.nz](http://www.data-mining.co.nz/)


## Automatic generation

Currently, a [github action](https://github.com/waikato-datamining/waikato-datamining.github.io/blob/src/.github/workflows/main.yml) automatically rebuilds the website as soon as a commit occurs on the repository.


## Manual generation

### Requirements

* Nikola (>= 8.0.3)
* ghp-import2


### Installation

* create virtual environment

  ```
  virtualenv -p /usr/bin/python3.7 venv
  ```

* install Nikola

  ```
  . venv/bin/activate
  pip install nikola ghp-import2
  ```

### Adding content

* [Nikola handbook](https://getnikola.com/handbook.html)
* Content is written in [reStructured Text](http://docutils.sourceforge.net/rst.html)
* Pages are located in `pages`
* News items (aka blog posts) are located in `posts`; should have a date prefix in the name
* `files/CNAME` contains `www.data-mining.co.nz` domain in order to deploy the `CNAME` file for github
* The nikola source is on branch `src`, the generated code is on `master`


### Deploy to Github

* [general notes](https://pages.gitlab.io/nikola/stories/handbook/#deploying-to-github)
* commit/push changes
* run the following commands

  ```
  . venv/bin/activate
  nikola github_deploy
  ```

