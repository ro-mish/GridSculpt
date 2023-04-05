# gridsculpt

Designed to be used in notebooks!

## How to use

1. Install from pypi

```
pip install gridsculpt
```

2. Import into a notebook instance

```
import gridsculpt.gridsculpt as gs
```

3. Plug in a photo of a 2x2 grid

```
fig, axs = gs.GridSculpt("[filename]").plot((10,5),{})
```

4. Use as if using matplotlib!
