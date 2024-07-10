# Python Modules Overview (Update 07/2024)

This repository provides an overview of some common and useful Python modules I use, categorized by their functionality. This list is not exhaustive but serves as a starting point for exploring various Python libraries.

## Table of Contents

- [Web Development and Networking](#web-development-and-networking)
- [Data Processing and Analysis](#data-processing-and-analysis)
- [Databases](#databases)
- [File and Directory Manipulation](#file-and-directory-manipulation)
- [Text Processing and Regular Expressions](#text-processing-and-regular-expressions)
- [Time and Date Management](#time-and-date-management)
- [Multithreading and Concurrency](#multithreading-and-concurrency)
- [Machine Learning](#machine-learning)
- [Scientific Computing](#scientific-computing)
- [Image Processing](#image-processing)
- [GUI Development](#gui-development)
- [Debugging and Testing](#debugging-and-testing)
- [Security and Encryption](#security-and-encryption)
- [Compression and Archiving](#compression-and-archiving)
- [Miscellaneous](#miscellaneous)

## Web Development and Networking

- `requests`: A module for making HTTP requests, simpler and more convenient than `http.client`.
- `urllib`: A module for working with URLs and performing HTTP requests.
- `BeautifulSoup`: A module for parsing and extracting information from HTML and XML files.
- `flask`: A lightweight web framework for Python.
- `django`: A comprehensive web framework for Python.
- `socket`: A module for working with network connections and sockets.
- `aiohttp`: Asynchronous HTTP client/server framework for asyncio and Python.
- `xmlrpc`: A module for working with XML-RPC (standard module).
- `socketserver`: A module for creating network servers (standard module).
- `select`: A module for waiting for I/O completion (standard module).
- `selectors`: A module for high-level I/O multiplexing (standard module).

## Data Processing and Analysis

- `numpy`: A module for numerical computations and array operations.
- `pandas`: A module for data manipulation and analysis, particularly for tabular data.
- `matplotlib`: A module for creating charts and visualizations.
- `scipy`: A module for scientific and technical computing.
- `scikit-learn`: A module for machine learning and data analysis.
- `scapy`: Able to forge or decode packets of a wide number of protocols.
- `stem`: A controller library that allows applications to interact with Tor.
- `seaborn`: A Python data visualization library based on matplotlib that provides a high-level interface for drawing attractive statistical graphics.
- `array`: A module for efficient array storage (standard module).
- `csv`: A module for reading and writing CSV files (standard module).
- `json`: A module for parsing JSON (standard module).
- `xml.etree.ElementTree`: A module for parsing XML (standard module).
- `plistlib`: A module for generating and parsing Mac OS X .plist files (standard module).
- `_json`: A module for JSON encoder and decoder (standard module).

## Databases

- `sqlite3`: A module for working with SQLite databases.
- `MySQLdb` (Python 2) / `mysql-connector-python` (Python 3): A module for working with MySQL databases. Please use Python 3!
- `psycopg2`: A module for working with PostgreSQL databases.
- `SQLAlchemy`: A module for working with SQL databases using an ORM (Object-Relational Mapping) approach.
- `redis-py`: The Redis Python Client.
- `dbm`: A module for simple database-like operations (standard module).
- `shelve`: A module for persistent storage of arbitrary Python objects (standard module).

## File and Directory Manipulation

- `os`: A module for operating system interactions, e.g., working with files and directories.
- `shutil`: A module for copying, moving, and deleting files and directories.
- `glob`: A module for searching for files matching specific patterns.
- `pathlib`: A module for working with file paths in a more object-oriented way.
- `watchdog`: Python API library and shell utilities to monitor file system events.
- `fnmatch`: A module for Unix filename pattern matching (standard module).
- `tempfile`: A module for creating temporary files and directories (standard module).
- `zipfile`: A module for reading and writing ZIP files (standard module).
- `tarfile`: A module for reading and writing tar archive files (standard module).
- `filecmp`: A module for comparing files and directories (standard module).
- `fileinput`: A module for iterating over lines from multiple input streams (standard module).
- `mimetypes`: A module for mapping filename extensions to MIME types (standard module).
- `mailbox`: A module for reading and writing mailboxes (standard module).
- `mailcap`: A module for handling mailcap files (standard module).
- `mmap`: A module for memory-mapped file support (standard module).

## Text Processing and Regular Expressions

- `re`: A module for working with regular expressions.
- `string`: A module with additional functions for working with strings.
- `NLTK`: A module for natural language processing, including text processing and analysis.
- `textblob`: Simplified text processing for Python, including noun phrase extraction, part-of-speech tagging, sentiment analysis, classification, translation, and more.
- `difflib`: A module for comparing sequences (standard module).
- `codecs`: A module for encoding and decoding data (standard module).
- `html.parser`: A module for parsing HTML (standard module).
- `pydoc`: A module for generating Python documentation (standard module).
- `quopri`: A module for encoding and decoding MIME quoted-printable data (standard module).
- `gettext`: A module for internationalization and localization services (standard module).

## Time and Date Management

- `time`: A module for working with time and date functions.
- `datetime`: A module for working with date and time.
- `arrow`: A module for working with dates and times in a more human-readable way, with timezone support.
- `pytz`: A Python library that allows accurate and cross-platform timezone calculations using Python.
- `calendar`: A module for working with calendars (standard module).
- `zoneinfo`: A module for IANA time zone support (standard module).
- `dateutil`: A module for powerful extensions to the standard datetime module (standard module).

## Multithreading and Concurrency

- `threading`: A module for working with threads.
- `multiprocessing`: A module for working with processes and parallel programming.
- `asyncio`: A module for asynchronous programming with coroutines.
- `gevent`: A coroutine-based Python networking library that uses greenlet to provide a high-level synchronous API on top of the libev event loop.
- `concurrent.futures`: A module for running concurrent tasks using thread or process pools (standard module).
- `queue`: A module for creating synchronized queues (standard module).

## Machine Learning

- `scikit-learn`: A module for machine learning and data analysis.
- `tensorflow`: An end-to-end open source platform for machine learning.
- `keras`: A high-level neural networks API, written in Python and capable of running on top of TensorFlow.
- `pytorch`: An open source machine learning library based on the Torch library.
- `lightgbm`: A fast, distributed, high-performance gradient boosting framework based on decision tree algorithms, used for ranking, classification, and many other machine learning tasks.

## Scientific Computing

- `numpy`: A module for numerical computations and array operations.
- `scipy`: A module for scientific and technical computing.
- `sympy`: A module for symbolic mathematics.
- `astropy`: A community-developed core Python package for Astronomy.
- `math`: A module for mathematical functions (standard module).
- `cmath`: A module for complex number mathematics (standard module).
- `statistics`: A module for statistical functions (standard module).

## Image Processing

- `PIL / Pillow`: Modules for opening, manipulating, and saving many different image file formats.
- `opencv-python`: A module for real-time computer vision.
- `scikit-image`: A module for image processing.
- `mahotas`: A library of fast computer vision algorithms (all implemented in C++) operating over numpy arrays.
- `binascii`: A module for converting between binary and ASCII (standard module).

## GUI Development

- `tkinter`: A module for creating graphical user interfaces (GUI) with Tk.
- `PyQt`: A module for creating GUI applications with Qt.
- `wxPython`: A module for creating cross-platform GUI applications with wxWidgets.
- `kivy`: An open source Python library for developing multitouch application software with a natural user interface (NUI).
- `curses`: A module for creating text-based user interfaces (standard module).
- `idlelib`: A module for the IDLE development environment (standard module).

## Debugging and Testing

- `pdb`: A module for the Python debugger (standard module).
- `faulthandler`: A module for handling faults in Python programs (standard module).
- `trace`: A module for tracing program execution (standard module).
- `unittest`: A module for writing and running tests (standard module).
- `timeit`: A module for measuring execution time of small code snippets (standard module).
- `py_compile`: A module for compiling Python source files (standard module).

## Security and Encryption

- `ssl`: A module for working with Secure Sockets Layer (SSL) protocol (standard module).
- `secrets`: A module for generating cryptographically strong random numbers suitable for managing data such as passwords, account authentication, security tokens, and related secrets (standard module).

## Compression and Archiving

- `gzip`: A module for reading and writing GNU zip files (standard module).
- `zipfile`: A module for reading and writing ZIP files (standard module).
- `tarfile`: A module for reading and writing tar archive files (standard module).
- `zlib`: A module for compression using the zlib library (standard module).

## Miscellaneous

- `__future__`: A module that helps in writing code that is compatible with future versions of Python (standard module).
- `_tracemalloc`: A module to trace memory allocations (standard module).
- `_uuid`: A module for generating universally unique identifiers (standard module).
- `graphlib`: A module for working with graph-like structures (standard module).
- `_weakref`: A module for creating weak references to objects (standard module).
- `_weakrefset`: A module for sets of weak references (standard module).
- `_heapq`: A module for heap queue algorithms (standard module).
- `_io`: A module for input/output operations (standard module).
- `runpy`: A module for locating and running Python modules (standard module).
- `sunau`: A module for working with Sun AU files (standard module).
- `webbrowser`: A module for controlling web browsers (standard module).
- `sched`: A module for event scheduling (standard module).
- `_warnings`: A module for managing warning messages (standard module).

Feel free to contribute and update this list as you discover new modules or gain experience with the existing ones. IT WILL HELP BEGINNERS.

## Your Support
If you find this project useful and want to support it, there are several ways to do so:

- If you find the paper helpful, please ⭐ it on GitHub. This helps make the project more visible and reach more people.
- Become a Follower: If you're interested in updates and future improvements, please follow my GitHub account. This way you'll always stay up-to-date.
- Learn more about my work: I invite you to check out all of my work on GitHub and visit my developer site https://volkansah.github.io. Here you will find detailed information about me and my projects.
- Share the project: If you know someone who could benefit from this project, please share it. The more people who can use it, the better.
**If you appreciate my work and would like to support it, please visit my [GitHub Sponsor page](https://github.com/sponsors/volkansah). Any type of support is warmly welcomed and helps me to further improve and expand my work.**

Thank you for your support! ❤️
** S. Volkan Kücükbudak**

### License
This project is licensed under the MIT - see the [LICENSE](LICENSE) file for details.
