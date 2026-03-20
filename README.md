# Building

```ns
ns prepare -dev ./lib
ns pack -dev ./lib ./pack
ns build -dev ./src
```

If you want to build HTMX core by yourself you can do it with

```MoV
cd <path to htmx sources>
mov make .
mov pack htmx
```
