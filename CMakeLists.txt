# version requirement
cmake_minimum_required(VERSION 2.8)

# project name
project(PathTreeUtility)

# check dependencies and retriebe the configuration
FIND_PACKAGE(Boost 1.55.0 COMPONENTS system REQUIRED)

# global includes directories
include_directories(
	${Boost_INCLUDE_DIR}
)
