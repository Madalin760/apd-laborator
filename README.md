## Autor
Madalin Nacu, Grupa 4LF342

## Hardware
Arduino Uno R3, senzor de temperatură TMP36Platformă: Arduino Uno R3 (ATmega328P)
Autor laborator: <Madalin Nacu>

## Parametri

Acest proiect folosește următorii parametri de configurare (definiți în `src/config.h`):

* **SENSOR_PIN (A0):** Specifică pinul analogic la care este conectat senzorul de temperatură.
* **SAMPLE_PERIOD_MS (1000):** Reprezintă perioada de eșantionare, adică timpul de așteptare (în milisecunde) între două măsurători consecutive.
* **SERIAL_BAUD (9600):** Setează viteza de comunicare a portului serial pentru transmiterea datelor către calculator.
* **LED_PIN (13):** Specifică pinul digital utilizat pentru LED-ul de stare al plăcii.
* **BUTTON_PIN (2):** Specifică pinul digital la care este conectat butonul pentru pornirea/oprirea achiziției de date.