# From-scratch CentOS 6.5 Docker image

As-minimal-as-possible CentOS 6.5 image using `febootstrap`.  The idea of
checking in a large, opaque binary file makes me itch, but the Docker model
doesn't currently allow for more control over image creation.  This is hopefully
the only time I'll have to do this…

Modeled after [docker-brew-ubuntu](https://github.com/tianon/docker-brew-ubuntu).

## generating filesystem image

    ./build_centos.sh
