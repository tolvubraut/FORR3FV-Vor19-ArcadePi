<style>
    body {
        margin-top:5em;
    }
    .headwrapper {
        position:fixed ;
        top:0;
        left:0;
        right:0;
        height: 3.5em;
        background-color: #fff; 
        border: 0;   
        box-shadow: 0 0 1em #ddd;
        z-index:99;
    }             
    .headmenu {
        width:100%;
        padding: 0 1em;
    } 
    .logo  {
        display: flex;
        align-content: center;
    }  
    .logo a{
        text-decoration: none;
    }
    .logo img{
        width: 2.5em;
        height: 3.5em;
    }
    .logotxt {   
        color: #0B3E7A;
        font-family: sans-serif;
        text-decoration: none;
        text-align: left;
        padding-top:1.3em;
    }
</style>

<div class="headwrapper">
    <div class="headmenu"> 
        <div class="logo"> 
            <a href="https://tolvubraut.github.io/" title="Tölvubraut Tækniskólans"><img src="tskoli-logo.svg" title="Aftur á vef tölvubrautar"></a>  
            <a href="https://tolvubraut.github.io/" title="Tölvubraut Tækniskólans" class="logotxt">TÖLVUBRAUT - <em>rétta leiðin</em></a>   
        </div>
    </div>
</div> 

# ArcadePi

![Image](arcadePi.svg)

## Höfundar:
* Benedikt
* Davíð
* Kristján

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

## Kóði

Við skrifuðum mjög lítinn kóða þar sem flest allt sem við gerðum var annaðhvort testing með kóða sem var nú þegar til eða bara hardware hlutir eins og að reyna að tengja allt saman rétt.
Mest allur kóði sem við notuðum var frá þessu adafruit matrix library:
https://github.com/hzeller/rpi-rgb-led-matrix

## Myndir og myndbönd

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
