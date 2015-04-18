# barefoot-cesium
Cesium to go in a second.

# how to install
```zsh
$ # mkdir -p ~/bin
$ cd ~/bin
$ wget http://handygeospatial.github.io/barefoot-cesium/cesium.html
```

# how to use
```zsh
$ # mkdir -p /your/own/directory
$ # cd /your/own/directory
$ cp ~/bin/cesium.html index.html
$ # vi index.html
$ # python -m SimpleHTTPServer &
$ # open http://localhost:8000
```

# trouble shoting
If you see black sky instead of the Earth, it is likely you run cesium.html (or index.html) from the local filesystem. You need to see the html file via http so that CORS works well.

If you do not have Python on your system, another choice is that you put your cesium.html onto a gh-pages branch of your own GitHub repository.

# see also
Cesium: http://cesiumjs.org/