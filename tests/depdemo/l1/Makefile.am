## Makefile.am -- Process this file with automake to produce Makefile.in
##
##   Copyright (C) 2003, 2010 Free Software Foundation
##   Written by Gary V. Vaughan, 2003
##
##   This file is part of GNU Libtool.
##
## GNU Libtool is free software; you can redistribute it and/or
## modify it under the terms of the GNU General Public License as
## published by the Free Software Foundation; either version 2 of
## the License, or (at your option) any later version.
##
## GNU Libtool is distributed in the hope that it will be useful,
## but WITHOUT ANY WARRANTY; without even the implied warranty of
## MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
## GNU General Public License for more details.
##
## You should have received a copy of the GNU General Public License
## along with GNU Libtool; see the file COPYING.  If not, a copy
## can be downloaded from  http://www.gnu.org/licenses/gpl.html,
## or obtained by writing to the Free Software Foundation, Inc.,
## 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301, USA.
#####

top_distdir = ../..

AUTOMAKE_OPTIONS = no-dependencies foreign

AM_CPPFLAGS = -I$(top_srcdir) -DBUILDING_LIBL1

lib_LTLIBRARIES = libl1.la
libl1_la_SOURCES = l1.c l1.h
libl1_la_LDFLAGS = -no-undefined
