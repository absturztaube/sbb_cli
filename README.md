# Bash SBB Fahrplan

Created this on a Sunday, just for the lulz.

This script uses the http://transport.opendata.ch/ API to lookup connections of SBB/CFF/FFS trains and stuff.

## Requirements

- curl
- jq

Maybe some other stuff to... I used the things available on my pc, so...

## Usage

Just run this script like this

	./sbb.sh bern zürich

This should give you the next 4 connections from bern to zürich

Time and Date can be specified by `-t` and `-d` switches

	./sbb.sh -d 14.10.2018 -t 10:15 bern zürich

Via is implemented by `-v` but not tested yet
Same goes for using the specified time as arrival time with `-a`

## Infos

Feel free to use this thing. Fork it, and make it your own^^
