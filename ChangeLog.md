# Overview

Fixed perf issues and few more things.

## Changes

Changed docker install to install via code-server the recommended way
changed docker install for ZSH to be installed the recommended way
changed extension install to use code-server so they are registered
changed code-server launch to use its config instead of command line args
changed boot scripts for readability
changed boot dependency order for stability
changed default files path
changed reset to use correct path

## Removed

removed boot time removal of code-server extensions

## Added

added auto dark mode!
added a common paths file for all boot scripts to eliminate path issues
added extra code-server config options to disable some unwanted things
added code to convert the os log setting to code-server so logging is increased for debugging
added a workspace to help cleanup the view to only HA files and not the local server
added a folder for code-server config files, to distinguish from ha config
added a new init script to run user-added scripts at boot to enhance functionality
added a tasks file for common tasks be in vs code.
added a script in custom boot to allow tasks to be code-backed for extra convenience.
added powershell

## TODO

get code to auto-launch terminal to motd
check install packages for needed