idf_component_register(SRCS
	"core/src/vl53l0x_api.cpp"
	"core/src/vl53l0x_api_calibration.cpp"
	"core/src/vl53l0x_api_core.cpp"
	"core/src/vl53l0x_api_ranging.cpp"
	"core/src/vl53l0x_api_strings.cpp"
	"platform/src/vl53l0x_i2c_comms.cpp"
	"platform/src/vl53l0x_platform.cpp"
	"Adafruit_VL53L0X.cpp"
	"Adafruit_VL53L0X.h"
	INCLUDE_DIRS ""
	REQUIRES arduino
	)
