# tilefetcher
fetch baidu map tiles.
test on python2.7 and windows7.

## Issuse
1. syntax error on python3. change `except Exception, e:` to `except Exception as e:` in `tilefetcher.py`[line 92]

## Usage
``` python
# left-bottom coordinate (lng1, lat1) right-top coordinate (lng2, lat2) zoomlevel(z)
fetch_tiles_z(114.467361, 34.127447, 122.985309, 38.125886, 17)
# left-bottom coordinate (lng1, lat1) right-top coordinate (lng2, lat2) zoomlevel range(z1, z2)
fetch_tiles(114.467361, 34.127447, 122.985309, 38.125886, 10, 18)
```
