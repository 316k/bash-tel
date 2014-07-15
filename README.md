bash-tel
========

A simple bash-based phone numbers manager

## Installation

Just include the `tel` file in your script directory (or any directory included your bash PATH).

## Usage

    Usage : tel - Shows the phone number file in `less`
            tel [--edit|-e] - Edit the phone number file in the default text editor
            tel [name] - Shows [name]'s phone numbers

## Configuration

The phone numbers are stored as plain-text in /.local/share/bash-tel
To change the path of this file, modify that line in the script

    file=~/.local/share/bash-tel
