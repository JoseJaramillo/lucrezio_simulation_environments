add_executable(pose_broadcaster_node
  pose_broadcaster_node.cpp
)

target_link_libraries(pose_broadcaster_node
  ${catkin_LIBRARIES}
)


add_dependencies(pose_broadcaster_node ${${PROJECT_NAME}_EXPORTED_TARGETS} ${catkin_EXPORTED_TARGETS})


