obj-m = sb_edac.o
KVERSION = $(shell uname -r)
#KVERSION = 3.11.0-17-generic
#define CONFIG_EDAC_DEBUG

all:
	make -C /lib/modules/$(KVERSION)/build M=$(PWD) modules
clean:
	make -C /lib/modules/$(KVERSION)/build M=$(PWD) clean
