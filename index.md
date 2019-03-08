---
layout: default
title: Home
description: "This is the homebrew's tap for the stable versions of the OSGeo geospatial toolset."
permalink: /
---

# Welcomed to the Homebrew OSGeo Page for documentation.

------

First, and foremost, please read below.

We are currently doing reforms in the tap trying to improve and make it easier to use it. Our main aim is to generate a QGIS formula that will install a complete QGIS with all the standard plugging, plus some additions, without the need by the end user to build it in their local machine.

Not to mention that we are running into some trouble at the moment and we are probably going to make you run in some too. We apologize for all the problems and we hope in the following weeks everything go to normal.

**Build Status**: [![CircleCI](https://circleci.com/gh/OSGeo/homebrew-osgeo4mac.svg?style=svg)](https://circleci.com/gh/OSGeo/homebrew-osgeo4mac)

This is the [homebrew's][homebrew] tap for the **stable** versions of the [OSGeo][osgeo] geospatial toolset. Right now our main focus is to provide and up-to-date [QGIS][qgis] formulae easy to install to the end user. The tap includes formulae that may not be specifically
from an OSGeo project, but do extend the toolset's functionality

## How do I install these formulae?

Just `brew tap osgeo/osgeo4mac` and then `brew install <formula>`. Easy, isn't it?

You can also install via URL:

```shell
$ brew install https://raw.githubusercontent.com/OSGeo/homebrew-osgeo4mac/master/Formula/<formula>.rb
```

## Docs

Run `brew help`, `man brew`, or check the Homebrew [documentation][].

[homebrew]:http://brew.sh
[taps]:https://github.com/Homebrew/homebrew-versions
[documentation]:https://github.com/Homebrew/brew/tree/master/docs#readme
[osgeo]: https://www.osgeo.org
[qgis]: https://www.qgis.org
[homebrew-core]: https://github.com/Homebrew/homebrew-core
[taps-docs]: https://docs.brew.sh/Taps
