#Configure cpr
set(ENV{USE_SYSTEM_CURL} ON)
set(ENV{BUILD_CPR_TESTS} OFF)
set(ENV{USE_SYSTEM_GTEST} ON)
add_subdirectory(cpr)
