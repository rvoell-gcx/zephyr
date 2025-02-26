# SPDX-License-Identifier: Apache-2.0

zephyr_library()

zephyr_library_sources_ifdef(CONFIG_GPIO_TELINK_B91 gpio_b91.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_CC13XX_CC26XX gpio_cc13xx_cc26xx.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_CC32XX     gpio_cc32xx.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_CMSDK_AHB  gpio_cmsdk_ahb.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_DW         gpio_dw.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_ESP32      gpio_esp32.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_SIFIVE     gpio_sifive.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_GECKO      gpio_gecko.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_IMX        gpio_imx.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_ITE_IT8XXX2 gpio_ite_it8xxx2.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_MCP23S17   gpio_mcp23s17.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_MCUX       gpio_mcux.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_MCUX_IGPIO gpio_mcux_igpio.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_MCUX_LPC   gpio_mcux_lpc.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_MMIO32     gpio_mmio32.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_XEC        gpio_mchp_xec.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_NRFX       gpio_nrfx.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_PCA95XX    gpio_pca95xx.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_STM32      gpio_stm32.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_SAM0       gpio_sam0.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_SAM        gpio_sam.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_SAM4L      gpio_sam4l.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_SX1509B    gpio_sx1509b.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_INTEL      gpio_intel.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_STELLARIS  gpio_stellaris.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_RV32M1     gpio_rv32m1.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_LMP90XXX   gpio_lmp90xxx.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_LITEX      gpio_litex.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_LPC11U6X   gpio_lpc11u6x.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_XLNX_AXI   gpio_xlnx_axi.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_NPCX       gpio_npcx.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_EMUL       gpio_emul.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_PSOC6      gpio_psoc6.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_PCAL6408A  gpio_pcal6408a.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_EOS_S3     gpio_eos_s3.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_RCAR       gpio_rcar.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_CY8C95XX   gpio_cy8c95xx.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_SNPS_CREG  gpio_creg_gpio.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_STMPE1600  gpio_stmpe1600.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_XEC_V2     gpio_mchp_xec_v2.c)
zephyr_library_sources_ifdef(CONFIG_GPIO_PCA953X    gpio_pca953x.c)

zephyr_library_sources_ifdef(CONFIG_GPIO_SHELL      gpio_shell.c)

zephyr_library_sources_ifdef(CONFIG_USERSPACE   gpio_handlers.c)
