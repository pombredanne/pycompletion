pycompletion
============

A lib to collect command line completion scripts of Python packages.
The following completion scripts are included:

* django (bash)
* fabric (bash)
* lanyon (bash)
* markdown (bash)
* nose (bash)
* pip (bash, zsh)
* pygments (bash)
* virtualenv (bash)

Dependencies
------------

`bash-completion 1.1 <http://bash-completion.alioth.debian.org>`_

Installing
----------

You can install pycompletion from the PyPI::

    pip install pycompletion

Then source the pycompletion script from your .bashrc::

    . `which pycompletion`

