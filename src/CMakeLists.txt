add_executable(chess chess/chess.cpp)
target_link_libraries(src LINK_PUBLIC Threads::Threads)
