################################################################################
# Automatically-generated file. Do not edit!
################################################################################

EMPTY := 
SPACE := $(EMPTY) $(EMPTY)

ORDERED_OBJS += \
$(GEN_CMDS_QUOTED) \
"./DVR_Main_ByLee.obj" \
"./asm/DSP281x_usDelay.obj" \
"./asm/DSP281x_CodeStartBranch.obj" \
"./source/DSP281x_SysCtrl.obj" \
"./source/DSP281x_PieVect.obj" \
"./source/DSP281x_PieCtrl.obj" \
"./source/DSP281x_MemCopy.obj" \
"./source/DSP281x_Gpio.obj" \
"./source/DSP281x_GlobalVariableDefs.obj" \
"./source/DSP281x_DefaultIsr.obj" \
"./source/DSP281x_Adc.obj" \
-l"libc.a" \
-l"rts2800_ml.lib" \
"../lib/IQmath.lib" \
"../cmd/DSP281x_Headers_nonBIOS.cmd" \
"../cmd/F2812_EzDSP_RAM_lnk.cmd" \

-include ../makefile.init

RM := DEL /F

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir.mk
-include source/subdir.mk
-include lib/subdir.mk
-include cmd/subdir.mk
-include asm/subdir.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 

# All Target
all: D-STATCOM_ByLee.out

# Tool invocations
D-STATCOM_ByLee.out: $(GEN_CMDS) $(OBJS)
	@echo 'Building target: $@'
	@echo 'Invoking: Linker'
	"D:/Program Files/Texas Instruments/ccsv4/tools/compiler/c2000/bin/cl2000" --silicon_version=28 -g --define="_DEBUG" --define="LARGE_MODEL" --diag_warning=225 --large_memory_model --unified_memory -z -m"D-STATCOM_ByLee.map" --stack_size=0x400 --warn_sections -i"D:/Program Files/Texas Instruments/ccsv4/tools/compiler/c2000/lib" -i"D:/Program Files/Texas Instruments/ccsv4/tools/compiler/c2000/include" --reread_libs --rom_model -o "D-STATCOM_ByLee.out" $(ORDERED_OBJS)
	@echo 'Finished building target: $@'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(C2000_EXECUTABLE_OUTPUTS__QTD) "D-STATCOM_ByLee.out"
	-$(RM) ".\source\DSP281x_Adc.obj" ".\source\DSP281x_DefaultIsr.obj" ".\source\DSP281x_GlobalVariableDefs.obj" ".\source\DSP281x_Gpio.obj" ".\source\DSP281x_MemCopy.obj" ".\source\DSP281x_PieCtrl.obj" ".\source\DSP281x_PieVect.obj" ".\source\DSP281x_SysCtrl.obj" ".\asm\DSP281x_CodeStartBranch.obj" ".\asm\DSP281x_usDelay.obj" ".\DVR_Main_ByLee.obj" 
	-$(RM) ".\asm\DSP281x_CodeStartBranch.pp" ".\asm\DSP281x_usDelay.pp" 
	-$(RM) ".\source\DSP281x_Adc.pp" ".\source\DSP281x_DefaultIsr.pp" ".\source\DSP281x_GlobalVariableDefs.pp" ".\source\DSP281x_Gpio.pp" ".\source\DSP281x_MemCopy.pp" ".\source\DSP281x_PieCtrl.pp" ".\source\DSP281x_PieVect.pp" ".\source\DSP281x_SysCtrl.pp" ".\DVR_Main_ByLee.pp" 
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets
