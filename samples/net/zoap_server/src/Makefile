ifeq ($(CONFIG_NET_TESTING), y)
ccflags-y +=-I${ZEPHYR_BASE}/samples/net/common/
ccflags-y +=-DNET_TESTING_SERVER=1
endif

obj-y = zoap-server.o
