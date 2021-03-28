add_library(jdrone-uc4h-v2
	boot.c
	led.c
)
target_link_libraries(jdrone-uc4h-v2 drivers_bootloaders)