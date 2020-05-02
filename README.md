# lexin

PlatformIO port of esp-skainet get_started example for Lyrat esp32 boards.

https://github.com/espressif/esp-skainet/tree/master/examples/get_started

See also:

https://docs.espressif.com/projects/esp-adf/en/latest/get-started/get-started-esp32-lyrat.html


## Prerequisites

Make sure python3 is installed and used exclusively in current environment (Mac example below).

```
brew install python3
python3 -m venv ~/py3
source ~/py3/bin/activate
```

## Compile and upload

```
pio run --target upload
```

If ``fatal error: sdkconfig.h: No such file or directory`` appears start pio run again. 

## Device monitor

```
pio device monitor
```

