# Simple linux project homework

### Installation
To install the project you need to run following comamnds inside the project folder:

```
aclocal
```

```
autoconf
```

```
automake --add-missing
```

```
./configure
```

Run
```
make
```
to simply compile the project or 
```
sudo make install
```
to compile project and copy compiled files to /usr/local/bin and /usr/local/include

To clean the intermediate files and remove installed files run
```
sudo make clean-all
```
