# Twisted-Wheel-problem -Solution
The process here describes the steps to correct the wheel error while installing scrapy

## Problem Statement

### While installing the scrapy in system using
```
$ py -m pip install scrapy
```  
#### Differs per system



The error displayed is, 
```
"Failed building wheel for twisted"
```


## Solution

Get to command prompt on windows
### 1. Check your python version
```
$ py -V
````
Results depends on your python version.
Mine is :
```
Python 3.6.3
```

### 2. Download .whl file from [here](https://www.lfd.uci.edu/~gohlke/pythonlibs/#twisted).
check Twisted section,

#### Select version as per your system specs and cp36 for python version 3.6 / or cp35 for python 3.5 and else so on.

 ### 3. After downloading get to command prompt and install .whl file to pip
 ```
 $ py -m pip install Path_of_file
 ```
 
 ### After installation you can run your pip command to install scrapy
