#
# Copyright 2009-2011 Freescale Semiconductor, Inc.
#
# SPDX-License-Identifier:	GPL-2.0+
#

obj-y += dtsec.o
obj-y += eth.o
obj-y += fdt.o
obj-y += fm.o
obj-y += init.o
obj-y += tgec.o
obj-y += tgec_phy.o

# Soc have FMAN v3 with mEMAC
obj-$(CONFIG_SYS_FMAN_V3) += memac_phy.o
obj-$(CONFIG_SYS_FMAN_V3) += memac.o

# SoC specific SERDES support
obj-$(CONFIG_P1017)	+= p1023.o
obj-$(CONFIG_P1023)	+= p1023.o
# The P204x, P304x, and P5020 are the same
obj-$(CONFIG_PPC_P2041) += p5020.o
obj-$(CONFIG_PPC_P3041) += p5020.o
obj-$(CONFIG_PPC_P4080) += p4080.o
obj-$(CONFIG_PPC_P5020) += p5020.o
obj-$(CONFIG_PPC_P5040) += p5040.o
obj-$(CONFIG_PPC_T1040) += t1040.o
obj-$(CONFIG_PPC_T1042)	+= t1040.o
obj-$(CONFIG_PPC_T1020)	+= t1040.o
obj-$(CONFIG_PPC_T1022)	+= t1040.o
obj-$(CONFIG_PPC_T1023) += t1024.o
obj-$(CONFIG_PPC_T1024) += t1024.o
obj-$(CONFIG_PPC_T2080) += t2080.o
obj-$(CONFIG_PPC_T2081) += t2080.o
obj-$(CONFIG_PPC_T4240) += t4240.o
obj-$(CONFIG_PPC_T4160) += t4240.o
obj-$(CONFIG_PPC_T4080) += t4240.o
obj-$(CONFIG_PPC_B4420) += b4860.o
obj-$(CONFIG_PPC_B4860) += b4860.o
obj-$(CONFIG_LS1043A)	+= ls1043.o
