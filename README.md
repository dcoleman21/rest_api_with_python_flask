# rest_api_with_python_flask

## Overview

This repository is practicing the implementation of creating and API using python and flask. [This](https://medium.com/duomly-blockchain-online-courses/how-to-create-a-simple-rest-api-with-python-and-flask-in-5-minutes-94bb88f74a23) tutorial is what I went off of. Upon completion of your `setup`, follow the tutorial.

## Table of Contents
  - [Setup](#setup)
  - [Notes](#notes)
  - [Postman](#postman)


### Setup
These setup instructions are for Mac OS X.

### Checking and installing the latest version of python

This sample requires the latest version of `Python 3`. Which at the time of this was `3.9.5`.

To check what version you currently have type `python` in your terminal. You should see something like the following:

```
WARNING: Python 2.7 is not recommended.
This version is included in macOS for compatibility with legacy software.
Future versions of macOS will not include Python 2.7.
Instead, it is recommended that you transition to using 'python3' from within Terminal.

Python 2.7.16 (default, Jun  5 2020, 22:59:21)
[GCC 4.2.1 Compatible Apple LLVM 11.0.3 (clang-1103.0.29.20) (-macos10.15-objc- on darwin
Type "help", "copyright", "credits" or "license" for more information.
```

To exit the python shell type `exit()` or `^D`.

To download the latest version of Python go [here](https://www.python.org/) and follow these steps:
1. click on `downloads`
2. click on the latest download for Mas OS X
3. Once the `pkg` file has downloaded, click on it
4. Follow the prompts given by your computer

To verify that the download worked correctly, go back to your terminal and type in `python3`. You should see something like the following:

```
Python 3.9.5 (v3.9.5:0a7dcbdb13, May  3 2021, 13:17:02)
[Clang 6.0 (clang-600.0.57)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
```

To exit the python shell type `exit()` or `^D`.

### Installing Flask

Now that you have `python3` installed you will enter the follwing commands to install `Flask`:

In your terminal type `pip3 intall Flask`

### Installing Flask_RESTful

In your terminal type `pip3 install Flask-RESTful`

## Notes:

In the tutorial, upon completion of creating logic for the methods, you will be asked to run the script so that we can check to see that our endpoints and logic is working correctly. 

To do this, type `python3 api.py` (api.py is the name of the file that our scripts live).

You should see something like this:

```
* Serving Flask app 'api' (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: on
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 743-530-580
 ```
 
 You will see that we are running on port `http://127.0.0.1:5000/` in this example. 
 
 In order to check that our request are functioning properly we will be using `Postman`. If you do not have `Postman` already, you can download it [here](https://www.postman.com/product/rest-client/).
 
 If you are following along with the [tutorial](https://medium.com/duomly-blockchain-online-courses/how-to-create-a-simple-rest-api-with-python-and-flask-in-5-minutes-94bb88f74a23) then you will copy the url from your terminal to paste into Postman.
 
 If you want to see a sample of the requests proceed to the section titled `Postman` below.
 
 
 ### Postman
 
 I have included a `Python-Flask Practice.postman_collection.json` file in this repo that has samples of the created requests. You can import that file into `Postman` to see these by following these steps:
 1. In `Postman`, click on the `import` button located in the top left corner next to the `+ New` button.
 2. In the pop up window, click on `Code repository NEW`.
 3. Then you will click on the `Connect to GitHub` button.
 4. This will redirect you away from Postman to authenticate GitHub.
 5. You will see a green `Authorize Postman` button. Once you have selected what you want access to, click that button.
 6. You will be prompted to enter your GitHub password.
 7. A pop up window will appear in Postman and you will need to select the repository that you want to import the file to and click `continue`.
