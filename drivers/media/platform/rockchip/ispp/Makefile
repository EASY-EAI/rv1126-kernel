# SPDX-License-Identifier: GPL-2.0
obj-$(CONFIG_VIDEO_ROCKCHIP_ISPP) += video_rkispp.o

video_rkispp-objs += dev.o \
		common.o \
		ispp.o \
		stream.o \
		params.o \
		stats.o \
		hw.o \
		procfs.o

ifdef CONFIG_VIDEO_ROCKCHIP_ISPP_FEC
video_rkispp-objs += fec.o
endif
