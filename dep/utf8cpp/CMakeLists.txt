# Copyright 2021 ShadowCore
#
# This file is free software; as a special exception the author gives
# unlimited permission to copy and/or distribute it, with or without
# modifications, as long as this notice is preserved.
#
# This program is distributed in the hope that it will be useful, but
# WITHOUT ANY WARRANTY, to the extent permitted by law; without even the
# implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

add_library(utf8cpp INTERFACE)

target_include_directories(utf8cpp
  INTERFACE
    ${CMAKE_CURRENT_SOURCE_DIR})
