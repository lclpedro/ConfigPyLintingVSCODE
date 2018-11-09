## Work Space Settings for Project.

* ${workspaceFolder} - Reference Project Folder
* "python.linting.pylintPath" - Select Python Env.

### For Windows

```
{
    "python.linting.pylintPath":"${workspaceFolder}\\env\\Scripts\\python",
    "python.linting.pep8Args": ["--ignore=E303"]
}
```

### For Linux

```
{
    "python.linting.pylintPath":"${workspaceFolder}/env/bin/python",
    "python.linting.pep8Args": ["--ignore=E303"],
}
```



Reference Font: https://code.visualstudio.com/docs/python/linting
