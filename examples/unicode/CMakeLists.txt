#
# Part of CMake configuration for lexertl library
#
# Copyright (c) 2013 Mateusz Loskot <mateusz@loskot.net>
#
# Distributed under the Boost Software License, Version 1.0. (See accompanying
# file licence_1_0.txt or copy at http://www.boost.org/LICENSE_1_0.txt)
#
add_executable(lexertl_unicode main.cpp)
target_link_libraries(lexertl_unicode PRIVATE lexertl)
target_compile_features(lexertl_unicode PUBLIC cxx_std_11)
