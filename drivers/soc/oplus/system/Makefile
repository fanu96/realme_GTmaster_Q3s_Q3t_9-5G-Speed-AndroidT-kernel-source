# SPDX-License-Identifier: GPL-2.0-only
# Copyright (C) 2018-2020 Oplus. All rights reserved.
#
# Makefile for the OPLUS Linux Kernel system team specific device drivers.
#

obj-y 	+= platform.o
obj-$(CONFIG_OPLUS_FEATURE_FEEDBACK) 	+= feedback/
obj-$(CONFIG_OPLUS_FEATURE_UBOOT_LOG) 	+= uboot_log/
obj-$(CONFIG_OPLUS_FEATURE_SHUTDOWN_DETECT)    += shutdown_detect/
obj-$(CONFIG_OPLUS_FEATURE_SLABTRACE_DEBUG) +=  slabtrace/
obj-$(CONFIG_OPLUS_FEATURE_OPROJECT) 	+= oplus_project/
obj-$(CONFIG_OPLUS_FEATURE_QCOM_MINIDUMP_ENHANCE) 	+= qcom_minidump/
obj-$(CONFIG_OPLUS_FEATURE_HUNG_TASK_ENHANCE) += hung_task_enhance/
obj-$(CONFIG_OPLUS_FEATURE_PHOENIX)     += oplus_phoenix/
obj-$(CONFIG_OPLUS_FEATURE_PMIC_MONITOR)     += oplus_pmic_monitor/
obj-$(CONFIG_OPLUS_FEATURE_SAUPWK)     += oplus_saupwk/
obj-$(CONFIG_OPLUS_FEATURE_DUMP_DEVICE_INFO)	+=  dump_device_info/
obj-$(CONFIG_OPLUS_FEATURE_RECORD_MDMRST)     += mdmrst/
obj-$(CONFIG_OPLUS_FEATURE_CMDLINE)     += cmdline_parser/
#ifdef OPLUS_FEATURE_DUMP_REASON
obj-$(CONFIG_OPLUS_FEATURE_DUMP_REASON)	+=  dump_reason/
#endif /* OPLUS_FEATURE_DUMP_REASON */

ifdef CONFIG_OPLUS_SYSTEM_KERNEL_QCOM
obj-$(CONFIG_OPLUS_FEATURE_PROJECTINFO)	+=  project_info/
endif

#ifdef OPLUS_FEATURE_ESIM
obj-$(CONFIG_OPLUS_OPPO_GPIO)    +=  oppo_gpio/
#endif /* OPLUS_FEATURE_ESIM */

#ifdef OPLUS_FEATURE_QCOM_PMICWD
obj-$(CONFIG_OPLUS_FEATURE_QCOM_PMICWD)     += qcom_pmicwd/
#endif /* OPLUS_FEATURE_QCOM_PMICWD */

#ifdef OPLUS_FEATURE_MM_FEEDBACK
obj-$(CONFIG_OPLUS_FEATURE_MM_FEEDBACK)         += oplus_mm_fb/
#endif /* OPLUS_FEATURE_MM_FEEDBACK */

#ifdef OPLUS_FEATURE_QCOM_WATCHDOG
obj-$(CONFIG_OPLUS_FEATURE_QCOM_WATCHDOG)     += qcom_watchdog/
#endif /* OPLUS_FEATURE_QCOM_WATCHDOG */

#ifdef OPLUS_FEATURE_ACM
obj-$(CONFIG_OPLUS_FEATURE_ACM)     += acm/
#endif /* OPLUS_FEATURE_ACM */
#ifdef OPLUS_FEATURE_THEIA
obj-$(CONFIG_OPLUS_FEATURE_THEIA)     += theia/
#endif /* OPLUS_FEATURE_THEIA */
#ifdef OPLUS_FEATURE_MISC
obj-y += misc/
#endif /* OPLUS_FEATURE_MISC */
