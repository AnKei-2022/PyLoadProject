# PyLoadProject
A simple installer of the program. Many probably know that it is possible to convert .py files to .exe, but what if the project includes not only modules and python files used.

```
pip install plp
```
First you need to have a Zip folder with your finished project to copy. Import the module, specify the parameters in the pyload function.

```python
import plp


plp.pyload(
    "MyProgram", # project name
    "MyProgram.zip", # 
    "C:\\Program Files\\MyProgram\\MyProgram.exe"
)

```

## How does it work?
All your files need to be compressed into a ZIP file, then this file is copied and embedded in Python code. When you run the program, a ZIP file is created on your PC and extracted with your files.
