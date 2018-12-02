F_CPU          = 32000000
MCU_NAME       = 32a4u
TARGET         = application
PACKAGES       = avrlibx .
APP_ROOT			 := $(shell dirname $(realpath $(lastword $(MAKEFILE_LIST))))
PROJECT_ROOT	 := $(shell dirname $(APP_ROOT))

include $(PROJECT_ROOT)/avrlibx/makefile.mk
