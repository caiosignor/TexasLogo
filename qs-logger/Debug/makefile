################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := D:/ti/ccs/tools/compiler/ti-cgt-arm_18.12.2.LTS

GEN_OPTS__FLAG := 
GEN_CMDS__FLAG := 

ORDERED_OBJS += \
"./acquire.obj" \
"./clocksetwidget.obj" \
"./flashstore.obj" \
"./images.obj" \
"./menus.obj" \
"./qs-logger.obj" \
"./startup_ccs.obj" \
"./stripchartmanager.obj" \
"./usb_serial_structs.obj" \
"./usbserial.obj" \
"./usbstick.obj" \
"./drivers/buttons.obj" \
"./drivers/cfal96x64x16.obj" \
"./drivers/slidemenuwidget.obj" \
"./drivers/stripchartwidget.obj" \
"./third_party/fatfs/port/fat_usbmsc.obj" \
"./third_party/fatfs/src/ff.obj" \
"./utils/uartstdio.obj" \
"./utils/ustdlib.obj" \
"../qs-logger_ccs.cmd" \
$(GEN_CMDS__FLAG) \
-llibc.a \
-l"C:/ti/tivaware_c_series_2_1_4_178/driverlib/ccs/Debug/driverlib.lib" \
-l"C:/ti/tivaware_c_series_2_1_4_178/grlib/ccs/Debug/grlib.lib" \
-l"C:/ti/tivaware_c_series_2_1_4_178/usblib/ccs/Debug/usblib.lib" \
-l"C:/ti/tivaware_c_series_2_1_4_178/sensorlib/ccs/Debug/sensorlib.lib" \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include drivers/subdir_vars.mk
-include third_party/fatfs/port/subdir_vars.mk
-include third_party/fatfs/src/subdir_vars.mk
-include utils/subdir_vars.mk
-include subdir_rules.mk
-include drivers/subdir_rules.mk
-include third_party/fatfs/port/subdir_rules.mk
-include third_party/fatfs/src/subdir_rules.mk
-include utils/subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(INO_DEPS)),)
-include $(INO_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(SV7A_DEPS)),)
-include $(SV7A_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(PDE_DEPS)),)
-include $(PDE_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
EXE_OUTPUTS += \
qs-logger.out \

EXE_OUTPUTS__QUOTED += \
"qs-logger.out" \

BIN_OUTPUTS += \
qs-logger.bin \

BIN_OUTPUTS__QUOTED += \
"qs-logger.bin" \


# All Target
all: qs-logger.out

# Tool invocations
qs-logger.out: $(OBJS) $(CMD_SRCS) $(GEN_CMDS)
	@echo 'Building target: "$@"'
	@echo 'Invoking: ARM Linker'
	"D:/ti/ccs/tools/compiler/ti-cgt-arm_18.12.2.LTS/bin/armcl" -mv7M4 --code_state=16 --float_support=FPv4SPD16 --abi=eabi -me -O2 --advice:power=all -g --gcc --define=ccs="ccs" --define=PART_TM4C123GH6PGE --define=TARGET_IS_TM4C123_RB1 --diag_warning=225 --diag_wrap=off --display_error_number --gen_func_subsections=on --ual -z -m"qs-logger_ccs.map" --stack_size=1024 --heap_size=0 -i"D:/ti/ccs/tools/compiler/ti-cgt-arm_18.12.2.LTS/lib" -i"D:/ti/ccs/tools/compiler/ti-cgt-arm_18.12.2.LTS/include" --reread_libs --diag_wrap=off --display_error_number --warn_sections --xml_link_info="qs-logger_linkInfo.xml" --rom_model -o "qs-logger.out" $(ORDERED_OBJS)
	@echo 'Finished building target: "$@"'
	@echo ' '
	@$(MAKE) --no-print-directory post-build

qs-logger.bin: $(EXE_OUTPUTS)
	@echo 'Building files: $(strip $(EXE_OUTPUTS__QUOTED))'
	@echo 'Invoking: ARM Hex Utility'
	"D:/ti/ccs/tools/compiler/ti-cgt-arm_18.12.2.LTS/bin/armhex"  -o "qs-logger.bin" $(EXE_OUTPUTS__QUOTED)
	@echo 'Finished building: $(strip $(EXE_OUTPUTS__QUOTED))'
	@echo ' '
	@$(MAKE) --no-print-directory post-build

# Other Targets
clean:
	-$(RM) $(BIN_OUTPUTS__QUOTED)$(EXE_OUTPUTS__QUOTED)
	-$(RM) "acquire.obj" "clocksetwidget.obj" "flashstore.obj" "images.obj" "menus.obj" "qs-logger.obj" "startup_ccs.obj" "stripchartmanager.obj" "usb_serial_structs.obj" "usbserial.obj" "usbstick.obj" "drivers\buttons.obj" "drivers\cfal96x64x16.obj" "drivers\slidemenuwidget.obj" "drivers\stripchartwidget.obj" "third_party\fatfs\port\fat_usbmsc.obj" "third_party\fatfs\src\ff.obj" "utils\uartstdio.obj" "utils\ustdlib.obj" 
	-$(RM) "acquire.d" "clocksetwidget.d" "flashstore.d" "images.d" "menus.d" "qs-logger.d" "startup_ccs.d" "stripchartmanager.d" "usb_serial_structs.d" "usbserial.d" "usbstick.d" "drivers\buttons.d" "drivers\cfal96x64x16.d" "drivers\slidemenuwidget.d" "drivers\stripchartwidget.d" "third_party\fatfs\port\fat_usbmsc.d" "third_party\fatfs\src\ff.d" "utils\uartstdio.d" "utils\ustdlib.d" 
	-@echo 'Finished clean'
	-@echo ' '

post-build:
	-"D:/ti/ccs/utils/tiobj2bin/tiobj2bin" "qs-logger.out" "qs-logger.bin" "D:/ti/ccs/tools/compiler/ti-cgt-arm_18.12.2.LTS/bin/armofd" "D:/ti/ccs/tools/compiler/ti-cgt-arm_18.12.2.LTS/bin/armhex" "D:/ti/ccs/utils/tiobj2bin/mkhex4bin"
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets

