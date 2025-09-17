# Переменные
TARGET = program
SRC = main.cpp
OBJ = main.o
CXX = g++
CFLAGS = -Wall -std=c++11

$(TARGET): $(OBJ)
	$(CXX) $(CXXFLAGS) -o $(TARGET) $(OBJ)

main.o: main.cpp
	$(CXX) $(CXXFLAGS) -c main.cpp

clean:
	rm -f $(OBJ) $(TARGET)

.PHONY: clean
