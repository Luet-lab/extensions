UBINDIR ?= /usr/bin
SHAREDIR ?= /usr/share
DESTDIR ?=
GOOS?=linux
GOARCH?=amd64

all: build install

build:
	CGO_ENABLED=0 go build -o luet-migrate-emerge  main.go

install: build
	install -d $(DESTDIR)/$(UBINDIR)
	install -m 0755 luet-migrate-emerge $(DESTDIR)/$(UBINDIR)/
