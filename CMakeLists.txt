cmake_minimum_required(VERSION 3.17)
project(PhoneBook)

set(CMAKE_CXX_STANDARD 14)

add_executable(PhoneBook main.cpp Person.h Date.h Group.h cli.h PhoneBook.h Human.h IToString.h)