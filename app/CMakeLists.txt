add_executable(human-detect-app main.cpp)
target_link_libraries(human-detect-app PRIVATE human_detector_tracker ${OpenCV_LIBS})