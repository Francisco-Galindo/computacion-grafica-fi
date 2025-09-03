CPPFLAGS=-lglfw -lGL -lGLEW -lpthread -lXi -ldl -lm 
INC=-Iinclude

%: %.cpp
	g++ $(CPPFLAGS) $(INC) $< Shader.cpp Mesh.cpp Window.cpp -o $@.out

%: %.c
	cc $(CPPFLAGS) $(INC) $< -o $@.out
