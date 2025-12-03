#1o2
1 - Beatriz:
-Troca por Arduino ou a  porta echo precisa ter um resistor de 1k fazendo queda de tensao antes de ligar no esp32.
--Uma configuração comum e segura para reduzir 5V para aproximadamente 3.3v é:R1 (Entre Echo e Pino D13):  1k e R2 (Entre Pino D13 e GND): 2k, o mais próximo de 2k possível, 2.2k ou 1.8k (acho mais rapido e pratico neste momento voce trocar por Arduino).
-Não pode usar o pino 12.
