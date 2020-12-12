# Práctica 5: Comunicaciones BLE y Bluetooth

### *Redes de sensores Electrónicos*

**Partes de la práctica** (cada una tiene un folder asociado):

1. **Enviar iBeacons**: *Advertising* hecho por el módulo ESP32 mediante iBeacons &rarr; Se envía UUID (*Universal Unique Identifier*), *Major* y *Minor* entre otros tipos de datos. Sirve para notificar la presencia del ESP32.
2. **Chat entre ESP32 y App**: Chat establecido mediante el perfil SPP (*Serial Port Profile*) entre el módulo y la App [Serial Bluetooth Terminal](https://play.google.com/store/apps/details?id=de.kai_morich.serial_bluetooth_terminal&hl=en_US&gl=US)

### Los códigos de este repositorio son prácticamente en su totalidad los ofrecidos en las siguientes fuentes:

* Para enviar iBeacons: [ESP32 based Bluetooth iBeacon](https://circuitdigest.com/microcontroller-projects/esp32-based-bluetooth-ibeacon)
* Para realizar el chat entre el ESP32 y la App: [Repositorio de Github de BluetoothSerial de Espressif](https://github.com/espressif/arduino-esp32/tree/master/libraries/BluetoothSerial)
