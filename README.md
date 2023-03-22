# file2py
File to python code
Usage: 
```sh
converter filename.ext
```
```python
from filename_ext import data as myfile
contents = myfile.read()
original = None
with open("filename.ext", "rb"): 
  original = f.read()
print(original == contents) # True
```
