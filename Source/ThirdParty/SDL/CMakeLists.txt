message(STATUS "Fetching SDL 2.30.10")

FetchContent_Declare(
  sdl2
  GIT_REPOSITORY https://github.com/libsdl-org/SDL.git
  GIT_TAG        release-2.30.10
)

FetchContent_MakeAvailable(sdl2)