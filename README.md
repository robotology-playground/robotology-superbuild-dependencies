# robotology-superbuild-dependencies

Windows binaries for the dependencies of robotology-superbuild .

The following libraries (and their dependencies) are built using `vcpkg`: 
* `ace`
* `freeglut`
* `gsl`
* `eigen3`
* `ode`
* `libxml2`
* `eigen3` 
* `opencv3` 
* `matio`
* `sdl1`
* `sdl2`
* `qt5-base`
* `qt5-declarative`
* `qt5-multimedia`
* `qt5-quickcontrols2`
* `sqlite3[core,tool]`

furthermore, the `ipopt-binary` and the `esdcan-binary` from [`robotology-vcpkg-binary-ports`](https://github.com/robotology-dependencies/robotology-vcpkg-binary-ports) is also installed.

The binaries are generated by installing vcpkg in `C:/robotology/vcpkg`, installing the selected ports, and compressing the vcpkg-robotology directory in a `.zip` archive.

See [releases](https://github.com/robotology/robotology-superbuild-dependencies-vcpkg/releases) to download the archives.

