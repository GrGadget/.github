# GrGadget

## LATfield2

Requirements:
- meson
- C++17 compiler 
- MPI library
- FFTW3
- HDF5
- GSL
- Boost

Instructions:
```
mkdir $BUILD_DIR
cd $BUILD_DIR
module load latfield/base
meson $SRC_DIR --prefix $INSTALL_DIR
ninja
ninja install
```

## gevolution-1.2

Requirements:
- meson
- C++17 compiler 
- MPI library
- FFTW3
- HDF5
- GSL
- Boost
- LATfield2

## Gadget4

Requirements:
- meson
- C++17 compiler 
- MPI library
- FFTW3
- HDF5
- GSL
- Boost
- LATfield2
- gevolution-1.2
- HWLOC
- Chealpix
