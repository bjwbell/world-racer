# Generated automatically from Makefile.in by configure.
# Makefile.in generated automatically by automake 1.4-p5 from Makefile.am

# Copyright (C) 1994, 1995-8, 1999, 2001 Free Software Foundation, Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.


SHELL = /bin/sh

srcdir = .
top_srcdir = ..
prefix = /usr/local
exec_prefix = ${prefix}

bindir = ${exec_prefix}/bin
sbindir = ${exec_prefix}/sbin
libexecdir = ${exec_prefix}/libexec
datadir = ${prefix}/share
sysconfdir = ${prefix}/etc
sharedstatedir = ${prefix}/com
localstatedir = ${prefix}/var
libdir = ${exec_prefix}/lib
infodir = ${prefix}/info
mandir = ${prefix}/man
includedir = ${prefix}/include
oldincludedir = /usr/include

DESTDIR =

pkgdatadir = $(datadir)/Pod_Racer_Clone
pkglibdir = $(libdir)/Pod_Racer_Clone
pkgincludedir = $(includedir)/Pod_Racer_Clone

top_builddir = ..

ACLOCAL = aclocal
AUTOCONF = autoconf
AUTOMAKE = automake
AUTOHEADER = autoheader

INSTALL = /usr/bin/install -c
INSTALL_PROGRAM = ${INSTALL} $(AM_INSTALL_PROGRAM_FLAGS)
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_SCRIPT = ${INSTALL_PROGRAM}
transform = s,x,x,

NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
host_alias = i686-pc-linux-gnu
host_triplet = i686-pc-linux-gnu
AS = @AS@
BUILD_INCLUDED_LIBINTL = no
CATOBJEXT = .gmo
CC = gcc
CXX = c++
DATADIRNAME = share
DLLTOOL = @DLLTOOL@
ECHO = echo
EXEEXT = 
GENCAT = gencat
GLIBC21 = yes
GMSGFMT = /usr/bin/msgfmt
HAVE_LIB = @HAVE_LIB@
INSTOBJEXT = .mo
INTLBISON = bison
INTLLIBS = 
INTLOBJS = 
INTL_LIBTOOL_SUFFIX_PREFIX = 
LIB = @LIB@
LIBICONV = 
LIBINTL = 
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LN_S = ln -s
LTLIB = @LTLIB@
LTLIBICONV = 
LTLIBINTL = 
MAKEINFO = makeinfo
MKINSTALLDIRS = ./mkinstalldirs
NO_PREFIX_PACKAGE_DATA_DIR = share/Pod_Racer_Clone
NO_PREFIX_PACKAGE_DOC_DIR = doc/Pod_Racer_Clone
NO_PREFIX_PACKAGE_HELP_DIR = share/Pod_Racer_Clone/help
NO_PREFIX_PACKAGE_MENU_DIR = share/Pod_Racer_Clone
NO_PREFIX_PACKAGE_PIXMAPS_DIR = share/Pod_Racer_Clone/pixmaps
OBJDUMP = @OBJDUMP@
OBJEXT = o
PACKAGE = Pod_Racer_Clone
PACKAGE_DATA_DIR = /usr/local/share/Pod_Racer_Clone
PACKAGE_DOC_DIR = /usr/local/doc/Pod_Racer_Clone
PACKAGE_HELP_DIR = /usr/local/share/Pod_Racer_Clone/help
PACKAGE_MENU_DIR = /usr/local/share/Pod_Racer_Clone
PACKAGE_PIXMAPS_DIR = /usr/local/share/Pod_Racer_Clone/pixmaps
POSUB = po
RANLIB = ranlib
STRIP = strip
USE_INCLUDED_LIBINTL = no
USE_NLS = yes
VERSION = 0.1

pod_racer_clone_includedir = $(pkgincludedir)

pod_racer_clone_include_DATA = \
	Camera.h\
	Functions.h\
	Game_Class.h\
	Light.h\
	MD3Functions.h\
	Md3.h\
	Object_Loader.h\
	Quad_Object.h\
	Terrain.h\
	Texture.h\
	main.h\
	tga.h\
	player.h\
	path.h\
	HUD.h\
	Speed_Display.h\
	display_text.h\
	Track_Marker.h\
	track_selection.h\
	World.h\
	Bush.h\
	Bushes.h\
	terrain_object.h\
	terrain_objects.h


EXTRA_DIST = $(pod_racer_clone_include_DATA)
mkinstalldirs = $(SHELL) $(top_srcdir)/mkinstalldirs
CONFIG_HEADER = ../config.h
CONFIG_CLEAN_FILES = 
DATA =  $(pod_racer_clone_include_DATA)

DIST_COMMON =  Makefile.am Makefile.in


DISTFILES = $(DIST_COMMON) $(SOURCES) $(HEADERS) $(TEXINFOS) $(EXTRA_DIST)

TAR = gtar
GZIP_ENV = --best
all: all-redirect
.SUFFIXES:
$(srcdir)/Makefile.in: Makefile.am $(top_srcdir)/configure.in $(ACLOCAL_M4) 
	cd $(top_srcdir) && $(AUTOMAKE) --gnu include/Makefile

Makefile: $(srcdir)/Makefile.in  $(top_builddir)/config.status $(BUILT_SOURCES)
	cd $(top_builddir) \
	  && CONFIG_FILES=$(subdir)/$@ CONFIG_HEADERS= $(SHELL) ./config.status


install-pod_racer_clone_includeDATA: $(pod_racer_clone_include_DATA)
	@$(NORMAL_INSTALL)
	$(mkinstalldirs) $(DESTDIR)$(pod_racer_clone_includedir)
	@list='$(pod_racer_clone_include_DATA)'; for p in $$list; do \
	  if test -f $(srcdir)/$$p; then \
	    echo " $(INSTALL_DATA) $(srcdir)/$$p $(DESTDIR)$(pod_racer_clone_includedir)/$$p"; \
	    $(INSTALL_DATA) $(srcdir)/$$p $(DESTDIR)$(pod_racer_clone_includedir)/$$p; \
	  else if test -f $$p; then \
	    echo " $(INSTALL_DATA) $$p $(DESTDIR)$(pod_racer_clone_includedir)/$$p"; \
	    $(INSTALL_DATA) $$p $(DESTDIR)$(pod_racer_clone_includedir)/$$p; \
	  fi; fi; \
	done

uninstall-pod_racer_clone_includeDATA:
	@$(NORMAL_UNINSTALL)
	list='$(pod_racer_clone_include_DATA)'; for p in $$list; do \
	  rm -f $(DESTDIR)$(pod_racer_clone_includedir)/$$p; \
	done
tags: TAGS
TAGS:


distdir = $(top_builddir)/$(PACKAGE)-$(VERSION)/$(subdir)

subdir = include

distdir: $(DISTFILES)
	here=`cd $(top_builddir) && pwd`; \
	top_distdir=`cd $(top_distdir) && pwd`; \
	distdir=`cd $(distdir) && pwd`; \
	cd $(top_srcdir) \
	  && $(AUTOMAKE) --include-deps --build-dir=$$here --srcdir-name=$(top_srcdir) --output-dir=$$top_distdir --gnu include/Makefile
	@for file in $(DISTFILES); do \
	  d=$(srcdir); \
	  if test -d $$d/$$file; then \
	    cp -pr $$d/$$file $(distdir)/$$file; \
	  else \
	    test -f $(distdir)/$$file \
	    || ln $$d/$$file $(distdir)/$$file 2> /dev/null \
	    || cp -p $$d/$$file $(distdir)/$$file || :; \
	  fi; \
	done
info-am:
info: info-am
dvi-am:
dvi: dvi-am
check-am: all-am
check: check-am
installcheck-am:
installcheck: installcheck-am
install-exec-am:
install-exec: install-exec-am

install-data-am: install-pod_racer_clone_includeDATA
install-data: install-data-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am
install: install-am
uninstall-am: uninstall-pod_racer_clone_includeDATA
uninstall: uninstall-am
all-am: Makefile $(DATA)
all-redirect: all-am
install-strip:
	$(MAKE) $(AM_MAKEFLAGS) AM_INSTALL_PROGRAM_FLAGS=-s install
installdirs:
	$(mkinstalldirs)  $(DESTDIR)$(pod_racer_clone_includedir)


mostlyclean-generic:

clean-generic:

distclean-generic:
	-rm -f Makefile $(CONFIG_CLEAN_FILES)
	-rm -f config.cache config.log stamp-h stamp-h[0-9]*

maintainer-clean-generic:
mostlyclean-am:  mostlyclean-generic

mostlyclean: mostlyclean-am

clean-am:  clean-generic mostlyclean-am

clean: clean-am

distclean-am:  distclean-generic clean-am
	-rm -f libtool

distclean: distclean-am

maintainer-clean-am:  maintainer-clean-generic distclean-am
	@echo "This command is intended for maintainers to use;"
	@echo "it deletes files that may require special tools to rebuild."

maintainer-clean: maintainer-clean-am

.PHONY: uninstall-pod_racer_clone_includeDATA \
install-pod_racer_clone_includeDATA tags distdir info-am info dvi-am \
dvi check check-am installcheck-am installcheck install-exec-am \
install-exec install-data-am install-data install-am install \
uninstall-am uninstall all-redirect all-am all installdirs \
mostlyclean-generic distclean-generic clean-generic \
maintainer-clean-generic clean mostlyclean distclean maintainer-clean


# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
