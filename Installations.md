# Building and Installing Software in Linux

> Many software packages for UNIX and LINUX systems come as compressed archieves of source code files.
 - archived (.tar)
 - compressed(.gz)
 
 To untar or unzip the package files 
 ```
tar xzvf filename
 ```
 For bzip(.bz2)
 ```
 bzip2 -cd filename | tar xvf
 ```
 
>>  Check the `README.md` or`INSTALL` file included in the software archive for specific instructions and install in the directory specified by the packer.
 - Prefered directory for new packages is  ``usr/local/bin ``
 - Sometimes it requires directory like /opt then create the directory as root and add it to the PATH environment variable.
 

 


 

 



