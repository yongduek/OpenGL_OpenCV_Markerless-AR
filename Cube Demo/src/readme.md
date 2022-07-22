install:
- glad, glfw, glm, opencv

opencv: OPENCV_ENABLE_NONFREE

compile:

`g++ main.cpp -lopencv_world   -lglfw3 -lGL -lGLU -ldl -lpthread -lglad`