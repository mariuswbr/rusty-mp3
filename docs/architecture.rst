Architecture
============

This document describes the architecture of the Rusty MP3 player.

Components
----------

The MP3 player is designed with the following components:

Main Application
~~~~~~~~~~~~~~~~

The main application entry point handles:

* Command-line argument parsing
* Application initialization
* Coordinating between different components

MP3 Parser (Future)
~~~~~~~~~~~~~~~~~~~

The MP3 parser component will be responsible for:

* Reading MP3 file headers
* Parsing MP3 frames
* Extracting audio data and metadata

Audio Player (Future)
~~~~~~~~~~~~~~~~~~~~~

The audio player component will handle:

* Audio output device management
* Audio buffer management
* Playback control (play, pause, stop, seek)

Design Principles
-----------------

The project follows these design principles:

* **Modularity**: Components are separated into distinct modules
* **Testability**: Code is written to be easily testable
* **Learning-focused**: Code is documented and easy to understand
* **Bazel build**: Modern build system with clear dependencies

Technology Stack
----------------

* **Language**: Rust
* **Build System**: Bazel (using Bazelmod/bzlmod)
* **Audio Libraries**: TBD (possibly rodio or cpal)
* **Testing**: Rust's built-in test framework

Build System
------------

The project uses Bazel with Bazelmod (MODULE.bazel) for build configuration.
This provides:

* Reproducible builds
* Clear dependency management
* Fast incremental builds
* Cross-platform support
