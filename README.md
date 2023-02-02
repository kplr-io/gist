# gist
replace spaces in files and dies
```
find . -depth -name "* *" -execdir rename 's/. /./g' "{}" \;
```
