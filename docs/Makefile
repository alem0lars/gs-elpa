MAN_SOURCES=gs-elpa
MANS=$(MAN_SOURCES:=.8)

RST2MAN=rst2man.py

all: ${MANS}

%.8: %.8.rst
	$(RST2MAN) $< $@
