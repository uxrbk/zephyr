ccflags-y += -I${ZEPHYR_BASE}/subsys/net/ip

ifeq ($(CONFIG_NET_TESTING), y)
ccflags-y +=-I${ZEPHYR_BASE}/samples/net/common/
ccflags-y +=-DNET_TESTING_SERVER=1
endif

ccflags-$(CONFIG_NET_L2_BT) += -I${ZEPHYR_BASE}/samples/bluetooth/

obj-y = leds-demo.o
