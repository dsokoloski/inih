AUTOMAKE_OPTIONS = foreign
ACLOCAL_AMFLAGS = -I m4

EXTRA_DIST = ini.h cpp/INIReader.h

AM_CFLAGS = ${CFLAGS}
AM_CXXFLAGS = ${CXXFLAGS}

lib_LTLIBRARIES = libini.la

libini_la_SOURCES = ini.c cpp/INIReader.cpp
libini_la_CFLAGS = ${AM_CFLAGS}
libini_la_CXXFLAGS = ${AM_CXXFLAGS}
libini_la_LDFLAGS = -static

