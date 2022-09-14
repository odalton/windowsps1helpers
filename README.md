# windowsps1helpers

## On Windows PowerShell says "execution of scripts is disabled on this system."

or 

```
some ps1 cannot be loaded because running scripts is disabled 
on this system. For more information, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170.
```


### Open PowerShell and run:

```
Set-ExecutionPolicy -ExecutionPolicy Unrestricted
```
