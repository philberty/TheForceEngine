add_subdirectory(zip)
include_directories(zip)
link_directories(zip)

file(GLOB HEADERS *.h)
source_group("Header Files" FILES ${HEADERS})

file(GLOB SOURCES *.cpp)
source_group("Source Files" FILES ${SOURCES})

add_library(TFE_Archive STATIC ${HEADERS} ${SOURCES})
