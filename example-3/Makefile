TARGET = program
CXX = g++
CXXFLAGS = -Wall -std=c++11

# Автоматически находим все .cpp файлы
SRCS = $(wildcard *.cpp)
OBJS = $(SRCS:.cpp=.o)

$(TARGET): $(OBJS)
	$(CXX) $(CXXFLAGS) -o $(TARGET) $(OBJS)

%.o: %.cpp
	$(CXX) $(CXXFLAGS) -c $< -o $@

clean:
	rm -f $(OBJS) $(TARGET)

.PHONY: clean# Переменные
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
