# ceia - JITeich

Los submodules están agregados de forma que trackeen la branch `main` siempre. Esto está en `.gitmodules`:
```git
[submodule "subm"]
    ...
    branch = main
```
Para agregar un nuevo submodulo y que automáticamente levante esta opción:
```shell
git submodule add -b main <url> path/to/submodule
```
