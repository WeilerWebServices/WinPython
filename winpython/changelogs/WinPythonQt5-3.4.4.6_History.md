﻿## History of changes for WinPython 3.4.4.6Qt5

The following changes were made to WinPython distribution since version 3.4.4.5Qt5.

### Python packages

New packages:

  * [bleach](http://pypi.python.org/pypi/bleach) 1.5.0 (An easy whitelist-based HTML-sanitizing tool)
  * [chardet](http://pypi.python.org/pypi/chardet) 2.3.0 (Universal encoding detector for Python 2 and 3)
  * [fuzzywuzzy](http://pypi.python.org/pypi/fuzzywuzzy) 0.14.0 (Fuzzy string matching in python)
  * [imageio](http://pypi.python.org/pypi/imageio) 2.1.1 (Library for reading and writing a wide range of image, video, scientific, and volumetric data formats.)
  * [metakernel](http://pypi.python.org/pypi/metakernel) 0.18.2 (Metakernel for Jupyter)
  * [nbdime](http://pypi.python.org/pypi/nbdime) 0.1.2 (Tools for diffing and merging of Jupyter notebooks)
  * [octave_kernel](http://pypi.python.org/pypi/octave_kernel) 0.23.2 (A Jupyter kernel for Octave.)
  * [olefile](http://pypi.python.org/pypi/olefile) 0.44 (Python package to parse, read and write Microsoft OLE2 files)
  * [pandocfilters](http://pypi.python.org/pypi/pandocfilters) 1.4.1 (Utilities for writing pandoc filters in python)
  * [pexpect](http://pypi.python.org/pypi/pexpect) 4.2.1 (Pexpect allows easy control of interactive console applications.)
  * [ptyprocess](http://pypi.python.org/pypi/ptyprocess) 0.5.1 (Run a subprocess in a pseudo terminal)
  * [requests_ftp](http://pypi.python.org/pypi/requests_ftp) 0.3.1 (FTP Transport Adapter for Requests.)
  * [s3transfer](http://pypi.python.org/pypi/s3transfer) 0.1.10 (An Amazon S3 Transfer Manager)
  * [scikit_fuzzy](http://pypi.python.org/pypi/scikit_fuzzy) 0.3.dev0 (Fuzzy logic toolkit for SciPy)
  * [snakeviz](http://pypi.python.org/pypi/snakeviz) 0.4.1 (An in-browser Python profile viewer)
  * [sortedcollections](http://pypi.python.org/pypi/sortedcollections) 0.4.2 (Python Sorted Collections)
  * [sortedcontainers](http://pypi.python.org/pypi/sortedcontainers) 1.5.7 (Python Sorted Container Types: SortedList, SortedDict, and SortedSet)
  * [sounddevice](http://pypi.python.org/pypi/sounddevice) 0.3.6 (Play and Record Sound with Python)
  * [testpath](http://pypi.python.org/pypi/testpath) 0.3 (Test utilities for code working with files and commands)

Upgraded packages:

  * [altair](http://pypi.python.org/pypi/altair) 1.1.0.dev0 → 1.2.0 (High-level declarative visualization library for Python)
  * [astroid](http://pypi.python.org/pypi/astroid) 1.4.8 → 1.4.9 (Rebuild a new abstract syntax tree from Python's ast (required for pylint))
  * [backports_abc](http://pypi.python.org/pypi/backports_abc) 0.4 → 0.5 (A backport of recent additions to the 'collections.abc' module.)
  * [beautifulsoup4](http://pypi.python.org/pypi/beautifulsoup4) 4.5.1 → 4.5.3 (Screen-scraping library)
  * [bokeh](http://pypi.python.org/pypi/bokeh) 0.12.3 → 0.12.4 (Statistical and novel interactive HTML plots for Python)
  * [boto3](http://pypi.python.org/pypi/boto3) 1.3.1 → 1.4.1 (The AWS SDK for Python)
  * [cffi](http://pypi.python.org/pypi/cffi) 1.8.3 → 1.9.1 (Foreign Function Interface for Python calling C code.)
  * [click](http://pypi.python.org/pypi/click) 6.6 → 6.7 (A simple wrapper around optparse for powerful command line utilities.)
  * [cloudpickle](http://pypi.python.org/pypi/cloudpickle) 0.2.1 → 0.2.2 (Extended pickling support for Python objects)
  * [cvxopt](http://pypi.python.org/pypi/cvxopt) 1.1.7 → 1.1.9 (Convex optimization package)
  * [cx_freeze](http://cx-freeze.sourceforge.net) 4.3.4 → 5.0.1 (Deployment tool which converts Python scripts into stand-alone Windows executables (i.e. target machine does not require Python or any other library to be installed))
  * [cython](http://www.cython.org) 0.25.1 → 0.25.2 (Cython is a language that makes writing C extensions for the Python language as easy as Python)
  * [cytoolz](http://pypi.python.org/pypi/cytoolz) 0.8.0 → 0.8.2 (Cython implementation of Toolz: High performance functional utilities)
  * [dask](http://pypi.python.org/pypi/dask) 0.12.0 → 0.13.0 (Minimal task scheduling abstraction)
  * [decorator](http://pypi.python.org/pypi/decorator) 4.0.10 → 4.0.11 (Better living through Python with decorators)
  * [distributed](http://pypi.python.org/pypi/distributed) 1.14.0 → 1.15.2 (Distributed computing)
  * [docutils](http://docutils.sourceforge.net) 0.12 → 0.13.1 (Text processing system for processing plaintext documentation into useful formats, such as HTML or LaTeX (includes reStructuredText))
  * [flask](http://pypi.python.org/pypi/flask) 0.11.1 → 0.12 (A microframework based on Werkzeug, Jinja2 and good intentions)
  * [greenlet](http://pypi.python.org/pypi/greenlet) 0.4.10 → 0.4.11 (Lightweight in-process concurrent programming)
  * [holoviews](http://pypi.python.org/pypi/holoviews) 1.6.2 → 1.7.dev4 (Composable, declarative data structures for building complex visualizations easily.)
  * [html5lib](http://pypi.python.org/pypi/html5lib) 0.999999999 → 0.9999999 (HTML parser based on the WHATWG HTML specification)
  * [ipykernel](http://pypi.python.org/pypi/ipykernel) 4.5.0 → 4.5.2 (IPython Kernel for Jupyter)
  * [ipyparallel](http://pypi.python.org/pypi/ipyparallel) 5.2.0 → 6.0.0 (Interactive Parallel Computing with IPython)
  * [jinja2](http://pypi.python.org/pypi/jinja2) 2.8 → 2.9.4 (Sandboxed template engine (provides a Django-like non-XML syntax and compiles templates into executable python code))
  * [jupyter_core](http://pypi.python.org/pypi/jupyter_core) 4.2.0 → 4.2.1 (Jupyter core package. A base package on which Jupyter projects rely.)
  * [keras](http://pypi.python.org/pypi/keras) 1.1.1 → 1.2.1 (Theano-based Deep Learning library)
  * [llvmlite](http://pypi.python.org/pypi/llvmlite) 0.14.0 → 0.15.0 (lightweight wrapper around basic LLVM functionality)
  * [lxml](http://pypi.python.org/pypi/lxml) 3.6.4 → 3.7.2 (Powerful and Pythonic XML processing library combining libxml2/libxslt with the ElementTree API.)
  * [markupsafe](http://pypi.python.org/pypi/markupsafe) 0.23 → 1.0.dev0 (Implements a XML/HTML/XHTML Markup safe string for Python)
  * [matplotlib](http://pypi.python.org/pypi/matplotlib) 1.5.3 → 2.0.0 (2D plotting library (embeddable in GUIs created with PyQt))
  * [mccabe](http://pypi.python.org/pypi/mccabe) 0.5.2 → 0.5.3 (McCabe checker, plugin for flake8)
  * [mpld3](http://pypi.python.org/pypi/mpld3) 0.2 → 0.3 (D3 Viewer for Matplotlib)
  * [msgpack_python](http://pypi.python.org/pypi/msgpack_python) 0.4.7 → 0.4.8 (MessagePack (de)serializer.)
  * [nbconvert](http://pypi.python.org/pypi/nbconvert) 4.2.0 → 5.1.1 (Converting Jupyter Notebooks)
  * [nbformat](http://pypi.python.org/pypi/nbformat) 4.1.0 → 4.2.0 (The Jupyter Notebook format)
  * [nbsphinx](http://pypi.python.org/pypi/nbsphinx) 0.2.10 → 0.2.12 (Jupyter Notebook Tools for Sphinx)
  * [netcdf4](http://pypi.python.org/pypi/netcdf4) 1.2.4 → 1.2.7 (python/numpy interface to netCDF library (versions 3 and 4))
  * [nltk](http://pypi.python.org/pypi/nltk) 3.2.1 → 3.2.2 (The Natural Language Toolkit (NLTK) is a Python package for natural language processing.)
  * [notebook](http://pypi.python.org/pypi/notebook) 4.2.3 → 4.3.1 (# Jupyter Notebook)
  * [numba](http://pypi.python.org/pypi/numba) 0.29.0 → 0.30.1 (compiling Python code using LLVM)
  * [numdifftools](http://pypi.python.org/pypi/numdifftools) 0.9.17 → 0.9.20 (Solves automatic numerical differentiation problems in one or more variables.)
  * [numpy](http://numpy.scipy.org/) 1.11.2 → 1.11.3+mkl (NumPy: multidimensional array processing for numbers, strings, records and objects (SciPy''s core module))
  * [oct2py](http://pypi.python.org/pypi/oct2py) 3.5.9 → 3.8.1 (Python to GNU Octave bridge --> run m-files from python.)
  * [pandas](http://pypi.python.org/pypi/pandas) 0.19.1 → 0.19.2 (Powerful data structures for data analysis, time series and statistics)
  * [pandas_datareader](http://pypi.python.org/pypi/pandas_datareader) 0.2.1 → 0.3.0.post0 (Data readers extracted from the pandas codebase,should be compatible with recent pandas versions)
  * [param](http://pypi.python.org/pypi/param) 1.4.1 → 1.4.2 (Declarative Python programming using Parameters.)
  * [partd](http://pypi.python.org/pypi/partd) 0.3.6 → 0.3.7 (Appendable key-value storage)
  * [pillow](http://pypi.python.org/pypi/pillow) 3.4.1 → 4.0.0 (Python Imaging Library (fork))
  * [pip](http://pypi.python.org/pypi/pip) 8.1.2 → 9.0.1 (A tool for installing and managing Python packages)
  * [pkginfo](http://pypi.python.org/pypi/pkginfo) 1.3.2 → 1.4.1 (Query metadatdata from sdists / bdists / installed packages.)
  * [prompt_toolkit](http://pypi.python.org/pypi/prompt_toolkit) 1.0.8 → 1.0.9 (Library for building powerful interactive command lines in Python)
  * [psutil](http://code.google.com/p/psutil) 4.4.2 → 5.0.1 (Provides an interface for retrieving information on all running processes and system utilization (CPU, disk, memory, network) in a portable way)
  * [py](http://pypi.python.org/pypi/py) 1.4.31 → 1.4.32 (library with cross-python path, ini-parsing, io, code, log facilities)
  * [pyaudio](http://pypi.python.org/pypi/pyaudio) 0.2.9 → 0.2.10 (Bindings for PortAudio v19, the cross-platform audio input/output stream library.)
  * [pycodestyle](http://pypi.python.org/pypi/pycodestyle) 2.1.0 → 2.2.0 (Python style guide checker)
  * [pyflakes](http://pypi.python.org/pypi/pyflakes) 1.3.0 → 1.5.0 (passive checker of Python programs)
  * [pyflux](http://pypi.python.org/pypi/pyflux) 0.4.0 → 0.4.14 (Open source time series library for Python)
  * [pylint](http://www.logilab.org/project/pylint) 1.6.4 → 1.6.5 (Logilab code analysis module: analyzes Python source code looking for bugs and signs of poor quality)
  * [pymc3](http://pypi.python.org/pypi/pymc3) 3.0rc2 → 3.0 (Markov Chain Monte Carlo sampling toolkit.)
  * [pymongo](http://pypi.python.org/pypi/pymongo) 3.3.0 → 3.4.0 (Python driver for MongoDB <http://www.mongodb.org>)
  * [pyodbc](http://pypi.python.org/pypi/pyodbc) 3.0.10 → 4.0.3 (DB API Module for ODBC)
  * [pyqtgraph](http://pypi.python.org/pypi/pyqtgraph) 0.9.10 → 0.10.0 (Scientific Graphics and GUI Library for Python)
  * [pyserial](http://pypi.python.org/pypi/pyserial) 3.1.1 → 3.2.1 (Library encapsulating the access for the serial port)
  * [pytest](http://pypi.python.org/pypi/pytest) 3.0.3 → 3.0.5 (pytest: simple powerful testing with Python)
  * [python_dateutil](http://labix.org/python-dateutil) 2.5.3 → 2.6.0 (Powerful extensions to the standard datetime module)
  * [pythonnet](http://pypi.python.org/pypi/pythonnet) 2.2.0.dev1 → 2.2.1 (.Net and Mono integration for Python)
  * [pytz](http://pypi.python.org/pypi/pytz) 2016.7 → 2016.10 (World Timezone Definitions for Python)
  * [pyzmq](http://pypi.python.org/pypi/pyzmq) 15.4.0 → 16.0.2 (Lightweight and super-fast messaging based on ZeroMQ library (required for IPython Qt console))
  * [qtawesome](http://pypi.python.org/pypi/qtawesome) 0.3.3 → 0.4.3 (FontAwesome icons in PyQt and PySide applications)
  * [qtpy](http://pypi.python.org/pypi/qtpy) 1.1.2 → 1.2.1 (Provides an abstraction layer on top of the various Qt bindings (PyQt5, PyQt4 and PySide) and additional custom QWidgets.)
  * [requests](http://pypi.python.org/pypi/requests) 2.11.1 → 2.12.5 (Requests is an Apache2 Licensed HTTP library, written in Python, for human beings.)
  * [requests_file](http://pypi.python.org/pypi/requests_file) 1.4 → 1.4.1 (File transport adapter for Requests)
  * [rx](http://pypi.python.org/pypi/rx) 1.5.3 → 1.5.7 (Reactive Extensions (Rx) for Python)
  * [s3fs](http://pypi.python.org/pypi/s3fs) 0.0.7 → 0.0.8 (Convenient Filesystem interface over S3)
  * [scikit_learn](http://pypi.python.org/pypi/scikit_learn) 0.18 → 0.18.1 (A set of Python modules for machine learning and data mining)
  * [setuptools](http://pypi.python.org/pypi/setuptools) 28.7.1 → 33.1.1 (Download, build, install, upgrade, and uninstall Python packages - easily)
  * [sphinx](http://pypi.python.org/pypi/sphinx) 1.4.8 → 1.5.1 (Tool for generating documentation which uses reStructuredText as its markup language)
  * [spyder](http://pypi.python.org/pypi/spyder) 3.1.0.dev0 → 3.1.2 (Scientific PYthon Development EnviRonment: designed for interactive computing and data visualisation with a simple and intuitive user interface)
  * [sqlalchemy](http://www.sqlalchemy.org) 1.1.3 → 1.1.5 (SQL Toolkit and Object Relational Mapper)
  * [toolz](http://pypi.python.org/pypi/toolz) 0.8.0 → 0.8.2 (List processing tools and functional utilities)
  * [tqdm](http://pypi.python.org/pypi/tqdm) 4.8.4 → 4.11.1 (A Simple Python Progress Meter)
  * [werkzeug](http://pypi.python.org/pypi/werkzeug) 0.11.11 → 0.11.15 (The Swiss Army knife of Python web development)
  * [winpython](http://winpython.github.io/) 1.7.20161101 → 1.7.20170128 (WinPython distribution tools, including WPPM (package manager))
  * [xarray](http://pypi.python.org/pypi/xarray) 0.8.2 → 0.9.0 (N-D labeled arrays and datasets in Python)
  * [xlsxwriter](http://pypi.python.org/pypi/xlsxwriter) 0.9.3 → 0.9.5 (A Python module for creating Excel XLSX files.)
  * [zarr](http://pypi.python.org/pypi/zarr) 2.1.3 → 2.1.4 (A minimal implementation of chunked, compressed, N-dimensional arrays for Python.)
  * [zict](http://pypi.python.org/pypi/zict) 0.1.0 → 0.1.1 (Mutable mapping tools)

Removed packages:

  * [webencodings](http://pypi.python.org/pypi/webencodings) 0.5 (Character encoding aliases for legacy web content)

* * *
