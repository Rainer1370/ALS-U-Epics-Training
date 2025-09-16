TOP = ../..
include $(TOP)/configure/CONFIG

# IOCSH += mouse.iocsh
IOCSH += $(patsubst ../%, %, $(wildcard ../*.iocsh))

include $(TOP)/configure/RULES

