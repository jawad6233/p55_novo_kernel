include $(srctree)/drivers/misc/mediatek/Makefile.custom

obj-y   +=  mt65xx_lcm_list.o

ifeq ($(CONFIG_CUSTOM_KERNEL_LCM),"otm1283a_jmo")
obj-y   +=  otm1283a_jmo.o
endif

ifeq ($(CONFIG_CUSTOM_KERNEL_LCM),"otm1283a_hd_pngd")
obj-y   +=  otm1283a_hd_pngd.o
endif

ifeq ($(CONFIG_CUSTOM_KERNEL_LCM),"otm1283a_hd_dsi")
obj-y   +=  otm1283a_hd_dsi.o
endif

