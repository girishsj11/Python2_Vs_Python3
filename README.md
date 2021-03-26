## Python2 Versus Python3

### Differece between Python 2 & Python 3 Versions

1. Version & usage :

   a. Python_2 :
   
      - Python 2 made code development process easier than earlier versions. It implemented technical details of Python Enhancement Proposal (PEP). Python 2.7 (last version in 2.x ) is no longer under development and in 2020 will be discontinued.
     
   b. Python_3 :
   
      - On December 2008, Python released version 3.0. This version was mainly released to fix problems which exist in Python 2. The nature of these change is such that Python 3 was incompatible with Python 2. It is backward incompatible Some features of Python 3 have been backported to Python 2.x versions to make the migration process easy in Python 3.
      
2. Key Difference

   - Python 3 syntax is simpler and easily understandable whereas Python 2 syntax is comparatively difficult to understand.
   - Python 3 default storing of strings is Unicode whereas Python 2 stores need to define Unicode string value with "u."
   - Python 3 value of variables never changes whereas in Python 2 value of the global variable will be changed while using it inside for-loop.
   - Python 3 exceptions should be enclosed in parenthesis while Python 2 exceptions should be enclosed in notations.
   - Python 3 rules of ordering comparisons are simplified whereas Python 2 rules of ordering comparison are complex.
   - Python 3 offers Range() function to perform iterations whereas, In Python 2, the xrange() is used for iterations.
   - If your development team is working on a project that depends on specific third-party libraries or software which you are not able to port to Python 3, then Python 2 is the only option available for you.
   
3. Primary difference in Tabluar format

   | Basis of comparison | Python 3 | Python 2 |
   | --- | --- | --- |
   | Release Date | 2008 | 2000 |
   | Function print | print ("hello") | print "hello" |
   | Division of Integers | Whenever two integers are divided, you get a float value. | When two integers are divided, you always provide integer value. |
   | Unicode | In Python 3, default storing of strings is Unicode. | To store Unicode string value, you require to define them with "u". |
   | Syntax | The syntax is simpler and easily understandable. | The syntax of Python 2 was comparatively difficult to understand. |
   | Iteration | The new Range() function introduced to perform iterations. | In Python 2, the xrange() is used for iterations. |
   | Exceptions | It should be enclosed in parenthesis. | It should be enclosed in notations. |
   | Leak of variables | The value of variables never changes. | The value of the global variable will change while using it inside for-loop. |
   | Library | Many recent developers are creating libraries which you can only use with Python 3. | Many older libraries created for Python 2 is not forward-compatible. |
   


### Differece between List & Tuples 

- List is mutable object & tuples are immutable objects
- We can only use tuples can be a set of keys in a dictionary , as because tuples are immutable & only immutable objects are hashed in dictionary.
- Tuples are defined by enclosing the elements in parentheses (()) , lists are enclosed with square brackets([]).
- Sometimes you don’t want data to be modified. If the values in the collection are meant to remain constant for the life of the program, using a tuple instead of a list guards against accidental modification.
- There is slight difference in indexing speed of list and tuple because tuples uses fewer pointers when indexing than that of list. Becuase of fewer pointers, acess mechanism is generally faster in tuples than lists.

  - List & Tuple Speed Comparison
  
    > Example 1
         
         #tuple creation
         from datetime import datetime
         start_time = datetime.now()
         t = (x for x in range(10000))
         end_time = datetime.now()
         print('Duration: {}'.format(end_time - start_time))
         
         
         #list creation
         from datetime import datetime
         start_time = datetime.now()
         l = [x for x in range(10000)]
         end_time = datetime.now()
         print('Duration: {}'.format(end_time - start_time))
  
- watch out the link : https://stackoverflow.com/questions/3340539/why-is-tuple-faster-than-list-in-python 

### List of Python Script File-Extensions

   Python scripts may have one of several file extensions. Each file extension has a special meaning and purpose.

1. *.py - Regular scripts

2. *.py3 - (rarely used) Python3 script; Python3 scripts usually end with "*.py" not "*.py3"

3. *.pyc - compiled script (Bytecode)

4. *.pyo - optimized pyc bytecode file (As of Python3.5, Python will only use pyc rather than pyo and pyc)

5. *.pyw - Python script for Windows that is executed with pythonw.exe

6. *.pyx - Cython src to be converted to C/C++

7. *.pyd - Python script made as a Windows DLL

8. *.pxd - Cython script which is equivalent to a C/C++ header

9. *.pyi - MyPy stub

10. *.pyi - Stub file (PEP 484)

11. *.pyz - Python script archive (PEP 441); this is a script containing compressed Python scripts (ZIP) in binary form after the standard Python script header

12. *.pywz - Python script archive for MS-Windows (PEP 441); this is a script containing compressed Python scripts (ZIP) in binary form after the standard Python script header

13. *.py[cod] - wildcard notation in ".gitignore" that means the file may be "*.pyc", "*.pyo", or "*.pyd"

14. *.rpy - RPython script or a Python script containing application or framework-specific features

15. *.pyde - Python script used by Processing (https://processing.org/)

16. *.pyp - Py4D Python Plugin

17. *.pyt - Python declaration file

18. *.xpy - Unknown

19. *.ipynb - Jupyter Notebook file
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
