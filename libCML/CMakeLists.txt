set(LIB_SRC CML.cpp)

add_library(libCML ${LIB_SRC})
set(LIBRARY_OUTPUT_PATH ${PROJECT_BINARY_DIR}/lib)

set_target_properties(libCML PROPERTIES OUTPUT_NAME "CML")