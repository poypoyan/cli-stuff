# Greed Terminal Game in Python

This is an implementation of [Greed](https://www.youtube.com/watch?v=XQHq6tdxylk) in Python 3. Tested on Linux and Windows. At least Python 3.6 is required because of **f-strings**. Controls are as follows:

```
q w e
 \|/ 
a-+-d
 /|\ 
z x c
```
However, this is editable through `CONTROL` variable. Also, press &lt;space&gt; to quit, but this is also editable through `QUITKEY` variable.

Required third-party libraries are **numpy** (for multidimensional array) and **readchar** (for getting keypress). To install:
```console
pip install numpy readchar
```
