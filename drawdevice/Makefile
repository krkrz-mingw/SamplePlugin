
SOURCES += BasicDrawDevice.cpp GDIDrawDevice.cpp Main.cpp

LDLIBS += -lgdi32

ifneq (x,x$(findstring intel,$(TARGET_ARCH)))
LDLIBS += -lvfw32
endif

PROJECT_BASENAME = drawdevice

TP_STUB_BASE = ../external/tp_stubz/
include $(TP_STUB_BASE)/Rules.lib.make
