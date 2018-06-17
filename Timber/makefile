CXX = g++
CXXFLAGS = -std=c++14
CXXLIBS = -lsfml-graphics -lsfml-window -lsfml-system -lsfml-audio

all: Timber

Timber: code/Timber.o
	$(CXX) $< -o $@ $(CXXLIBS)

code/%.o: %.cpp
	$(CXX) $< -o $@



clean:
	rm Timber code/*.o

