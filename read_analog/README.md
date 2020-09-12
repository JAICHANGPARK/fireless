| Supported Targets | ESP32 |
| ----------------- | ----- |

### Configure the project

```
idf.py menuconfig
```

### Build and Flash

Build the project and flash it to the board, then run monitor tool to view serial output:

```
idf.py -p PORT flash monitor
```

(To exit the serial monitor, type ``Ctrl-]``.)

See the Getting Started Guide for full steps to configure and use ESP-IDF to build projects.

## Example Output

you will see the following log output on the serial monitor:

```
Raw: 486	Voltage: 189mV
Raw: 435	Voltage: 177mV
Raw: 225	Voltage: 128mV
Raw: 18	    Voltage: 79mV
```

