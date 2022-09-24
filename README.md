**Adafruit QT Py RP2040** and **Adafruit APDS9960 Proximity, Light, RGB, and Gesture Sensor** when come together, can help newbies create their own cool embedded system projects. Let's start! This project uses the sensor data (color, proximity, brightness) to implement a "firefly" and a custom real-time visualizer. All you will need is an Adafruit dev board with RP2040 and a sensor.

**Requirements:**

Adafruit QT Py RP2040

<img src="https://circuitpython.org/assets/images/boards/large/adafruit_qtpy_rp2040.jpg" width="200" height="200"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/Plus_symbol.svg/1200px-Plus_symbol.svg.png" width="150" heigth="150"> <img src="https://cdn-shop.adafruit.com/970x728/3595-04.jpg" width="200" height="200"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/Plus_symbol.svg/1200px-Plus_symbol.svg.png" width="150" heigth="150"> <img src="https://cdn1-shop.mikroe.com/img/product/wire-jumpers-female-to-female-15cm-10pcs/wire-jumpers-female-to-female-15cm-10pcs-thickbox_default-12x.jpg" width="200" heigth="200">

Now, let's implement a firefly!
<\br>
So, the gist here is: the Neopixel led on the QT Py board should blink in synchronization with an actual firefly video. 
