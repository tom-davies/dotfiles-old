theme="current"

ifndef VERBOSE
.SILENT:
endif

desktop: 
	@rm -f config
	@rm -f settings.d/.*~
	@rm -f settings.d/*~
	@cat settings.d/*-* > config
	@rm -f settings.d/desktop.d/.*~
	@rm -f settings.d/desktop.d/*~
	@cat settings.d/desktop.d/* >> config


laptop:
	@rm -f config
	@rm -f settings.d/.*~
	@rm -f settings.d/*~
	@cat settings.d/*-* > config
	@rm -f settings.d/laptop.d/.*~
	@rm -f settings.d/laptop.d/*~
	@cat settings.d/laptop.d/* >> config
