mediatek-drm-y := mtk_disp_ovl.o \
		  mtk_drm_crtc.o \
		  mtk_drm_ddp.o \
		  mtk_drm_ddp_comp.o \
		  mtk_drm_drv.o \
		  mtk_drm_fb.o \
		  mtk_drm_gem.o \
		  mtk_drm_plane.o \
		  mtk_dsi.o \
		  mtk_mipi_tx.o \
		  mtk_dpi.o
ifeq ($(CONFIG_DEBUG_FS),y)
mediatek-drm-y += mtk_drm_debugfs.o
endif

obj-$(CONFIG_DRM_MEDIATEK) += mediatek-drm.o

mediatek-drm-hdmi-objs := mtk_drm_hdmi_drv.o \
			  mtk_cec.o \
			  mtk_hdmi_ddc_drv.o \
			  mtk_hdmi.o \
			  mtk_hdmi_hw.o
ifeq ($(CONFIG_DEBUG_FS),y)
mediatek-drm-hdmi-objs += mtk_hdmi_debugfs.o
endif

obj-$(CONFIG_DRM_MEDIATEK_HDMI) += mediatek-drm-hdmi.o
