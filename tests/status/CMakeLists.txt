#  Copyright (c) 2014-2017 Andrey Upadyshev <oliora@gmail.com>
#
#  Use, modification and distribution are subject to the
#  Boost Software License, Version 1.0. (See accompanying file
#  LICENSE_1_0.txt or copy at http://www.boost.org/LICENSE_1_0.txt)

project(status-tests)
add_executable(${PROJECT_NAME}
    ../main.cpp
    status_tests.cpp
)
link_test_libs(${PROJECT_NAME})
add_catch_test(${PROJECT_NAME})
