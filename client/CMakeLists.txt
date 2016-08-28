add_executable(StundenPlaner stunden_planer.cpp)

add_subdirectory(cpr)

include_directories(${CPR_INCLUDE_DIRS})
target_link_libraries(StundenPlaner ${CPR_LIBRARIES})
