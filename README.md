# Evolver scripting language for Sublime Text 3
Partial support of Ken Brakke's Evolver language for Sublime Text 3 (build 4126).
* syntax highlight
* build command
* some completions
* shortcut for commenting

## Resources
Evolver programmers may find the following repositories useful:
* [@elmisback/python-evolver](https://github.com/elmisback/python-evolver)
* [@kashif/evolver](https://github.com/kashif/evolver)

### Useful snippet
To run an Evolver script from Python and write outputs to a text file:
```python
import os
evolver_path = "C:/Portable/Evolver/Evolver.exe"
filepath = "script.fe"
os.system(f"{evolver_path} -q -p8 \"{filepath}\" > evolver_log.txt")
```

## Disclaimer
The code in this repository was written for the purpose of my own work with Evolver and has not been tested further.
Therefore, it is provided as is, without any guarantees and could be greatly improved by someone who has experience with YAML.
The keywords were simply copy-pasted from the PDF documentation and adjusted along the way.
Comments and pull requests are welcome.

## Source
The Surface Evolver program along with its documentation can be found on [Ken Brakke's personal web page](http://facstaff.susqu.edu/brakke/evolver/evolver.html).
