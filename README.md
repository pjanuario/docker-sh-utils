# Docker Shell Utils

The image is based on the lightweight Alpine Linux image and adds [Bash](https://www.gnu.org/software/bash/) and some other tools such as: grep, sed, awk, bc, head, tail, curl and iputils.

# Usage

    $ docker run --rm prnjanuario/sh-utils bash -c 'echo "Hey"'

# Kubernetes interactive shell

    $ kubectl run my-shell --rm -i --tty --image prnjanuario/sh-utils -- bash
