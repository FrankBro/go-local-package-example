
```
> go run .\exe1
exe1\main.go:5:2: cannot find package "go-local-package-example" in any of:
        C:\Go\src\go-local-package-example (from $GOROOT)
        C:\Users\user\go\src\go-local-package-example (from $GOPATH)
> cd exe1
> go run .
build go-local-package-example/exe1: cannot load go-local-package-example: cannot find module providing package go-local-package-example
```