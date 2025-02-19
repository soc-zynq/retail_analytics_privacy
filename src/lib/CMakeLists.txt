# Create a library called "retail_analytics_privacy"
add_library(retail_analytics_privacy_lib retail_analytics_privacy.cpp)

# Specify include directories for the library
target_include_directories(retail_analytics_privacy_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../../include)
