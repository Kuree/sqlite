cmake_minimum_required(VERSION 3.10)
project(sqlite3)

add_library(sqlite3 src/sqlite3.c include/sqlite3.h)
