# podman-python
this will have sample example of podman feature implementing using python code

## Podman Command.
# podman pull command to fetch the already build image from specified image registry.
    podman pull <image registry>/<imagename>:<tag>
# To build the image locally, you need to go to root directory of the project where dockerfile exist and run the below command.
    podman build -t <image name> .
