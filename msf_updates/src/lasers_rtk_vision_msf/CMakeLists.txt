add_executable(lasers_rtk_vision main.cpp)

target_link_libraries(lasers_rtk_vision pose_distorter ${catkin_LIBRARIES})

add_dependencies(lasers_rtk_vision ${${PROJECT_NAME}_EXPORTED_TARGETS})
