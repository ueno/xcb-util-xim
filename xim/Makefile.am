
MAINTAINERCLEANFILES = Makefile.in

lib_LTLIBRARIES = libxcb-xim.la

xcbinclude_HEADERS = xcb_xim.h

AM_CFLAGS = $(CWARNFLAGS)

libxcb_xim_la_SOURCES = xim.c
libxcb_xim_la_CPPFLAGS = $(XCB_CFLAGS) $(XPROTO_CFLAGS)
libxcb_xim_la_LIBADD = $(XCB_LIBS) $(XPROTO_LIBS)
libxcb_xim_la_LDFLAGS = -version-info 4:0:0 -no-undefined

pkgconfig_DATA = xcb-xim.pc

EXTRA_DIST = xcb-xim.pc.in
