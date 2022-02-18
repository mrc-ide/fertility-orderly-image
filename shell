#!/bin/sh
set -ex
if [ "$#" -eq 0 ]; then
    CMD=bash
else
    CMD=$1
    shift
fi

docker exec -it orderly_web_orderly $CMD $*
