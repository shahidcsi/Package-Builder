# Package-Builder

This repository contains build and utility scripts used for continuous integration builds on the Travis CI environment. It also contains a very useful Makefile for building Swift packages that our team develops.

Feature of this repository:

1.  If you need a specific verison of Swift to be used.  Place that version in a .swift-version file in the root level of our repository
2.  If you need a special swift compile line, other than the normal swift build.  Need to place a .swift-build-linux or .swift-build-macOS in the root
    level of your repository.  Please make these files executable so they can be executed.

