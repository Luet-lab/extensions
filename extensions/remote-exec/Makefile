UBINDIR ?= /usr/bin
SHAREDIR ?= /usr/share
DESTDIR ?=

all: build install

build:
	@echo "Nothing to build"

install: build
	install -d $(DESTDIR)/$(UBINDIR)
	install -m 0755 luet-remote-exec $(DESTDIR)/$(UBINDIR)/
