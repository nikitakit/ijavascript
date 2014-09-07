# IJavascript (like IPython)

## Setup instructions

Symlink `frame.html` into `~/.ipython/profile_default/static/`

### MathJax setup (needed due to a bug)

Run `ipython profile create default` to generate config files.

Change the corresponding line to `c.NotebookApp.enable_mathjax = True`
in `~/.ipython/profile_default/ipython_notebook_config.py`
