# Makefile.am - PIN entry emacs frontend.
# Copyright (C) 2002, 2015 g10 Code GmbH
#
# This file is part of PINENTRY.
#
# PINENTRY is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2 of the License, or
# (at your option) any later version.
#
# PINENTRY is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program; if not, see <https://www.gnu.org/licenses/>.
# SPDX-License-Identifier: GPL-2.0+

## Process this file with automake to produce Makefile.in

bin_PROGRAMS = pinentry-emacs

AM_CPPFLAGS = $(COMMON_CFLAGS) $(NEMACS_INCLUDE) -I$(top_srcdir)/pinentry
LDADD = ../pinentry/libpinentry.a ../secmem/libsecmem.a \
	$(COMMON_LIBS) $(LIBEMACS) $(LIBICONV)

pinentry_emacs_SOURCES = pinentry-emacs.c
