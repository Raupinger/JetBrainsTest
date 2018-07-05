cmake_minimum_required(VERSION 3.10)
project(untitled)

add_custom_target(untitled ALL
        COMMAND /Library/Developer/Toolchains/swift-latest.xctoolchain/usr/bin/swift build
        WORKING_DIRECTORY ${CMAKE_SOURCE_DIR}
        SOURCES Sources/main.swift)
