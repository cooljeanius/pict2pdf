dnl#                                               -*- Autoconf -*-
dnl# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.61])
AC_INIT([pict2pdf],[1.1],[prahl@bme.ogi.edu])
AC_CONFIG_SRCDIR([pict2pdf.c])
AC_CONFIG_AUX_DIR([build-aux])
AC_CONFIG_MACRO_DIR([m4])
AC_CONFIG_HEADER([config.h])
dnl#TODO: convert to AM\_INIT\_AUTOMAKE
AM_MAINTAINER_MODE
AC_CANONICAL_HOST

# Checks for programs.
AC_PROG_CXX
AC_PROG_CC
AM_PROG_CC_C_O
AC_PROG_CPP
AC_PROG_INSTALL
AC_PROG_LN_S
AC_PATH_PROG([RM],[rm])
AX_PROG_SCP
AC_SUBST([RM])dnl
EBG_DEVELOPER_DIR
AC_SUBST([DEVELOPER_DIR])dnl

# Checks for libraries.

# Checks for header files.
AC_HEADER_STDC
AC_CHECK_HEADERS([ApplicationServices/ApplicationServices.h QD.h QD/QD.h \
                  Quickdraw.h QD/Quickdraw.h])dnl

# Checks for typedefs, structures, and compiler characteristics.
AC_CHECK_TYPES([QDPictRef])dnl

# Checks for library functions.

# Output.
AC_CONFIG_FILES([Makefile])
AC_OUTPUT
