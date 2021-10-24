# Vaja-2-ADC-Continious-conversion

Kot analogni vhod sva se odločila za pin PC0.Ko povežemo potenciometer na utrezni kanal se pinh obarva zeleno in poleg njega se izpiše ADC1_IN1.
Ko v Clock Configuration spremenimo APB1 peripheral clock na 16MHz, se tudi ABP1 Timer clock spremeni in sicer na 32MHz.
Clock Prescaler nastavimo z deliteljem 4.
Preslikana Frekvenca takta je sedaj 4MHz.
Pravi čas vzorčenja Tvz=62,88uS

Komentar na delovanje:
Delovanje je pravilo in tekoče. Ima samo eno pomankljivost in sicer da gre pontenciometer samo do vrednosti 251.
