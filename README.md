# Docker-Cheat-Sheet
[Setup](#Setup).
[Linux](#Linux).
[Window](#Window).


## Setup
### Linux
Run commandline: 
```sh
curl -sSL https://get.docker.com/ | sh
```
### Window
Link to download Docker: https://desktop.docker.com/win/stable/Docker%20Desktop%20Installer.exe .
Instructions: Reference https://viblo.asia/p/cai-dat-docker-tren-windows-10-3Q75w6gelWb .

## Container
### Lifecycle
Creates a container but does not start it
```sh
docker create
```
Allows the container to be renamed
```sh
docker rename
```
Creates and starts a container in one operation
```sh
docker run
```
Deletes a container
```sh
docker rm
```
updates a container's resource limits
```sh
docker update
```
