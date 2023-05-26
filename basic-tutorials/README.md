## Basic tutorials of GStreamer

### Coding environment
```
Ubuntu 20.04
gcc 9.4.0
gstreamer 1.16.3 
gst-launch-1.0 version 1.16.3
```
### Install required packages

```
# Install GStreamer
apt-get install libgstreamer1.0-dev libgstreamer-plugins-base1.0-dev libgstreamer-plugins-bad1.0-dev gstreamer1.0-plugins-base gstreamer1.0-plugins-good gstreamer1.0-plugins-bad gstreamer1.0-plugins-ugly gstreamer1.0-libav gstreamer1.0-tools gstreamer1.0-x gstreamer1.0-alsa gstreamer1.0-gl gstreamer1.0-gtk3 gstreamer1.0-qt5 gstreamer1.0-pulseaudio

# Install Visual Studio Code 
```

### Compile and run the programs
```
gcc filename.c -o filename `pkg-config --cflag --libs gstreamer-1.0`
```
