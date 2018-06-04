you'll need to have xwindows working, this is a GUI.
Run with something like: `docker run --rm -it --net=host -v /cdata/ContainerData/pentaho-data:/data --env="DISPLAY" --volume="$HOME/.Xauthority:/root/.Xauthority:rw" pdi`
