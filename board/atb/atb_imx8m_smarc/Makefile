#
# Copyright 2017 NXP
#
# SPDX-License-Identifier:      GPL-2.0+
#

obj-y += atb_imx8m_smarc.o

ifdef CONFIG_SPL_BUILD
obj-y += spl.o
obj-$(CONFIG_IMX8M_LPDDR4) += lpddr4_timing_b0.o
obj-$(CONFIG_IMX8M_LPDDR4) += lpddr4_timing.o
endif
