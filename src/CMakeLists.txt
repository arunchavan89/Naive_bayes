cmake_minimum_required(VERSION 3.15)
project( NaiveBayes )
file(GLOB NaiveBayes_SRC
    "*.h"
    "*.cpp"
	"*.board"
)
add_executable(NaiveBayes ${NaiveBayes_SRC})

#find_package( OpenCV REQUIRED )
#include_directories( ${OpenCV_INCLUDE_DIRS} )
#target_link_libraries( AStar ${OpenCV_LIBS} )