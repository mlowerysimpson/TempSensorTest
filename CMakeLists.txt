cmake_minimum_required(VERSION 2.8)
project(TempSensorTest)
# Locate libraries and headers

# Include headers

#the file(GLOB...) allows for wildcard additions:
file(GLOB SOURCES "./*.cpp")
add_executable(TempSensorTest ${SOURCES})

# Link against libraries



