# configure.ac
# ------------------------------------------------------------------------------
#
# Process this file with autoconf, to create a configure script for
# MinGW.OSDN base package specification maintenance.
#
# $Id$
#
  m4_define([__VERSION__],[0.1])
#
# Written by Keith Marshall <keith@users.osdn.me>
# Copyright (C) 2022, MinGW.OSDN Project
#
#
# Permission is hereby granted, free of charge, to any person obtaining a
# copy of this software and associated documentation files (the "Software"),
# to deal in the Software without restriction, including without limitation
# the rights to use, copy, modify, merge, publish, distribute, sublicense,
# and/or sell copies of the Software, and to permit persons to whom the
# Software is furnished to do so, subject to the following conditions:
#
# The above copyright notice and this permission notice (including the next
# paragraph) shall be included in all copies or substantial portions of the
# Software.
#
# THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
# OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
# FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
# AUTHORS OR THE COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
# LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
# FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
# DEALINGS IN THE SOFTWARE.
#
# ------------------------------------------------------------------------------
#
  AC_INIT([mingw-pkgspecs],[__VERSION__],[https://mingw.osdn.io/?page=buginfo])

# Identify the host architecture, to which the generated specifications
# are to relate.
#
  AC_ARG_VAR([ARCH],[Host OS identifier for target architecture [[mingw32]]])
  AC_SUBST([ARCH],[${ARCH-mingw32}])

# Checks for programs required to support the build system.
#
  AC_PROG_AWK
  AC_PROG_LN_S
  AC_PROG_MKDIR_P
  AC_PROG_SED

# Construct the basic build system configuration framework.
#
  AC_CONFIG_FILES([Makefile])
  AC_OUTPUT
#
# $RCSfile$: end of file
