#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.
#
# $Id: configure.ac,v 1.12 2004/09/19 20:19:16 psy Exp $

AC_PREREQ(2.57)
AC_INIT(GPP, 2.24, psychonaut@nothingisreal.com, gpp)
AM_INIT_AUTOMAKE
AC_CONFIG_SRCDIR([src/gpp.c])
AC_CONFIG_HEADER([config.h])

# Checks for programs.
AC_PROG_CC

# Checks for libraries.

# Checks for header files.
AC_HEADER_STDC
AC_CHECK_HEADERS([stdlib.h string.h fnmatch.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_C_CONST
AC_C_INLINE
AC_TYPE_SIZE_T

# Checks for library functions.
AC_CHECK_FUNCS([strcasecmp strchr strdup strtol])

AC_CONFIG_FILES([Makefile
                 src/Makefile])
AC_OUTPUT
