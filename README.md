### Prerequisite

#### Install conan

Install conan using python 2.7, as with 3.x the conan recipes for boost have problems due to escaped strings bubbling to the shell script.

```
mkvirtualenv conan2 -p/usr/local/bin/python2
pip install conan
workon conan2
```

#### Add repo

```
conan remote add bincrafters https://api.bintray.com/conan/bincrafters/public-conan
```

