# CarSaver Homebrew Tap

This repository contains Homebrew (AKA, Brew) "formulae" for CarSaver.

For the moment, this repository consists of a single formula: FFmpeg

## Installation

If the formula has already been installed from homebrew-core, you will first need to uninstall it:

    brew uninstall ffmpeg

Then look at the formula source and choose which options you want — the options shown below are only examples. Then install via:

    brew tap CarSaver/tap
    brew tap-pin CarSaver/tap
    brew install ffmpeg

Alternatively, you can install the formula by naming it explicitly:

    brew install CarSaver/tap/ffmpeg
