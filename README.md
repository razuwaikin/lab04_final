# lab04_final
Эта лабораторная стоила мне очень большой редакции кода, с котороым предполагалось работать, 
sqt - sqrt
std::
#include  <cmath>


language: cpp

script:
- cd solver_application
- cmake CMakeLists.txt
- make
- cd ..
- cd hello_world_application
- cmake CMakeLists.txt
- make

addons:
  apt:
  
    sources:
  
      - george-edison55-precise-backports
  
    packages:
  
      - cmake
      - cmake-data
      - mingw-w64
  
 [![Build Status](https://www.travis-ci.com/razuwaikin/lab04_final.svg?branch=main)](https://www.travis-ci.com/razuwaikin/lab04_final)
  https://www.travis-ci.com/razuwaikin/lab04_final.svg?branch=main
