## Lýsing
Þetta verkefni stefnir að því að búa til hágæða Arcade vél sem verður með nokkra sérhannaða leiki og getur emulate-að leiki frá flestum eldri leikjatölvum eins og SNES, Gameboy etc. Body-ið á vélinni mun vera búinn til í framtíðarstofunni. 

![Image](arcadePi.svg)

## Myndbönd af verkferlinu

<a href="http://www.youtube.com/watch?feature=player_embedded&v=HgUZTIXKdLo
" target="_blank"><img src="http://img.youtube.com/vi/HgUZTIXKdLo/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
<a href="http://www.youtube.com/watch?feature=player_embedded&v=b05tBVBXyNg
" target="_blank"><img src="http://img.youtube.com/vi/b05tBVBXyNg/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
<a href="http://www.youtube.com/watch?feature=player_embedded&v=CV4-rwr6hdc
" target="_blank"><img src="http://img.youtube.com/vi/CV4-rwr6hdc/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
<a href="http://www.youtube.com/watch?feature=player_embedded&v=E8BBhOTaYSk
" target="_blank"><img src="http://img.youtube.com/vi/E8BBhOTaYSk/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
<a href="http://www.youtube.com/watch?feature=player_embedded&v=jp3dPthCsVM
" target="_blank"><img src="http://img.youtube.com/vi/jp3dPthCsVM/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
<a href="http://www.youtube.com/watch?feature=player_embedded&v=jBmVpUQb9HM
" target="_blank"><img src="http://img.youtube.com/vi/jBmVpUQb9HM/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>


## Kóði

Við skrifuðum mjög lítinn kóða þar sem flest allt sem við gerðum var annaðhvort testing með kóða sem var nú þegar til eða bara hardware hlutir eins og að reyna að tengja allt saman rétt.
Mest allur kóði sem við notuðum var frá þessu adafruit matrix library:
[RGB LED Matrix](https://github.com/hzeller/rpi-rgb-led-matrix)


## Hversu langt komumst við?

Það komu upp mjög mörg skrautleg vandamál sem við sáum ekki fyrir í þessu verkefni, og það hægði frekar mikið á okkur. Þess vegna þurftum við að minnka verkefnið smá til að það væri hægt að ná deadline-inu.

* festum alla skjánna við 3x3 frame
* tengdum þá alla við raspberri pi kóða sem gat spilað video eða display-að myndir á pi-inn
* tengdum input takka við pi-inn sem gat interactað við skjáinn
* settum upp blueprint fyrir hvernig þetta ætti að líta út að lokum (sést að ofan)
* kynntum okkur pixel mapper kóða til þess að við gætum skrifað okkar eiginn pixel mapper kóða.
* kynntum okkur hvernig á að vinna með ffmpeg

## Hvað vantar upp á verkefnið? 

* Fá ffmpeg screen capture til að displaya á matrixið
* Búa til custom pixel mapper fyrir setup-ið okkar
* Forrita leonardo til að senda usb-signal
* Búa til kassa utan um vélina

## Höfundar:
Benedikt, Davíð og Kristján
