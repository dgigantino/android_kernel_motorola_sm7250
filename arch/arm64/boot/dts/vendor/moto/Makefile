ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_RACER_DTB) += \
                racer/lito-racer_01.dtbo \
                racer/lito-racer_02.dtbo \
                racer/lito-racer_03.dtbo

        dtbo-$(CONFIG_NAIRO_DTB) += \
                nairo/lito-nairo_01.dtbo \
                nairo/lito-nairo_02.dtbo \
                nairo/lito-nairo_03.dtbo \
                nairo/lito-nairo_04.dtbo \
                nairo/lito-nairo_05.dtbo \
                nairo/lito-nairo_06.dtbo \
                nairo/lito-nairo_07.dtbo \
                nairo/lito-nairo_08.dtbo \
                nairo/lito-nairo_09.dtbo \
                nairo/lito-nairo_10.dtbo \
                nairo/lito-nairo_11.dtbo \
                nairo/lito-nairo_12.dtbo \

endif

always		:= $(dtb-y) $(dtbo-y)
subdir-y	:= $(dts-dirs)
clean-files    := *.dtb *.dtbo
