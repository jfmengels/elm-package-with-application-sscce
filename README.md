This is an SSCCE for https://github.com/elm/compiler/issues/2256

You can run

```bash
elm make src/Main.elm
```

which will cause the compiler to output an `index.html` file, even though the project is marked as an Elm package project.