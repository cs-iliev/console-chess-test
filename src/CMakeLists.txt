add_executable(src chess/chess.cpp)
target_link_libraries(src LINK_PUBLIC Threads::Threads)
