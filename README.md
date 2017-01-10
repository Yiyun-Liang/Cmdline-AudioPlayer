# Cmdline-AudioPlayer

A command line ogg/vorbis audio player written in C using the GStreamer framework.

### Installation 
#### on mac

```
brew install gstreamer

```

#### on Ubuntu

```
sudo apt-get install gstreamer1.0-tools gstreamer1.0-alsa gstreamer1.0-plugins-base gstreamer1.0-plugins-good gstreamer1.0-plugins-bad gstreamer1.0-plugins-ugly gstreamer1.0-libav

```


### Compilation & Execution

To compile the file, run: ```gcc -Wall audioPlayer.c -o audioPlayer $(pkg-config --cflags --libs gstreamer-1.0)```.

To run the application, use: ```./audioPlayer file.ogg```.

Official documentation of GStreamer can be found [here](https://gstreamer.freedesktop.org/documentation/application-development/index.html).