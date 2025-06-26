# rocket_recovery_lm393_leds_uv

Sistema eletrônico cuja funcionalidade prevista é liberar um paraquedas logo após atingir o apogeu da trajetória do lançamento. O funcionamento do cirtuto é basedo no monitoramento de tensões elétricas em duas portas analógicas do CI LM393, as tensões são geradas por 2 LEDs UV. LED UV tem a paricularidade de criar uma tensão V nos seus terminais quando exposta á luz ultravioleta, no caso do foguete, a luz ultravioleta do Sol. Quando há inversão da tensão nos terminais o LM393 atravéz do seu pino de saída faz a saturação do TIP122 que passa a conduzir corrente elétrica direta da bateria de 9V fazendo a ignição da carga.

Esquema elétrico 25-06-2025
![image](https://github.com/user-attachments/assets/3ec3e2eb-5073-4bbb-8c16-77cab1cbe4ad)


Placa de circuito 25-06-2025
![image](https://github.com/user-attachments/assets/5081be8b-6693-4a67-b3a5-2645a3511df3)


