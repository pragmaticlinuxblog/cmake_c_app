# Specify the minimum version
cmake_minimum_required(VERSION 3.7)

# Specify the project name
project(myapp)

# Add sources
set(
  PROG_SRCS
  source/main.c
)

# Specify what is needed to create the main target.
add_executable(myapp ${PROG_SRCS})

# Specify how to install the binary.
install (TARGETS myapp RUNTIME DESTINATION bin)
