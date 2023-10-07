# SPDX-License-Identifier: GPL-2.0-or-later
#
# Makefile for the linux exFAT filesystem support.
#

exfat-y	:= inode.o namei.o dir.o super.o fatent.o cache.o nls.o misc.o file.o balloc.o
obj-$(CONFIG_EXFAT_FS) += exfat.o

.PHONY : all clean install uninstall
