# Copyright 2013, 2014, 2015 by Martin Moene
#
# Distributed under the Boost Software License, Version 1.0. (See accompanying
# file LICENSE_1_0.txt or copy at http://www.boost.org/LICENSE_1_0.txt)

cmake_minimum_required( VERSION 2.8 )

project( lest )

include_directories( "include/lest" )

add_subdirectory( test )
add_subdirectory( example )
add_subdirectory( contrib )

# configure unit tests via CTest:
enable_testing()

# end of file
