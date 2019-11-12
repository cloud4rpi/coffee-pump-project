# Smart Coffee Machine Pump controlled by Raspberry Pi & Ultrasonic HC-SR04 sensor.

Automatic water pump system for SAECO Aulika Focus coffee machine using the HC-SR04 sensor, Raspberry Pi and Cloud4RPi.

For details read the [full article on Medium](https://medium.com/cloud4rpi/smart-coffee-machine-pump-controlled-by-raspberry-pi-hc-sr04-ultrasonic-sensor-bd135598f1a4).


## How to use

1. Install dependencies:
    ```sh
    sudo pip3 install cloud4rpi hcsr04sensor
    ```

2. Run the [main.py](main.py):
    ```sh
    sudo python3 coffee-pump/main.py
    ```

    or use make:
    ```sh
    make run
    ```

3. Install as a Service:
    ```bash
    chmod +x service_install.sh
    make install
    ```

4. Use as a Service:
    ```bash
    make start|stop|status
    ```

5. Show service output:
    ```bash
    make log
    ```

## Demo Video

https://youtu.be/JSZgaPKaC8s

## See Also

[Cloud4RPi on GitHub](https://github.com/cloud4rpi)
