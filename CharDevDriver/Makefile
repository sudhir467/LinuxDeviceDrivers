
obj-m	:=char_fops3.o

KDIR 	:= /lib/modules/$(shell uname -r)/build
PWD		:= $(shell pwd)

default	:
		$(MAKE) -C $(KDIR) M=$(PWD) modules

clean	:
		$(MAKE) -C $(KDIR) M=$(PWD) clean

