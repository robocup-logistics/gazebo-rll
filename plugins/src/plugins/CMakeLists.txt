# ***************************************************************************
# Created:   Mon  3 May 15:04:26 CEST 2021
#
# Copyright  2021  Till Hofmann <hofmann@kbsg.rwth-aachen.de>
# ****************************************************************************/
# This program is free software; you can redistribute it and/or modify it under
# the terms of the GNU General Public License as published by the Free Software
# Foundation; either version 2 of the License, or (at your option) any later
# version.
#
# This program is distributed in the hope that it will be useful, but WITHOUT
# ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS
# FOR A PARTICULAR PURPOSE.  See the GNU Library General Public License for more
# details.
#
# Read the full text in the LICENSE.md file.
#

set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${PROJECT_BINARY_DIR}/plugins)

add_subdirectory(conveyor-vision)
add_subdirectory(depthcam)
add_subdirectory(gripper)
add_subdirectory(gyro)
add_subdirectory(light-control)
add_subdirectory(motor)
add_subdirectory(localization)
add_subdirectory(odometry)
add_subdirectory(mps)
add_subdirectory(time-sync)
add_subdirectory(puck)
add_subdirectory(llsf-refbox-comm)
add_subdirectory(light-signal-detection)
add_subdirectory(mps-placement)
add_subdirectory(tag)
add_subdirectory(tag-vision)
