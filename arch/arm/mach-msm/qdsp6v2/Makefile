obj-y += rtac.o
ifdef CONFIG_ARCH_MSM8X60
obj-y += audio_dev_ctl.o
ifeq ($(CONFIG_MACH_MSM8X60_PRESTO),y)
obj-y += board-presto-audio.o
else
obj-y += board-msm8x60-audio.o
endif
obj-$(CONFIG_TIMPANI_CODEC) += snddev_icodec.o
obj-y += snddev_ecodec.o snddev_mi2s.o snddev_virtual.o
obj-y += pcm_out.o pcm_in.o fm.o
obj-y += audio_lpa.o
obj-y += q6voice.o
obj-y += snddev_hdmi.o
obj-y += audio_mvs.o
obj-$(CONFIG_FB_MSM_HDMI_MSM_PANEL) += lpa_if_hdmi.o
endif
obj-$(CONFIG_MSM_QDSP6_APR) += apr.o apr_tal.o q6core.o dsp_debug.o
obj-y += audio_acdb.o
obj-y += aac_in.o qcelp_in.o evrc_in.o amrnb_in.o audio_utils.o
obj-y += audio_wma.o audio_wmapro.o audio_aac.o audio_multi_aac.o audio_utils_aio.o
obj-$(CONFIG_MSM_QDSP6_CODECS) += q6audio_v1.o q6audio_v1_aio.o
obj-$(CONFIG_MSM_ULTRASOUND) += ultrasound/
obj-y += audio_mp3.o audio_amrnb.o audio_amrwb.o audio_evrc.o audio_qcelp.o amrwb_in.o

ifeq ($(CONFIG_PANTECH_AUDIO_PRESTO_FAB2200), y)
obj-y += snd_presto_sub_fab2200.o
obj-$(CONFIG_PANTECH_AUDIO_SUBCHIP_CAL_TOOL) += sky_snd_presto_extampctrl.o
endif
obj-$(CONFIG_PANTECH_AUDIO_PRESTO_AUDIENCE2020) += snd_presto_audience_a2020.o
