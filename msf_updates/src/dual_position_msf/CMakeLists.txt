add_executable(dual_position_sensor main.cpp)

target_link_libraries(dual_position_sensor pose_distorter ${catkin_LIBRARIES})

add_dependencies(dual_position_sensor ${${PROJECT_NAME}_EXPORTED_TARGETS})
