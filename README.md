# Dockerized Go Server
Full CRUD GoLang server running in a docker container connected to a postgres database.

# Running the Server
To start the server, run `make start`. 
This will build the Go files and run the resulting executable in a docker container. 
The docker portion is contained in `docker-compose.yml` and `server/Dockerfile`.

## Available Make Commands

```bash
build-local                    Builds a local executable of the project via "go build"
help                           Help documentation
start-local                    Builds and starts a local version of the program
start                          Builds and starts the project in a docker container
```
