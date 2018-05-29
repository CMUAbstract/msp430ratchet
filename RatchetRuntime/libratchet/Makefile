LIB = libratchet

OBJECTS = \
	ratchet.o \

override SRC_ROOT = ../../src

# TODO: ENERGY appears to be unused

override CFLAGS += \
	-DRATCHET \
	-DENERGY=$(ENERGY) \
	-I$(SRC_ROOT)/include \
	-I$(SRC_ROOT)/include/$(LIB) \

include $(MAKER_ROOT)/Makefile.$(TOOLCHAIN)
