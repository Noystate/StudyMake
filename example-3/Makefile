# Переменные
TARGET = program
SRC = Cazino-Royal.cpp
OBJ = Cazino-Royal.o
CXX = g++
CFLAGS = -Wall -std=c++11

$(TARGET): $(OBJ)
	$(CXX) $(CXXFLAGS) -o $(TARGET) $(OBJ)

Cazino-Royal.o: Cazino-Royal.cpp
	$(CXX) $(CXXFLAGS) -c Cazino-Royal.cpp

clean:
	rm -f $(OBJ) $(TARGET)

.PHONY: clean
