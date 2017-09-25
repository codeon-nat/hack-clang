cmake_minimum_required(VERSION 3.4.3)

install( PROGRAMS
# @mulle-objc@ >
                   utils/mulle-clang-add-brew-post-commit-hook
# @mulle-objc@ <
    DESTINATION share/clang
)
