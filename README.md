
## A Golang Linter Configuration file for [golangci-lint](https://golangci-lint.run/)

This is an opinionated configuration file for golangci-lint.
Before using this config file you need to do two below steps:

## 1) install golangci-lint
    
    
    # first way: binary will be $(go env GOPATH)/bin/golangci-lint

    curl -sSfL https://raw.githubusercontent.com/golangci/golangci-lint/master/install.sh | sh -s -- -b $(go env GOPATH)/bin latest


    # alternative way: install it into user ./bin/
    
    curl -sSfL https://raw.githubusercontent.com/golangci/golangci-lint/master/install.sh | sh -s latest


    # docker way:
    
    docker run --rm -v $(pwd):/app -v ~/.cache/golangci-lint/v1.55.2:/root/.cache -w /app golangci/golangci-lint:latest golangci-lint run -v
    
    
## 2) put `.golangci.yml` in your project root directory


For more information and a detailed story you can read this story [What is A Golang Linter And How To Use It?](https://golangci-lint.run/).

## Used Linters

List of used linter inside config file:

- [asasalint]
- [cyclop]
- [depguard]
- [dupl]
- [errcheck]
- [errorlint]
- [exhaustive]
- [goconst]
- [gocritic]
- [godox]
- [gocyclo]
- [gomnd]
- [gosimple]
- [gosec]
- [govet]
- [misspell]
- [musttag]
- [perfsprint]
- [prealloc]
- [predeclared]
- [usestdlibvars]
- [whitespace]
- [wsl]
- [revive]
- [bodyclose]
- [exportloopref]
- [ineffassign]
- [nolintlint]
- [stylecheck]
- [unconvert]


[//]: # (links)
[asasalint]: <https://github.com/asasalint>
[cyclop]: <https://github.com/cyclop>
[depguard]: <https://github.com/depguard>
[dupl]: <https://github.com/dupl>
[errcheck]: <https://github.com/errcheck>
[errorlint]: <https://github.com/errorlint>
[exhaustive]: <https://github.com/exhaustive>
[goconst]: <https://github.com/goconst>
[gocritic]: <https://github.com/gocritic>
[godox]: <https://github.com/godox>
[gocyclo]: <https://github.com/gocyclo>
[gomnd]: <https://github.com/gomnd>
[gosimple]: <https://github.com/gosimple>
[gosec]: <https://github.com/gosec>
[govet]: <https://github.com/govet>
[misspell]: <https://github.com/misspell>
[musttag]: <https://github.com/musttag>
[perfsprint]: <https://github.com/perfsprint>
[prealloc]: <https://github.com/prealloc>
[predeclared]: <https://github.com/predeclared>
[usestdlibvars]: <https://github.com/usestdlibvars>
[whitespace]: <https://github.com/whitespace>
[wsl]: <https://github.com/wsl>
[revive]: <https://github.com/mgechev/revive>
[bodyclose]: <https://github.com/bodyclose>
[exportloopref]: <https://github.com/exportloopref>
[ineffassign]: <https://github.com/ineffassign>
[nolintlint]: <https://github.com/nolintlint>
[stylecheck]: <https://github.com/stylecheck>
[unconvert]: <https://github.com/unconvert>
