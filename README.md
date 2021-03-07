# concourse-s390x-worker

```
./build.sh
```

Will build the docker registry-image resource, zip it and put it in the
right path. Will then build the main docker file which builds concourse
first and then uses the binaries in a fresh docker image.

While this does not cross-compile, it can be run on s390x machines with docker.

