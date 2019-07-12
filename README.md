# PI2 - Estação de Solda - Forno - Eletrônica

Esse projeto é responsável por fazer o controle PID de temperatura de um forno para reflow da solda SAC305. O trabalho foi desenvolvido para a matéria Projeto Integrador 2, na Universidade de Brasília.

## Versões de placas e *libraries*

1. esp8266 - 2.0.0;
2. Ticker - versão nativa para esp8266 2.0;
3. ESP8266WiFi - versão nativa para esp8266 2.0;
4. ESP8266WebServer - versão nativa para esp8266 2.0;
5. WiFiClient - versão nativa para esp8266 2.0.

## Instruções de uso
1. Copiar `sensor_PI2` para pasta de bibliotecas `arduino/libraries`;
2. Instalar placa esp8266 na Arduino IDE segundo o tutorial: https://www.filipeflop.com/blog/programar-nodemcu-com-ide-arduino/, selecionando a versão 2.0.0;
3. Carregar o arquivo `controle_PID`, modificando as variáveis `ssid` e `password`para rede WiFi que será utilizada;
4. Abrir o *Serial Monitor* para verificar qual IP e porta foram utilizados para o *Web Server*;
5. Abrir o navegador e entrar no IP especificado;
6. Apertar o botão Iniciar na interface;

Para usos subsequentes, iniciar a partir da instrução 5 (sem conectar via USB), visto que o IP será fixo para a rede selecionada.
