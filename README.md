# Conversor-USB-UART-SPI-I2C-JTAG

![Status do Projeto](https://img.shields.io/badge/Status-Desenvolvimento-yellow)
![PCB](https://img.shields.io/badge/PCB-KiCad-green)

## Descrição
Esta PCB trata-se de um poderoso circuito eletrônico que transforma uma única porta USB em múltiplos canais seriais de alta velocidade, ideal para desenvolvedores que precisam de versatilidade em seus projetos.

<p align="center">
  <img width="679" height="605" alt="usb2UartSpiI2c" src="https://github.com/user-attachments/assets/d942b77e-0439-4e70-87df-7e57c2c5ee0d" />
</p>

---

## Descrições técnicas

- Interface USB: Dispositivo USB High-Speed de 480Mbps;
- Possui duas UART (UART0 e UART1), uma SPI, uma I2C, uma JTAG e 8 pinos de GPIOs controlados diretamente pela USB;
- Taxa de Transmissão (Baud Rate): Variável de 1200bps até 6Mbps;
- Alimentação Principal: Requer apenas 3.3V;
- Controle de Fluxo: Suporte completo a Hardware Flow Control (CTS e RTS);
- Buffering (FIFO):
  - RX FIFO: 2048 bytes por UART.
  - TX FIFO: 1024 bytes por UART.
- Configurações UART:
  - Bits de Dados: 8 bits;
  - Paridade: Ímpar, Par e Nenhuma;
  - Bits de Parada: 1 ou 2.

---

## Estrutura do repositório
Os arquivos de hardware foram desenvolvidos utilizando o KiCad 9.0.
- **`.kicad_pcb`**: Layout da placa de circuito impresso (Board).
- **`.kicad_sch`**: Esquemático eletrônico do sistema (Schematic).
- **`.kicad_pro`**: Gerenciador de projeto do KiCad (Project).

---

## Autor
**Dr. Luiz Fernando Pinto de Oliveira**

*Engenheiro Eletrônico especializado em Sistemas Embarcados e Ultra-Low Power.*
- **Website:** [FAPLO](https://faplo.webnode.page/)
- **LinkedIn:** [lfpo](https://www.linkedin.com/in/lfpo/)

---

Shield: [![CC BY-NC-ND 4.0][cc-by-nc-nd-shield]][cc-by-nc-nd]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-NoDerivs 4.0 International License][cc-by-nc-nd].

[![CC BY-NC-ND 4.0][cc-by-nc-nd-image]][cc-by-nc-nd]

[cc-by-nc-nd]: http://creativecommons.org/licenses/by-nc-nd/4.0/
[cc-by-nc-nd-image]: https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png
[cc-by-nc-nd-shield]: https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg
