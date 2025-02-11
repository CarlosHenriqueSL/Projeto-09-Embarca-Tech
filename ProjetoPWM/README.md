# Projeto Servomotor

Este projeto demonstra o controle de um servomotor utilizando o PWM do RP2040 com a Pico SDK. O código utiliza a GPIO 22 para gerar um sinal PWM com período de 20 ms (50 Hz) e ajusta a posição do servomotor por meio da modulação do ciclo de trabalho.

## Funcionalidades

- **Configuração PWM:** Período de 20 ms com ticks de 1 µs.
- **Posições Pré-definidas:**
  - **180°:** Pulso de 2400 µs (aguarda 5 segundos).
  - **90°:** Pulso de 1470 µs (aguarda 5 segundos).
  - **0°:** Pulso de 500 µs (aguarda 5 segundos).
- **Varredura Suave:** Movimento contínuo entre 0° e 180° com incrementos/decrementos de 5 µs a cada 10 ms.
