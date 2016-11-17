add_executable(pose_position_pressure main.cpp)

target_link_libraries(pose_position_pressure pose_distorter ${catkin_LIBRARIES})

add_dependencies(pose_position_pressure ${${PROJECT_NAME}_EXPORTED_TARGETS})
