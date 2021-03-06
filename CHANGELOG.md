# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).
This project is **not** using [Semantic Versioning](https://semver.org/spec/v2.0.0.html)
(I still going to use same-looking versioning with three numbers separated with dots, 
just to highlight big changes when changing MAJOR or MINOR numbers, but is not used for 
backward compatibility)

## [0.1.1] - Future release
Supervised training improvements and engine strength estimation

## [0.1.0] - Future release
Documentation release

### Added

- Documentation generator is added. Now documentation will be stored under /docs dir and 
online version at (https://example.com).
- Installation with docker is now in the docs
- Supervised NN training tutorial is now in the docs

## [0.0.1] - 2022.05.27
Minimal NN chess engine

### Added

- This is the first changelog of the Dinora project. The engine is in the early stages of development:
it can play some chess, but the engine is weak
- The standard variant of chess is supported as well as a standard clock with or without increment
 (3+0, 3+2, 5+0, 5+5)
- You can train supervised NN by providing PGN. But it is a blind experience: no graphs or logs, 
and most parameters are default e.g. learning rate.
- To play with the engine you can install any UCI-compatible GUI and follow readme installation.

[0.0.1]: https://github.com/DinoraChess/dinora/releases/tag/v0.0.1
