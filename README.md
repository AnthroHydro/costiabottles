# costiabottles

See the [wiki](https://github.com/AnthroHydro/costiabottles/wiki) for installation instructions.

Example code for use as an import:

```python
from bottledetector import BottleDetector

model = BottleDetector()
model.track(path='demo.mp4')
```
Type `python bottledetector.py --help` for command line usage and list of arguments.

Alternatively, in Python after importing the BottleDetector module, call `help(BottleDetector)` for class documentation.

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
