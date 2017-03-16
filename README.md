# Notes on various topics

#### Installing KDevelop 5.x.x from sources
If after compilation, KDevelop crashes and the output contains the following record:
```
Could not initialize GLX
```
export this variable
```
export KDEV_DISABLE_PLUGINS=KDevWelcomePage
```
and try to run again.
