
include_directories( ../src )
add_executable( array_test ../src/Debug.cc ArrayTest.cc      )
#add_executable( filereader_test ../src/FileReader.cc ../src/Debug.cc FileReaderTest.cc )
#add_executable( SORTest ../src/Array.cc ../src/FileReader.cc ../src/StaggeredGrid.cc ../src/SORSolver.cc ../src/Debug.cc SORTest.cc)
#add_executable( staggeredTest ../src/Array.cc ../src/FileReader.cc ../src/StaggeredGrid.cc ../src/SORSolver.cc ../src/Debug.cc ../src/FluidSimulator.cc StaggeredTest.cc)
#add_executable( FluidSimTest ../src/Array.cc ../src/FileReader.cc ../src/StaggeredGrid.cc ../src/SORSolver.cc ../src/Debug.cc ../src/VTKWriter.cc ../src/FluidSimulator.cc FluidSimTest.cc)
add_executable( EnhancedFluidSimTest ../src/FileReader.cc ../src/StaggeredGrid.cc ../src/Geometry2D.cc ../src/lodepng.cc ../src/GrayScaleImage.cc ../src/SORSolver.cc ../src/CGSolver.cc ../src/Debug.cc ../src/VTKWriter.cc ../src/EnhancedFluidSimulator.cc EnhancedFluidSimTest.cc)

add_executable( pois_test         ../src/FileReader.cc ../src/Debug.cc ../src/Array_new.hh ../src/Geometry2D.cc ../src/lodepng.cc ../src/GrayScaleImage.cc ../src/StaggeredGrid.cc ../src/SORSolver.cc ../src/CGSolver.cc PoisTest.cc)
#add_executable( ex3aTest ../src/Array.cc ../src/FileReader.cc ../src/StaggeredGrid.cc ../src/SORSolver.cc ../src/Debug.cc ../src/VTKWriter.cc ../src/FluidSimulator.cc ex3aTest.cc)
