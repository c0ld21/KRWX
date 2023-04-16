obj-m += krwx.o


K=$(KERNEL_PATH)

all:
	make -C $K M=$(PWD) modules

clean:
	make -C $K M=$(PWD) clean
