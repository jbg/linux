# SPDX-License-Identifier: GPL-2.0
obj-$(CONFIG_WILC1000) += wilc1000.o

ccflags-y += -DFIRMWARE_1002=\"atmel/wilc1002_firmware.bin\" \
		-DFIRMWARE_1003=\"atmel/wilc1003_firmware.bin\"

wilc1000-objs := cfg80211.o netdev.o mon.o \
			hif.o wlan_cfg.o wlan.o

obj-$(CONFIG_WILC1000_SDIO) += wilc1000-sdio.o
wilc1000-sdio-objs += sdio.o

obj-$(CONFIG_WILC1000_SPI) += wilc1000-spi.o
wilc1000-spi-objs += spi.o
