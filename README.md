
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


For more information and a detailed story you can read [What is A Golang Linter And How To Use It?](https://rezakhademix.medium.com/what-is-a-golang-linter-and-how-to-use-it-1bffc0bd8062).

## Used Linters

List of used linters inside config file:

- [revive]
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
- [bodyclose]
- [exportloopref]
- [ineffassign]
- [nolintlint]
- [stylecheck]
- [unconvert]


[//]: # (links)
[asasalint]: <https://github.com/alingse/asasalint>
[cyclop]: <https://github.com/bkielbasa/cyclop>
[depguard]: <https://github.com/OpenPeeDeeP/depguard>
[dupl]: <https://github.com/golangci/golangci-lint/blob/master/pkg/golinters/dupl.go>
[errcheck]: <https://github.com/kisielk/errcheck>
[errorlint]: <https://github.com/polyfloyd/go-errorlint>
[exhaustive]: <https://github.com/nishanths/exhaustive>
[goconst]: <https://github.com/jgautheron/goconst>
[gocritic]: <https://github.com/go-critic/go-critic>
[godox]: <https://golangci-lint.run/usage/linters/#godox>
[gocyclo]: <https://github.com/fzipp/gocyclo>
[gomnd]: <https://github.com/tommy-muehle/go-mnd>
[gosimple]: <https://honnef.co/go/tools/simple>
[gosec]: <https://github.com/securego/gosec>
[govet]: <https://pkg.go.dev/cmd/vet>
[misspell]: <https://github.com/qax-os/goreporter>
[musttag]: <https://github.com/go-simpler/musttag>
[perfsprint]: <https://github.com/catenacyber/perfsprint>
[prealloc]: <https://github.com/alexkohler/prealloc>
[predeclared]: <https://github.com/nishanths/predeclared>
[usestdlibvars]: <https://github.com/sashamelentyev/usestdlibvars>
[whitespace]: <https://github.com/bombsimon/wsl>
[wsl]: <https://github.com/bombsimon/wsl>
[revive]: <https://github.com/mgechev/revive>
[bodyclose]: <https://github.com/bodyclose>
[exportloopref]: <https://github.com/exportloopref>
[ineffassign]: <https://github.com/ineffassign>
[nolintlint]: <https://github.com/ashanbrown/nolintlint>
[stylecheck]: <https://github.com/golangci/golangci-lint/blob/master/pkg/golinters/stylecheck.go>
[unconvert]: <https://github.com/mdempsky/unconvert>
