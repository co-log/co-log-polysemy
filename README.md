# co-log-polysemy

![Co-logo](https://user-images.githubusercontent.com/8126674/80955687-92f21a80-8df7-11ea-90d3-422dafdc8391.png)

[![GitHub CI](https://github.com/kowainik/co-log/workflows/CI/badge.svg)](https://github.com/kowainik/co-log/actions)
[![Hackage][hk-img-ps]][hk-ps]
[![MPL-2.0 license](https://img.shields.io/badge/license-MPL--2.0-blue.svg)](https://github.com/kowainik/co-log/blob/main/LICENSE)

`co-log-polysemy` package is a implementation of the 
[co-log-core](http://hackage.haskell.org/package/co-log-core) logging based on 
the [polysemy](http://hackage.haskell.org/package/polysemy) extensible 
effects library.

## Goals

We created the `co-log-polysemy` project in pursuit of the following goals:

## Features

## How to use

`co-log-polysemy` is compatible with the GHC compiler
versions starting from `8.4.4` upto `9.0.1`.

In order to start using `co-log-polysemy` in your project, you
will need to set it up with the these easy steps:

1. Add the dependency on `co-log-polysemy` in your project's
   `.cabal` file. For this, you should modify the `build-depends`
   section by adding the name of this library. After the adjustment,
   this section could look like this:

   ```haskell
   build-depends: base >= 4.11 && < 4.16
                , co-log-polysemy ^>= 0.0.1.3
   ```

2. To use the module add the import:

   ```haskell
   import Colog.Polysemy
   ```

## Comparison to other libraries

## Acknowledgement


