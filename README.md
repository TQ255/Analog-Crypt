# Analog Crypt

Five browser apps that recreate analogue pay-TV scrambling from the 1980s and 1990s.
Vijf browserapps die de analoge betaal-tv-scrambling van de jaren 80 en 90 nabootsen (Nederlands hieronder).

**Try them / Probeer ze:** https://tq255.github.io/Analog-Crypt/

| App | System | Used by |
|---|---|---|
| [VideoCrypt](videocrypt/) | Every line cut and rotated, VideoCrypt S | Sky, BBC Select |
| [Syster](syster/) | Nagravision Syster, Discret 11, Smartcrypt | Canal+, Premiere |
| [Luxcrypt](luxcrypt/) | Sync replaced by a burst, picture turned negative | RTL 4, RTL 5, Veronica, SBS 6 |
| [Eurocrypt](eurocrypt/) | D2-MAC, single and double cut | FilmNet, TV1000, Canal+ |
| [Fantasycrypt](fantasycrypt/) | Made up: pixels spread over the whole picture | nobody, and there is a reason for that |

## English

Each app lets you scramble your own photos, videos or camera, and view the result three ways: as it went out over the air, as a subscriber with the right card saw it, and as a pirate tried to crack it without a card.

In every app:
- a test card with its own ident tune, photo or video, live camera with microphone;
- a data stripe at the top, so a saved scrambled picture or clip is recognised and decoded later;
- a virtual video recorder (fast forward, rewind, frame by frame);
- a CRT picture tube with overscan (WebGL, with CSS as a fallback);
- saving as PNG and recording as video with sound;
- an English/Dutch language switch at the top.

Where the technique is documented, the apps follow it as closely as possible, often after the hacktv source code. Where it is not, the gaps are filled in and listed in each app as assumptions. No real card keys are included. This is technical history and a toy; the broadcasts themselves are long gone.

Every app is a single self-contained HTML file with no build step. You can also download one and open it locally.

## Nederlands

Elke app laat je je eigen foto's, video's of camerabeeld scramblen, en het resultaat bekijken op drie manieren: zoals het uitgezonden werd, zoals een abonnee met de juiste kaart het zag, en zoals een piraat het zonder kaart probeerde te kraken.

In alle apps:
- testbeeld met eigen herkenningsmelodie, foto of video, live camera met microfoon;
- een datastreep bovenin, zodat een opgeslagen gescrambeld beeld of filmpje later weer herkend en ontsleuteld wordt;
- een virtuele videorecorder (spoelen, beeld voor beeld);
- een CRT-beeldbuis met overscan (WebGL, met CSS als terugval);
- opslaan als PNG en opnemen als video met geluid;
- een taalkeuze Engels/Nederlands bovenin.

Waar de techniek bekend is, volgen de apps die zo precies mogelijk, vaak naar de broncode van hacktv. Wat niet bekend is, is ingevuld en staat in elke app onderaan als aanname. Er zitten geen echte kaartsleutels in. Dit is technische geschiedenis en speelgoed; de uitzendingen zelf bestaan allang niet meer.

Elke app is één los HTML-bestand zonder build-stap. Je kunt het ook downloaden en lokaal openen.

## Licence / Licentie

GNU General Public License v3.0, see [LICENSE](LICENSE). Parts of the code (the Syster key tables and shift registers, Discret 11, the D2-MAC line layout and scrambling) are derived from [hacktv](https://github.com/fsphil/hacktv) by Philip Heron and Alex L. James, which is GPL-3.0.

## Sources and thanks / Bronnen en dank

- [hacktv](https://github.com/fsphil/hacktv), Philip Heron and Alex L. James
- [Cryptimage](https://github.com/Potomac/cryptimage)
- Markus G. Kuhn, analyses of VideoCrypt and Nagravision
- Michael Niedermayer, on Nagravision/Syster descrambling
- Fabien Sanglard, [Discret 11](https://fabiensanglard.net/discret11/)
- European Scrambling Systems FAQ (1996)

Made by Daniel, with help from Claude.
