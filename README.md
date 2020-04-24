# Windows 10 setup
1. install python 3.6
2. pip install beets
3. run "beet config -p" to locate beets config file
4. replace content of yaml
5. install plugin dependencies:
* pip install discogs-client
* pip install beets-copyartifacts
* pip install requests
* pip install pylast

separate installation:
1. install imagemagick

patches:
1. replace C:\Users\Misthunter\AppData\Local\Programs\Python\Python36\Lib\site-packages\beetsplug\copyartifacts.py with latest in plugin_patch directory


## To dos:
-------
1. Run external cuetools command: e.g.:
CUETools.ARCUE --verbose Ghosteen.cue > accurip.log

