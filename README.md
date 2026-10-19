# Analog Crypt

Vijf browserapps die de analoge betaal-tv-scrambling van de jaren 80 en 90 nabootsen.
Five browser apps that recreate analogue pay-TV scrambling from the 1980s and 1990s (English below).

**Probeer ze / Try them:** https://tq255.github.io/Analog-Crypt/

| App | Systeem | Gebruikt door |
|---|---|---|
| [VideoCrypt](videocrypt/) | Knippen en ronddraaien van elke lijn, VideoCrypt S | Sky, BBC Select |
| [Syster](syster/) | Nagravision Syster, Discret 11, Smartcrypt | Canal+, Premiere |
| [Luxcrypt](luxcrypt/) | Sync vervangen door een burst, beeld in negatief | RTL 4, RTL 5, Veronica, SBS 6 |
| [Eurocrypt](eurocrypt/) | D2-MAC, enkele en dubbele snede | FilmNet, TV1000, Canal+ |
| [Fantasycrypt](fantasycrypt/) | Verzonnen: pixels over het hele beeld verdeeld | niemand, en daar is een reden voor |

## Nederlands

Elke app laat je je eigen foto's, video's of camerabeeld scramblen, en het resultaat bekijken op drie manieren: zoals het uitgezonden werd, zoals een abonnee met de juiste kaart het zag, en zoals een piraat het zonder kaart probeerde te kraken.

In alle apps:
- testbeeld met eigen herkenningsmelodie, foto of video, live camera met microfoon;
- een datastreep bovenin, zodat een opgeslagen gescrambeld beeld of filmpje later weer herkend en ontsleuteld wordt;
- een virtuele videorecorder (spoelen, beeld voor beeld);
- een CRT-beeldbuis met overscan (WebGL, met CSS als terugval);
- opslaan als PNG en opnemen als video met geluid;
- een taalkeuze Nederlands/Engels bovenin.

Waar de techniek bekend is, volgen de apps die zo precies mogelijk, vaak naar de broncode van hacktv. Wat niet bekend is, is ingevuld en staat in elke app onderaan als aanname. Er zitten geen echte kaartsleutels in. Dit is technische geschiedenis en speelgoed; de uitzendingen zelf bestaan allang niet meer.

Elke app is één los HTML-bestand zonder build-stap. Je kunt het ook downloaden en lokaal openen.

## English

Each app lets you scramble your own photos, videos or camera, and view the result three ways: as it went out over the air, as a subscriber with the right card saw it, and as a pirate tried to crack it without a card. Every app has an NL/EN language switch at the top.

Where the technique is documented, the apps follow it as closely as possible, often after the hacktv source code. Where it is not, the gaps are filled in and listed in each app as assumptions. No real card keys are included. This is technical history and a toy; the broadcasts themselves are long gone.

Every app is a single self-contained HTML file with no build step.

## Licentie / Licence

GNU General Public License v3.0, see [LICENSE](LICENSE). Parts of the code (the Syster key tables and shift registers, Discret 11, the D2-MAC line layout and scrambling) are derived from [hacktv](https://github.com/fsphil/hacktv) by Philip Heron and Alex L. James, which is GPL-3.0.

## Bronnen en dank / Sources and thanks

- [hacktv](https://github.com/fsphil/hacktv), Philip Heron and Alex L. James
- [Cryptimage](https://github.com/Potomac/cryptimage)
- Markus G. Kuhn, analyses of VideoCrypt and Nagravision
- Michael Niedermayer, on Nagravision/Syster descrambling
- Fabien Sanglard, [Discret 11](https://fabiensanglard.net/discret11/)
- European Scrambling Systems FAQ (1996)

Gemaakt door Daniel, met hulp van Claude.
