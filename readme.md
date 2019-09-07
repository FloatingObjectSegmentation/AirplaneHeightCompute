## Airplane Height computation

This is a fast implementation of RBNN in C++. Works only on Windows 10.

## Building from source

- Install PCL 1.8.1
- Install cmake 3.0 or higher
- Build using cmake from the root folder using CMakeLists.txt and the main .cpp file
- Open the project in Visual Studio 2017
- Build in Release mode

## Usage
Takes as input the ./airplane_height.exe [dmr_directory] [dmr_filename] [aug_directory] [aug_file].
Aug file should be in PBBMDF format, DMR should be a pcd.

## Result
Outputs the heights of the dmr at each of the augmentables. Used for computing the height of the airplane at the position and
time of scanning.


