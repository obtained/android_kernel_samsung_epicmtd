#
# Makefile for kernel Onedram drivers.
#
ifeq ($(CONFIG_MACH_FORTE),y)
obj-$(CONFIG_SAMSUNG_PHONE_TTY) +=dpram_forte.o
endif

ifeq ($(CONFIG_MACH_ATLAS),y)
obj-$(CONFIG_SAMSUNG_PHONE_TTY) +=dpram_atlas.o
endif
ifeq ($(CONFIG_MACH_VICTORY),y)
obj-$(CONFIG_SAMSUNG_PHONE_TTY) +=dpram.o
endif
