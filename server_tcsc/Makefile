CONTIKI_PROJECT = server


# Do not try to build on Sky because of code size limitation
PLATFORMS_EXCLUDE = sky z1

# Include CoAP resources
MODULES_REL += ./resources

CONTIKI_TARGET_SOURCEFILES += dht22.c

all: $(CONTIKI_PROJECT)

CONTIKI=../../../../..

include ../Makefile.common

include $(CONTIKI)/Makefile.include




