ccflags-y := -I$(src) -Wall -Werror

LINUXINCLUDE    += \
                -I$(srctree)/techpack/audio/include/dsp \
                -I$(srctree)/techpack/audio/include/uapi \
                -I$(srctree)/techpack/audio/include

obj-y += elliptic.o
obj-y += elliptic_mixer_controls.o
obj-y += io_modules/msm/elliptic_data_msm_io.o
obj-y += io_modules/userspace/elliptic_data_userspace_io.o
obj-y += io_modules/userspace/elliptic_data_userspace_ctrl.o
obj-y += elliptic_sysfs.o
