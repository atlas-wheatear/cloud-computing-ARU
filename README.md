# Cloud Computing SID 1800209

## Introduction

This is a proof-of-concept for the containerisation of the godot engine, alongside the flite TTS system, in a microservices architecture using docker.

## Text-to-Speech

The sequence diagram for the TTS subsystem is  below:

![TTS_API](https://user-images.githubusercontent.com/40772658/122076487-d2f54080-cdf2-11eb-9368-ef83e8fe2ee6.png)


## Installing

On a workstation with docker and docker-compose installed, run:

`git clone --recurse-submodules https://github.com/emoulsdale/cloud-computing-ARU.git`

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
