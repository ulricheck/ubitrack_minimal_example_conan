## This repository holds a conan recipe to demonstrate the usage of ubitrack.

[Conan.io](https://conan.io) demo for the [Ubitrack](https://github.com/Ubitrack) project

## For Users: Use this package

### Basic setup

    $ conan remote add bincrafters "https://api.bintray.com/conan/bincrafters/public-conan"
    $ conan remote add tum-ubitrack-deps "https://api.bintray.com/conan/tum-ubitrack-deps/public-conan"
    $ conan remote add tum-ubitrack "https://api.bintray.com/conan/tum-ubitrack/public-conan"

    $ conan install --build missing

### Testing

    $ cd bin
    $ utcore_tests

