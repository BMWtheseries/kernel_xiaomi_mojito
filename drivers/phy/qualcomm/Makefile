# SPDX-License-Identifier: GPL-2.0
obj-$(CONFIG_PHY_QCOM_APQ8064_SATA)	+= phy-qcom-apq8064-sata.o
obj-$(CONFIG_PHY_QCOM_IPQ806X_SATA)	+= phy-qcom-ipq806x-sata.o
obj-$(CONFIG_PHY_QCOM_PCIE2)		+= phy-qcom-pcie2.o
obj-$(CONFIG_PHY_QCOM_QMP)		+= phy-qcom-qmp.o
obj-$(CONFIG_PHY_QCOM_QUSB2)		+= phy-qcom-qusb2.o

obj-$(CONFIG_PHY_QCOM_UFS) 	+= phy-qcom-ufs.o
ifeq ($(CONFIG_ARCH_SM6150), y)
obj-$(CONFIG_PHY_QCOM_UFS) 	+= phy-qcom-ufs-qmp-v3-660.o
else
obj-$(CONFIG_PHY_QCOM_UFS) 	+= phy-qcom-ufs-qmp-v3.o
obj-$(CONFIG_PHY_QCOM_UFS) 	+= phy-qcom-ufs-qmp-14nm.o
obj-$(CONFIG_PHY_QCOM_UFS) 	+= phy-qcom-ufs-qrbtc-sdm845.o
obj-$(CONFIG_PHY_QCOM_UFS) 	+= phy-qcom-ufs-qmp-v3-660.o
obj-$(CONFIG_PHY_QCOM_UFS) 	+= phy-qcom-ufs-qmp-v4.o
endif

obj-$(CONFIG_PHY_QCOM_USB_HS) 		+= phy-qcom-usb-hs.o
obj-$(CONFIG_PHY_QCOM_USB_HSIC) 	+= phy-qcom-usb-hsic.o
