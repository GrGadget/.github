# GrGadget

Welcome to GrGadget superproject!

# Dependencies

- C++17 compiler
- MPI
- FFTW3 with parallel support
- boost
- hdf5 with parallel support
- gsl
- healpix
- hwloc (optional)

# Get started

```
git clone https://github.com/GrGadget/GrGadget-main.git
mkdir build && cd build
module load $dependencies
cp ../GrGadget-main/examples/Config.sh .
meson ../GrGadget-main
ninja
```
