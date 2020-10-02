![WinPython](WinPython.png)
# WinPython

## *FREE Python-distribution* for *Windows* platform, including *prebuilt* packages for *Scientific* Python.

---

***WinPython*** is a free open-source portable distribution of the [Python programming language](https://www.python.org/) for Windows 8/10 and scientific and educational usage.

It is a full-featured (see the [Wiki](https://github.com/winpython/winpython/wiki)) Python-based scientific environment:

-   Designed for scientists, data-scientists, and education (thanks to [NumPy](https://www.numpy.org/), [SciPy](https://www.scipy.org/), [Sympy](https://www.sympy.org/), [Matplotlib](https://matplotlib.org/), [Pandas](https://pandas.pydata.org/), [pyqtgraph](http://www.pyqtgraph.org/), etc.):

    -   interactive data processing and visualization using Python with [Spyder](https://www.spyder-ide.org/) and [Jupyter/IPython](https://jupyter.org/), Pyzo, IDLEX or IDLE
    
    -   ***fully integrated Cython and Numba!*** See [included example](https://nbviewer.ipython.org/github/winpython/winpython_afterdoc/blob/master/docs/Winpython_checker.ipynb)
    
    -   connectors (cffi, odbc, rpy2, scilab2py, requests, ...) for advanced users
    
---
    
-   **Portable**:

    -   Runs out of the box(*) on any Windows 8+ with 2GB Ram (Jupyter Notebook will require a recent browser)
    
    -   The WinPython folder can be moved to any location (**) (local, network, USB drive) with most of the [application settings](https://github.com/winpython/winpython/wiki/Installation#settings)

---

-   **Flexible**:

    -   You can install as many WinPython distributions as you want on the same machine: each one is isolated and self-consistent
    
    -   These installations can be of different versions of Python (3.7/3.8/3.9...)
    
---

-   **Customizable**:

    -   The integrated WinPython Package Manager ([WPPM](https://github.com/winpython/winpython/wiki/WPPM)) helps installing, uninstalling or upgrading Python packages
    
    -   It's also possible to install or upgrade packages using **pip** from the WinPython command prompt
    
    -   A configuration file allows you to set [environment variables](https://github.com/winpython/winpython/wiki/Environment) at runtime

---
    
WinPython is **something different** from other Python Distributions (see historic [motivation and concept](https://github.com/winpython/winpython/wiki/Roadmap)):

-   **non-invasive**: WinPython lives entirely in its own directory, without any OS installation

-   **customizable**: add your missing packages, zip the WinPython directory and give it to your students

-   **do your own version**: a winpython-creator [kit](https://sourceforge.net/projects/winpython/files/WinPython_Source/Do_It_Yourself/) is made available for you

---

Portable or not, the choice is yours!

WinPython is a portable application, so the user should not expect any integration into Windows explorer during [installation](https://github.com/winpython/winpython/wiki/Installation). However, the [WinPython Control Panel](https://github.com/winpython/winpython/wiki/Winpython-Control-Panel) allows to "register" your distribution to Windows.

---

Registering your WinPython installation will:

-   associate file extensions `.py`, `.pyc` and `.pyo` to Python interpreter

-   register Python icons in Windows explorer

-   add context menu entries `Edit with IDLE` and `Edit with Spyder` for `.py` files

-   register WinPython as a standard Python distribution (standard Python Windows installers will see WinPython in Windows registry)

That is exactly what the official Python installer would do to your machine: in other words, you can have it both ways!

(*) For recent WinPython, Windows 8..10 users may have to install missing system DLL [Microsoft Visual C++ Redistributable for Visual Studio 2017..2019](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads) (vc_redist_x86.exe for WinPython 32bit, vc_redist_x64.exe for Winpython 64bit)

(*) For best Winpython 2018-01 and later experience, it is recommended to have Winpython base directory path smaller than 37 characters. example: C:\Users\xxxxxxxx\Downloads\WinPython

(**) Since WinPython 2019-02, all installers are just 7zip auto-extracts.

---
