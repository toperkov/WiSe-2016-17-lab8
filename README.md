# Bežične senzorske mreže - Lab 8

### FESB, smjer 110/111/112/114/120, akademska godina 2016/2017

**NAPOMENA: Vježba je napravljena po uzoru na upute dane na https://tmrh20.github.io/RF24Mesh/index.html** 

U sklopu današnje vježbe student će realizirati jednostavnu bežičnu senzorsku mrežu *stablaste topologije* (``tree topology``) korištenjem ``RF24Mesh`` bibiloteke.

Centralni čvor prati jedinstvene ID-ove ostalih čvorova i dodijeljene ``RF24Network`` adrese. Kada se čvor fizički preseli ili izgubi vezu s mrežom, može ga se postaviti tako da se automatski pridruži mreži i ponovo se konfigurira unutar mreže.

Svakom čvoru je dodijeljen jedinstveni broj u rasponu od 1 do 255, dok se adresiranjem, usmjeravanjem itd. bavi biblioteka ``RF24Mesh``.

U takvoj topologiji konfiguraciji senzori/čvorovi ne trebaju biti fiksni nego mogu biti mobilni tako da se adresiranje i topologija mogu mijenjati.

## Zadatak

Student će u sklopu današnje vježbe realizirati stablastu strukturu korištenjem RF24Mesh biblioteke. Nadalje, student će koristiti kod koji je dan u direktoriju vjezba. Zadatak svakog studenta modificirati kod na strani centralnog uređaja te posredničkih i krajnjih uređaja tako da šalje informacije o temperaturi, vlažnosti i osvjetljenju. Nadalje, na strani centrlnog uređaja modificirajte kod tako da vam ispisuje vrijnosti temperature, vlage i osvjetljenja kao i ID čvora.

Spojite posredničke i krajnje senzorske uređaje prema slici:

<img src="https://cloud.githubusercontent.com/assets/8695815/24838259/eed6ec80-1d44-11e7-8137-7fabad4a0e53.png" width="400px" />


## Korisni linkovi
 [1] https://tmrh20.github.io/RF24Mesh/index.html
