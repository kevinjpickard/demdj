[![Coverage Status](https://coveralls.io/repos/github/kevinjpickard/DemDJ/badge.svg?branch=master)](https://coveralls.io/github/kevinjpickard/demdj?branch=master)
[![Build Status](https://travis-ci.org/kevinjpickard/demdj.svg?branch=master)](https://travis-ci.org/kevinjpickard/demdj)
[![Windows Build status](https://ci.appveyor.com/api/projects/status/5grajhscy718wc02?svg=true)](https://ci.appveyor.com/project/kevinjpickard/demdj)
# DemDJ
DemDJ: Music By the People, For the People

## Dependencies
This repo uses [glide](https://github.com/Masterminds/glide) to manage dependencies. To install:
```
curl https://glide.sh/get | sh
```
Then, to install all dependencies:
```
glide install
```

## Testing
Test are run using the [Ginko Testing Framework](https://github.com/onsi/ginkgo). To run all tests, run:
```
go get -u github.com/onsi/ginkgo/ginkgo  # installs the ginkgo CLI
go get -u github.com/onsi/gomega/...     # fetches the matcher library
ginko
```
or 
```
go test
```
When writing tests, please use the [Gomega Matcher Library](https://github.com/onsi/gomega) ([Gomega documentation](http://onsi.github.io/gomega/#provided-matchers))
