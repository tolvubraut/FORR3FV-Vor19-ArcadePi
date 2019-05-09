## Höfundar:
### Benedikt
### Davíð
### Kristján


# ArcadePi

![Image](arcadePi.svg)

## Lýsing
Þetta verkefni stefnir að því að búa til há gæða Arcade vél sem verður með nokkra sérhannaða leiki og getur emulate-að leiki frá flestum eldri leikjatölvum eins og SNES, Gameboy etc. Body-ið á vélinni mun vera búinn til í framtíðarstofunni. Þessi Arcade mun henta æðislega fyrir sýningar og atburði til þess að auglýsa Tölvubraut og framtíðarstofuna.

## Part list
#### 86,844 kr
[Power Supply * 3](https://www.meanwell-web.com/en-gb/ac-dc-single-output-enclosed-power-supply-output-rs--25--5)<br>
[Screen 64x64px * 9](https://www.adafruit.com/product/3649)<br>
[Arduino Leonardo * 3](https://store.arduino.cc/leonardo)<br>
[Start Button * 2](https://www.adafruit.com/product/1188)<br>
[C14 Male Power Socket * 3](https://www.amazon.com/URBEST-Socket-Module-Switch-Terminals/dp/B06XNMT3WL/ref=sr_1_1_sspa?keywords=C14+Inlet+Male+Plug+Power+Socket&qid=1552381915&s=gateway&sr=8-1-spons&psc=1)<br>
[Screen power adapter * 6](https://www.adafruit.com/product/3211)<br>
[Screen driver pcb * 2](https://www.adafruit.com/product/2345)

## Hversu langt komumst við?

Það komu upp mjög mörg skrautleg vandamál sem við sáum ekki fyrir í þessu verkefni, og það hægði frekar mikið á okkur. Þess vegna þurftum við að minnka verkefnið smá til að það væri hægt að ná deadline-inu.

Við festum alla skjánna við 3x3 frame
Við tengdum þá alla við raspberri pi kóða sem gat spilað video eða display-að myndir á pi-inn
Við tengdum input takka við pi-inn sem gat interactað við skjáinn
Við kynntum okkur pixel mapper kóða til þess að við gætum skrifað okkar eiginn pixel mapper kóða.
Við kynntum okkur hvernig á að vinna 

## Hvað vantar upp á verkefnið? 

* Fá ffmpeg screen capture til að displaya á matrixið
* Búa til custom pixel mapper fyrir setup-ið okkar
* Forrita leonardo til að senda usb-signal
* Búa til kassa utan um vélina

## Kóði

Mest allur kóði sem við notuðum var frá þessu pixel mapper library:
#(EKKI FINAL VERSION PLZ SETJIÐ INN EINHVERN KÓÐA)
https://github.com/hzeller/rpi-rgb-led-matrix
