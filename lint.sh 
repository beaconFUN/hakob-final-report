#!/bin/sh

docker run --rm \
  -v `pwd`/"$@":/textlint/"$@" \
  sititou70/beacon-report-linter \
  pandoctextlint "$@"