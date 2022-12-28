file(GLOB HEADERS *.h)
source_group("Header Files" FILES ${HEADERS})

file(GLOB SOURCES *.cpp)
source_group("Source Files" FILES ${SOURCES})

add_library(TFE_Asset STATIC ${HEADERS} ${SOURCES})
