### Code for checking code quality using flake8

****************************************************************

#### On normal python script

Sample output for file code_quality/flake_script.py is saved as flake_script.txt 

```

$ flake8 path_to_file/folder

```

For saving results in a file named flake8_src.txt use

```
$ flake8 path_to_file/folder > flake8_src.txt

```

#### On normal python script

Sample output for file code_quality/flake_notebook.ipynb is saved as flake_notebook.txt 

```
$ nbqa flake8 path_to_file/folder
```


For saving results in a file named flake8_nb.txt use

```
$ nbqa flake8 path_to_file/folder > flake8_nb.txt

```

### Code formatting for beautiful indentation using black

****************************************************************\

Black indents code, remove extra whitespace and in general beautify code. All changes would be done inside the original code file itself. You can use git diff to check difference in code.

#### On normal python script


```

$ black path_to_file/folder

```

#### On normal python script


```
$ nbqa black path_to_file/folder

```

