![rozmístění pinů](https://www.theengineeringprojects.com/wp-content/uploads/2018/07/introduction-to-raspberry-pi-3-b-plus-2.png)
## Humidity & Temperature sensor (_DHT11_)
3 piny na sensoru: _dout_ (gpio pin), _gnd_ (ground pin) a _vcc_ (5V pin)

1. připojit vypnuté raspberry k breadboardu skrz správné piny (např. vcc: 2, gnd: 6, dout: 7)
2. zapnout raspberry a stáhnout knihovnu https://github.com/szazo/DHT11_Python.git pomocí clone git, následně upravit soubor _DHT11_example.py_:


~~~~ 
clone git https://github.com/szazo/DHT11_Python.git
cd DHT11_Python
sudo nano DHT11_example.py
~~~~

3. přepíšeme GPIO číslo z pin=11 na pin=4 (podle GPIO4)
4. v terminálu spustíme skript:
~~~~
python DHT11_example.py
~~~~

Návod na [YouTube](https://youtu.be/KUr8WgSIsfk)
