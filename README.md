# Help-in-my-code-
Help in my code has an error

Unhandled exception in listener callback
Traceback (most recent call last):
  File "C:\Users\Usuario\AppData\Local\Programs\Python\Python310\lib\site-packages\pynput\_util\__init__.py", line 228, in inner
    return f(self, *args, **kwargs)
  File "C:\Users\Usuario\AppData\Local\Programs\Python\Python310\lib\site-packages\pynput\keyboard\_win32.py", line 287, in _process
    self.on_press(key)
  File "C:\Users\Usuario\AppData\Local\Programs\Python\Python310\lib\site-packages\pynput\_util\__init__.py", line 144, in inner
    if f(*args) is False:
  File "c:\Users\Usuario\Desktop\prueba.py", line 76, in on_press
    write_file(keys,count)
  File "c:\Users\Usuario\Desktop\prueba.py", line 122, in write_file
    f.write(k)
ValueError: I/O operation on closed file.
Traceback (most recent call last):
  File "c:\Users\Usuario\Desktop\prueba.py", line 140, in <module>
    main()
  File "c:\Users\Usuario\Desktop\prueba.py", line 136, in main
    listener.join()
  File "C:\Users\Usuario\AppData\Local\Programs\Python\Python310\lib\site-packages\pynput\_util\__init__.py", line 276, in join
    six.reraise(exc_type, exc_value, exc_traceback)
  File "C:\Users\Usuario\AppData\Local\Programs\Python\Python310\lib\site-packages\six.py", line 718, in reraise
    raise value.with_traceback(tb)
  File "C:\Users\Usuario\AppData\Local\Programs\Python\Python310\lib\site-packages\pynput\_util\__init__.py", line 228, in inner
    return f(self, *args, **kwargs)
  File "C:\Users\Usuario\AppData\Local\Programs\Python\Python310\lib\site-packages\pynput\keyboard\_win32.py", line 287, in _process
    self.on_press(key)
  File "C:\Users\Usuario\AppData\Local\Programs\Python\Python310\lib\site-packages\pynput\_util\__init__.py", line 144, in inner
    if f(*args) is False:
  File "c:\Users\Usuario\Desktop\prueba.py", line 76, in on_press
    write_file(keys,count)
  File "c:\Users\Usuario\Desktop\prueba.py", line 122, in write_file
    f.write(k)
ValueError: I/O operation on closed file.
  
please help
  
