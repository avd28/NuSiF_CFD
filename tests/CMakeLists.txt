
include_directories( ../src )
#add_executable( array_test      ../src/Array.cc      ../src/Debug.cc ArrayTest.cc      )
#add_executable( filereader_test ../src/FileReader.cc ../src/Debug.cc FileReaderTest.cc )
#add_executable( SORTest ../src/Array.cc ../src/FileReader.cc ../src/Geometry2D.cc ../src/StaggeredGrid.cc ../src/SORSolver.cc ../src/Debug.cc SORTest.cc)
add_executable( PSolverTest ../src/Array.cc ../src/FileReader.cc ../src/MatrixCOO.cc ../src/Geometry2D.cc ../src/double_compares.cpp ../src/StaggeredGrid.cc ../src/PSolver.cc ../src/Debug.cc PSolverTest.cc)
#add_executable( staggeredTest ../src/Array.cc ../src/FileReader.cc ../src/StaggeredGrid.cc ../src/SORSolver.cc ../src/Debug.cc ../src/FluidSimulator.cc StaggeredTest.cc)
#add_executable( FluidSimTest ../src/Array.cc ../src/FileReader.cc ../src/StaggeredGrid.cc ../src/SORSolver.cc ../src/Debug.cc ../src/VTKWriter.cc ../src/FluidSimulator.cc FluidSimTest.cc)
add_executable( EnhancedFluidSimTest ../src/Array.cc ../src/FileReader.cc ../src/StaggeredGrid.cc ../src/Geometry2D.cc ../src/lodepng.cc ../src/GrayScaleImage.cc ../src/SORSolver.cc ../src/Debug.cc ../src/VTKWriter.cc ../src/EnhancedFluidSimulator.cc EnhancedFluidSimTest.cc)
add_executable( MatrixCOOTest      ../src/MatrixCOO.cc   ../src/Array.cc   ../src/Debug.cc ../src/double_compares.cpp MatrixCOOTest.cc      )
