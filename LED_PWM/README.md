# Projeto LED com PWM

Este projeto demonstra o controle de um LED utilizando o módulo PWM do RP2040 com o Pico SDK. O código utiliza a GPIO 12 para gerar um sinal PWM com resolução de 8 bits, criando um efeito de fade in/fade out no LED.

## Funcionalidades

- **Configuração PWM:**  
  Configura o PWM com resolução de 8 bits (wrap = 255) e frequência aproximada de 1 kHz, garantindo uma modulação de brilho suave.

- **Efeito Visual:**  
  O LED realiza transições contínuas de brilho (fade in e fade out), demonstrando a variação do ciclo de trabalho (duty cycle) do PWM.
