# Copyright 2021 ShadowCore
#
# This file is free software; as a special exception the author gives
# unlimited permission to copy and/or distribute it, with or without
# modifications, as long as this notice is preserved.
#
# This program is distributed in the hope that it will be useful, but
# WITHOUT ANY WARRANTY, to the extent permitted by law; without even the
# implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

find_package(Threads REQUIRED)

add_library(threads INTERFACE)
target_link_libraries(threads
  INTERFACE
    ${CMAKE_THREAD_LIBS_INIT})
