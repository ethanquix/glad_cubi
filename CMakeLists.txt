set(GLAD_SRCS src/glad.c include/glad/glad.h include/KHR/khrplatform.h)

set(GLAD_HEADERS ${CMAKE_CURRENT_LIST_DIR}/include PARENT_SCOPE)

include_directories(include)

add_library(glad STATIC ${GLAD_SRCS})
