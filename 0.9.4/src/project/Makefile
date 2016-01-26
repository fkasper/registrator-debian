#!/usr/bin/make -f

EXECUTABLE=project
CP=cp -f
RM=rm -f
CHMOD=chmod
BUILD_DIR=/

install:
	$(CP) etc/registrator.toml $(BUILD_DIR)etc
	$(CP) etc/systemd/system/registrator.service $(BUILD_DIR)etc/systemd/system/registrator.service
	$(CP) usr/bin/registrator $(BUILD_DIR)usr/bin
	$(CHMOD) +x $(BUILD_DIR)usr/bin/registrator

.PHONY: install
