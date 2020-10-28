## Docker test

### Building image
docker build -t=woosyume/hello-world .

### Running image
#### General
docker run -it woosyume/hello-world

#### With entrypoint
docker run -it --entrypoint=/bin/sh woosyume/hello-world
