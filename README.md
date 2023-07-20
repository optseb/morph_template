# morph_template
A template repo into which you can start developing a morphologica program

To build and run:

```bash
# Clone this example
git clone git@github.com:optseb/morph_template # or your fork of it

# Install morphologica dependencies
sudo apt install build-essential cmake git wget  \
                 freeglut3-dev libglu1-mesa-dev libxmu-dev libxi-dev \
                 libglfw3-dev libfreetype-dev libarmadillo-dev libhdf5-dev

# Clone morphologica INSIDE your example
cd morph_template # or whatever you named your fork/copy
git clone git@github.com:ABRG-Models/morphologica

# Build
mkdir build
cd build
cmake ..
make
./prog1
```
