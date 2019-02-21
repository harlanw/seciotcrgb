DTS = seciotcrgb.dts
DTBO = $(DTS:.dts=.dtbo)

INSTALL_PATH = /boot/overlays/

$(DTBO): $(DTS)
	dtc  $< > $@

install: $(DTBO)
	@echo "Copying $(DTBO) to $(INSTALL_PATH)"
	sudo cp $(DTBO) $(INSTALL_PATH)
