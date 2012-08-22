#
# Makefile for the sensor drivers.
#

# Each configuration option enables a list of files.

ifeq ($(CONFIG_MACH_MSM7X27_THUNDERG), y)
obj-$(CONFIG_SENSOR_GP2AP)  += gp2ap002_thunderg.o
else
obj-$(CONFIG_SENSOR_GP2AP)  += gp2ap002.o
endif
obj-$(CONFIG_SENSOR_BMA150)	+= bma150.o
obj-$(CONFIG_SENSOR_KR3DM)	+= kr3dm.o
obj-$(CONFIG_SENSOR_KR3DH)	+= kr3dh.o
obj-$(CONFIG_SENSOR_AK8973)	+= akm8973.o
obj-$(CONFIG_SENSOR_AMI602) += ami602.o
obj-$(CONFIG_SENSOR_AMI304) += ami304.o
