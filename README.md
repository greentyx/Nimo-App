✨ O que é o Nimo?
O Nimo é um robozinho companheiro feito à mão, pensado especialmente para crianças de até 10 anos — com foco em crianças com Transtorno do Espectro Autista (TEA). Ele combina um hardware simples e acessível com um site educacional interativo, criando uma experiência de apoio emocional e aprendizado lúdico.
O Nimo reage ao toque, exibe expressões no display OLED, toca melodias suaves e tem comportamento sempre previsível — uma característica essencial para o conforto de crianças autistas.

Diagrama de ligações
ESP32-C3          OLED SSD1306
  GPIO 8  ──────  SDA
  GPIO 9  ──────  SCL
  3.3V    ──────  VCC
  GND     ──────  GND

ESP32-C3          Buzzer Passivo
  GPIO 5  ──────  IO
  5V      ──────  VCC
  GND     ──────  GND

ESP32-C3          TTP223B Touch
  GPIO 4  ──────  SIG
  3.3V    ──────  VCC
  GND     ──────  GND

Bibliotecas Arduino necessárias
Instale pelo Arduino IDE → Gerenciar Bibliotecas:

Adafruit SSD1306 (by Adafruit)
Adafruit GFX Library (instalada automaticamente junto)
