ifneq ($(ARCH),s390)
nothing:
	@echo "NOTE: ARCH=$(ARCH), wont build..."
.PHONY: all clean run_tests install
.SILENT:
else
TEST_GEN_PROGS := test_uvdevice
endif

CFLAGS += -Wall -Werror -static $(KHDR_INCLUDES)

include ../../../lib.mk
