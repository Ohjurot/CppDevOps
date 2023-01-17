# CMakeList.txt : CMake project for HelloWorld, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable(HelloWorld "HelloWorld.cpp" "HelloWorld.h")

set_property(TARGET HelloWorld PROPERTY CXX_STANDARD 20)

# TODO: Add tests and install targets if needed.
