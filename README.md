# Govtech-todo

This is a GovTech assignment to create a script/application that scans a specific directory and returns all the files that contains the word "TODO".\

Application is a console programs written in C# using Microsoft Visual Studio 2019. Main implementation can be found in the Program.cs file.

## Build Instruction
Application is written using Visual Studio 2019 running in .NetCore 3.1.
Open the Assignment.sln in Visual Studio 2019 to compile and run

There is a self contain version in the executable folder built for win x64 environment

## Usage
There is a Config.txt that contains 2 keys. Path and Ignore.

Path - Specifies the root directory in which you want to start scanning the files from.\
Ignore - Specifies the extensions of files which you do not want to check. You can specify multiple extension type and separate them by semi-colons.

Eg. \
﻿Path=E:\\DotNetProjects\\SM3\\ClientBackend\
Ignore=.svn;Logs;bin;obj

Note: The Assignment.exe and the Config.txt need to be residing in the same folder in order to execute.
