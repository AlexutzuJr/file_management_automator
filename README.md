# Project Overview

In this project, we aim to automate the organization of files into categorized directories based on their types. The process begins by monitoring a source directory for changes, then moving files to their respective destination directories according to their file extensions. The automation script will handle image, video, audio, and document files. Our goal is to streamline the file organization process, reducing manual effort.

**Project Steps**
* Monitor source directory
* Classify files
* Move files
* Handle file name conflicts
* Log activities

# Local Setup

## Installation

To follow this project, we will need to install the following locally:

* Python 
* Python packages
    * watchdog
    * logging
    * shutil
    * os

 # Usage
 This script continuously monitors the specified source directory and moves files to designated folders based on their extensions, ensuring a well-organized file system.
