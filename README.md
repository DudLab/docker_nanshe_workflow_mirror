# Purpose

Allows for a lightweight mirroring of the `nanshe_workflow` container ( <https://hub.docker.com/r/dudlab/nanshe_workflow> ). Thus, codebases pulling from the original `dudlab/nanshe_workflow` image will still pull the same common layers.

# Building

## Automatic

This repo is part of an automated build, which is hosted on Docker Hub ( <https://hub.docker.com/r/dudlab/nanshe_workflow> ). Changes added to this trigger an automatic rebuild and deploy the resulting image to Docker Hub. To download an existing image, one simply needs to run `docker pull dudlab/nanshe_workflow`.

## Manual

If one wishes to develop this repo, building will need to be performed manually. This container can be built simply by `cd`ing into the repo and using `docker build -t <NAME> .` where `<NAME>` is the name tagged to the image built. More information about building can be found in Docker's documentation ( <https://docs.docker.com/reference/builder> ). Please consider opening a pull request for changes that you make.

# Testing

The container used by this container as a base, `dudlab/nanshe_workflow`, is tested independently along with its contents. As this image is merely a placeholder for `dudlab/nanshe_workflow` and does nothing but use that image, no further testing is performed.

# Usage

For more information about how to use this container visit the repo on GitHub ( <https://github.com/DudLab/docker_nanshe_workflow> ).
