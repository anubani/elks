BASEDIR=..

include $(BASEDIR)/Make.defs

###############################################################################
#
# Include standard packaging commands.

include $(BASEDIR)/Make.rules

###############################################################################

PRGS =	pres/pres

NETPRGS =

all:
	$(MAKE) -C prem all
	$(MAKE) -C pres all

install: $(PRGS)
	sudo install $(PRGS) $(TARGET_MNT)/bin

clean:
	$(MAKE) -C pres clean
	$(MAKE) -C prem clean
