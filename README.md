# pyxdelta
Python interface for xdelta.

## Installation
`pip install pyxdelta`

## Usage
```
import pyxdelta

pyxdelta.run("source.bin", "target.bin", "patch.xdelta")

pyxdelta.decode("source.bin", "patch.xdelta", "target.bin")
```
