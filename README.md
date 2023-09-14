# gits_backend
The main repository for the GITS backend.

## Cloning

This repository uses git submodules to be able to retrieve the repositories of all services into this repository when cloning. To do this, do the following:

1. As with any repo, clone it using `git clone https://github.com/IT-Rex-Platform/gits_backend.git`
2. Move into the repository (`cd gits_backend`)
3. Initialize the submodules using `git submodule init`
4. Pull the submodules using `git submodule update`

## Deployment

The local deployment of the backend is done in two steps:
* start docker (desktop)
* execute the .bat or .sh file found under ./gits_backend/compose.bat using `compose.bat up --build` (builds everytime) or `compose.bat up`. 
