dtbs-$(CONFIG_CPU_SUBTYPE_J2) += j2_mimas_v2.dtb

ifneq ($(CONFIG_BUILTIN_DTB_SOURCE),"")
obj-y += $(patsubst "%",%,$(CONFIG_BUILTIN_DTB_SOURCE)).dtb.o
endif
