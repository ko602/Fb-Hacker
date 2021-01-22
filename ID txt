#!/usr/bin/env sh

set -x

padded_day=${1:-$(date '+%d')}
day=$((10#$padded_day))
session=$(<.session)
curl --cookie "session=${session}" https://adventofcode.com/2020/day/${day}/input -o input/day${padded_day}.txt && echo DONE
