
# `purescript-intmaps`

[![Build Status](https://travis-ci.org/tel/purescript-intmaps.svg?branch=master)](https://travis-ci.org/tel/purescript-intmaps)
[![Dependency Status](https://www.versioneye.com/user/projects/56981655af789b002e000b59/badge.svg?style=flat)](https://www.versioneye.com/user/projects/56981655af789b002e000b59)

Finite maps from integers to arbitrary values. Current implementation is a *big
endian Patricia tree* which is an efficient binary search tree on (positive)
integer keys.

## Prior Art

- Haskell’s `containers`,
  [Data.IntMap.Strict](https://hackage.haskell.org/package/containers-0.5.7.1/docs/Data-IntMap-Strict.html)
- Chris Okasaki and Andy Gill, ["Fast Mergeable Integer
  Maps"](http://citeseer.ist.psu.edu/okasaki98fast.html) Workshop on ML,
  September 1998, pages 77-86


