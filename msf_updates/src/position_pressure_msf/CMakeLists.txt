add_executable(position_pressure_sensor main.cpp)

target_link_libraries(position_pressure_sensor pose_distorter ${catkin_LIBRARIES})

add_dependencies(position_pressure_sensor ${${PROJECT_NAME}_EXPORTED_TARGETS})
