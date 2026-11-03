## Kansrekening in vogelvlucht, H Tijms
Hier zijn de uitwerkingen van de opdrachten zo goed als dat ik het begrepen heb.
## opmerkingen
- (10 boven 5) schrijf ik hier als bin(10,5)

## hoofdstuk 1

Testvragen:

- nummerplaten: 
	- [26³ . 10³](https://www.wolframalpha.com/input?i=26%C2%B3+*+10%C2%B3)
	- [26\*25\*24\*10\*9\*8](https://www.wolframalpha.com/input?i=26+*+25+*+24+*+10+*+9+*+8)
- cadeautjes: lastig maar ik heb zo gedacht. Kind 1 kan niet cadeau 1 krijgen maar wel 2, 3 of 4. Stel zij krijgt cadeau 2, dan zijn er voor kind 2,3,4 precies 3 mogelijkheden, nl. (1,4,3),  (3,4,1), (4,1,3). Dit geldt natuurlijk ook als kind 1 cadeau 3 of 4 krijgt. Dus zijn er 3 x 3 mogelijkheden, is 9.
- champions league. Ik dacht eerst 4! = 24. Dat is ook zo als je weet hoe er meestal geloot wordt in de Cl, nl dat de helft van de teams recht hebben op een eerste thuiswedstrijd. Maar dat wordt hier niet bedoeld. 'met in achtneming van wie eerst thuis speelt' duidt er op dat Ajax - Barcelona een andere wedstrijd is dan Barcelona - Ajax. De uitkomt krijg je dan door het volgende: met 8 teams kun je op 8! rangschikken (t1 - t2, t3 - t4, etc waarbij de oneven teams dus thuis spelen). Maar t1 - t2, t3 - t4 is natuurlijk gelijk aan t3 - t4, t1 - t2. Maw de volgorde van de wedstrijd is niet relevant. 4 wedstrijden kun je op 4! manier rangschikken. het antwoord is dus [8! / 4!](https://www.wolframalpha.com/input?i=8%21+%2F+4%21)
- juryleden: [bin(10,3) * bin(7,2)](https://www.wolframalpha.com/input?i=bin%2810%2C3%29+*+bin%287%2C2%29)
- commissie: stel dat iedere bestuursfunctie uniek is dan zijn er 10 * 9 * 8 * 7 * 6 samenstellingen. Maar de functie van 'gewoon lid' is niet uniek. Je kunt deze 3 leden op 3! manieren rangschikken. Dus [10 \* 9 \* 8 \* 7 \* 6  / 3!](https://www.wolframalpha.com/input?i=10+*+9+*+8+*+7+*+6+%2F+3%21)
- twee teams: ik denk dat dit de logica is. Zonder Steven en Achmed hebben we 8 spelers waaruit we 5 spelers kiezen voor team 1. Dus bin(8,5) = 56. Team 2 is dan ook bekend: de 3 overige spelers + Steven + Achmed. Nu zou je Steven en Achmed ook in team 1 kunnen indelen. Bij team 1 + team 2 is dat niet zo relevant maar als je de teams Ajax en 010 noemt wél. In dat geval is het antwoord dus [2 \* bin(8,5)](https://www.wolframalpha.com/input?i=2+*+bin%288%2C5%29)
- strafschoppen: in het eerste geval (A direct na C) kun je speler A+C als 1 speler zien waarna je dus 4 spelers kunt gaan rangschikken. Het antwoord is dus 4! = 24. In het tweede geval (A na C) kun je voor C op plek 1,2,3,4 de mogelijkheden voor de overige spelers nagaan. De rekensom wordt dan 4! + 3\*3! + 2\*3\*2 + 3! = 60. Maar ja het kan simpeler, er zijn voor 5 spelers 5! = 120 verschillende volgordes waarvan in de helft C voor A komt. Dus 5!/2 = 60
- Mississippi: [11! / (4! \* 4! \* 2!)](https://www.wolframalpha.com/input?i=11%21+%2F+%284%21+*+4%21+*+2%21%29) want 4x i, 4x s en 2x p
- hotel shuttle: #todo
- chocoladerepen: #todo
- 

## Hoofdstuk 2
2.1: Voor een dobbelsteen 4 of lager gooien: 4/6. Dus twee stenen 4 of lager 4*4/6*6 = 16/36. Vanzelf is het complement dan 20/36

2.2 In totaal zijn er 16 mogelijkheden nl. 4 keer kiezen tussen m/v, dus 2 \^4 = 16. Voor 2 x j + 2 x m heb je bin (4,2) = 6 mogelijkheden, dus de kans is 6/16. 3 x j + 1 x m: bin(4,3) = 4 en idem voor 3 x j, 1 x m, dus samen geeft dit kans 8/16.

2.3: er zijn in totaal 3 \^ 3 = 27 mogelijkheden. Als ieder een andere loodgieter belt dan worden loodgieter A, B en C verdeeld over 3 klanten. Dit kan op 3! = 6 manieren. Dus 6/27 = 2/9

2.4 samen 4 euro betekent simpelweg dat beide NIET de rode bal trekken. De kans om geen rode bal te trekken is 0.9. Als beide dat niet moeten doen wordt dit 0.9² = 0.81

2.5.a Het antwoord is het complement van de kans op geen enkele dubbele waarde. Dus 1 \* 5/6 \* 4/6 = 20 / 36 = 5 / 9. Het complement is 4/9.
2.5.b Wederom het complement van de kans op geen enkele dubbele waarde. Dus 37/37 \* 36/37 \* ..... 31 /37 en daar het complement van. [1 - (37! / (30! \* 37⁷))](https://www.wolframalpha.com/input?i=1+-+%2837%21+%2F+%2830%21+*+37%E2%81%B7%29%29) = 0.4534. Het boek, tweede druk, bevat een fout antwoord.

2.6 Het antwoord is het complement van de kans dat geen enkele code goed wordt geraden. Voor 1 pas is dit (9999/10000)³ (bij een domme dief....). Voor 500 pinpassen is het antwoord dus [1 - ((9999/10000)³)⁵00](https://www.wolframalpha.com/input?i=1-+%28%289999%2F10000%29%C2%B3%29%E2%81%B500). Zelf zou ik, als dief, niet twee keer dezelfde code proberen, op dezelfde pas. De kans op succes voor de dief stijgt dan behoorlijk naar 0.259. Tamelijk verrassend vind ik.

2.7 Ik weet niet zo veel van bridge maar blijkbaar geldt de aas niet als 1 maar als 13. Dus blijven er 8 (2-9) kaarten in een set van 13 over die onder de 10 zijn. Dus voor de eerste kaart geldt een kans van 32/52 dat die onder de 10 is. Voor de tweede is dit 31/51, etc. Omdat ze alle 13 onder de 9 moeten zijn wordt de kans [(31!/19!)/(52!/39!)](https://www.wolframalpha.com/input?i=%2832%21%2F19%21%29%2F%2852%21%2F39%21%29). Je kunt ook uitgaan van het totale aantal combinaties in bridge: (32 boven 13)/(52 boven 13) maar dat is feitelijk hetzelfde want de 13!-deler valt boven en onder weg.

2.8 Neem het complement van de kans dat er geen zelfde getal wordt geloot. Bij de eerste loting is dit 10000/10000 (goh!), de tweede 9999/10000, etc. Al die kansen moet je vermenigvuldigen. Dus [1 - (10000!/9800!)/10000²00](https://www.wolframalpha.com/input?i=1-%2810000%21%2F9800%21%29%2F10000%C2%B200) Ik denk dat het boek een foute afronding gebruikt.

2.9 Er zijn 4 posities waarbij er de eerste keer geen knal volgt. Van die 4 posities is er 3 die niet vooraf gaat aan een knalpatroon (de knalpatronen zijn immers aangrenzend geplaatst). Dus 3/4 = 0.75

2.10 Bij 20 keer kopmunt zijn er 2²0 verschillende uitkomsten (als je iedere worp uniek ziet). Hiervan zijn er (20 boven 10) combinaties die 10/10 kop/munt geven. Dus [bin(20, 10)/2²0](https://www.wolframalpha.com/input?i=bin%2820%2C+10%29%2F2%C2%B20)

2.11 Er zijn 6 mogelijke indelingen van de deuren (ASF, AFS, etc). Als je die uitschrijft en dan voor iedere indelingen het algoritme volgt dan zie je dat in de 2 opties waarin Pa de auto niet treft dat de dochter dan ook de sleutel niet treft en vice versa. Dus 4/6 kans op succes.

2.12 Dit kan als team A twee keer wint( kans 0.6 \* 0.6) of als A wint, B wint en A wint (0.6 \* 0.4 \* 0.6) maar hier is ook de variant BAA goed. Dus 0.6² + 0.6² \* 0.4 \* 2 = 0.36 + 0.288 = 0.648

2.13.a Het oppervlak van een vierkant is a². De munt valt geheel binnen dit vierkant als het middelpunt van de munt tenminste d afstand ligt van de rand van het vierkant. Dus het vierkant waar binnen het middelpunt moet liggen meet a-d bij a-b, dus oppervlak (a-d)² Dan is de kans dus (a-d)²/a².
2.13.b Hiervoor is echte wiskunde nodig: Het oppervlak van het gehele vierkant is 1 x 1 = 1. De vergelijking heeft 2 reele nulpunten als de abc-formule (ken je hem nog?) een positieve waarde heeft voor het gedeelte onder de wortel. Dus b² -4ac > 0, met a=1, b=B, c=C. Dit herschijven we als c = 1/4 \* b² of y = 1/4 \* x². Dit is een kromme, hangende lijn die door (0,0) en (1, 1/4) gaat. De oppervlakte ondere deze lijn is het gebied waar we 2 gezochte reele waarden vinden. Om de oppervlakte hiervan te bepalen hebben we de integraal van 1/4 \* x² nodig, dit is 1/3 \* 1/4 \* x³ = 1/12 \* x³. Voor x = b = 1 is dit 1/12. Dit moeten we delen door de gehele oppervlakte (1), dus is de uitkomst 1/12.

2.14 Als we de vrienden met witte wijn beschouwen: bij de eerste geldt de kans 2/5 en voor de tweede vriend 1/4. Vermeningvuldig deze en je krijg 1/10. De kans dat een van hen rode wijn krijgt is 3/5 \* 2/4 = 6 /20 = 3/10

2.15 Voor de eerste sok mag alles als het maar geen wit is: 4/5. Voor de tweede moet deze dan de gelijke kleur hebben: 1/4. Vermenigvuldigd: 1/5

2.16 De kans op twee keer zwart: 14/21 \* 13/20. De kans op rood en zwart (hiervan zijn er 2 combinaties): 2 \* 14/21 \* 7/20. Dit laatste is dus groter (want 2\*7 > 13).

2.17 Wat hier wordt bedoeld, denk ik: De kans dat de eerste wint is 1/10. Daarna zeg je: A is de gebeurtenis dat de eerste persoon NIET wint (9/10) en B dat de 2e persoon wel wint. Dan geldt dus dat de kans dat zowel A als B optreden : P(A en B) = P(A) \* P(B|A). P(B|A) = 1/9, immers er zijn dan nog 9 lootjes waarvan er één winnend is. Dus P(A en B) = 9/10 \* 1/9 = 1/10. Enzovoort.

2.18 Nee, natuurlijk niet zou ik haast zeggen. 4 finalisten uit 12 kandidaten trekken,  geeft 1/3 kans voor iedere kandidaat. Wat de Juinense courant fout doet is dat ze de voorwaardelijke kans vergeten voor de kansen 1/11, 1/10 en 1/9. De kans om als 2e te worden getrokken is immers de kans om getrokken te worden uit 11 kandidaten maal de kans dat je NIET als eerste wordt getrokken. Dus 1/11 \* 11/12 = 1/12. Etc.

2.19. Stel er zijn in totaal N kinderen waarvan Nb met blauwe ogen dan is de kans op 2 keer blauwe ogen N/Nb \* (N-1)/( Nb - 1) en dat is dan gelijk aan 0,5. Dit is lastig op te lossen maar inderdaad als je N = 4 en  Nb = 3 neemt dan klopt het 3/4 \* 2/3 = 1/2

2.20. De kans in de eerste beurt is 2/6. De kans dat de ander in de 2e beurt verlies is dan: 2/3 \* 2/5 = 4/15. De kans dat de eerste persoon in de tweede beurt verliest is dan: 2/3 \* 11/15 \* 2/4. Ga zo door en je vindt als antwoord 0.646.

2.21 Iedere trekking opnieuw moet je dus éé blauwe en één rode bal trekken, volgorde maakt niet uit. Bij iedere trekking maakt de eerste bal niet uit maar de tweede moet dan van een ander kleur zijn. Voor de eerste trekking is de kans dus 4/7, want van de 7 ballen zijn er 4 van een andere kleur dan de eerste. Tweede trekking 3/5 en de derde trekking 2/3. De laatste trekking is dan altijd goed of fout. Dus 4/7 \* 3/5 \* 2/3 = 8/35

2.22 Als ik hinein redeneer naar het antwoord toe krijg ik zo het juiste antwoord: voor een willekeurige Spaanse club is er 2/7 kans dat die een Spaanse tegenstander loot. (In dat geval zijn er verder geen 100% Spaanse lotingen meer mogelijk.) De kans dat die NIET het geval is is 5/7 en in dat geval is er voor het tweede Spaanse team nog 1/5 kans (1 Spaans team van de 5 overgebleven teams) op een 100% Spaanse loting: 5/7 \* 1/5 = 1/7. 2/7 + 1/7 = 3/7 kans op een Spaanse loting, dus 4/7 kans is het antwoord.

2.23 Je kunt zeggen, er zijn 11 combi's met minimaal één 6, hiervan is er één met dubbel zes. Dus 1/11. Formeel werkt het zo: De kans op 2 keer 6 (situatie B) gegeven één 6 (A) is P(A en B)/P(A). P(A en B), dus de situatie één zes én twee zessen is 1/36. P(A), dus één 6 met 2 dobbelstenen, is 11/36. Dus (1/36) / (11/36) = 1/11.

2.24 Vrij simpel dus laten we het formeel berekenen: A = aangebrand, B = op tijd. Dan P(A) = P(A|B)P(B) + P(A|!B)P(!B) = 0.8 \* 0.15 + 0.2 \* 0.5 = 0.12 + 0.1 = 0.22

2.25 Via de wet kunnen we dit stellen. A = ze staan naast elkaar. B1=de nederlander heeft één buurman m/v (e.g. aan de rand), B2= de nederlander heeft twee buurmannen m/v (e.g. staat midden in de groep). Dan geldt P(A) = P(A|B1)P(B1) + P(A|B2)P(B2) = 1/7 \* 2/8 + 2/7 \* 6/8 = 1/28 + 6/28 = 1/4 = 0,25

2.26 Misschien is het de bedoeling hier recursie te gebruiken maar ik zou dit stellen. 26 koffers waarvan 24 zonder een prijs. Dus de eerste keer is de kans op geen prijs 24/26, dan 23/25, ... en tenslotte, bij koffer 20, 4/6. Dit geeft (24!/4!) / (26!/6!) = 5 \* 6 / 26 \* 25 = 3 / (5 \* 13) = 3/65. 

2.27 Erg lastig #todo 

2.28 Als je het formeel wil doen: A= kleur is gelijk, B1 = zwart/zwart, B2=zwart/rood, B3=rood/rood. Dan is P(A) = P(A|B1)P(B1) + P(A|B2)P(B2) + P(A|B3)P(B3) = 1 \* 1/3 + 0 \* 1/3 + 1 \* 1/3 = 2/3

2.29 Hoe vaak ik het ook nareken, ik kom met geen mogelijkheid op het gegeven antwoord uit. Ik vind 295 ook een hele rare deler omdat het nergens in de buurt komt als factor van 6. Mijn antwoord zou daarom dit zijn: in de eerste rond is er 8/36 kans op directe winst (11 en 7 kun je op 2 + 6 manier gooien) en 4/36 kans op direct verlies (1 + 2 + 1). Derhalve 24/36 kans op een tweede ronde. Daarin geeft een 7 6/36 kans op verlies en 2,3,11,12 een kans van 6/36 kans op een replay. Dus kans op winst 24/36 in de tweede ronde. Omdat in volgende rondes dit wordt herhaald zal uiteindelijk de verhoudind winst/verlies 24:6 worden, dus winstkans van 24/(24+6). In totaal, inclusief eerste ronde geeft dit 8/36 + 24/36 \* 24/30 = 68/90 = 34/45

2.30 Via deze tabel


|     |  Ballen  | Afleiding | Kans |Hoogste kans|
| --- | --- | ---| ---|---|
||Rood-Rood| 3/5 \* 2/4| 0,3|*|	
|Schaal A|WW|2/5 \* 1/4|0,1||
||RW|12/20|0,6|*|
||||||
||RR|4/7 \* 3/6|0,29||
|Schaal B|WW|3/7 \* 2/6|0,14|*|
||RW|24/42|0,57||

Hieruit volgt dat bij Wit/Wit de kans op schaal B het grootst is (0,14 vs 0,1), etc. Om de kans dan te berekenen neem je winst kansen (0,3 + 0,6 + 0,14) en dat deel je door twee (want alle kansen tesamen zijn hier 2, of eigenlijk omdat beide schalen 50% kans hebben gekozen te worden)

2.31 Via stug doorrekenen kom ik zo een beetje in de buurt: kans op eerste worp >=55 is 0,55 met verwachte waarde van 77,5. Indien eerste worp is <55 is de verwachte waarde 27,5. Daarmee is de kans op een geldige tweede worp ongeveer 3/4 (e.g. 5 t/m 70) en de verwachte waarde wordt dan 27,5 + (70+5)/2 = 60.

Voor de tweede speler geldt dan, in het eerste geval (waarde 77,5), een kans van 1/4 op winst per worp. Dus 1/4 + 3/4 \* 1/4. Voor speler 1 wordt dit 1 - (1/4 + 3/16). In het tweede geval (waarde 60) 2/5 kans op winst per worp, 2/5 + 3/5 \* 2/5. Speler 1: 1 - (2/5 + 6/25)

Rest ons nog alle deelkansen te vermenigvuldigen en op te tellen (hou rekening met de voorwaardelijke kans op worp 2!): 

0,55 \* 9/16 + 0,45 \* 3/4 \* 9/25 = [0.4308](https://www.wolframalpha.com/input?i=0.55+*+9%2F16+%2B+0.45+*3%2F4*+9%2F25)

Waar zit de fout?

2.32 H = het regent morgen, E = regen voorspeld voor morgen. Prior odds = 1/9, bayes factor: P(E|H)/P(E|!H) = 85%/25% = 17/5. Posterior odds dus 1/9 * 17/5 = 17/45. Dus P(H|E) = 17/45/(1+17/45) = 17/62

2.33 H = er is olie, E = positieve test op olie, prior odds: 40%/60%=2/3, bayes factor: 90/15 = 6, posterior odds: 2/3 * 6 = 4. P = 4/(1+4) = 0,8

2.34 De vissenkom: H = er zit een piranha in, E = er is een piranha opgevist,  prior 0.5/0.5 = 1, factor P(E|H)/P(E|!H) = 1 / 0,5 = 2, post: 1 * 2 = 2, P = 2/(1+2)  = 2/3

Het kaartspel: H = zelfde kleur, E = kaart is rood. prior: 2/1, factor: 1, post: 2, kans = 2/(1+2) = 2/3

2.35 H = uitspraak is waar, E = bewoner zegt dat de uitspraak waar is. prior: 1/2, factor (deze is onafhankelijk van H): E | H / E | !H = 1/3 / 2/3 = 1/2, post 1/4, kans = 1/4 / ( 1 + 1/4) = 1/5

2.36 H = X is de dader, E = dader heeft Bloedgroep A, prior: 1/1, factor E | H / E | !H = kans op A indien X de dader is / kans A indien Y de dader is = 10% / 100% = 1/10, post = 1/10, kans = 1/10 / (1+1/10) = 1/11

2.37 H = white cabs is doorgereden, E = white is gezien bij aanrijding, prior: 15% / 85% = 3/17, factor: E|H / E|!H = wit gezien indien wit dader / wit gezien indien geel de dader = 80% / 20% = 4, post: 12/17. kans = 12/17 / (1 + 12/17) = 12 / (17 + 12) = 12/29

2.38 H = persoon is ziek, E = positieve test, prior: 0,1%/99,9% = 1/999, factor:: 99%/1% = 99, post: 99/999, kans = 99/(999 + 99) = 9.02%. Na een tweede test  wordt de factor 99², dus post: 99²/999, kans: 99²/(999 + 99²) = 90,8%

2.39 H = gekozen doos bevat het 100 euro biljet, E = we trekken 2 euro biljetten. prior: 0,5/0,5 = 1, E | H: we trekken 2 euro biljetten gegeven doos met 100 euro: 2/3 * 1/2 = 1/3 kans, E | !H : we trekken 2 euro biljetten gegeven doos met 5 euro: 9/10 * 8/9 = 4/5. dus factor: 1/3 / 4/5 = 5/12, post = 1 * 5/12 = 5/12. Dus kans op doos met 100 euro is 5 /17. En kans dat de 100 euro in de andere doos zit dus 12/17. Echter als we dan wisselen zitten er ook nog 2 euro biljetten in die doos. Dus de kans om het 100 euro biljet uit deze doos te trekken is dan 1/3 * 12/17 = 4/17. Terwijl die euro biljetten in het andere geval al uit de doos zijn, dus daar blijft de kans op 100 euro 5/17. Niet wisselen dus.

2.40 die is niet zo moeilijk, gewoon per uitkomst (2,3,4,....) de kans berekenen.

2.41. Eerst de kans op aantal keer kop voor 0,1,2 is 1/4,1/2,1/4. Dus is de kans op uitkomst 0 1/4. Voor de andere uitkomst moet je steeds de kans splitsen tussen gooien met 1 dobbelsteen en met 2 dobbelstenen. Voor 1 dobbelsteen is de kans op 1 t/m 6 steeds 1/6 en dat dan keer 1/2 vanwege de eerder genoemde kans. Voor twee dobbelstenen staat de formule gegeven in voorbeeld 2.13 (k-1)/36 en dat dan weer keer 1/4 vanwege kop/munt kans. kansen optellen en klaar.

2.42 De opgaven over verwachtingwaarde en variantie zijn vooral meer van het zelfde en stug doorrekenen. Er lijken mij geen quick-wins te behalen. Ik zal er daarom slechts enkele van uitwerken. Happy hour: [2\*0.16  + 3\*0.4 + 4\*0.25 + 4.5\*0.08 + 5.5\*0.1 + 7 \* 0.01](https://www.wolframalpha.com/input?i=2*0.16++%2B+3*0.4+%2B+4*0.25+%2B+4.5*0.08+%2B+5.5+*0.1+%2B+7+*+0.01) = 3.5, [Sqrt[2²\*0.16  + 3²\*0.4 + 4²\*0.25 + 4.5²\*0.08 + 5.5² \*0.1 + 7² \* 0.01 - 3.5²]](https://www.wolframalpha.com/input?i2d=true&i=Sqrt%5B2%C2%B2*0.16++%2B+3%C2%B2*0.4+%2B+4%C2%B2*0.25+%2B+4.5%C2%B2*0.08+%2B+5.5%C2%B2+*0.1+%2B+7%C2%B2+*+0.01+-+3.5%C2%B2%5D) = 1.06. Munten en dobbelstenen precies zo doorrekenen.

2.43 E(X): iedere college heeft 1/4 kans om gekozen te worden. Dus E(X) = (15 + 20 + 75 + 125)/4 = 235/4 =  58.75. E(Y): de kans voor een college om gekozen te worden is nu afhankelijk van het aantal leerlingen in dat college, dus 15/ (15 + 20 + 75 + 125) voor het eerste college; met een waarde van 15, etc. Dus is E(Y) = (15² + 20² + 75² + 125²)/235 = 93.09

2.44 de sokken: de eerste sok is altijd prijs, vanaf de tweede sok keren de kansen. De kans dat de tweede sok gelijk is aan de eerste is 1/9, de kans dat we bij de derde sok een paar hebben is 8/9 \* 2/8 (eerste kans kans op niet 2 en dan 2 sokken uit 8 sokken), de kans op paar bij 4 sokken: 8/9 \* 7/9 \* 3/7 (kans op niet 2 maal kans op niet 3 maal 3 sokken uit 7), en ga zo door. Reken dit door en vind het juuiste antwoord,

2.45 de kippenschuur, deze is nog leuk want logisch redeneren: 50% van de kippen wordt zeker één gepikt, daarvan wordt 50% twee keer gepikt, gemiddeld genomen, Dus kun je verwachten dat 25% niet wordt gepikt.

2.46 #TBD

2.47 Bernouille: E(X) = 1 \* p + 0 * (1-p) = p, E(X²) = 1² \* p + 0² \* (1-p) = p. Dus de afwijking is: Sqrt(p - p²) = Sqrt(p(1-p))

2.48 - 2.53 #TBD

2.54 #TBD

2.55 Verwachte waarde: gemiddeld zal één dobbelsteen met een cijfer boven landen; omdat de kans voor 1,2,3,4,5,6 hierbij gelijk zijn zal de verwachte waarde (1+2+3+4+5+6)/6 = 3.5 zijn. De berekening van de afwijking is veel lastiger, meer rekenen. De mogelijke waarden varieren van 0 tot 21 en door het kwadraat is dit niet meer lineair. Je moet dus voor iedere uitkomst de waarde maal kans berekenen minus de verwachte waarde en dat dan kwadrateren, someren, en de wortel ervan nemen. Succes!

2.56 #TBD

2.57-2.76 #TBD

3.1 Neem in de binominaal vergelijking:
p = 0.5, n = 6, k = 3, [bin(6, 3) * .5^6](https://www.wolframalpha.com/input?i2d=true&i=bin%5C%2840%296%5C%2844%29+3%5C%2841%29+*+Power%5B.5%2C6%5D)) = 0.3125 (of 6*5*4/(2*3*64) = 5/16) . Dit is de kans op 2 euro winst. Ergo, de kans op 1 euro verlies is 11/16. Netto verlies je dus met 5\*2 tegen 11.

3.2 Dit is een logische uitkomst als je uitgaat van de binominaal vergelijking met meerdere uitkomsten. Bij 2 uitkomsten is de kans p2 = (1-p1) en k2 = (1-k1)! en daarmee volgt de genoemde vergelijking uit de binominaal vergelijking. Bij 3 uitkomsten heb je 3 kansen: p1, p2, p3 die je dan via machtverhevven met elkaar moet vermenigvuldigen. En het n-boven-k wordt dan n!/(k1!\*k2!\*k3!).

3.3 n = 157, p = 0.05. Voor de berekening van precies 6 no-showers neem je de binominaal vergelijking met k = 6: [bin(157, 6) * Power[.08,6]* Power[0.92,151]](https://www.wolframalpha.com/input?i2d=true&i=bin%5C%2840%29157%5C%2844%29+6%5C%2841%29+*+Power%5B.08%2C6%5D*+Power%5B0.92%2C151%5D) = 0.0168. Close but no sigar. We moeten namelijk ook de kansen op k = 5, 4, etc meenemen, die zijn niet allemaal te negeren. En dus: [voor k = 6 ...3](https://www.wolframalpha.com/input?i2d=true&i=bin%5C%2840%29157%5C%2844%29+6%5C%2841%29+*+Power%5B.08%2C6%5D*+Power%5B0.92%2C151%5D+%2B+bin%5C%2840%29157%5C%2844%29+5%5C%2841%29+*+Power%5B.08%2C5%5D*+Power%5B0.92%2C152%5D+%2B+bin%5C%2840%29157%5C%2844%29+4%5C%2841%29+*+Power%5B.08%2C4%5D*+Power%5B0.92%2C153%5D+%2B+bin%5C%2840%29157%5C%2844%29+3%5C%2841%29+*+Power%5B.08%2C3%5D*+Power%5B0.92%2C154%5D) = 0.282

3.4 p = 4/25, n = 5 en neem dan de som van k = 3,4,5, [bin(5, 3) * Power[.16,3]* Power[0.84,2] + bin(5, 4) * Power[.16,4]* Power[0.84,1] + bin(5, 5) * Power[.16,5]* Power[0.84,0]](https://www.wolframalpha.com/input?i2d=true&i=bin%5C%2840%295%5C%2844%29+3%5C%2841%29+*+Power%5B.16%2C3%5D*+Power%5B0.84%2C2%5D+%2B+bin%5C%2840%295%5C%2844%29+4%5C%2841%29+*+Power%5B.16%2C4%5D*+Power%5B0.84%2C1%5D+%2B+bin%5C%2840%295%5C%2844%29+5%5C%2841%29+*+Power%5B.16%2C5%5D*+Power%5B0.84%2C0%5D)

3.5 n = het aantal detectoren, we zoeken dus n-5. k = het aantal falende detectoren, het systeem faalt dus als geheel als k = n - 4. p = 0.05 en de uitkomst van de binominaal vergelijking moet > 0.001 zijn. En dan maar proberen voor meerdere waarden voor n. Nemen we 7 dan is de [faalkans 0.35%](https://www.wolframalpha.com/input?i2d=true&i=bin%5C%2840%296%5C%2844%29+2%5C%2841%29+*+Power%5B.05%2C2%5D*+%5C%2840%29Power%5B.95%2C4%5D](https://www.wolframalpha.com/input?i2d=true&i=bin%5C%2840%297%5C%2844%29+3%5C%2841%29+*+Power%5B.05%2C3%5D*Power%5B.95%2C4%5D)), nemen we 8 dan wordt dit [0.036%](https://www.wolframalpha.com/input?i2d=true&i=bin%5C%2840%298%5C%2844%29+4%5C%2841%29+*+Power%5B.05%2C4%5D*Power%5B.95%2C4%5D). Bij n=8 is het antwoord dus 3.

3.6 Er zijn 3 mogelijkheden: team A wint 2 keer, wint 1 keer of wint 0 keer. Team A moet altijd de laatste wedstrijd winnen. En dan volgen de kansen:

0.6² \* 0.4² \* 0.6 \* bin(4,2) = [0.2074]([https://www.wolframalpha.com/input?i2d=true&i=0.6%C2%B2+*+0.4%C2%B2+*+0.4+*+bin%5C%2840%294%5C%2844%292%5C%2841%29](https://www.wolframalpha.com/input?i2d=true&i=0.6%C2%B2+*+Power%5B0.4%2C2%5D+*+0.6+*+bin%5C%2840%294%5C%2844%292%5C%2841%29))
0.6² \* 0.4 \* 0.6 \* bin(3,2) = [0.2592]([https://www.wolframalpha.com/input?i2d=true&i=0.6+*+0.4%C2%B2+*+0.4+*+bin%5C%2840%293%5C%2844%29+2%5C%2841%29](https://www.wolframalpha.com/input?i2d=true&i=0.6%C2%B2+*+0.4+*+0.6+*+bin%5C%2840%293%5C%2844%292%5C%2841%29))
0.6² \* 0.6 = [0.216]([https://www.wolframalpha.com/input?i2d=true&i=0.4%C2%B2+*+0.4](https://www.wolframalpha.com/input?i2d=true&i=0.6%C2%B2+*+0.6))
Opgeteld: 0.6826

3.7 p=0.5, n=10, r=?. Het startkapitaal is meer dan gehalveerd als: power(0.5, n-r) \* power(1.7, r) < 0.5. Met wat uitproberen volgt dan een r = 5. Je hebt namelijk een r = 6 nodig om winst te maken . Neem die r=1..5 en vul die in in de binominaal vergelijking en sommeer:

[power(0.5, 10) * (bin (10,5) + bin(10,4) + bin(10,3) + bin(10,2) + bin(10,1))](https://www.wolframalpha.com/input?i2d=true&i=power%5C%2840%290.5%5C%2844%29+10%5C%2841%29+*+%5C%2840%29bin+%5C%2840%2910%5C%2844%295%5C%2841%29+%2B+bin%5C%2840%2910%5C%2844%294%5C%2841%29+%2B+bin%5C%2840%2910%5C%2844%293%5C%2841%29+%2B+bin%5C%2840%2910%5C%2844%292%5C%2841%29+%2B+bin%5C%2840%2910%5C%2844%291%5C%2841%29%5C%2841%29) = 0.6221. Ik heb wel een klein afrondingsverschil?

3.8 Als ik heb goed begrijp worden de zener kaarten terug gelegd dus kunnen we de binominaal vergelijking gebruiken. p = 0.2, n=250, r >= 82. Nemen we alleen voor het gemak even r=82:

[Power[0.2,82] * Power[0.8,\(40)250-82\(41)] * bin(250, 82)](https://www.wolframalpha.com/input?i2d=true&i=Power%5B0.2%2C82%5D+*+Power%5B0.8%2C%5C%2840%29250-82%5C%2841%29%5D+*+bin%5C%2840%29250%5C%2844%29+82%5C%2841%29) = 6.82 e-7.

Als we door rekenen met r = 83, 84, ... en sommeren komen we goed in de buurt.

3.9 n = 180, r >= 2. Maar wat is p? De kans dat een renner tijdens de tour jarig is 23/365. De kans dat een tweede renner op dezelfde dag jarig is 179/365? Maar dan kom ik niet op het antwoord uit.

3.10 Via de hypergeomatrische verdeling (want er wordt niet teruggelegd). R = 20, R=60, n = 10, r >= 5. Voor 5 geeft dit [0.0514](https://www.wolframalpha.com/input?i2d=true&i=bin%5C%2840%2920%5C%2844%295%5C%2841%29+*+bin%5C%2840%2960%5C%2844%295%5C%2841%29+Divide%5B1%2Cbin%5C%2840%2980%5C%2844%2910%5C%2841%29%5D). Als je dit doorrekend met r = 6, 7 en sommeert volgt het antwoord.

3.11 R=10, W=5, n=8, r=5,6,7,8. Voor r=5: [(56/143)](https://www.wolframalpha.com/input?i2d=true&i=bin%5C%2840%2910%5C%2844%295%5C%2841%29+*+bin%5C%2840%295%5C%2844%298-5%5C%2841%29+*+Divide%5B+1%2Cbin%5C%2840%2915%5C%2844%298%5C%2841%29%5D). Doorrekenen met r=6,7,8 geeft exact het juiste antwoord.

3.12 R=3, W=48, n=12, r=1,2,3. Voor r=1: [0.4270](https://www.wolframalpha.com/input?i2d=true&i=bin%5C%2840%2948%5C%2844%29+12-1%5C%2841%29+*+bin%5C%2840%293%5C%2844%291%5C%2841%29+*++Divide%5B+1%2Cbin%5C%2840%2951%5C%2844%2912%5C%2841%29%5D). Ook hier weer doorrekeken met r=2,3 en het juiste antwoord volgt.

3.13 Aantal combinaties bij 6/42 is (42 boven 6). Slechts een combi is goed. Dus de kans op winst is p = 1/(42 boven 6) = 1.906e-7
n = 5e6
ʎ = 1.906e-7 * 5e6 

Dus de kans dat niemand (k = 0) de jackpot heeft is: e ^ -1ʎ = [0.3855](https://www.wolframalpha.com/input?i=pow%28e%2C-1.906e-7*5e6%29).

Daarmee, de kans dat 1 of meer mensen winnen is 1 - 0.3885 = 0.6145

3.14 PI-day! Analoog aan oplossing van voorbeeld 3.6:

aantal trekkingen in 4 jaar * 5 rijtjes = 4 *2 * 52 * 5 = 2080

aantal koppels in deze trekkingen = (2080 boven 2) = 2.16e6

kans op jackpot, zie 3,13, is 1/(42 boven 6) = 1.906e-7
dus de kans dat een  deelnemer twee keer de jackpot wint is 1.906e-7 power 2 = 3.634e-14

als slechts één iemand mee doet aan de trekking is ʎ = 2.16e6 * 3.634e-14

bij 5e7 deelnemers is ʎ dan 5e7 * 2.16e6 * * 3.634e-14 = 3.929

de kans dat niemand 2 keer of meer de jackpot heeft is daarmee e ^ -3.929.

de kans dat iemand dit wél heeft is dus [1 - (e ^ -3.929) = 0.9803](https://www.wolframalpha.com/input?i=1+-+exp%28-1+*+5e7+*+2.16e6+*+3.634e-14%29).

3.15. verwachtte waarde van haaienaanvallen, ʎ =  8

Indien 50% hoger dan is k = 12, 13, 14, ... en die kansen optellen

poisson voor k = 12: [(e ^ -8) * (8 ^ 12) / 12! = 0.048](https://www.wolframalpha.com/input?i=+exp%28-8%29+*+pow%288%2C12%29+%2F+12%21)

etc voor k = 13 (p = 0.030), 14 (p = 0.017), ...

vanaf k = 19 (p = 4e-4) wordt het niet meer relevant

deze kansen opgeteld is dit 0,112

3.16
In het boek wordt 327 genoemd, dat had 324 moeten zijn. En dan klopt het:
z = [(379 - 324) / wortel(324) = 55 / 18 = 3.1](https://www.wolframalpha.com/input?i=%28379+-+324%29+%2F+sqrt%28324%29)

3.17
de basis formule voor jarig op dezelfde dag is gegeven bij voorbeeld 3.6. Als we niet dezelfde dag vereisen maar een dag eerder of later ook goedkeuren dan is de kans op succes dus keer 3. En dat verklaart de 3 in de gegeven formule.

3.18 #TBD 

3.19 15 dagen met een std afwijking van 10 betekent dat we zoeken naar de kans P(z > 15/10): [p(z > 1.5) en die is 0.0668](https://www.wolframalpha.com/input?i=p%28z+%3E+1.5%29)

3.20 We zoeken s = μ + Z95% * σ. Met μ = 5.2 en σ = 0.85. Het percentiel voor 95% wordt gegeven in het boek: 1.6449. Dus antwoord: [6.27](https://www.wolframalpha.com/input?i=5.2+%2B+1.6449+*+0.65)

3.21 Uit de tekst volgt dat een afwijking van 0.35 mm teveel is. Bij een std afwijking van 0.1 mm geeft dit een z > 3.5 óf een z < -3.5 (want de afwijking geldt aan boven en onderkant). Ik heb moeite om de juiste notatie in WolphramAlpha hiervoor te vinden maar via [deze](https://www.wolframalpha.com/input?i=standard+deviation%2C+z+%3D+3.5) vind je juiste antwoord onder |z| > 3.5.

3.22 z = (21500 - 15000)/2000 = 65/20 = 3.5

3.23 De afwijking van het gemiddels is 249. Bij de normale verdeling geldt σ = wortel(np(1-p)). Omdat p = 0.5 wordt dit 1/2 \* sqrt(n) = 50 bij 10000 worpen. Dit geeft een z = 249 / 10 = 4.98

3.24 Dan geldt 100 + Z5% \* σ > 125, dus σ = 25/1.6449 = 15.1

3.25 Omdat de normale verdeling symmetrisch is is met deze verdeling μ = (80 + 120)/2 = 100. En σ \* Z10% = 20. Het 10% percentiel (zie een tabel op internet) is 1.282. Dus σ = 20 / 1.282 = 15.6.

3.26 Een soortgelijke vergelijking is gegeven op pagina 80. En dan zijn er drie verschillen. In de opgave wordt de absolute waarde van X - μ genomen. Omdat de het 5% percentiel even groot is als het groter dan 95% percentiel (vanwege de symmetrie in de grafiek) verklaard dit de factor 2 in de opgave. Dan, X - μ < kσ, kan je ook schijven als X < kσ + μ en dan is die rechterhelft gelijk te stellen aan x van pagina 80. Vul je dit dan in in deze vergelijking dan blijft over Φ(k), want de μ en σ vallen dan weg. Het derde verschil is de >= vs de <. En dat verklaart de 1 - Φ(k). Immers de kans dat X < x is het complement van X >= x.

3.27 Maak niet, zo als ik, de fout om de afwijking te vermenigvuldigen met n. Dat mag niet bij de afwijking. Bij de verwachte waarde mag dit wel, 20000 deelnemers, 150 euro geeft een verwachte waarde van 3e6. We zoeken dus de kans op een afwijking van 3e5 (3.3e6 - 3e6). Voor de afwijking moeten we dan 750 \* sqrt(n)  (zie par 2.7) met n = 20000 = 106006. Dit geeft een z van 300000 / 106006 = 2.83. Zoek dit op in een tabel met de standard normale verdeling (engelse wikipedia) en je vind 0.0023 (voor z > 2.83)!.

3.28 Ik laat de binominaal berekeing even liggen , te veel werk. Voorde normale verdeling: Bij 1000 rondes moet je als speler 500 keer winnen om winst te maken (eigenlijk 501 maar dan komen we niet op het gegeven antwoord uit). Het verwachte aantal winst rondes is np = 1000 \* 18/37 = 486.5 met een afwijking van √(1000 \* 18/37 * 19/37) = 15.8. Voor winst zijn nog 14 extra winst rondes nodig, dus z \*  15.8 >= 14, z > 0.886. Dit geeft volgens de tabellen een kans van 0.1867. Zie https://statcalc.net/standard-normal-table/

Voor 10000 rondes wordt np = 4865, we hebben nog 135 winst rondes nodig, met een afwijking van √10 \* 15.6 = 49.3. Dit geeft een z van 2.74, p = 0.0031, ik weet niet waar de afronding precies fout gaat.

3.29 We moeten eerst het aantal benodigde winstrondes berekenen voordat we de normale verdeling kunnen gebruiken. Stel r = het aantal keer winst voor de speler dan is de winst/verlies voor het casino: 2500 \* 10 - 5 \*(2500 - r) - 20 \* r. Bij een max verlies van -6500 volgt r = 1267 of wel het casino mag max 1233 keer verliezen. De verwachting is np = 2500 \* 19/35 = 1284 keer met een afwijking van √(2500 \* 18/37 \* 18/37) = 25. 1284 - 1233 = 51 geeft een z = 51 / 25 = 2.04, p = 0.9793. Ook ergens een afronding mis.

3.30 Belangrijkste hier is te realiseren dat om 12 uur het aantal kort parkeerder de helft is van het aantal langparkeerders, gezien de parkeerduur. En dan volgt het antwoord, ook gezien de 2 eigenschappen van de poisson processen genoemd in dit hoofdstuk.

3.31. Dit is hard rekenen en als je daar zin in hebt dan: er zijn 12 datapunten, waarbij de laatste is geschat want 11 t/m 14 moet je samenvoegen zodat ze op hoger dan 5 uitkomen. Daarmee volgt dat er 10 (12 - 1 - 1) vrijheidsgraden zijn, dus chi-kwadraat 10. De verwachte waarde is 2608/15 = 173.8 en daarmee kun je d berekenen (de som van de kwadraten van de verschillen delen door de verwachte waarde) en ik neem aan dat dat op 12.961 uitkomt.

3.32 Volgens mij moet je weer de jaren met 4 doden samen nemen met de 3 doden, want 2 jaren is minder dan 5. Daarmee is hebben we 2 vrijheidsgraden (4 - 1 -1). Verwachte waarde is 196/136 = 1.44 doden. Maak de rekensom van de kwadraten en je krijg, denk ik, 1.952. Succes.

Hfdstuk 5
De opgaven over de Monta Carlo simulaties zal ik niet behandelen.


























#kansrekening






- 

