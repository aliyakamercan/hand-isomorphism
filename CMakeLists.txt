cmake_minimum_required (VERSION 3.12)

project(hand-isomorphism LANGUAGES C)

include_directories(${PROJECT_SOURCE_DIR}/src)

add_executable(check
    src/check-main.c
    src/deck.h
    src/deck.c
    src/hand_index.h
    src/hand_index.c
    src/hand_index-impl.h)