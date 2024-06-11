# The project can be found [here](https://hub.docker.com/repository/docker/joacims/tiralabra/general)
## Instructions to run:

### create the following directories:

input/

output/compressed/

output/decompressed/

Then run the app with:

`docker run -it -v"$(pwd)/input:/usr/src/app/src/input" -v"$(pwd)/output:/usr/src/app/src/output" tiralabra`
