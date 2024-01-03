add_library(factory SHARED factory.cc)
target_link_libraries(factory
  ${GAZEBO_LIBRARIES}
)
