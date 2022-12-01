## Process this file with automake to produce Makefile.in

## Created by Anjuta

AM_CPPFLAGS = \
	-DPACKAGE_LOCALE_DIR=\""$(localedir)"\" \
	-DPACKAGE_SRC_DIR=\""$(srcdir)"\" \
	-DPACKAGE_DATA_DIR=\""$(pkgdatadir)"\"

AM_CFLAGS =\
	 -Wall\
	 -g

lib_LTLIBRARIES = libtest.la


libtest_la_SOURCES = \
	lib.c

libtest_la_LDFLAGS = 

libtest_la_LIBADD = 



include_HEADERS = \
	libtest.h

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = libtest-0.1.pc

EXTRA_DIST = \
	libtest-0.1.pc.in
