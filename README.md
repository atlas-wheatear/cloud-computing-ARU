# Cloud Computing SID 1800209

## Installing

On a workstation with docker and docker-compose installed, run:

`git clone --recurse-submodules https://github.com/emoulsdale/docker-compose-test.git`

## Running

### Server

Run the command:

`docker-compose up --build`

### Client

On a workstation on which the
[Godot Engine Editor version 3.3](https://godotengine.org/download/windows)
has been installed:

- Open the project
- Change the run arguments in the editor
(Project/Project Settings/Application/Editor/Main Run Args) and provide a string
of the address then the port of the server (default **7070**), separated by a
space
