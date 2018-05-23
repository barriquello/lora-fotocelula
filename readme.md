# Fotocélula LoRaWAN

 Baseado na implementação de endpoint LoRaWAN Semtech versão 4.4.1

 Compatível com "LoRaWAN Regional Parameters v1.0.2rB" e "LoRaWAN specification 1.0.2" classes A e C.

 Plataforma

* RAK811
  * **MCU**     : STM32L151CB - 128K FLASH, 10K RAM, Timers, SPI, I2C,
                          USART,
                          USB 2.0 full-speed device/host/OTG controller,
                          DAC, ADC, DMA
  * **RADIO**   : SX1276
  * **LEDS**    : 2
  * **SENSORES** : Tensão, corrente, luminosidade
  * **ATUADOR** : Relé
 
## Usage

A CMAKE building system is used in order to generate the right set of files to compile and debug the different projects.

Further information can be found in [Development environment](Doc/development-environment.md) document.

## Changelog

### 2018-05-23, V 0.0.0 

 Baseado no projeto Semtech 2018-03-07, V4.4.1

