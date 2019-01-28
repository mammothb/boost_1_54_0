# boost_1_54_0

## Build/install `iostreams`
Install external library `libbz2-dev`

## Build/install `mpi`
Add `using mpi ;` to the auto-generated `project-config.jam`

## Sample build commands
```
cd path/to/boost_1_54_0
./bootstrap.sh
./b2 toolset=gcc cxxflags="-std=c++11"
./b2 install
```
