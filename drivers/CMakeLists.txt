#
# Copyright (c) 2018 Nordic Semiconductor
#
# SPDX-License-Identifier: LicenseRef-BSD-5-Clause-Nordic
#

add_subdirectory_ifdef(CONFIG_GPS_SIM gps_sim)
add_subdirectory_ifdef(CONFIG_LTE_LINK_CONTROL lte_link_control)
add_subdirectory_ifdef(CONFIG_SENSOR sensor)
