# sage_notebooks
sagemath jupyter notebooks

# howto run
Run
sage --notebook

and pick any notebook in Jupyter inteface

# if interactive widgets don't work
You can notice the message:
[IPKernelApp] WARNING | Widget Javascript not detected.  It may not be installed or enabled properly. Reconnecting the current kernel may help.

Can be fixed with:
sage -pip install --upgrade ipywidgets

