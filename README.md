## Installation Steps
The installation process involves some optional and necessary steps. Here's the detailed breakdown:
1.Creating env
```
conda create -n Py python=3.9.0
conda activate Py
```
2.Installing PyEpiSIM Using pip
```
pip install -i https://pypi.org/simple/ PyEpiSIM
```
Note: Due to network issues, you may need to attempt the installation multiple times before it succeeds. If the installation fails, try running the command again until it completes successfully.
3.Using PyEpiSIM
```
from PyEpiSIM import PyEpiSIM
PyEpiSIM.run()
```
