### Modules:

First, head over to the modules/ directory, inside of there are sub directories based on the Penetration Testing Execution Standard (PTES) phases. Go into those phases and look at the different modules. As soon as you add a new one, for example testing.py, it will automatically be imported next time you launch PTF. There are a few key components when looking at a module that must be completed.

```
cd ~/ptf/modules && ls
```

Choose the sub directory

```
cd <sub directory>
```

Below is a sample module

```
AUTHOR=""

DESCRIPTION=""

INSTALL_TYPE="GIT"

REPOSITORY_LOCATION="url"

INSTALL_LOCATION="name"

DEBIAN="python, pip"

BYPASS_UPDATE="NO"

AFTER_COMMANDS="cd {INSTALL_LOCATION},x"

LAUNCHER=""

```
