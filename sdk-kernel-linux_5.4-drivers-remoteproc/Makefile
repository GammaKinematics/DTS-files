# SPDX-License-Identifier: GPL-2.0
#
# Generic framework for controlling remote processors
#

obj-$(CONFIG_REMOTEPROC)		+= remoteproc.o
remoteproc-y				:= remoteproc_core.o
remoteproc-y				+= remoteproc_debugfs.o
remoteproc-y				+= remoteproc_sysfs.o
remoteproc-y				+= remoteproc_virtio.o
remoteproc-y				+= remoteproc_elf_loader.o
remoteproc-$(CONFIG_SUNXI_REMOTEPROC_TRACE_DEV)	+= sunxi_rproc_trace.o
obj-$(CONFIG_IMX_REMOTEPROC)		+= imx_rproc.o
obj-$(CONFIG_OMAP_REMOTEPROC)		+= omap_remoteproc.o
obj-$(CONFIG_WKUP_M3_RPROC)		+= wkup_m3_rproc.o
obj-$(CONFIG_DA8XX_REMOTEPROC)		+= da8xx_remoteproc.o
obj-$(CONFIG_KEYSTONE_REMOTEPROC)	+= keystone_remoteproc.o
obj-$(CONFIG_QCOM_RPROC_COMMON)		+= qcom_common.o
obj-$(CONFIG_QCOM_Q6V5_COMMON)		+= qcom_q6v5.o
obj-$(CONFIG_QCOM_Q6V5_ADSP)		+= qcom_q6v5_adsp.o
obj-$(CONFIG_QCOM_Q6V5_MSS)		+= qcom_q6v5_mss.o
obj-$(CONFIG_QCOM_Q6V5_PAS)		+= qcom_q6v5_pas.o
obj-$(CONFIG_QCOM_Q6V5_WCSS)		+= qcom_q6v5_wcss.o
obj-$(CONFIG_QCOM_SYSMON)		+= qcom_sysmon.o
obj-$(CONFIG_QCOM_WCNSS_PIL)		+= qcom_wcnss_pil.o
qcom_wcnss_pil-y			+= qcom_wcnss.o
qcom_wcnss_pil-y			+= qcom_wcnss_iris.o
obj-$(CONFIG_ST_REMOTEPROC)		+= st_remoteproc.o
obj-$(CONFIG_ST_SLIM_REMOTEPROC)	+= st_slim_rproc.o
obj-$(CONFIG_STM32_RPROC)		+= stm32_rproc.o
obj-$(CONFIG_SUNXI_REMOTEPROC)		+= sunxi_remoteproc.o
sunxi_remoteproc-y			+= sunxi_rproc.o
sunxi_remoteproc-y			+= sunxi_rproc_boot.o
sunxi_remoteproc-y			+= sunxi_rproc_firmware.o
obj-$(CONFIG_SUNXI_REMOTEPROC_HIFI4_BOOT) += sunxi_rproc_hifi4_boot.o
obj-$(CONFIG_SUNXI_REMOTEPROC_E906_BOOT) += sunxi_rproc_e906_boot.o
obj-$(CONFIG_SUNXI_REMOTEPROC_C906_BOOT) += sunxi_rproc_c906_boot.o
obj-$(CONFIG_SUNXI_REMOTEPROC_SRM_CORE)	+= sunxi_rproc_srm_core.o
obj-$(CONFIG_SUNXI_REMOTEPROC_SRM_DEV)	+= sunxi_rproc_srm_dev.o
