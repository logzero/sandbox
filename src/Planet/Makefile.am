INCLUDES = -I$(top_srcdir)/src/EngineCore
LDADD = -lpthread -lpng -lGL -lGLEW -lSDL-1.1 $(top_builddir)/src/EngineCore/libEngineCore.a

bin_PROGRAMS = Planet
Planet_SOURCES = \
GrassFactory.cpp                PlanetaryMap.h \
GrassFactory.h                  PlanetaryMapCoord.cpp \
PlanetaryMapCoord.h \
MixedHeightMapFactory.cpp       PlanetaryMapNode.cpp \
MixedHeightMapFactory.h         PlanetaryMapNode.h \
Planet.cpp                      PlanetaryObject.cpp \
PlanetaryMap.cpp                PlanetaryObject.h

