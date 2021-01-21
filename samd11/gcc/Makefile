################################################################################
# Automatically-generated file. Do not edit!
################################################################################

ifdef SystemRoot
	SHELL = cmd.exe
	MK_DIR = mkdir
else
	ifeq ($(shell uname), Linux)
		MK_DIR = mkdir -p
	endif

	ifeq ($(shell uname | cut -d _ -f 1), CYGWIN)
		MK_DIR = mkdir -p
	endif

	ifeq ($(shell uname | cut -d _ -f 1), MINGW32)
		MK_DIR = mkdir -p
	endif

	ifeq ($(shell uname | cut -d _ -f 1), MINGW64)
		MK_DIR = mkdir -p
	endif

	ifeq ($(shell uname | cut -d _ -f 1), DARWIN)
		MK_DIR = mkdir -p
	endif
endif
MK_DIR = mkdir -p
VENDOR = microchip
CHIP_FAMILY = samd

# List the subdirectories for creating object files
SUB_DIRS +=  \
 \
gcc \
hpl/usb \
hpl/dmac \
hal/src \
hpl/pm \
hpl/sysctrl \
hal/utils/src \
hpl/sercom \
examples \
hpl/gclk \
gcc/gcc \
hpl/core \
tinyusb \
tinyusb/src \
tinyusb/src/common \
tinyusb/src/device \
tinyusb/src/class/audio \
tinyusb/src/class/cdc \
tinyusb/src/class/dfu \
tinyusb/src/class/hid \
tinyusb/src/class/midi \
tinyusb/src/class/msc \
tinyusb/src/class/net \
tinyusb/src/class/usbtmc \
tinyusb/src/class/vendor \
tinyusb/src/portable/$(VENDOR)/$(CHIP_FAMILY)/ \

TINY_USB_OBJS += \
tinyusb/src/common/tusb_fifo.o \
tinyusb/src/device/usbd.o \
tinyusb/src/device/usbd_control.o \
tinyusb/src/class/audio/audio_device.o \
tinyusb/src/class/cdc/cdc_device.o \
tinyusb/src/class/dfu/dfu_rt_device.o \
tinyusb/src/class/hid/hid_device.o \
tinyusb/src/class/midi/midi_device.o \
tinyusb/src/class/msc/msc_device.o \
tinyusb/src/class/net/net_device.o \
tinyusb/src/class/usbtmc/usbtmc_device.o \
tinyusb/src/class/vendor/vendor_device.o \
tinyusb/src/portable/$(VENDOR)/$(CHIP_FAMILY)/dcd_$(CHIP_FAMILY).o \
usb_descriptors.o \
tinyusb/src/tusb.o \
T1.o \

TINY_USB_OBJS_AS_ARGS += \
"tinyusb/src/tusb.o" \
"tinyusb/src/common/tusb_fifo.o" \
"tinyusb/src/device/usbd.o" \
"tinyusb/src/device/usbd_control.o" \
"tinyusb/src/class/audio/audio_device.o" \
"tinyusb/src/class/cdc/cdc_device.o" \
"tinyusb/src/class/dfu/dfu_rt_device.o" \
"tinyusb/src/class/hid/hid_device.o" \
"tinyusb/src/class/midi/midi_device.o" \
"tinyusb/src/class/msc/msc_device.o" \
"tinyusb/src/class/net/net_device.o" \
"tinyusb/src/class/usbtmc/usbtmc_device.o" \
"tinyusb/src/class/vendor/vendor_device.o" \
"tinyusb/src/portable/$(VENDOR)/$(CHIP_FAMILY)/dcd_$(CHIP_FAMILY).o" \
"usb_descriptors.o" \
"T1.o" \

TINY_USB_DEPS += \
"tinyusb/src/tusb.d" \
"tinyusb/src/common/tusb_fifo.d" \
"tinyusb/src/device/usbd.d" \
"tinyusb/src/device/usbd_control.d" \
"tinyusb/src/class/audio/audio_device.d" \
"tinyusb/src/class/cdc/cdc_device.d" \
"tinyusb/src/class/dfu/dfu_rt_device.d" \
"tinyusb/src/class/hid/hid_device.d" \
"tinyusb/src/class/midi/midi_device.d" \
"tinyusb/src/class/msc/msc_device.d" \
"tinyusb/src/class/net/net_device.d" \
"tinyusb/src/class/usbtmc/usbtmc_device.d" \
"tinyusb/src/class/vendor/vendor_device.d" \
"tinyusb/src/portable/$(VENDOR)/$(CHIP_FAMILY)/dcd_$(CHIP_FAMILY).d" \
"usb_descriptors.d" \

TINY_USB_FLAGS += \
  -mthumb \
  -mabi=aapcs-linux \
  -mcpu=cortex-m0plus \
  -nostdlib -nostartfiles \
  -D__SAMD11C14A__ \
  -DCONF_DFLL_OVERWRITE_CALIBRATION=0 \
  -DOSC32K_OVERWRITE_CALIBRATION=0 \
  -DCFG_TUSB_MCU=OPT_MCU_SAMD11

# List the object files

# List the object files
OBJS +=  \
hal/src/hal_io.o \
hal/src/hal_spi_s_async.o \
hal/utils/src/utils_syscalls.o \
hal/src/hal_delay.o \
hpl/pm/hpl_pm.o \
hpl/core/hpl_init.o \
hal/utils/src/utils_list.o \
hpl/core/hpl_core_m0plus_base.o \
hal/utils/src/utils_assert.o \
hpl/dmac/hpl_dmac.o \
hpl/sysctrl/hpl_sysctrl.o \
hpl/gclk/hpl_gclk.o \
hal/src/hal_init.o \
main.o \
examples/driver_examples.o \
driver_init.o \
hal/src/hal_usart_async.o \
hpl/sercom/hpl_sercom.o \
hal/utils/src/utils_ringbuffer.o \
hal/src/hal_gpio.o \
hal/utils/src/utils_event.o \
hal/src/hal_sleep.o \
gcc/system_samd11.o \
gcc/gcc/startup_samd11.o \
hal/src/hal_atomic.o \
# hpl/usb/hpl_usb.o \
# hal/src/hal_usb_device.o \

OBJS_AS_ARGS +=  \
"hal/src/hal_io.o" \
"hal/src/hal_spi_s_async.o" \
"hal/utils/src/utils_syscalls.o" \
"hal/src/hal_delay.o" \
"hpl/pm/hpl_pm.o" \
"hpl/core/hpl_init.o" \
"hal/utils/src/utils_list.o" \
"hpl/core/hpl_core_m0plus_base.o" \
"hal/utils/src/utils_assert.o" \
"hpl/dmac/hpl_dmac.o" \
"hpl/sysctrl/hpl_sysctrl.o" \
"hpl/gclk/hpl_gclk.o" \
"hal/src/hal_init.o" \
"main.o" \
"examples/driver_examples.o" \
"driver_init.o" \
"hal/src/hal_usart_async.o" \
"hpl/sercom/hpl_sercom.o" \
"hal/utils/src/utils_ringbuffer.o" \
"hal/src/hal_gpio.o" \
"hal/utils/src/utils_event.o" \
"hal/src/hal_sleep.o" \
"gcc/system_samd11.o" \
"gcc/gcc/startup_samd11.o" \
"hal/src/hal_atomic.o" \
# "hpl/usb/hpl_usb.o" \
# "hal/src/hal_usb_device.o" \

OBJS += $(TINY_USB_OBJS)
OBJS_AS_ARGS += $(TINY_USB_OBJS_AS_ARGS)

# List the directories containing header files
DIR_INCLUDES +=  \
-I"../" \
-I"../config" \
-I"../examples" \
-I"../hal/include" \
-I"../hal/utils/include" \
-I"../hpl/core" \
-I"../hpl/dmac" \
-I"../hpl/gclk" \
-I"../hpl/pm" \
-I"../hpl/port" \
-I"../hpl/sercom" \
-I"../hpl/sysctrl" \
-I"../hpl/usb" \
-I"../hri" \
-I"../" \
-I"../CMSIS/Core/Include" \
-I"../include" \
-I"../tinyusb" \
-I"../tinyusb/src" \
-I"../tinyusb/hw/bsp" \


# List the dependency files
DEPS := $(OBJS:%.o=%.d)

DEPS_AS_ARGS +=  \
"hal/src/hal_spi_s_async.d" \
"hal/src/hal_io.d" \
"hal/src/hal_gpio.d" \
"hal/utils/src/utils_syscalls.d" \
"hpl/core/hpl_core_m0plus_base.d" \
"hal/utils/src/utils_list.d" \
"hpl/dmac/hpl_dmac.d" \
"hal/utils/src/utils_assert.d" \
"hal/src/hal_delay.d" \
"hpl/core/hpl_init.d" \
"hpl/sysctrl/hpl_sysctrl.d" \
"hpl/gclk/hpl_gclk.d" \
"hal/src/hal_init.d" \
"driver_init.d" \
"hal/src/hal_usart_async.d" \
"main.d" \
"examples/driver_examples.d" \
"gcc/system_samd11.d" \
"hal/src/hal_sleep.d" \
"hal/utils/src/utils_ringbuffer.d" \
"hpl/sercom/hpl_sercom.d" \
"hal/utils/src/utils_event.d" \
"hal/src/hal_atomic.d" \
"gcc/gcc/startup_samd11.d" \
"hpl/pm/hpl_pm.d" \
# "hpl/usb/hpl_usb.d" \
# "hal/src/hal_usb_device.d" \

DEPS_AS_ARGS += $(TINY_USB_DEPS)

OUTPUT_FILE_NAME :=T1-samd
QUOTE := "
OUTPUT_FILE_PATH +=$(OUTPUT_FILE_NAME).elf
OUTPUT_FILE_PATH_AS_ARGS +=$(OUTPUT_FILE_NAME).elf

vpath %.c ../
vpath %.s ../
vpath %.S ../

# All Target
all: $(SUB_DIRS) $(OUTPUT_FILE_PATH)

# Linker target

$(OUTPUT_FILE_PATH): $(OBJS)
	@echo Building target: $@
	@echo Invoking: ARM/GNU Linker
	$(QUOTE)arm-none-eabi-gcc$(QUOTE) -o $(OUTPUT_FILE_NAME).elf $(OBJS_AS_ARGS) -Wl,--start-group -lm -Wl,--end-group -mthumb \
-Wl,-Map="$(OUTPUT_FILE_NAME).map" --specs=nano.specs -Wl,--gc-sections -mcpu=cortex-m0plus \
 \
-T"../gcc/gcc/samd11c14a_flash.ld" \
-L"../gcc/gcc"
	@echo Finished building target: $@

	"arm-none-eabi-objcopy" -O binary "$(OUTPUT_FILE_NAME).elf" "$(OUTPUT_FILE_NAME).bin"
	"arm-none-eabi-objcopy" -O ihex -R .eeprom -R .fuse -R .lock -R .signature  \
        "$(OUTPUT_FILE_NAME).elf" "$(OUTPUT_FILE_NAME).hex"
	"arm-none-eabi-objcopy" -j .eeprom --set-section-flags=.eeprom=alloc,load --change-section-lma \
        .eeprom=0 --no-change-warnings -O binary "$(OUTPUT_FILE_NAME).elf" \
        "$(OUTPUT_FILE_NAME).eep" || exit 0
	"arm-none-eabi-objdump" -h -S "$(OUTPUT_FILE_NAME).elf" > "$(OUTPUT_FILE_NAME).lss"
	"arm-none-eabi-size" "$(OUTPUT_FILE_NAME).elf"

# Compiler targets
%.o: %.c
	@echo Building file: $<
	@echo ARM/GNU C Compiler
	$(QUOTE)arm-none-eabi-gcc$(QUOTE) -x c $(TINY_USB_FLAGS) -mthumb -DDEBUG -Os -ffunction-sections -mlong-calls -g3 -Wall -c -std=gnu99 \
-D__SAMD11C14A__ -mcpu=cortex-m0plus  \
$(DIR_INCLUDES) \
-MD -MP -MF "$(@:%.o=%.d)" -MT"$(@:%.o=%.d)" -MT"$(@:%.o=%.o)"  -o "$@" "$<"
	@echo Finished building: $<

%.o: %.s
	@echo Building file: $<
	@echo ARM/GNU Assembler
	$(QUOTE)arm-none-eabi-as$(QUOTE) -x c $(TINY_USB_FLAGS) -mthumb -DDEBUG -Os -ffunction-sections -mlong-calls -g3 -Wall -c -std=gnu99 \
-D__SAMD11C14A__ -mcpu=cortex-m0plus  \
$(DIR_INCLUDES) \
-MD -MP -MF "$(@:%.o=%.d)" -MT"$(@:%.o=%.d)" -MT"$(@:%.o=%.o)"  -o "$@" "$<"
	@echo Finished building: $<

%.o: %.S
	@echo Building file: $<
	@echo ARM/GNU Preprocessing Assembler
	$(QUOTE)arm-none-eabi-gcc$(QUOTE) -x c $(TINY_USB_FLAGS) -mthumb -DDEBUG -Os -ffunction-sections -mlong-calls -g3 -Wall -c -std=gnu99 \
-D__SAMD11C14A__ -mcpu=cortex-m0plus  \
$(DIR_INCLUDES) \
-MD -MP -MF "$(@:%.o=%.d)" -MT"$(@:%.o=%.d)" -MT"$(@:%.o=%.o)"  -o "$@" "$<"
	@echo Finished building: $<

# Detect changes in the dependent files and recompile the respective object files.
ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(DEPS)),)
-include $(DEPS)
endif
endif

$(SUB_DIRS):
	$(MK_DIR) "$@"

flash: all
	@edbg -b -t samd11 -e -pv -f $(OUTPUT_FILE_NAME).bin


clean:
	rm -f $(OBJS_AS_ARGS)
	rm -f $(OUTPUT_FILE_PATH)
	rm -f $(DEPS_AS_ARGS)
	rm -f $(OUTPUT_FILE_NAME).a $(OUTPUT_FILE_NAME).hex $(OUTPUT_FILE_NAME).bin \
        $(OUTPUT_FILE_NAME).lss $(OUTPUT_FILE_NAME).eep $(OUTPUT_FILE_NAME).map \
        $(OUTPUT_FILE_NAME).srec