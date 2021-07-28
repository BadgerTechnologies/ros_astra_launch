cmake_minimum_required(VERSION 3.0.2)
project(astra_launch)

find_package(catkin REQUIRED)

catkin_package()

# install the launch files
install(DIRECTORY launch/
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/launch)

