---
name: Tide
version: "1.2"
major: 1
minor: 2
description: A Tiled Interactive DisplayWall Environment
updated: 17/12/16
homepage: https://github.com/BlueBrain/Tide
repository: https://github.com/BlueBrain/Tide.git
issuesurl: https://github.com/BlueBrain/Tide/issues
packageurl: 
license: BSD
maturity: EP
maintainers: Blue Brain Project (bbp-open-source@googlegroups.com)
contributors: Raphael Dumusc
readmetype: text/x-markdown
---
# Tide

Welcome to Tide, a software for Tiled Interactive DisplayWall Environments
providing multi-user touch interaction for collaborations.
[See Tide in action](https://www.youtube.com/watch?v=wATHwvRFGz0)

## Features

Tide provides the following features:
* Interactively view, present and collaborate on media such as high-resolution
  images and movies.
* Receive and interact with content streamed from remote sources such as
  laptops / desktops or high-performance remote visualization machines using the
  [Deflect library](https://github.com/BlueBrain/Deflect.git).

## Usage

Run 'tide' from the bin folder to launch the application. By default it launches
three wall processes in a horizonal layout. Content can be opened from the
control user interface or by interacting with touchpoints that are received via
the TUIO protocol on port 1701. Click the rocket icon on the left control bar
to browse for contents and applications.

For more information see the
[UserGuide](http://bluebrain.github.io/Tide-1.2/user_guide.html).

## Building from Source

```
  git clone https://github.com/BlueBrain/Tide.git
  mkdir Tide/build
  cd Tide/build
  cmake -GNinja ..
  ninja
```

For more information see
[Building Tide](http://bluebrain.github.io/Tide-1.2/building.html).

## Documentation

The documentation is available at
[bluebrain.github.io](http://bluebrain.github.io/Tide-1.2)

