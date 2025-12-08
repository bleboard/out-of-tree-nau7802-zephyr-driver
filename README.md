First, activate virtual environment:
`source ~/zephyrproject/.venv/bin/activate`

Then, build:
`west build -p -b adafruit_feather_esp32/esp32/procpu`

To flash:
`west flash`

To monitor:
`west espressif monitor -p /dev/tty.wchusbserial575E0524461`

/!\ Make sure to run `west blobs fetch hal_espressif`

The `adafruit_feather_esp32` board is only available in a very recent (at the time of this publication) Zephyr version.