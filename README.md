# LibTorch builds for Apple Silicon

This repository contains a single GitHub Action workflow that can be used to trigger
LibTorch builds for the a specified branch.

Built libraries are uploaded to the [Releases page](https://github.com/mlverse/libtorch-mac-m1/releases)
and can be easily downloaded.

Build are using cmake instructions available [here](https://github.com/pytorch/pytorch/blob/master/docs/libtorch.rst),
with an extra `-DUSE_MPS=ON` CMake flag.