# TDD Docker
* don't 🚢💩
* Tools: goss or serverspec. (goss.rocks)

## goss
* testes and validates system config 
* docker goss -> dgoss validates container config
* dgoss starts a container and runs the tests it. Same syntax as `docker run`
* `goss add command goss` -> add a test for the goss command to the goss yml. 
* You can `goss add` a lot of stuff and then clean that up in the yml
* `goss validate` -> run test
* With mounting the docker socket (`/var/run/docker.sock`) you can have a goss container that starts other containers and tests them
