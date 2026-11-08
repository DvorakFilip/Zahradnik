

PORT := /dev/ttyACM0
FQBN := esp32:esp32:esp32c6



compile:
	arduino-cli compile . --fqbn "$(FQBN)"

upload:
	arduino-cli upload . --port "$(PORT)" --fqbn "$(FQBN)"

monitor:
	arduino-cli monitor --port "$(PORT)" --config 115200


