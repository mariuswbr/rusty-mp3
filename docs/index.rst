Rusty MP3 Player Documentation
===============================

Welcome to the Rusty MP3 Player documentation!

Overview
--------

Rusty MP3 is a simple MP3 player written in Rust for learning purposes.
This project aims to provide a basic understanding of:

* Audio file handling
* MP3 format parsing
* Audio playback in Rust
* Building Rust projects with Bazel

Getting Started
---------------

Building the Project
~~~~~~~~~~~~~~~~~~~~

This project uses Bazel as its build system. To build the project::

    bazel build //src:rusty-mp3

Running the Player
~~~~~~~~~~~~~~~~~~

To run the MP3 player::

    bazel run //src:rusty-mp3

Testing
~~~~~~~

To run the tests::

    bazel test //tests:all

Project Structure
-----------------

The project is organized as follows:

* ``src/`` - Source code for the MP3 player
* ``tests/`` - Integration and unit tests
* ``docs/`` - Project documentation in reStructuredText format

Future Enhancements
-------------------

Planned features include:

* MP3 file parsing
* Audio playback support
* Playlist management
* Command-line interface
* Configuration options

Contributing
------------

This is a learning project. Feel free to experiment and extend it!

License
-------

This project is for educational purposes.
