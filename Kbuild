
dtbo-$(CONFIG_ARCH_WAIPIO) += waipio-audio.dtbo \
#                 waipio-audio-cdp.dtbo \
#                 waipio-audio-mtp.dtbo \
#                 waipio-audio-qrd.dtbo \
#                 waipio-audio-atp.dtbo \
#                 waipio-audio-rumi.dtbo \
#                 waipio-audio-hdk.dtbo

dtbo-$(CONFIG_ARCH_DIWALI) += diwali-audio.dtbo \
                 diwali-audio-idp.dtbo \
                 diwali-audio-idp-amoled.dtbo \
                 diwali-audio-qrd.dtbo \
                 diwali-audio-atp.dtbo \
                 diwali-audio-idp-hsp.dtbo \
                 diwali-audio-idp-usbc.dtbo

dtbo-$(CONFIG_ARCH_PARROT) += parrot-audio.dtbo \
                 parrot-audio-idp.dtbo \
                 parrot-audio-idp-wcn3990.dtbo \
                 parrot-audio-idp-wcn3990-amoled-rcm.dtbo \
                 parrot-audio-idp-wcn6750-amoled.dtbo \
                 parrot-audio-idp-wcn6750-amoled-rcm.dtbo \
                 parrot-audio-qrd.dtbo \
                 parrot-audio-qrd-wcn6750.dtbo \
                 parrot-audio-atp.dtbo

dtbo-$(CONFIG_ARCH_CAPE) += cape-audio.dtbo \
                 cape-audio-cdp.dtbo \
                 cape-audio-cdp-qhd.dtbo \
                 cape-audio-mtp.dtbo \
                 cape-audio-mtp-120fps.dtbo \
                 cape-audio-mtp-nodisplay.dtbo \
                 cape-audio-atp.dtbo \
                 cape-audio-qrd.dtbo

#OPLUS_DTS_OVERLAY start
#for waipio platform
dtbo-$(CONFIG_ARCH_WAIPIO) += oplus/wly-20846-audio-waipio-overlay.dtbo \
                 oplus/mt-20845-audio-waipio-overlay.dtbo \
                 oplus/jnc-20865-audio-waipio-overlay.dtbo \
                 oplus/baize-21001-audio-waipio-overlay.dtbo \
                 oplus/ferrari-21631-audio-waipio-overlay.dtbo \
                 oplus/kunpeng-21009-audio-waipio-overlay.dtbo \
                 oplus/jennie-21605-audio-waipio-overlay.dtbo \
                 oplus/jennie-21606-audio-waipio-overlay.dtbo \
                 oplus/ovaltine-21841-audio-waipio-overlay.dtbo

#for cape platform
dtbo-$(CONFIG_ARCH_CAPE) += oplus/kunpeng-21009-audio-cape-overlay.dtbo \
                 oplus/jennie-21605-audio-cape-overlay.dtbo \
                 oplus/jennie-21606-audio-cape-overlay.dtbo \
                 oplus/ovaltine-21841-audio-cape-overlay.dtbo

#for diwali platform
dtbo-$(CONFIG_ARCH_DIWALI) += oplus/wuyi-21125-audio-diwali-overlay.dtbo \
                 oplus/wuyi-21125-audio-diwali-overlay-t0.dtbo
#OPLUS_DTS_OVERLAY end

 always-y    := $(dtb-y) $(dtbo-y)
 subdir-y    := $(dts-dirs)
 clean-files    := *.dtb *.dtbo
