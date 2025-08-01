# DataWhys Content Notebooks (R version)

This repository contains data science training content for DataWhys in the form of JupyterLab notebooks (.ipynb files).

These notebooks are completely portable to all JupyterLab environments but require a Blockly extension for the full user experience (see prerequisites below).

For a complete list of topics covered, see [the course outline](Course-outline.ipynb).
Each topic has an introduction/worked example notebook and an independent problem solving notebook (`-PS`).

All materials are in R. See [here](https://github.com/memphis-iis/datawhys-content-notebooks-python) for the same materials in Python.

## Check it out!

### Static viewing

Click on any notebook in the repository, and GitHub will render it in your browser as a non-interactive document.

### Interactive viewing

Launch a demo session by clicking on the Binder badge below.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/memphis-iis/datawhys-content-notebooks-r/master?urlpath=lab)

If you've never used Jupyter or want to try the Blockly extension, check out the tutorial video below.

[![Tutorial video using Blockly](https://img.youtube.com/vi/Bmd60BQP0Qk/0.jpg)](https://youtu.be/Bmd60BQP0Qk "Tutorial video using Blockly")

Additional R-specific features are show in this video:

[![Tutorial video using Blockly for R](https://img.youtube.com/vi/zP3KvN3PM1U/0.jpg)](https://youtu.be/zP3KvN3PM1U "Tutorial video using Blockly for R")


## Development

### Prerequisites

- [JupyterLab](https://jupyter.org/install)
- [JupyterLab Blockly extension](https://github.com/aolney/jupyterlab-blockly-polyglot-extension) (optional but strongly recommended)

The above is a minimal environment.
See the `binder` subfolder for the recommended [conda env](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file) and [JupyterLab extension](https://jupyterlab.readthedocs.io/en/stable/user/extensions.html#using-the-terminal) installation, but note these are for JupyterLab 1.2.x; see [the core repo](https://github.com/memphis-iis/datawhys-content-notebooks) for the latest JupyterLab.


### Internal development

Any other content-related materials, e.g. spreadsheets, should be placed [in the OneDrive folder](https://livememphis-my.sharepoint.com/:f:/r/personal/aolney_memphis_edu/Documents/DataWhys/content-planning?csf=1&e=LPEGbr). If you create an issue that references a document in that folder, please try to link to said document.

## Contributing

If you want to change/correct content, either create an issue describing your change or [use a `git` workflow to make the change](https://www.atlassian.com/git/tutorials/making-a-pull-request).
