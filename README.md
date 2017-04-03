# Python-libraries-windows
Some steps for people new to python- install libraries
<br>

---

Think of python libraries as R's packages. We are using many of the functions/ methods in these libraries. I recall when I first get in touch with python, I am lost as it does not have an all in one IDE like Rstudio where we can get packages ... etc 
<br>
There are 2 methods to install libraries. Lets assume you are using Anacanda3 to install your python 
<br> 
https://www.continuum.io/downloads
<br>
<br>
## **Method 1** 
1) Open anaconda prompt (if your window user is not the admin, right-click start as admin) 
2) pip install XXXX (for the libraries, you can do a search to find what is the command in their github) 
<br> 
e.g pip install fuzzywuzzy (for fuzzy library ) 
    pip install pandas 
    
## **Method 2** 
If for some reason, you are getting an error that the library cannot be installed or wheel not found, we will have to use this method. 
<br> 
1) Go to: http://www.lfd.uci.edu/~gohlke/pythonlibs/ 
2) Locate the library wheel (.whl) file you need. Download the version you need (if you are unsure, you can just try each) 
3) Put the .whl file on your desktop 
4) Open cmd (if your window user is not the admin, right-click start as admin)
5) type :cd to your desktop directory 
<br>
e.g >  cd C\User\Germ\Desktop
6) type: pip install wheelfilename.whl 
<br>
> pip install XXXXXXXXXXXXXXXXX.whl 
<br>
for the wheel file name, just copy the entire file name and right click paste 
