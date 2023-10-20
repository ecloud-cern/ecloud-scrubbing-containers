# ecloud-scrubbing-containers

Dockerfiles for containers related to electron cloud codes.

Example to build an image:

```
$ sudo docker build -f xsuite_2022.1 -t registry.cern.ch/ecloud-scrubbing/xsuite:2022.1 .
```

To push the image to the registry:
```
$ sudo docker login registry.cern.ch
$ sudo push registry.cern.ch/ecloud-scrubbing/xsuite:2022.1
```

Your password to login in registry.cern.ch via docker be found in the user profile in registry.cern.ch (called "CLI secret").

