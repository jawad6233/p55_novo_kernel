
include $(srctree)/drivers/misc/mediatek/Makefile.custom

# Module project related part

ifeq ($(CONFIG_MTK_SENSOR_SUPPORT),y)
ifeq ($(CONFIG_MTK_CM36283),y)
obj-y	+=  alsps/cm36283/
endif

ifeq ($(CONFIG_MTK_BMA056),y)
obj-y   +=  accelerometer/bma056/
endif

ifeq ($(CONFIG_MTK_BMA222E_AUTO),y)
obj-y   +=  accelerometer/bma222E_auto/
endif

ifeq ($(CONFIG_MTK_BMM056_NEW),y)
obj-y	+=  magnetometer/bmm056-new/
endif
endif
ifneq ($(CONFIG_ARCH_MTK_PROJECT),)
ARCH_MTK_PROJECT := $(shell echo $(CONFIG_ARCH_MTK_PROJECT))
obj-y	+= core/
obj-y	+= dct/dct/
endif

#obj-y   +=  lcm/
obj-y	+=  camera/camera/
obj-y 	+=  flashlight/constant_flashlight/
obj-y	+=  vibrator/
obj-y	+=  leds/
obj-y	+=  keypad/
obj-y	+=  sound/
obj-y	+=  accdet/


