subdir-ccflags-y += 

mediatek-drm-y := mtk_disp_color.o \
		  mtk_disp_ovl.o \
		  mtk_disp_rdma.o \
		  mtk_drm_crtc.o \
		  mtk_drm_ddp.o \
		  mtk_drm_ddp_comp.o \
		  mtk_drm_drv.o \
		  mtk_drm_fb.o \
		  mtk_drm_gem.o \
		  mtk_drm_plane.o \
		  mtk_dsi.o \
		  mtk_mipi_tx.o \
		  mtk_dpi.o \
		  mtk_lvds.o \
		  mtk_lvds_phy.o

ifeq ($(CONFIG_DEBUG_FS),y)
mediatek-drm-y += mtk_drm_debugfs.o
endif

obj-$(CONFIG_DRM_MEDIATEK) += mediatek-drm.o

mediatek-drm-hdmi-objs := mtk_cec.o \
			  mtk_hdmi.o \
			  mtk_hdmi_ddc.o \
			  mtk_mt8173_hdmi_phy.o

obj-$(CONFIG_DRM_MEDIATEK_HDMI) += mediatek-drm-hdmi.o
