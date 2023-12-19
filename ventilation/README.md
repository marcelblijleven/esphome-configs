# Ventilation

Controlling a Zehnder ComfoFan S through ESPHome with nRF905

## Pinout

*Board: nodemcu-32s*

| nRF905 pin | ESP32 pin | ESP32 GPIO |
|:----------:|:---------:|:----------:|
|     Vcc    |    3.3V   |    3.3V    |
|     Gnd    |    Gnd    |    Gnd     |
|     AM     |    D32    |  GPIO 32   |
|     CD     |    D33    |  GPIO 33   |
|     CE     |    D27    |  GPIO 27   |
|     DR     |    D35    |  GPIO 35   |
|     PWR    |    D26    |  GPIO 26   |
|    TX_EN   |    D25    |  GPIO 25   |
|    MOSI    |    D13    |  GPIO 13   |
|    MISO    |    D12    |  GPIO 12   |
| CLK or SCK |    D14    |  GPIO 14   |
|  CS or CSN |    D15    |  GPIO 15   |