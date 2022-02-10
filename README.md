# Introduction

*git4everyone* aims to be a GUI front-end for **git**, that anyone with no background on software development can easily use.

# Explicit goals

- Easy of use for the non developer user.
- Front-end for the most important git tools (https://git-scm.com/docs).
- Easy to maintain and contribute.
- Clean interface.

# Project structure

- ***README.md*** - (This file) It’s an introduction to the project.
- [***.gitignore***](./.gitignore) - Special git file to specify which files and folders must be ignored when updating a project.
- [***LICENSE.md***](./LICENSE.md) - File that specify source code’s terms of use.
- ***src/*** - Contains the main source code files
  - ***[main.py](./src/main.py)*** - Main source code file. The whole program starts running this file.
  - ***modules/*** - Folder where *python modules* are stored.
- ***tests/*** - Contains small programs to test the source code.
- ***doc/*** - Contains documentation files.
  - ***[INSTALL.md](./doc/INSTALL.md)*** - Instructions to install this program from source.
  - ***[FAQ.md](./doc/FAQ.md)*** - Frequetly asked questions.
  - ***[CONTRIBUTE.md](./doc/CONTRIBUTE.md)*** - On this file there is all the information you need to contribute to the project.
  - [***ROADMAP.md***](./doc/ROADMAP.md) - Roadmap of the project. What we’ve done and what we’ll do next.
  - ***[NEWS.md](./doc/NEWS.md)*** - Announcements about the project that might interest users.
  - ***[CHANGELOG.md](./doc/CHANGELOG.md)*** - Detailed chronology of changes that the project has suffered until this date.
- ***ide/*** - Contains IDE specific files
- ***media/*** - Contains media files that are used in documentation and other files

# TODO

- [ ] Choose license
- [ ] Set IDE to work
- [ ] Redo .gitignore
- [ ] Make some tests
- [ ] Design GUI
- [ ] Write docs
