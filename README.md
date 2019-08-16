# dotnet-core-nightly-nodejs
dotnet core nightly docker image with latest nodejs

- mcr.microsoft.com/dotnet/core-nightly/sdk:3.0-disco with Ubuntu 19.04
- nodejs from https://deb.nodesource.com/setup_10.x
- tzdata with LocalDateTime to Europe/Berlin
- nodejs libraries pre-installed globally: node-sass core-js core-js-pure date-fns


### Build
    docker build -t dotnet-core-sdk .

### Run bash
    docker run -it dotnet-core-sdk /bin/bash
