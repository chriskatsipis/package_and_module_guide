## Guide on Package and module making

### Making the package and modules
##### 1. Create a folder (repository) in the root repository of your project
This folder will serve as the package
##### 2. Create a python file inside the folder and name it "\_\_init\_\_.py"
This file converts the folder it is located in to a package
##### 3. Create a python file inside the folder
This file will serve as a module of the package

### Importing the package and modules
##### 1. Importing the package in another file
To import the package we use "`import packagename`
This will import any 
Any code inside the "\_\_init\_\_.py" file will execute at this time
##### 2. Importing a module in another file
To import a module we use `from packagename import modulename`
The module is accessed with "modulename"
Any code inside the "modulename\.py" file will execute at this time
##### 3. Importing a module as attribute
Although not common, we can also import a module by reffering to it as an attribute of the package with `import packagename.modulename`
The module is accessed with "packagename.modulename" and not with "modulename"

### Objects in modules
##### 1. Calling a module's functions
We can call a module's function with `modulename.objectname` 

