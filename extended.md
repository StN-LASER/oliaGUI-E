## Extended.md

Extended operation oliaGUI based GUI, used with our olia based STN-LIA-MPU boards


## run .exe, after intalling opengl
709 WARNING: Failed to collect submodules for 'pyqtgraph.opengl' because importing 'pyqtgraph.opengl' raised: ModuleNotFoundError: No module named 'OpenGL'

https://www.analyticsvidhya.com/blog/2024/01/ways-to-convert-python-scripts-to-exe-files/


solution 27
https://stackoverflow.com/questions/11215362/importerror-no-module-named-opengl-gl



## original README.md
OLIAGUI.py is a simple python gui for use with OLIA. Requires the libraries PyQt5, numpy, pyqtgraph and pyserial to run. The first two of these libraries are included by default with [Anaconda](https://www.anaconda.com/), and the latter two can be installed using the included conda package manager. To do this, first install Anaconda, then run `conda install -c anaconda pyserial` in the Anaconda prompt to install pyserial (following the prompts as they arise). After installation has finished, run `conda install -c anaconda pyqtgraph` to install pyqtgraph. 

The script "communicator.py" and ui file "interface.ui" must be included in the same directory as OLIAGUI.py. Further instructions on the use of the software are available in the [OLIA usage instructions.](https://github.com/ajharvie/OLIA/blob/main/doc/usageGuide.md)
