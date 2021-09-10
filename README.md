### Package for File Handling

**[DOCUMENTATION]**(https://filehandling.netlify.app/docs.html)


**Getting started**
```py
from EasyFileHandling.main import FileHandler

x = FileHandler('test.py', 'py')

print(x.get_file_content()) # This will print file content.

```
**Whats so special about package**


*This lets you use `os` module easily not all features but some of them.


**BETA**

*Howdy all, we have decided to add `AsyncFileHandler` for asynchronous python codes. Now you can do all those `append`, `write` and  `read` asynchronouly.* ***REMEMBER THIS IS A BETA***


*How do I use it?*


*Simply import this and get started.*


```py
from EasyFileHandling.beta.main import AsyncFileHandler
```


**Whats New?**

*Howdy, new version `1.4.0` just dropped. You all be thinking whats new `byte` and `json` support added. We have also added `type` hints. Let me show you a example how json handler works*


**JsonHandler**


```py
from EasyFileHandling.json import JsonHandler
my_obj = [
    {'Sad': 100}
]
x = JsonHandler('sad.json')
x.write_to_json(obj)
```


*If you are having any issues let us know [Here](https://github.com/ProjectsWithPython/FileHandling/issues).*



