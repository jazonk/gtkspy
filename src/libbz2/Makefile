# Makefile.in generated by automake 1.13.1 from Makefile.am.
# src/libbz2/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994-2012 Free Software Foundation, Inc.

# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.




am__make_dryrun = \
  { \
    am__dry=no; \
    case $$MAKEFLAGS in \
      *\\[\ \	]*) \
        echo 'am--echo: ; @echo "AM"  OK' | $(MAKE) -f - 2>/dev/null \
          | grep '^AM OK$$' >/dev/null || am__dry=yes;; \
      *) \
        for am__flg in $$MAKEFLAGS; do \
          case $$am__flg in \
            *=*|--*) ;; \
            *n*) am__dry=yes; break;; \
          esac; \
        done;; \
    esac; \
    test $$am__dry = yes; \
  }
pkgdatadir = $(datadir)/gtkwave
pkgincludedir = $(includedir)/gtkwave
pkglibdir = $(libdir)/gtkwave
pkglibexecdir = $(libexecdir)/gtkwave
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
subdir = src/libbz2
DIST_COMMON = $(srcdir)/Makefile.in $(srcdir)/Makefile.am \
	$(top_srcdir)/depcomp
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
mkinstalldirs = $(install_sh) -d
CONFIG_HEADER = $(top_builddir)/config.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
LIBRARIES = $(noinst_LIBRARIES)
AR = ar
ARFLAGS = cru
AM_V_AR = $(am__v_AR_$(V))
am__v_AR_ = $(am__v_AR_$(AM_DEFAULT_VERBOSITY))
am__v_AR_0 = @echo "  AR      " $@;
am__v_AR_1 = 
libbz2_a_AR = $(AR) $(ARFLAGS)
libbz2_a_LIBADD =
am_libbz2_a_OBJECTS = blocksort.$(OBJEXT) compress.$(OBJEXT) \
	decompress.$(OBJEXT) randtable.$(OBJEXT) bzlib.$(OBJEXT) \
	crctable.$(OBJEXT) huffman.$(OBJEXT)
libbz2_a_OBJECTS = $(am_libbz2_a_OBJECTS)
AM_V_P = $(am__v_P_$(V))
am__v_P_ = $(am__v_P_$(AM_DEFAULT_VERBOSITY))
am__v_P_0 = false
am__v_P_1 = :
AM_V_GEN = $(am__v_GEN_$(V))
am__v_GEN_ = $(am__v_GEN_$(AM_DEFAULT_VERBOSITY))
am__v_GEN_0 = @echo "  GEN     " $@;
am__v_GEN_1 = 
AM_V_at = $(am__v_at_$(V))
am__v_at_ = $(am__v_at_$(AM_DEFAULT_VERBOSITY))
am__v_at_0 = @
am__v_at_1 = 
DEFAULT_INCLUDES = -I. -I$(top_builddir)
depcomp = $(SHELL) $(top_srcdir)/depcomp
am__depfiles_maybe = depfiles
am__mv = mv -f
COMPILE = $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) \
	$(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
AM_V_CC = $(am__v_CC_$(V))
am__v_CC_ = $(am__v_CC_$(AM_DEFAULT_VERBOSITY))
am__v_CC_0 = @echo "  CC      " $@;
am__v_CC_1 = 
CCLD = $(CC)
LINK = $(CCLD) $(AM_CFLAGS) $(CFLAGS) $(AM_LDFLAGS) $(LDFLAGS) -o $@
AM_V_CCLD = $(am__v_CCLD_$(V))
am__v_CCLD_ = $(am__v_CCLD_$(AM_DEFAULT_VERBOSITY))
am__v_CCLD_0 = @echo "  CCLD    " $@;
am__v_CCLD_1 = 
SOURCES = $(libbz2_a_SOURCES)
DIST_SOURCES = $(libbz2_a_SOURCES)
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
am__tagged_files = $(HEADERS) $(SOURCES) $(TAGS_FILES) $(LISP)
# Read a list of newline-separated strings from the standard input,
# and print each of them once, without duplicates.  Input order is
# *not* preserved.
am__uniquify_input = $(AWK) '\
  BEGIN { nonempty = 0; } \
  { items[$$0] = 1; nonempty = 1; } \
  END { if (nonempty) { for (i in items) print i; }; } \
'
# Make sure the list of sources is unique.  This is necessary because,
# e.g., the same source file might be shared among _SOURCES variables
# for different programs/libraries.
am__define_uniq_tagged_files = \
  list='$(am__tagged_files)'; \
  unique=`for i in $$list; do \
    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
  done | $(am__uniquify_input)`
ETAGS = etags
CTAGS = ctags
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} /e/gtkspy/gtkspy/missing aclocal-1.13
AET2_CFLAGS = 
AET2_LDADD = 
ALLOCA = 
AMTAR = $${TAR-tar}
AM_DEFAULT_VERBOSITY = 1
AUTOCONF = ${SHELL} /e/gtkspy/gtkspy/missing autoconf
AUTOHEADER = ${SHELL} /e/gtkspy/gtkspy/missing autoheader
AUTOMAKE = ${SHELL} /e/gtkspy/gtkspy/missing automake-1.13
AWK = gawk
CC = gcc
CCDEPMODE = depmode=gcc3
CFLAGS = -g -O2  -DFST_WRITER_PARALLEL
COCOA_GTK_CFLAGS = 
COCOA_GTK_LDADD = 
COCOA_GTK_LDFLAGS = 
CPP = gcc -E
CPPFLAGS = -DWAVE_USE_GTK2 
CXX = g++
CXXDEPMODE = depmode=gcc3
CXXFLAGS = -g -O2
CYGPATH_W = echo
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EGREP = /bin/grep -E
EXEEXT = .exe
EXTDEBUG = notfound
EXTDEBUG2 = notfound
EXTDEBUG3 = notfound
EXTDEBUG4 = notfound
EXTLOAD_CFLAGS = 
FASTTREE_CFLAGS = 
FSDB_CFLAGS = 
FSDB_LDADD = 
GCONF_CFLAGS = 
GCONF_LIBS = 
GEDITTEST = notfound
GEDIT_CFLAGS = 
GPERF = /c/MinGW/bin/gperf
GREP = /bin/grep
GTK_CFLAGS = -mms-bitfields -Ic:/MinGW/include/gtk-2.0 -Ic:/MinGW/lib/gtk-2.0/include -Ic:/MinGW/include/atk-1.0 -Ic:/MinGW/include/cairo -Ic:/MinGW/include/gdk-pixbuf-2.0 -Ic:/MinGW/include/pango-1.0 -Ic:/MinGW/include/glib-2.0 -Ic:/MinGW/lib/glib-2.0/include -Ic:/MinGW/include -Ic:/MinGW/include/pixman-1 -Ic:/MinGW/include/freetype2 -Ic:/MinGW/include/libpng15  
GTK_CONFIG = 
GTK_LIBS = -Wl,-luuid -Lc:/MinGW/lib -lgtk-win32-2.0 -lgdk-win32-2.0 -limm32 -lshell32 -lole32 -latk-1.0 -lpangocairo-1.0 -lgio-2.0 -lgdk_pixbuf-2.0 -lpangoft2-1.0 -lpangowin32-1.0 -lgdi32 -lfreetype -lfontconfig -lpango-1.0 -lm -lcairo -lgobject-2.0 -lglib-2.0 -lintl  
GTK_MAC_CFLAGS = 
GTK_MAC_LIBS = 
GTK_UNIX_PRINT_CFLAGS = 
GTK_UNIX_PRINT_LIBS = 
INSTALL = /bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
LDFLAGS = 
LEX = flex
LEXLIB = 
LEX_OUTPUT_ROOT = lex.yy
LIBBZ2_CFLAGS = -I$(top_srcdir)/src/libbz2
LIBBZ2_DIR = libbz2
LIBBZ2_LDADD = $(top_builddir)/src/libbz2/libbz2.a
LIBJUDY_CFLAGS = 
LIBJUDY_LDADD = 
LIBOBJS =  ${LIBOBJDIR}error$U.o ${LIBOBJDIR}lstat$U.o
LIBS = -lm -ldl 
LIBXZ_CFLAGS = 
LIBXZ_LDADD = 
LIBZ_CFLAGS = 
LIBZ_DIR = 
LIBZ_LDADD = -lz
LTLIBOBJS =  ${LIBOBJDIR}error$U.lo ${LIBOBJDIR}lstat$U.lo
MAINT = #
MAKEINFO = ${SHELL} /e/gtkspy/gtkspy/missing makeinfo
MINGW_LDADD = -lcomdlg32
MKDIR_P = /bin/mkdir -p
OBJEXT = o
PACKAGE = gtkwave
PACKAGE_BUGREPORT = bybell@rocketmail.com
PACKAGE_NAME = gtkwave
PACKAGE_STRING = gtkwave 3.3.64
PACKAGE_TARNAME = gtkwave
PACKAGE_URL = 
PACKAGE_VERSION = 3.3.64
PATH_SEPARATOR = :
PKG_CONFIG = /c/MinGW/bin/pkg-config
POW_LIB = 
RANLIB = ranlib
SET_MAKE = 
SHELL = /bin/sh
STRIP = 
STRUCT_PACK = 
TCL_DEFADD = -DHAVE_LIBTCL
TCL_INCLUDE_SPEC = -I/mingw/include
TCL_LDADD = -L/mingw/lib -ltcl86
TCL_LIB_SPEC = -L/mingw/lib -ltcl86
TCL_MAJOR_VERSION = 8
TCL_MINOR_VERSION = 6
TK_INCLUDE_SPEC = 
TK_LDADD = -L/mingw/lib -ltk86
TK_LIB_SPEC = -L/mingw/lib -ltk86
UPDATE_DESKTOP_DATABASE = no
UPDATE_MIME_DATABASE = no
VERSION = 3.3.64
XDGDATADIR = ${datadir}
abs_builddir = /e/gtkspy/gtkspy/src/libbz2
abs_srcdir = /e/gtkspy/gtkspy/src/libbz2
abs_top_builddir = /e/gtkspy/gtkspy
abs_top_srcdir = /e/gtkspy/gtkspy
ac_ct_CC = gcc
ac_ct_CXX = g++
am__include = include
am__leading_dot = .
am__quote = 
am__tar = $${TAR-tar} chof - "$$tardir"
am__untar = $${TAR-tar} xf -
bindir = ${exec_prefix}/bin
build_alias = 
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
host_alias = 
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /e/gtkspy/gtkspy/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = $(MKDIR_P)
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /usr/local
program_transform_name = s,x,x,
psdir = ${docdir}
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = ../../
top_builddir = ../..
top_srcdir = ../..
noinst_LIBRARIES = libbz2.a
libbz2_a_SOURCES = blocksort.c  bzlib.h          compress.c  decompress.c  randtable.c \
	bzlib.c      bzlib_private.h  crctable.c  huffman.c

EXTRA_DIST = bzlib.h LICENSE
all: all-am

.SUFFIXES:
.SUFFIXES: .c .o .obj
$(srcdir)/Makefile.in: # $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --foreign src/libbz2/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --foreign src/libbz2/Makefile
.PRECIOUS: Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure: # $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4): # $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):

clean-noinstLIBRARIES:
	-test -z "$(noinst_LIBRARIES)" || rm -f $(noinst_LIBRARIES)
libbz2.a: $(libbz2_a_OBJECTS) $(libbz2_a_DEPENDENCIES) $(EXTRA_libbz2_a_DEPENDENCIES) 
	$(AM_V_at)-rm -f libbz2.a
	$(AM_V_AR)$(libbz2_a_AR) libbz2.a $(libbz2_a_OBJECTS) $(libbz2_a_LIBADD)
	$(AM_V_at)$(RANLIB) libbz2.a

mostlyclean-compile:
	-rm -f *.$(OBJEXT)

distclean-compile:
	-rm -f *.tab.c

include ./$(DEPDIR)/blocksort.Po
include ./$(DEPDIR)/bzlib.Po
include ./$(DEPDIR)/compress.Po
include ./$(DEPDIR)/crctable.Po
include ./$(DEPDIR)/decompress.Po
include ./$(DEPDIR)/huffman.Po
include ./$(DEPDIR)/randtable.Po

.c.o:
	$(AM_V_CC)$(COMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
	$(AM_V_at)$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	$(AM_V_CC)source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(AM_V_CC_no)$(COMPILE) -c $<

.c.obj:
	$(AM_V_CC)$(COMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ `$(CYGPATH_W) '$<'`
	$(AM_V_at)$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	$(AM_V_CC)source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(AM_V_CC_no)$(COMPILE) -c `$(CYGPATH_W) '$<'`

ID: $(am__tagged_files)
	$(am__define_uniq_tagged_files); mkid -fID $$unique
tags: tags-am
TAGS: tags

tags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	set x; \
	here=`pwd`; \
	$(am__define_uniq_tagged_files); \
	shift; \
	if test -z "$(ETAGS_ARGS)$$*$$unique"; then :; else \
	  test -n "$$unique" || unique=$$empty_fix; \
	  if test $$# -gt 0; then \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      "$$@" $$unique; \
	  else \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      $$unique; \
	  fi; \
	fi
ctags: ctags-am

CTAGS: ctags
ctags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	$(am__define_uniq_tagged_files); \
	test -z "$(CTAGS_ARGS)$$unique" \
	  || $(CTAGS) $(CTAGSFLAGS) $(AM_CTAGSFLAGS) $(CTAGS_ARGS) \
	     $$unique

GTAGS:
	here=`$(am__cd) $(top_builddir) && pwd` \
	  && $(am__cd) $(top_srcdir) \
	  && gtags -i $(GTAGS_ARGS) "$$here"
cscopelist: cscopelist-am

cscopelist-am: $(am__tagged_files)
	list='$(am__tagged_files)'; \
	case "$(srcdir)" in \
	  [\\/]* | ?:[\\/]*) sdir="$(srcdir)" ;; \
	  *) sdir=$(subdir)/$(srcdir) ;; \
	esac; \
	for i in $$list; do \
	  if test -f "$$i"; then \
	    echo "$(subdir)/$$i"; \
	  else \
	    echo "$$sdir/$$i"; \
	  fi; \
	done >> $(top_builddir)/cscope.files

distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH tags

distdir: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
check: check-am
all-am: Makefile $(LIBRARIES)
installdirs:
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	if test -z '$(STRIP)'; then \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	      install; \
	else \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	    "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'" install; \
	fi
mostlyclean-generic:

clean-generic:

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am

clean-am: clean-generic clean-noinstLIBRARIES mostlyclean-am

distclean: distclean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
distclean-am: clean-am distclean-compile distclean-generic \
	distclean-tags

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am:

install-dvi: install-dvi-am

install-dvi-am:

install-exec-am:

install-html: install-html-am

install-html-am:

install-info: install-info-am

install-info-am:

install-man:

install-pdf: install-pdf-am

install-pdf-am:

install-ps: install-ps-am

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-compile mostlyclean-generic

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am:

.MAKE: install-am install-strip

.PHONY: CTAGS GTAGS TAGS all all-am check check-am clean clean-generic \
	clean-noinstLIBRARIES cscopelist-am ctags ctags-am distclean \
	distclean-compile distclean-generic distclean-tags distdir dvi \
	dvi-am html html-am info info-am install install-am \
	install-data install-data-am install-dvi install-dvi-am \
	install-exec install-exec-am install-html install-html-am \
	install-info install-info-am install-man install-pdf \
	install-pdf-am install-ps install-ps-am install-strip \
	installcheck installcheck-am installdirs maintainer-clean \
	maintainer-clean-generic mostlyclean mostlyclean-compile \
	mostlyclean-generic pdf pdf-am ps ps-am tags tags-am uninstall \
	uninstall-am


# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
