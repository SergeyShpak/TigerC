file (GLOB TEST_SRC ${CMAKE_CURRENT_SOURCE_DIR}/*.c)

get_filename_component(PROJECT_ID ${CMAKE_CURRENT_SOURCE_DIR} NAME)
add_executable(${PROJECT_ID} ${TESTED_SRC} ${UNITY_SRC} ${TEST_SRC})
