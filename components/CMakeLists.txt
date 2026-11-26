
cmake_minimum_required(VERSION 3.10)

project(toygit)

add_library(components
  src/Directory.cpp
  src/StagingArea.cpp
  src/WorkingDirectory.cpp
  src/LocalCommitTree.cpp
  src/Repository.cpp
)

  
target_include_directories(components PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
