## 2.1 - List of Modules Modified/Affected

We will be modifing the *w* module. The *w* command relies on a few other modules which we may need to modify as well. These modules inclue *history, who, uptime,* and *ps*. The main module modified will be *w.c* though because the bulk of our project will be making sure that the *w* command displays information more clearly than it does now. We are not necessarily changing the information that is displays, but instead are changing how the information is displayed. The module contains print statements which we will modify and reformat. 

## 2.2 - List of New Modules Produced

We will not be producing any new modules for this project.

## 2.3 - Class Diagram of Affected Modules

<img width="337" alt="Screen Shot 2019-04-11 at 6 48 43 PM" src="https://user-images.githubusercontent.com/23061329/56006718-e6447880-5c8a-11e9-91f7-dcccd102b15b.png">

## 2.4 - Explanation of All Command Line Options Implemented
Command line options:

*w* with no other commands following will output the header and relevent information in a clear table 

*-h*: Removes the header from the output (defeats the purpose of our entire project but we're keeping it so there's another command line option)
