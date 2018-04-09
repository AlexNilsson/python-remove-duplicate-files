# removedupes
Remove duplicate files from a directory, fast

Files will be compared by size,
then by first (1024) chunk hash,
then by full hash

## Install
```
pip install removedupes
```

## Format
```python
from removedupes import removeDuplicates

removeDuplicates(directory)
```
