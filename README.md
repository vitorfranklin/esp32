# ESP32 - Guia de Introdução

Bem-vindo ao repositório de introdução ao ESP32! Este repositório fornece informações e recursos para começar a trabalhar com o ESP32, uma poderosa placa de desenvolvimento para projetos de Internet das Coisas (IoT).

## 🚀 Sobre o ESP32

O ESP32 é um microcontrolador de baixo custo e alto desempenho da Espressif Systems. Ele possui conectividade Wi-Fi e Bluetooth integradas, tornando-o ideal para uma ampla variedade de aplicações, desde dispositivos de automação residencial até sistemas de monitoramento industrial.

### Características Principais

- **Processador:** Dual-core Tensilica LX6
- **Memória:** 520 KB SRAM
- **Armazenamento:** Flash embutida e suporte a cartões microSD
- **Conectividade:** Wi-Fi 802.11 b/g/n, Bluetooth v4.2 BR/EDR e BLE
- **GPIOs:** Até 36 pinos de GPIO programáveis
- **Periféricos:** UART, I2C, SPI, PWM, ADC, DAC

## 📦 Conteúdo do Repositório

Este repositório contém os seguintes recursos para ajudar você a começar com o ESP32:

- **Documentação:** Informações detalhadas sobre a configuração e uso do ESP32.
- **Exemplos de Código:** Scripts de exemplo em várias linguagens de programação, incluindo MicroPython, Arduino, e C++.
- **Tutoriais:** Guias passo a passo para projetos comuns, como conectar o ESP32 a uma rede Wi-Fi, controlar LEDs, e ler sensores.

## 🛠️ Ferramentas Necessárias

Para começar a desenvolver com o ESP32, você precisará de algumas ferramentas:

- **IDE de Programação:** Recomendamos o [Arduino IDE](https://www.arduino.cc/en/software) ou o [Thonny IDE](https://thonny.org/) para MicroPython.
- **Driver USB:** Certifique-se de instalar o [driver CP210x](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers?tab=downloads) para comunicação serial.
- **Firmware:** Baixe o firmware apropriado para sua linguagem de programação:
  - [MicroPython](https://micropython.org/download/esp32/)
  - [Arduino](https://github.com/espressif/arduino-esp32)

## 📋 Instalação e Configuração

### 1. Configuração do Ambiente de Desenvolvimento

- **Arduino IDE:**
  1. Instale o [Arduino IDE](https://www.arduino.cc/en/software).
  2. Adicione a URL de Gerenciador de Placas do ESP32: `https://dl.espressif.com/dl/package_esp32_index.json`.
  3. Vá para **Ferramentas** > **Placa** > **G
