ccflags-y += -Idrivers/media/platform/msm/camera_v2_oppo_n3
ccflags-y += -Idrivers/media/platform/msm/camera_v2_oppo_n3/sensor/io
ifeq ($(CONFIG_MSM_CSI20_HEADER),y)
  ccflags-y += -Idrivers/media/platform/msm/camera_v2_oppo_n3/sensor/csiphy/include/csi2.0
else ifeq ($(CONFIG_MSM_CSI22_HEADER),y)
  ccflags-y += -Idrivers/media/platform/msm/camera_v2_oppo_n3/sensor/csiphy/include/csi2.2
else ifeq ($(CONFIG_MSM_CSI30_HEADER),y)
  ccflags-y += -Idrivers/media/platform/msm/camera_v2_oppo_n3/sensor/csiphy/include/csi3.0
endif
obj-$(CONFIG_MSM_CSIPHY) += msm_csiphy.o
