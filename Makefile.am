
EXTRA_DIST = README.md

lib_LTLIBRARIES = libwebsocket.la

#libwebsocket_la_LIBADD = 
libwebsocket_la_LDFLAGS = @LIBTOOL_VERSION_RELEASE@ -export-dynamic

libwebsocket_la_SOURCES = \
	websocket.c \
	md5.c

websocketincludedir = $(includedir)/websocket
nobase_websocketinclude_HEADERS = \
	websocket.h


