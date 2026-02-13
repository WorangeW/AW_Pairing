cmake_minimum_required(VERSION 3.20)

project(AW_Pairing VERSION 1.0)

find_package(Qt6 REQUIRED COMPONENTS
    Core
    Gui
    Widgets
    Network
    OpenGL
    Svg
    Qml
    Quick
)

add_subdirectory(FluentUI)
add_subdirectory(src)
