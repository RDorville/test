<link href="style.css" rel="stylesheet"></link>

> Trying to embed a stylesheet in Markdown


Anaconda

## Anaconda

A virtual environment manager for Python

* Installation: [anaconda site]()
* Cheat Sheet: 
* Simple How-to: Cory Schafer [Anaconda]() Youtube 

### Summary

```
(base) $									# anaconda's base installation
(base) $ python								# shows running in anaconda
Python 3.7.6 (default, Jan  8 2020, 19:59:22) 
[GCC 7.3.0] :: Anaconda, Inc. on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 

```

|Command               | Explanation                                     |
|----------------------|-------------------------------------------------|
| conda --help         | produces list of commands |
| conda list           | shows packages already installed in environment |
| conda install <package>  | installs a package, may be other than .py |
| pip                  | alternatively can still use pip |
| conda create --name <envN> <at-least-one-package> | create new environment, must specify at least one package |
| conda create --name <envN> python=2.7 | create new environment, using 2.7 |
| conda activate <envN>  | activate environment <envN> |
| conda deactivate | deactivate current environment |
| conda env list | list environments |
| conda remove --name <envN> --all | remove environment <envN> and all packages |

Let's see how this appears on GitHub!



