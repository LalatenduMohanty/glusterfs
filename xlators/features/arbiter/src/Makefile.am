xlator_LTLIBRARIES = arbiter.la
xlatordir = $(libdir)/glusterfs/$(PACKAGE_VERSION)/xlator/features

arbiter_la_LDFLAGS = -module -avoid-version

arbiter_la_SOURCES = arbiter.c
arbiter_la_LIBADD = $(top_builddir)/libglusterfs/src/libglusterfs.la

noinst_HEADERS = arbiter.h arbiter-mem-types.h

AM_CPPFLAGS = $(GF_CPPFLAGS) -I$(top_srcdir)/libglusterfs/src

AM_CFLAGS = -Wall $(GF_CFLAGS)

CLEANFILES =
