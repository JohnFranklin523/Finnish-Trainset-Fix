﻿Finnish Trainset Fix README
===============================

----------
0 Sisällysluettelo
----------

1   NewGRF:n kuvaus
2   Yleistä tietoa
    2.1  Vaatimukset
    2.2  Asennus
    2.3  NewGRF-Parametriasetukset
    2.4  Käyttö
3   Tiedossaolevat ongelmat
4   Taustatietoa
5   Usein Kysytyt Kysymykset
6   Lopputekstit
7   Yhteystiedot
    7.1  Bugiraportointi
    7.2  Muut ongelmat
    7.3  Yleiset tiedustelut
8   Lisenssi
9   Lähdekoodin saatavuus


-------
1 NewGRF:n kuvaus
-------

Suomen junakalusto-NewGRF sisältää Suomalaista 
junakalustoa vuodesta 1870 nykypäivään saakka. 

Tämän junakalusto-NewGRF:n on tehnyt Finnish Trainset-tiimi. 
(ks. lopputekstit)


---------------------
2 Yleistä tietoa
---------------------

2.1 Vaatimukset
----------------
- OpenTTD 1.2.0 tai nightly r23842, tai	korkeampi
- Ei ole yhteensopiva TTDPatch:in kanssa


2.2 Asennus
----------------
OpenTTD:
  katso http://wiki.openttd.org/NewGRF
  Tämä NewGRF on saatavilla OpenTTD:n Sisällönlatausjärjestelmästä.


2.3 NewGRF-parametriasetukset
----------------------

Lähiliikenteen ja kaukoliikenteen vaunujen sekä makuuvaunujen, 
moottorijunien ja moottorivaunujen lastausnopeudet voidaan
määritellä NewGRF-parametreillä. Oletusarvot ovat:

Lähiliikenteen vaunut: 40
Kaukoliikenteen vaunut: 25
Makuuvaunut: 15

Liikkuvan kaluston ostohinnat ja käyttökustannukset 
voidaan määritellä NewGRF-parametreillä. Oletusarvot ovat:

Ostohinnat: 100%
Käyttökustannukset: 100%

Matkustaja- ja tavaravaunujen käyttökustannukset voidaan ottaa
käyttöön NewGRF-parametrillä (Vaunujen käyttökustannukset)

Oletusasetus vaunujen käyttökustannuksille on päällä.


2.4 Käyttö
---------

Tässä junasetissä on Suomalaisen liikkuvan kaluston lisäksi
myös useita vaunutyyppejä Suomen itäisestä (Venäjän) ja läntisestä 
(Ruotsi/Saksa, RailShip/SeaRail) yhdysliikenteestä.

Veturien ja moottorivaunujen sovittamisella voidaan muuttaa
nopeutta ja vetovoimaa sopivaksi tavara- tai matkustajaliikenteeseen
ja/tai väritystä tiettynä aikana voimassaolevaksi.

Kun värityksen sovittaminen on johonkin kalustoon saatavilla, 
oletusasetus on pelin vuodesta riippuvainen väritys. Tällöin, 
kun väritys on ajoitettu muttumaan tiettyinä vuosina, veturi, 
moottorijuna, moottorivaunu tai vaunu päivittyy automaattisesti 
seuraavaan väritykseensä.

Seuraava sovitusvaihtoehto on valmistusvuoden väritys. Tällöin veturi,
moottorijuna, moottorivaunu tai vaunu jää on the valmistusvuonna 
voimassaolleensa väritykseensä. Se ohittaa automaattisen värityksen 
päivityksen, mahdollistaen entisen värityksen käytön aikana, 
jolloin se ei olisi muuten mahdollista.

Kolmas sovitusvaihtoehto on manuaalisesti valita väritys niiden
väritysten joukosta, jotka ovat tai ovat olleet saatavilla.

Nopeus ja vetovoima voidaan valita samanaikaisesti (jos kyseisessä 
veturissa, moottorijunassa tai vaunussa sen voi valita) 
vuodesta riippuvan, valmistusvuoden tai manuaalisen värityksen 
valinnan kanssa, mikäli värityksiä ja nopeuksia/vetovoimia on enemmän
kuin yksi käytettävissä.

Vaunun sovittaminen toimii kuten muissakin OpenTTD:n vaunuissa, 
suuressa osassa tavaravaunuja on rahtikohtaiset grafiikat.

-------------------------
3 Tiedossaolevat ongelmat
-------------------------

Jotkut vaunut näyttävät liian "putkimaisilta" jos ne ovat peräkkäin. 
Vaunuista on lista Suomen Junasetin DevZone-sivulla:
http://dev.openttdcoop.org/issues/5450

Jos mielestäsi joku listaamaton vaunu näyttää peräkkäin aseteltuna 
liian "putkimaiselta", ilmoita siitä TT-Foorumin Finnish Trainset
-ketjuun tai raportoi siitä DevZonelle. (Katso kohta 7.1, bugien 
raportointi. DevZone sekä TT-foorumi vaativat rekisteröitymisen)


--------------
4 Taustatietoa
--------------

Liikkuvaa kalustoa koskeva tieto on kerätty luotettavista lähteistä.
Tiedoissa voi olla virheitä, raportoi jos löydät niitä.
(katso kohta 7.1 Bugien raportointi)

Jotkut veturit ja moottorivaunut sisältävät tyhjäkäynti-, kiihdytys-
ja ajoääniefektejä. Seuraavat henkilöt ovat toimittaneet niitä Finnish 
Trainset-tiimin käyttöön:

Oskari Kvist, Ville Saarelainen, Suomen Rautatiemuseo, Lari Nylund, 
Juhana Konttinen, Niklas Savinsaari, Pietu Tuovinen, Mikael Sarhervo, 
Timo Keski-Pitäjä ja muut.

--------------------------
5 Usein Kysytyt Kysymykset
--------------------------

K: Miksi en voi käyttää tätä NewGRF:ää OpenTTD:n vanhemmissa 
versioissa tai TTDPatch:issa?

V: Tämä NewGRF käyttää joitakin ominaisuuksia jotka ovat saatavilla
vain OpenTTD:n revisioon r23842 ja sitä uudempiin revisioihin. 
Lisäksi NML:n uusin versio jota käytetään tämän NewGRF:än kompilointiin, 
tuottaa GRF-version 8. Tätä versiota tukee vain OpenTTD:n versio r23166
tai uudempi.



--------------
6 Lopputekstit
--------------

Perustaja:
- Villem

Projektin johto ja managerointi:
- DanMacK (Dan MacKellar)
- Kyosuke1989 (Oskari Kvist)

Tiedot liikkuvasta kalustosta:
- DanMacK (Dan MacKellar)
- as
- Lakie (Nathaniel Lake)
- Kyosuke1989 (Oskari Kvist)
- juzza1 (Jussi Virtanen)

Grafiikka:
- DanMacK (Dan MacKellar)
- Purno
- Hairysteed
- jpl (Juhani Pirttilahti)
- Kyosuke1989 (Oskari Kvist)
- juzza1 (Jussi Virtanen)
- Emperor Jake
- alluke

Ääniefektit:
- Kyosuke1989 (Oskari Kvist)

Koodi:
- FooBar (Jasper Vries), alustava DevZone-käyttöönotto
- juzza1 (Jussi Virtanen), NML-pohjainen koodaus DevZone-ympäristössä
- Lakie (Nathaniel Lake), aiemmat NFO-pohjaiset koodaukset

Käännökset:
- Suomi:  Kyosuke1989 (Oskari Kvist)

Makefile-järjestelmä:
- planetmaker (Ingo von Borstel)


Erityiskiitokset kaikille projektissa mukana oleville ja olleille.


---------------------
7 Yhteystiedot
---------------------

7.1 Bugien raportointi
---------------
Raportoi tarvittaessa kaikki löytämäsi bugit Englanninkielellä:
  DevZoneen: http://dev.openttdcoop.org/projects/finnishtrainset/issues
  tai TT-foorumille: http://www.tt-forums.net/viewtopic.php?f=26&t=21457

Huomaathan että DevZone on kansainvälinen, kuten myös TT-foorumi, 
joten keskustelun kielenä käytetään aina englantia. 
DevZone sekä TT-foorumi vaativat rekisteröitymisen.
  
Sisällytä toimittamaasi bugiraporttiin aina yksityiskohtainen bugin 
kuvaus, mieluiten kuvakaappauksen ja pelin tallennuksen kanssa. 
Kerro myös mitä OpenTTD:n ja tämän NewGRF:n versiota käytät.

Jos löydät bugin pelin tallennuksessa, joka sisältää
NewGRF-tiedostoja, jotka eivät ole saatavilla OpenTTD:n 
Sisällönlatauspalvelusta, yritä tuottaa bugi uudessa pelissä, jonka
NewGRF-tiedostot ovat helposti saatavilla.

Jos käytät patchattua versiota pelistä, yritä tuottaa bugi uudelleen
virallisella OpenTTD:n jakeluversiolla. Jos et voi tuottaa bugia näin 
uudelleen, älä raportoi sitä tänne, vaan foorumin patchia tai
patchpakia koskevaan ketjuun.


7.2 Muut ongelmat
------------------
Jos sinulla on ongelmia käyttäessäsi tätä NewGRF:ää (ongelmia jotka
eivät ole Usein Kysytyissä Kysymyksissä), voit kysyä asiasta englanniksi
TT-foorumin ketjussa: http://www.tt-forums.net/viewtopic.php?f=26&t=21457
(Vaatii rekisteröitymisen)

7.3 Yleiset tiedustelut
---------------------

Jos sinulla on kysymyksiä, joita ei voida kysyä foorumin aiheessa, 
ota yhteyttä henkilöön kyosuke1989 yksityisviestillä
osoitteessa www.tt-forums.net. (Vaatii rekisteröitymisen)



----------
8 Lisenssi
----------

FTS - Suomen junakalusto
Copyright (C) 2013 Finnish Trainset-tiimi

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License along
with this program; if not, write to the Free Software Foundation, Inc.,
51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.



--------------------
9 Lähdekoodin saanti
--------------------

Lähdekoodi voidaan hakea #openttdcoop DevZonelta
lähdekoodin selaimella:
    http://dev.openttdcoop.org/projects/finnishtrainset/repository
tai mercurial checkoutilla:
    hg clone http://hg.openttdcoop.org/finnishtrainset
tai lähteen bundle-latauksella (ainoastaan releaset):
    http://bundles.openttdcoop.org/finnishtrainset/

Ohjeet lähdekoodista kompilointiin ja sen vaatimukset sisältyvät 
lähteeseen tiedostossa /docs/building_from_source.txt.
