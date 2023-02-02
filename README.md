# gist
replace spaces in files and folders recursively
```
find . -depth -name "* *" -execdir rename 's/. /./g' "{}" \;
find . -depth -name "* *" -execdir rename 's/findthis/replabythis/g' "{}" \;

```
