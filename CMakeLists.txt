cmake_minimum_required(VERSION 3.22)

project(TheForceEngine)

# NOTE
# this project uses explicit specialization as seen in TheForceEngine/filesteam.h this is a bug in GCC see
# https://gcc.gnu.org/bugzilla/show_bug.cgi?id=85282 clang seems to work

add_subdirectory(TheForceEngine)
# add_subdirectory(fs)
