### 1. How To Check if a File or Directory Exists?


See if file exists:

**Method1**

`import os`
`os.path.exists()` 

 Calling os.path.exists() will return True for files and directories if they exist.
 
`os.path.isfile()`

If you want to ensure that a given path points to a file and not to a directory, you can use the os.path.isfile() function.
With both functions it’s important to keep in mind that they will only check if a file exists—and not if the program actually has access to it. If verifying access is important then you should consider simply opening the file while looking out for an I/O exception (IOError) to be raised. Alternatively, you can use the `os.access()` function in the standard library to check whether a file exists and is accessible at the same time. This would be more similar to using the `os.path.exists()` function for checking if a file exists.


**Method2**

`open()`
`try..except(IOError/FileNotFoundError)`

**Method3**

`pathlib.Path.exists()` and 
`pathlib.Path.is_file()`

For video, see [here](https://www.youtube.com/watch?v=DvZTW5g82pQ&__s=ce4x51vmize8shbt6e7u).


