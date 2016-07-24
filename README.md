# dici - a better python dictionary

**dici** is an easier to use implementation of a dictionary that makes
accessing members easier to write. The main thing **dici** allows is
for the user to access the dictionary keys not by indexing them but by
using dot notation. This makes writing things like:

```python
if lookup['foo']['bar']:
    pass
```

a bit easier like so:

```python
if lookup.foo.bar:
    pass
```

# coming soon

 - [ ] automatic testing through travis
 - [ ] coveralls coverage badge in README

# development

This was pieced together quickly in order to satisfy a need I had in another
library and I'll continue to develop on it if others find it useful so open a 
pull request or an issue if you find this of any use.
