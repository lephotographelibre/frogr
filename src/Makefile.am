# Copyright (C) 2009-2012 Mario Sanchez Prada
# Authors: Mario Sanchez Prada <msanchez@gnome.org>
#
# This program is free software; you can redistribute it and/or
# modify it under the terms of version 3 of the GNU General Public
# License as published by the Free Software Foundation.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
# General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program; if not, see <http://www.gnu.org/licenses/>

MAINTAINERCLEANFILES = \
	Makefile.in

SUBDIRS = flicksoup examples

bin_PROGRAMS = frogr

frogr_LDADD = \
       flicksoup/libflicksoup.a \
       $(FROGR_LIBS)

frogr_CFLAGS = $(FROGR_CFLAGS) \
	-DDATA_DIR=\"$(DATA_DIR)\"

if PLATFORM_MAC
frogr_CFLAGS += -DPLATFORM_MAC
else
frogr_LDFLAGS = -export-dynamic
endif

frogr_SOURCES = \
	frogr-about-dialog.c \
	frogr-about-dialog.h \
	frogr-account.c \
	frogr-account.h \
	frogr-add-tags-dialog.c \
	frogr-add-tags-dialog.h \
	frogr-add-to-group-dialog.c \
	frogr-add-to-group-dialog.h \
	frogr-add-to-set-dialog.c \
	frogr-add-to-set-dialog.h \
	frogr-auth-dialog.c \
	frogr-auth-dialog.h \
	frogr-config.c \
	frogr-config.h \
	frogr-controller.c \
	frogr-controller.h \
	frogr-create-new-set-dialog.c \
	frogr-create-new-set-dialog.h \
	frogr-details-dialog.c \
	frogr-details-dialog.h \
	frogr-file-loader.c \
	frogr-file-loader.h \
	frogr-global-defs.h \
	frogr-group.c \
	frogr-group.h \
	frogr-live-entry.c \
	frogr-live-entry.h \
	frogr-location.c \
	frogr-location.h \
	frogr-main-view.c \
	frogr-main-view.h \
	frogr-model.c \
	frogr-model.h \
	frogr-photoset.c \
	frogr-photoset.h \
	frogr-picture.c \
	frogr-picture.h \
	frogr-settings-dialog.c \
	frogr-settings-dialog.h \
	frogr-util.c \
	frogr-util.h \
	main.c
