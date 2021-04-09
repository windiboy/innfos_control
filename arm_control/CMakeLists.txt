add_executable(controller src/controller.cpp)
target_link_libraries(controller ${catkin_LIBRARIES} ${Boost_LIBRARIES})
install(TARGETS controller DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION})

install(DIRECTORY launch DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
