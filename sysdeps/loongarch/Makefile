ifeq ($(subdir),misc)
sysdep_headers += sys/asm.h
endif

# LoongArch's assembler also needs to know about PIC as it changes the
# definition of some assembler macros.
ASFLAGS-.os += $(pic-ccflag)
