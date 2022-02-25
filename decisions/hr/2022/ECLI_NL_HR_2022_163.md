---
ecli: "ECLI:NL:HR:2022:163"
court: "Hoge Raad"
court_code: "HR"
docket: "20/01111"
decided: "2022-02-25"
published: "2022-02-10"
type: "uitspraak"
procedure: "Cassatie"
subject: "Civiel recht"
source_url: "https://uitspraken.rechtspraak.nl/details?id=ECLI:NL:HR:2022:163"
published_in: ["Rechtspraak.nl", "NJB 2022/539", "RvdW 2022/263", "BIE 2022/5", "AA20220796 met annotatie van Engelen van Th.C.J.A. Dick"]
relations: [["Formele relatie", "Conclusie: ECLI:NL:PHR:2021:847, Contrair"], ["Formele relatie", "In cassatie op : ECLI:NL:GHDHA:2019:3433, Bekrachtiging/bevestiging"]]
---

# ECLI:NL:HR:2022:163 Hoge Raad , 25-02-2022 / 20/01111

## Inhoudsindicatie

Intellectuele eigendomsrecht; octrooirecht. Octrooi op gebied van mobiele telecommunicatie. Octrooi nietig wegens gebrek aan inventiviteit? Problem solution approach (PSA).

## Uitspraak

HOGE RAAD DER NEDERLANDEN

CIVIELE KAMER

Nummer	20/01111

Datum   	25 februari 2022

ARREST

In de zaak van

KONINKLIJKE PHILIPS N.V.,gevestigd te Eindhoven,

EISERES tot cassatie,

hierna: Philips,

advocaten: W.A. Hoyng en F.W.E. Eijsvogels,

tegen

WIKO SAS,gevestigd te Marseille, Frankrijk,

VERWEERSTER in cassatie,

hierna: Wiko,

advocaat: H.J. Pot.

1.	Procesverloop

Voor het verloop van het geding in feitelijke instanties verwijst de Hoge Raad naar:

het vonnis in de zaak C/09/509477/HA ZA 16-472 van de rechtbank Den Haag van 27 september 2017;

het arrest in de zaak 200.231.812/01 van het gerechtshof Den Haag van 24 december 2019.

Philips heeft tegen het arrest van het hof beroep in cassatie ingesteld.

Wiko heeft een verweerschrift tot verwerping ingediend.

De zaak is voor Philips mondeling toegelicht door haar advocaten.

De zaak is voor Wiko mondeling en schriftelijk toegelicht door haar advocaat en mede door     R. Broekstra.

De conclusie van de Advocaat-Generaal G.R.B. van Peursem strekt tot vernietiging en verwijzing.

De advocaten van partijen hebben schriftelijk op die conclusie gereageerd.

2
Uitgangspunten en feiten

2.1

In cassatie kan worden uitgegaan van de feiten en omstandigheden vermeld in de conclusie van de Advocaat-Generaal onder 1.1-1.28. Deze komen, kort samengevat, op het volgende neer.

(i) Philips is houdster van Europees octrooi EP 1 685 659 (hierna: EP 659 of het octrooi), dat op 3 oktober 2007 is verleend voor ‘a radiocommunication system, method of operating a communication system, and a mobile station’ op basis van een internationale aanvrage van 9 november 2004 (gepubliceerd als WO 2005/048483). Hierbij is prioriteit ingeroepen van de Britse octrooiaanvrage GB 0326365 van              12 november 2003.

Stand van de techniek

(ii) Draadloze communicatiesystemen bevatten basisstations die draadloze verbindingen realiseren met mobiele stations. Het basisstation verbindt het mobiele station binnen zijn bereik met een achterliggend netwerk, bijvoorbeeld het vaste telefoonnet of het internet. Communicatie van het basisstation naar het mobiele station wordt aangeduid als communicatie in de downlink-richting/neergaande richting. Communicatie van het mobiele station naar het basisstation wordt aangeduid als communicatie in de uplink-richting/opgaande richting. De draadloze communicatie vindt plaats door middel van radiosignalen.

(iii) Tot de stand van de techniek behoren de UMTS- en CDMA-standaarden. De UMTS-standaard bestaat uit verschillende technische specificaties, waaronder TS 25.211. In UMTS wordt gebruikgemaakt van de CDMA-techniek. In CDMA wordt voor de transmissies van en naar de verschillende mobiele stations gebruikgemaakt van dezelfde frequenties en dezelfde timeslots, en worden de kanalen van elkaar onderscheiden door gebruik te maken van verschillende codes.

(iv) De kanaalcode binnen CDMA wordt ook wel spreidingscode genoemd. Met de spreidingsfactor (hierna ook: SF) wordt aangegeven over hoeveel chips het verzenden van één (uit 2 bits bestaand) symbool wordt uitgesmeerd. Om binnen een CDMA-communicatiesysteem de verschillende codes te kunnen creëren waarmee tegelijkertijd op de verschillende kanalen wordt uitgezonden, wordt gebruikgemaakt van een boomstructuur. De spreidingsfactor is daardoor altijd een macht van 2 (dus 4, 8, 16, 32, 64, 128, 256, 512, 1024 etc.).

(v) In UMTS staat het aantal chips per slot vast, dat is 2.560. Dat betekent dat over een kanaal met spreidingsfactor 64 per slot (2.560 : 64 =) 40 symbolen kunnen worden uitgezonden. Chips worden in UMTS altijd met een vaste snelheid van 3,84 miljoen chips per seconde verzonden. Dit betekent dat, wanneer wordt gekozen voor een hogere spreidingsfactor (waardoor het versturen van een symbool meer chips vergt) het uitzenden van één symbool meer tijd kost (omdat er dan meer chips moeten worden verzonden). Bij verdubbeling van de spreidingsfactor (dat is: de verdubbeling van het aantal chips dat voor een symbool is benodigd) wordt de data-snelheid (het aantal symbolen per seconde) dus gehalveerd.

(vi) In zowel de uplink- als de downlink-richting worden in het UMTS-systeem meerdere soorten gegevens verstuurd, waaronder gebruikersgegevens en besturingsgegevens. De gebruikersgegevens en besturingsgegevens kunnen synchroon worden uitgezonden over de verschillende daarvoor bestemde kanalen: besturingsgegevens over besturingskanalen (‘control channels’, ook weergegeven als CCH) en gebruikersgegevens via gegevenskanalen (‘data channels’, ook weergegeven als DCH).

(vii) Vermogensbesturing heeft betrekking op het regelen van het vermogen waarmee radiosignalen, zowel in de uplink- als de downlink-richting, worden uitgezonden in het UMTS-systeem. De signalen moeten niet te zwak en niet te sterk zijn. In dat kader wordt de signaal/interferentieverhouding, oftewel ‘signal to interference ratio’ (SIR) gemeten. Op de prioriteitsdatum werd daartoe gebruikgemaakt van zogenoemde pilootsignalen, TPC-commando’s en (ten behoeve van de datasnelheid van gebruikersgegevens:) TFCI-bits.

(viii) In Release 99 van TS 25.211 is het ‘Downlink Dedicated Physical Channel’ (DPCH) beschreven. Dit kanaal bestaat uit een ‘Dedicated Physical Control Channel’ (DPCCH), dat control information draagt, en het ‘Dedicated Physical Data Channel’ (DPDCH), dat user information (‘data’) vervoert.

(ix) In een voorstel van Nortel Networks (hierna: Nortel) over ‘An additional slot structure to support low bit rate services as a result of the harmonisation’ (hierna: Nortel 1) wordt – in relatie tot de implementatie van een bepaald type spraakverkeer, de EVRC – een voorstel gedaan voor de inrichting van het DPCH volgens TS 25.211. In hoofdstuk 4 worden voor het DPCCH-deel vier slotstructuren als optie genoemd:

4
Slot and frame structure for the support of EVRC in UTRA FDD

(…)

Looking at Table 9 in 25.211 for the Downlink DPDCH and DPCCH fields, there are four possible options for combinations of TFCI, TPC and Pilot bits that might be contemplated for SF=256:

1. N_tfci = 0, N_tpc = 2, N_pilot = 0

=> DPCCH = 30 bits/frame, DPDCH = 270 bits/frame

2. N_tfci = 0, N_tpc = 2, N_pilot = 2

=> DPCCH = 60 bits/frame, DPDCH = 240 bits/frame

3. N_tfci = 2, N_tpc = 2, N_pilot = 0

=> DPCCH = 60 bits/frame, DPDCH = 240 bits/frame

4. N_tfci = 2, N_tpc = 2, N_pilot = 2

=> DPCCH = 90 bits/frame, DPDCH = 210 bits/frame

The last of these options is really not acceptable for an EVRC voice service as the puncturing rate is 1 - 210/293 * 0.28 or 28%. Option 1 would be the most ideal if the objective is to minimize the level of puncturing, however, if one wants to estimate the SIR for power control from the DPCCH, the estimate will not be that accurate with only one symbol (the TPC symbol). (…)”

(x) Bij UMTS-Release 5 uit 2002 is het HSPA (‘High Speed Packet Access’) protocol geïntroduceerd.

(xi) In bijdragen van Nortel ten behoeve van werkgroepbijeenkomsten in mei en oktober 2003 (hierna: de Nortel 2-voorstellen, of Nortel 2) is voorgesteld dat het downlink DPCH wordt geconfigureerd als een fractioneel DPCH (kortweg: F-DPCH), fractioneel omdat het werd gedeeld door meerdere mobiele stations die dezelfde kanaalcode gebruiken op verschillende fracties van een tijdslot. In deze bijdragen is hierover onder meer vermeld:

“* 	Pilot bits are needed to allow the Fractional dedicated physical channel  to be power controlled and allow DL synchronisation to be maintained by each UE.”

“The fractional dedicated channel can thus be seen as a shared power control channel i.e. one code is shared between different users to carry power control and pilot bits”.

en:

“The number of UE which can be multiplexed on a single code also depends on the desired number of TPC and pilot bits. In the following, we have considered existing number of pilot bits from 25.211)

Het octrooi

(xii) De conclusies 1-3 van EP 659 luiden in de niet-bestreden Nederlandse vertaling als volgt:

“1. 	Mobiel station (200) voor gebruik in een communicatiesysteem met een basisstation (100) waarbij het mobiele station (200) het volgende omvat:

ontvangmiddelen (220) voor het ontvangen van een eerste neergaand signaal van het basisstation (100)

meetmiddelen (250) voor het meten van een parameter van het ontvangen eerste neergaande signaal,

vermogensbesturingsmiddelen (230) voor het opwekken van eerste vermogensbesturingscommando’s in reactie op de gemeten parameter en zendmiddelen (240) voor het verzenden van eerste vermogensbesturingscommando’s naar het basisstation (100);

waarbij de meetmiddelen (250) zijn ingericht voor het meten van de parameter van het eerste neergaande signaal terwijl dit eerste neergaande signaal gemoduleerd wordt met niet vooraf bepaalde gegevenswaarden en aan een transmissievermogensbesturing onderworpen wordt overeenkomstig de eerste vermogensbesturingscommando’s.

2. 	Mobiel station (200) volgens conclusie 1, waarbij de ontvangmiddelen (200) ingericht zijn voor het ontvangen van een tweede, niet vermogensgestuurd neergaand signaal van het basisstation, voor het afleiden van een schatting ten aanzien van het kanaal uit het tweede neergaande signaal en voor het gebruiken van deze schatting ten aanzien van het kanaal om het eerste neergaande signaal te decoderen.

3. 	Mobiel station volgens conclusie 1 of 2, waarbij de vermogensbesturingsmiddelen (230) zijn ingericht voor het decoderen van de niet vooraf bepaalde gegevenswaarden die tweede besturingscommando’s omvatten en voor het aanpassen van het zendvermogen van de zendmiddelen overeenkomstig de gedecodeerde tweede besturingscommando’s.”

(xiii) Volgens de beschrijving stelt de uitvinding zich ten doel de benodigde hoeveelheid systeemelementen (‘system resources’) te verminderen. In § 0011 is uiteengezet dat de uitvinding op het inzicht berust dat de vermogensbesturing in de neergaande richting uitgevoerd kan worden door middel van het meten van de kwaliteit van ontvangen, niet vooraf bepaalde neergaande gegevenssymbolen (de ‘tweede’ TPC-commando’s) in plaats van vooraf bepaalde pilootsymbolen en dat onder bepaalde omstandigheden aparte neergaande pilootsignalen voor elk actief mobiel station voor de kanaalbeoordeling niet noodzakelijk zijn.

(xiv) Eén toepassing van de uitvinding is gelegen in een fractioneel besturingskanaal in de duplexmodus met frequentieverdeling. Gegeven een spreidingsfactor van 256 zijn er dan 10 symbolen per slot. Hierdoor kan één slot op geschikte wijze 2, 5 of 10 gebruikers ondersteunen met respectievelijk 5, 2 of 1 symbool per TPC-commando (§ 0033).

(xv) Philips heeft een eerste en tweede hulpverzoek geformuleerd. Het eerste hulpverzoek (hierna: Hulpverzoek I) berust op § 0011 van de beschrijving en houdt in dat over het besturingskanaal/‘control channel’, waarover de besturingsdata van het basisstation naar het mobiele station neergaand/‘downlink’ worden verzonden, geen pilootsignalen worden getransporteerd. Het tweede hulpverzoek (hierna: Hulpverzoek II) voegt daaraan toe de maatregel uit § 0033 van de beschrijving om de spreidingsfactor van 256 toe te passen en de maatregel daaruit dat één slot 10 gebruikers kan ondersteunen met 1 symbool per TPC-commando, waarmee onder bescherming wordt gesteld dat een tweede TPC-commando uit slechts 1 symbool bestaat. Conclusie 1 conform Hulpverzoek II luidt – met de door de rechtbank aangebrachte en door het hof overgenomen onderverdeling in kenmerken en met inachtneming van Philips’ formulering daarvan in hoger beroep – als volgt, waarbij de toegevoegde kenmerken van Hulpverzoek I en Hulpverzoek II respectievelijk zijn aangeduid met I (a, b) en II:

1.1

Mobiel station (200) voor gebruik in een communicatiesysteem met een basisstation (100) waarbij het mobiele station (200) het volgende omvat:

1.2

ontvangmiddelen (220) voor het ontvangen van een eerste neergaand signaal van het basisstation (100)

Ia op een neergaand fractioneel functiegebonden kanaal uitsluitend bestaande uit niet vooraf bepaalde gegevenswaarden die tussen gebruikers gemultiplext zijn,

1.3

meetmiddelen (250) voor het meten van een parameter van het ontvangen eerste neergaande signaal,

1.4

vermogensbesturingsmiddelen (230) voor het opwekken van eerste vermogensbesturingscommando’s in reactie op de gemeten parameter;

1.5

en zendmiddelen (240) voor het verzenden van eerste vermogensbesturingscommando’s naar het basisstation (100);

1.6

waarbij de meetmiddelen (250) zijn ingericht voor het meten van de parameter van het eerste neergaande signaal terwijl het eerste neergaande signaal gemoduleerd wordt met de niet vooraf bepaalde gegevenswaarden

1.7

en aan een transmissievermogensbesturing onderworpen wordt overeenkomstig de eerste vermogensbesturingscommando’s,

Ib en waarin de niet vooraf bepaalde gegevenswaarden bestaan uit tweede vermogensbesturingscommando’s

II en waarin het neergaand fractioneel functiegebonden kanaal een fractioneel besturingskanaal in UMTS-FDD-modus is met een spreidingsfactor van 256 en omvattende 10 symbolen per venster, zodanig dat één venster tien gebruikers kan ondersteunen met één symbool per TPC commando.

(xvi) Wiko is een Franse vennootschap die in 2011 is opgericht en die mobiele telefoons onder het merk ‘Wiko’ distribueert en verkoopt.

2.2

In dit geding vordert Philips jegens Wiko een inbreukverbod, en een verklaring voor recht dat de producten van Wiko met HSDPA-functionaliteit onder de beschermingsomvang van EP 659 vallen, en heeft zij diverse nevenvorderingen ingesteld. Wiko vordert in reconventie vernietiging van het Nederlandse deel van EP 659 wegens gebrek aan nieuwheid en inventiviteit.

2.3

De rechtbank heeft in reconventie het Nederlandse deel van EP 659 vernietigd en in conventie de op dat octrooi gebaseerde vorderingen van Philips afgewezen.

2.4

Het hof heeft het vonnis van de rechtbank bekrachtigd op de grond dat EP 659 nietig is wegens gemis aan inventiviteit.

3
Toelaatbaarheid conclusie van repliek

3.1

Wiko heeft bezwaar gemaakt tegen de door Philips ingediende conclusie van repliek, gelet op de omvang en de inhoud daarvan. De conclusie kan niet worden aangemerkt als een beknopte reactie op de schriftelijke toelichting van Wiko en is in strijd met het recht op hoor en wederhoor, aldus Wiko. Philips heeft daar tegenin gebracht dat de zaak van groot belang is, dat Wiko ervan heeft afgezien haar verweer al in het verweerschrift op te nemen, waardoor dit verweer Philips pas tijdens het pleidooi en door kennisneming van de schriftelijke toelichting van Wiko bekend is geworden, en dat Wiko ook enkele nieuwe argumenten heeft aangevoerd.

3.2

Conclusies van repliek en dupliek in cassatie dienen beperkt te blijven tot een beknopte reactie op de schriftelijke toelichting en, als tevens mondeling pleidooi heeft plaatsgevonden, de pleitnota van de wederpartij. Deze regel houdt verband met de omstandigheid dat de conclusies van repliek en dupliek in cassatie ertoe dienen te reageren op de schriftelijke toelichting van de wederpartij en dat deze conclusies (evenals de schriftelijke toelichtingen) tegelijk worden genomen. Partijen hebben dus geen gelegenheid om op elkaars repliek respectievelijk dupliek te reageren.

3.3

De namens Philips genomen conclusie van repliek beslaat 46 pagina’s en bevat zowel een reactie op hetgeen namens Wiko in haar pleitnota en schriftelijke toelichting (tezamen 53 pagina’s) is aangevoerd, als een nadere toelichting op haar cassatieklachten. Deze nadere toelichting had eerder dan bij conclusie van repliek kunnen en dus behoren te worden gegeven. Philips had ervoor kunnen kiezen om haar cassatieklachten niet alleen mondeling, maar ook schriftelijk toe te lichten. Nu zij daarvan heeft afgezien, stond het haar niet meer vrij om haar middel bij conclusie van repliek nader toe te lichten. Wiko kon daarop immers niet meer reageren. Anders dan Philips heeft aangevoerd, is er geen grond de conclusie van repliek toch toe te laten wegens het belang van de zaak, of omdat Wiko haar verweer niet al bij verweerschrift naar voren heeft gebracht. De Hoge Raad zal de conclusie van repliek dan ook buiten beschouwing laten.

4
Beoordeling van het middel

Het hof

4.1

Bij de beoordeling van de geldigheid van EP 659 is het hof op verzoek van Philips primair uitgegaan van het octrooi volgens Hulpverzoek II (waarin Hulpverzoek I is begrepen, zie hiervoor in 2.1 onder (xv)). Voorts is het hof er, met partijen, van uitgegaan dat de Nortel 2-voorstellen (zie hiervoor in 2.1 onder (xi)) moeten worden aangemerkt als de meest nabije stand van de techniek. Het hof heeft in rov. 3.2.3 overwogen dat in de visie van Philips de volgende drie verschilmaatregelen bestaan tussen de Nortel 2-voorstellen en Hulpverzoek II:

i) 	in de Nortel 2-voorstellen is de in Hulpverzoek II genoemde spreidingsfactor van 256 niet geopenbaard, maar alleen spreidingsfactoren van ten hoogste 128;

ii) 	in het kanaal volgens Hulpverzoek II worden geen pilootsymbolen verzonden, in het kanaal volgens de Nortel 2-voorstellen wel;

iii) in het kanaal volgens Hulpverzoek II wordt de SIR-meting verricht op 2 bits (namelijk 1 TPC-symbool), in het kanaal volgens de Nortel 2-voorstellen op 4 tot 8 bits (namelijk 2 tot 4 pilootsymbolen).

Voorts heeft het hof overwogen dat volgens Philips het effect van deze verschilmaatregelen tezamen een significante (meer dan drievoudige) verbetering oplevert in het gebruik van de systeembronnen (namelijk 2 x 10 in plaats van 1 x 6 gebruikers van het fractionele kanaal), en dat volgens Philips het objectieve technische probleem dient te worden geformuleerd als: hoe de efficiëntie van de beschikbare systeemruimte te verhogen.

Deze vaststellingen zijn in cassatie niet bestreden.

4.2

In de rov. 3.2.4-3.2.9 heeft het hof als volgt overwogen:

“3.2.4 In de §§ 0007 en 0015 van de beschrijving van EP 659 is als doel van de uitvinding genoemd het verminderen van de behoefte aan systeemruimte/het verbeteren van de systeemcapaciteit. In § 0005 van de beschrijving van EP 659 is vermeld dat de transmissie van pilootsignalen en TPC-commando’s systeemruimte inneemt. De verschilmaatregelen ii) en iii) bevorderen dus de efficiency van het systeem. Dit is door Wiko onderschreven (…). Verschilmaatregel i) heeft tot gevolg dat het aantal beschikbare kanalen verdubbelt.

3.2.5

Wiko betwist echter dat de in verschilmaatregel i) beschreven verhoging van de spreidingsfactor naar 256 enig voordeel biedt. Wat er met de verhoging van de spreidingsfactor in de lengte wordt gewonnen, wordt namelijk in de breedte weer ingeleverd, aldus Wiko (…).

3.2.6

Onder (…) is toegelicht dat het aantal beschikbare kanalen bij een bepaalde spreidingsfactor gelijk is aan die spreidingsfactor. Bij een spreidingsfactor van 128 zijn er dus 128 kanalen. Onder (…) is tevens uiteengezet dat het aantal symbolen dat per slot over een kanaal wordt verzonden 2560 gedeeld door de spreidingsfactor is, dus (2560:128 =) 20 symbolen per slot bij spreidingsfactor 128, en (2560:256 =) 10 symbolen per slot bij spreidingsfactor 256. Dit alles is door Philips niet betwist.

Wanneer de spreidingsfactor wordt verhoogd van 128 naar 256, dan verdubbelt weliswaar het aantal kanalen, maar halveert tegelijkertijd het aantal symbolen dat per slot over een kanaal kan worden verzonden (van 20 naar 10). Zoals Wiko terecht heeft opgemerkt maakt dit per saldo voor de efficiency van de beschikbare systeemruimte geen verschil. De maatregel van Hulpverzoek II om de spreidingsfactor te stellen op/te verhogen naar 256 heeft dus geen enkel efficiency-verbeterend effect.

3.2.7

Dit wordt bevestigd door Philips’ deskundige [betrokkene 1], die in punt 17 van zijn ‘second statement' heeft verklaard dat de deskundige van Wiko, [betrokkene 2] ‘correct (is) in stating that an increase in the spreadingfactor as such does not increase system efficiency (…)’

3.2.8

Nu de door Philips gestelde verschilmaatregel i) met betrekking tot de spreidingsfactor geen enkele bijdrage levert aan de oplossing van het door haar gestelde objectieve probleem, kan daarin de inventiviteit van Hulpverzoek II niet zijn gelegen.

3.2.9

De verschilmaatregelen ii) en iii) hebben tot gevolg dat er meer systeemruimte ontstaat in het neergaande fractionele besturingskanaal volgens Nortel 2 (…). Het zojuist gegeven oordeel, dat verschilmaatregel i) geen gewicht in de schaal kan leggen, brengt dus met zich dat het objectieve probleem, zoals door Philips geformuleerd, moet worden geconcretiseerd tot de vraag hoe dat neergaande fractionele besturingskanaal efficiënter kan worden ingericht (…).”

Het middel

4.3

Onderdeel II van het middel is onder meer gericht tegen de hiervoor in 4.2 aangehaalde overwegingen. Het betoogt dat het hof verschilmaatregel i) ten onrechte afzonderlijk heeft beschouwd en dus geen oordeel heeft gegeven over de combinatie van verschilmaatregelen i), ii) en iii). Het hof had de combinatie van maatregelen moeten vergelijken met de dichtstbijzijnde stand van de techniek (Nortel 2) en zich moeten afvragen of die combinatie op het relevante tijdstip voor de vakman voor de hand lag (onderdelen II.1a en 1b). Het hof heeft uit het oog verloren dat de systeemruimte/-capaciteit in de uitvinding moeten worden vergeleken met dezelfde systeemruimte/-capaciteit in Nortel 2 (onderdeel II.2). Philips heeft gesteld dat de combinatie van de drie verschilmaatregelen leidt tot een meer dan drievoudige verbetering in het gebruik van de beschikbare systeembronnen, hetgeen door Wiko niet is betwist. Als alleen rekening wordt gehouden met de maatregelen ii) en iii) in vergelijking met de dichtstbijzijnde stand van de techniek (Nortel 2), namelijk wanneer alleen wordt gekeken naar het aantal gebruikers per kanaal en niet ook naar het aantal beschikbare codes als gevolg van de gebruikte spreidingsfactor (maatregel i)), dan is de verbetering door de uitvinding niet een drievoudige verbetering (van 6 gebruikers bij spreidingsfactor 128 naar 2 x 10 gebruikers bij spreidingsfactor 256), maar slechts een (bijna) tweevoudige verbetering (van 6 gebruikers per kanaal in Nortel 2 naar 10 gebruikers per kanaal) (onderdeel II.4). Het hof heeft voorts ten onrechte het objectieve technische probleem geherformuleerd tot de vraag hoe het neergaande fractionele besturingskanaal van Nortel 2 efficiënter kan worden ingericht. Onjuist of onbegrijpelijk is dat het hof niet kijkt naar de efficiëntie (capaciteit) van het gehele systeem, maar alleen naar de efficiëntie (capaciteit) van één kanaal en dat het hof verschilmaatregel i) niet bij de (her)formulering betrekt (onderdelen II.5-7).

De klachten worden hierna gezamenlijk beoordeeld.

4.4

Het hof heeft ter beoordeling van de inventiviteit van het octrooi volgens Hulpverzoek II in navolging van partijen de problem solution approach (PSA) gehanteerd, zoals omschreven in de Guidelines for Examination van het Europees Octrooibureau (EOB) en toegepast door de kamers van beroep van het EOB. Ook het middel gaat uit van toepassing van de PSA. Bij toepassing van de PSA wordt het objectieve technische probleem vastgesteld aan de hand van het technische effect zoals dat blijkt uit de verschilmaatregelen die duidelijk worden door een vergelijking tussen het in het octrooi geclaimde en de meest nabije stand van de techniek. Verschilmaatregelen die in het geheel niet bijdragen aan het technische karakter van de uitvinding – noch afzonderlijk noch in combinatie met andere verschilmaatregelen – worden niet meegewogen bij de inventiviteitsbeoordeling. Het in de octrooiaanvraag vermelde probleem wordt wel gebruikt als startpunt, maar kan zo nodig worden geherformuleerd.

4.5

In overeenstemming met het hiervoor in 4.4 weergegeven beoordelingskader heeft het hof de stelling van Philips beoordeeld dat de drie verschilmaatregelen die resulteren uit vergelijking van het octrooi volgens Hulpverzoek II en Nortel 2, tezamen een significante (meer dan drievoudige) verbetering opleveren in het gebruik van de systeembronnen (namelijk 2 x 10 in plaats van 1 x 6 gebruikers van het fractionele kanaal) en aldus de efficiëntie van de beschikbare systeemruimte verhogen (rov. 3.2.3). Het hof heeft het in dat kader door Wiko gevoerde verweer beoordeeld en is tot het oordeel gekomen dat maatregel i) (het hanteren van een spreidingsfactor van 256) geen enkel efficiency verbeterend effect heeft en aldus geen enkele bijdrage levert aan de oplossing van het door Philips gestelde objectieve probleem     (rov. 3.2.6 en 3.2.8). In dat oordeel ligt, mede gelet op de passages in de gedingstukken waarnaar het hof verwijst (zie hierna in 4.6), besloten dat het gebruik van een spreidingsfactor van 256 ook in combinatie met de verschilmaatregelen ii) en iii) geen bijdrage levert aan de oplossing van het probleem.

4.6

Het oordeel dat het gebruik van een spreidingsfactor van 256 ook in combinatie met de verschilmaatregelen ii) en iii) geen bijdrage levert aan de oplossing van het probleem is niet onbegrijpelijk. Wiko heeft de (in onderdeel II.4 aangehaalde) stelling van Philips dat, als alleen rekening wordt gehouden met de maatregelen ii) en iii) in vergelijking met de dichtstbijzijnde stand van de techniek (Nortel 2), namelijk wanneer alleen wordt gekeken naar het aantal gebruikers per kanaal en niet ook naar het aantal beschikbare codes als gevolg van de gebruikte spreidingsfactor (maatregel i)), de verbetering door de uitvinding niet een drievoudige verbetering (van 6 gebruikers bij spreidingsfactor 128 naar 2 x 10 gebruikers bij spreidingsfactor 256), maar slechts een (bijna) tweevoudige verbetering (van 6 gebruikers per kanaal in Nortel 2 naar 10 gebruikers per kanaal) oplevert, gemotiveerd betwist. Zij heeft gesteld en onderbouwd dat de meer dan drievoudige verbetering van het gebruik van de systeembronnen (20 gebruikers in plaats van 6) het gevolg is van de verschilmaatregelen ii) en iii) en dus ook optreedt wanneer, zoals in Nortel 2, een spreidingsfactor van 128 wordt gehanteerd (zie bijvoorbeeld de memorie van antwoord onder 126-129 en 153). Dat is door Philips niet weersproken. Voor zover Philips bij pleidooi in cassatie heeft aangevoerd dat 1 x 20 gebruikers in een kanaal (bij een spreidingsfactor van 128) een ander technisch effect heeft dan 2 x 10 gebruikers (bij een spreidingsfactor van 256) (pleitnota onder 48-50), is sprake van een ontoelaatbaar novum. Voorts mist de bij pleidooi ingenomen stelling dat het hof aldus is uitgegaan van een hypothetische conclusie in plaats van de conclusie volgens Hulpverzoek II feitelijke grondslag. Het oordeel van het hof houdt immers in dat de in dat hulpverzoek toegevoegde verschilmaatregel i) geen bijdrage levert aan de oplossing van het probleem dat het octrooi beoogt op te lossen en berust op een vergelijking van het technisch effect van het gebruik van de met die verschilmaatregel geclaimde spreidingsfactor van 256 en de in Nortel 2 gebruikte spreidingsfactor van 128.

4.7

Gelet op hetgeen hiervoor in 4.4-4.6 is overwogen, stond het het hof vrij het objectieve technische probleem te herformuleren in de in rov. 3.2.9 vermelde zin.

4.8

Het bovenstaande leidt tot de conclusie dat de hiervoor in 4.3 weergegeven klachten tevergeefs zijn aangevoerd.

4.9

Het onderdeel voert onder II.3 nog aan dat het hof in rov. 3.2.7 selectief heeft geciteerd uit de verklaring van deskundige [betrokkene 1]. Deze klacht kan niet tot cassatie leiden, nu het niet gaat om een dragende overweging. Bovendien is het oordeel van het hof over verschilmaatregel i) ook in het licht van de verdere inhoud van de verklaring van de deskundige niet onbegrijpelijk.

4.10

De overige klachten van het middel kunnen evenmin tot cassatie leiden. De Hoge Raad hoeft niet te motiveren waarom hij tot dit oordeel is gekomen. Bij de beoordeling van deze klachten is het namelijk niet nodig om antwoord te geven op vragen die van belang zijn voor de eenheid of de ontwikkeling van het recht (zie art. 81 lid 1 RO).

4.11

Wiko heeft verzocht haar proceskosten te begroten op de voet van art. 1019h Rv. Partijen hebben overeenstemming bereikt over de aldus te begroten kosten, aan de zijde van Wiko op € 90.000,--. Gelet op punt 4 van de Indicatietarieven in octrooizaken Hoge Raad zal dit bedrag worden toegewezen.

5
Beslissing

De Hoge Raad:
-	 verwerpt het beroep;

- veroordeelt Philips in de kosten van het geding in cassatie, tot op deze uitspraak aan de zijde van Wiko begroot op € 90.000,--, vermeerderd met de wettelijke rente over deze kosten indien Philips deze niet binnen veertien dagen na heden heeft voldaan.

Dit arrest is gewezen door de vicepresident M.V. Polak als voorzitter, de vicepresident             M.J. Kroeze en de raadsheren T.H. Tanja-van den Broek, C.H. Sieburgh en F.J.P. Lock, en in het openbaar uitgesproken door de raadsheer H.M. Wattendorff op 25 februari 2022.

Vgl. HR 7 januari 1994, ECLI:NL:HR:1994:ZC1224, rov. 3 en HR 6 januari 1995, ECLI:NL:HR:1995:ZC1602, rov. 3.

Vgl. de conclusie van de Advocaat-Generaal onder 2.7-2.8.
