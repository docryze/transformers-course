### for macos with x86
```shell
poetry env use 3.12.0

poetry add torch@2.2.2

poetry add "numpy@<2"

poetry add transformers

```


### for clean
```
poetry lock --no-cache --regenerate
```
