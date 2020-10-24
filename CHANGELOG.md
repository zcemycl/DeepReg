# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this project
adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

Here we write upgrading notes for brands. It's a team effort to make them as
straightforward as possible.

### Added

- Added option to change kernel size and a kernel type for LNCC image similarity loss.
- Added visualization tool for generating gifs from model outputs.
- Added log_root argument for training and prediction to customize the log file
  location.
- Added environment.yml file for Conda environment creation.
- Added Dockerfile.
- Added documentation about using UCL cluster with DeepReg.

### Changed

- Updated instruction on Conda environment creation.
- Updated TensorFlow version to 2.3.1.
- Updated the issue and pull-request templates to fix some
- Updated the pre-trained models in MR brain demo.
- Updated pre-commit hooks version.
- Updated references in JOSS paper to address reviewers' comments.

### Fixed

- Fixed tensor comparison in unit tests and impacted tests.
- Removed normalization of DDF/DVF when saving in Nifti formats.
- Fixed invalid link in the quick start page.

## [0.1.0b1] - 2020-09-01

Initial beta release.