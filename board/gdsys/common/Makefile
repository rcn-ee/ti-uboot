# SPDX-License-Identifier: GPL-2.0+
#
# (C) Copyright 2007
# Stefan Roese, DENX Software Engineering, sr@denx.de.

obj-$(CONFIG_SYS_FPGA_COMMON) += fpga.o
obj-$(CONFIG_CMD_IOLOOP) += cmd_ioloop.o
obj-$(CONFIG_CONTROLCENTERD) += dp501.o
obj-$(CONFIG_TARGET_GAZERBEAM) += osd.o ihs_mdio.o ioep-fpga.o

ifdef CONFIG_OSD
obj-$(CONFIG_GDSYS_LEGACY_OSD_CMDS) += osd_cmd.o
endif
