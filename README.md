# M463K · Summing

Ward-Beck Systems M463K, 1974|7. Wiki page: [M463K on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M463K.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 72 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 12 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 9 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 419 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 0 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 14 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 66 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [1 topic](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1974 - M463K - P003 - 1-1.jpg](MANUALS/1974%20-%20M463K%20-%20P003%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | Unity +/ -0.5 dB _ (With fader dB &quot;in-hand&quot; position. |
| **Frequency response** | +/ -25 dB from 20 Hz kHz _ (Equalizer in bypass position. |
| **Noise** | dB below -10 dBm nominal output level (20 Hz to 20 kHz) |
| **Harmonic distortion** | Less than 0.25% from Hz 20 kHz +28 dBm less Typically less than 0.05% across most bandwidth) |
| **Source impedances** | Summing 30,000 ohms balanced Direct: 600 ohms less balanced |
| **Sum mingless than direct** | 000 ohms ohms |
| **Output impedance** | Less than 100 ohms (at outputs 8-109A amplifiers only 8-109 |
| **Load impedance** | 600 ohms balanced and DIRECT output). (at insertion point |
| **Output level** | dBm nominal insertion. ~10 dBm nominal DIRECT output _ +28 dBm maximum (at outputs 8-109 8_109A amplifiers only) |
| **Phasing** | Input and output terminals designated by numbers are phase. |
| **Power requirements** | volts dc, 100 MA nominal 300 MA maximum |
| **Ambient temperature** | 60 degrees Celsius |
| **Dimensions** | wide 14.5&quot; high 6.5&quot; deep (41 Mm 360 mm 165 Mm) |

## Circuit description

From [1974 - M463K - Submaster Module (2).pdf](MANUALS/1974%20-%20M463K%20-%20Submaster%20Module%20(2).pdf) pages 4-9 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The MA63K is a combination SUB MASTE R/E QUAL IZ ER mod u lr, designed 10 acceP I combined or mixed feeds from previously &quot;ss igned mixing c h&quot;n ne l Inputs. As maybe required, the unit p!'&quot;Oc e sses the mixed signal, equalizes it and routes it to thea p prop r ia te points wil hint h eco nsol e system..

Inpul and Summing A m~

The signal o r l g n ati n g from the e&quot;, t e r n&quot;, 1 m i &quot;, ing nelwork is applied 10 the edge cc n nec tor PI, pins 1 and A and subs e q u e n l l y. conn ecls tot hes u mming current nodes oft h e 4 _141 summing &quot;m pilfi e r. to facilitate module l esl l ng, a direct i npul isp ro v ide don PI, pins 17 and U..

EQUALIZER Section

The OUl put oft h e 4 -141 summing amplifier is !'&quot;Ou ted 10 one of the normally closed c cote ct s of Ih e EOUALIZER INSERTs w i lc h SW13 to allow bypassing oft h e equalizer. Addilionally, the A_141 output is fed t o Zl, t tte first o f four cascaded summing amplifiers Zl I h rough

Zl I hl'&quot;Ough Z4 serve a s mixing and ISOlation amplifiers. They &quot;' reused 10 mix the p dma r y input signal wilh a c or rec lion signal derived from the outputs of I h e 4 -126 lilt er networks, result ing in raising o r lowering the level o f s el e c led p o rlion s of I h e audio spectrum. Additionally, they isolate the filler networks from each ol hera nd p rev en lint eraction between them, resulting inaccurate and repeal able equalizing performance.

The CUT/ eOO ST controls R21, 1'122 and 1'123 feed ani n -ph a se o r ou to f phase prop o rti o n a l sign ll l to Ihe buffer amplifiers ZS, Z6 lind Z8 respective l y. The level o f the sign ll l fed to thebu fl e r s;5 depend e n ton the CUT/ BOOST con lro l selling wilh mllx imum level occurring ate i the rend o f I hep otentiom eter, and a null selling all hep ot e n t io_ meter m i d_pos i t ion. Full clockwise o r full c ou n lel'&quot;Clock wise pOle nti o~ meIer se ni ngs will result int h e ma &quot;, imum equalization o f +15 dB

and -15 dB respect iv ely.

The outputs of buffer amplifiers Z5, Z6 and Z8 are routed to the

4 -1 26 printed ci l'&quot;Cui t board which contains three ban dp ass filters corresponding to each o f the three sections o f I heequaliz er.

The HIGH FREQUENCY secuen o f lhe unil provides SHELVING TYPE of eQ u all z a llon. R21 d e lermi ne s Ihe amounl of CUT 0.- BoOST w llh a lOla I,.ange from -15 10 ·15 dB. F,.equ e n c y is conli n u ou sly adjustable from 1.6 10 2S kHz by Rl /R2. The ff'eQu ency cal lb,.ali on ~fe r-s 10 lhe 3 dB rolloff po inl &quot;, hen lhe un ll is ope,.at inge t Ihe ma&quot; i&quot;,um available CUT 0.- BOOST of I S dB..

The MtD FREQUENCY e qua liza t ion 1$ adjusted by R. /R5, c ov e,.ing a f,.eq u e n c y range f.-om 0.4 10 6 •• kHz. CUT/BOOST i s control led by R22. R6 adjus ls thee re cree, P osll ive or neg allve b el l-shaped PEA I(INGe qua liza lion Is applicable In Ih e mid-f r equency ran ~.

The LOW FREQUENCY eQual i z a lion OPe r,., tess im ila r ly 10 the high frequency s&quot;&quot;, t ion. R7/R8 lIdJu st s the frequency r llng e from 25 to 400 Hz while R23 controls CUT or BOOST.

T h&quot; threes ig n a ls which leave Ih e 4 -1 26 filter are &quot;ce-eeeuce signals &quot; ell her in-ph a s e or 18 0 degrees out-of-pha se wl lh Ih e equalize r inp UI and b andpa s s limited as deler m ln e d by thee qua l - Izer section &quot; nd control Settings. These &quot;eo-reeuee signals &quot; are then summed together with the primary (Inpu~J signal b y the operational amplifier s 2 1, 22 and 24 thus forming the equalized OUtput signal.

This Con Cepl of adding III cce -ecttce signal loget her &quot;, llh Ih e Incoming signal to form l he equalized signal i s direcl ly ~sp onsi b le f o.the low noise and diS IOt'l ion capabilities of I h ls u n ll.

The compound signal as generated along the entire processing chain a ppear-s a l Ihe output o f 2 • • From h.....e It i s roul ed 10 one o f lhe no.-ma l ly open contaCl s o f the EQUALI2ER INSERTs witch SWI 3.

ThUS, with SWi3 depressed, Ih e equalized signal is fed to Ih e OUlp u tamp lifi e r 8-109A. Ina ddit ion, a s SWi3 Is depressed, l he LEO Indic a tOt' Is activated.

8 -1ogA Output Ampl ifi..... and INSERT

The 8 -109A amplifier raises rb e signal to -10 dBm nominally. The

output Is active l y balanced and fed 10 the &quot;inserl p olnl&quot; 111.1 pins 2 2

and 2 of module eeeoee ree P i. This point is usually connected t o II. ' n o.-m ll.l led ' se l o fin sert Jacks, with the OUIPUI side conn ec ted t o

Ihe sub maS l e r fad er.

PREF A DELI ST EN (PF L)

The b,-i dg ing takeoff f o,t he PFL output is picked up a t t heou l put side of SW2 1.

The StJB ON switch SW2 1 con tr&quot;&lt;lls all outputs of the modUle with I he except ion of the PFL output.

The oUt pu l o f the balanced fad e,i s,-etu,-n ed to Ih e module via pins 14 and R o f Pl. The feed fo,th e PREFACE FO L OBA CK (F B), the PREFACE STAGE AMPLIFIER (SAl and the PRE FAO E PUBLIC ADDRESS (PAl channels is br&quot;&lt;lugh lout atP I, pins 20 and)(and 0&quot;; gi nale5 normally from the input side oft h e tee er •

**SLATING**

. An external slate input is pr&quot;&lt;lvid c dat conn ec,to,- P2, pins 8 and J. The slates ig n al is injected;n place of the '-eg ul a r signal when ~:~: r. K l is activated. Trim pot R l 4 2 serves to calibrate Ih e si ale

8 -109Booste rAm~

This amplifier operates with II gain of I S dB. It recovers the lSd B &quot; i n hand &quot; loss incurred by the fade r.

A DIRECT output fr&quot;&lt;lm the 13-109 amplifier i s pr&quot;&lt;lvi de dat corvrec torP2, pins 12 and N.

Master Outputs and PAN Control

Two lef land two,-i g ht outputs area ls o fed b y the 13-109 output

signal. They e r-e routed via PANs witch SWl4 lind PAN control R24 10

R2 7. followed by four MASTER ASSIGNMENT SWITCHES SW22 to SW25. The

ma Sl er OUlpu ts are connected 10 thea p prop r i ale module out pu l t..,-mi n a l s v 1a summing network resistors to b e combined with feeds fr&quot;&lt;lm

other sub master mixing channels.

Au x i liar yOu tp uts

I n ~ d d l ti o n.... SOLO output is av ~ i labl e via SWI6, to ~ l low setec tlve monitoring o f the p ~ r t 1c ul ~r $u b master channel. Other feeds originating from the 8-109 amplifier are supplied to the P OSTF AOE F B. SA and PA cx enners, '

PRE/POS T Selector Switches and Leve! Controls

PRE/POS T selection oft h e SA, F Band P A ch ~nnel sis r ec turered b y switChes SWI8, SWI9, S W20 and SW4 resp e cti v e l y; each switCh Is followed b y its associated level control. The outputs o f the le ve i controls ~ ref edt o the summing outputs via;ndi'vidu~1 assignments witches. Following the assignments witChes, t h e&quot;&quot;, outputs are fed to their appropriate mixing buses vi ~ summing resistors.

Auxiliary Control Functions

DC control contacts are provided on the SOLO &quot; nd P A &quot;ss i g n men t. switChes to permit ex tern ~1 muting a ods e l e c ti v eco n lNl I functions &quot;s maybe required.

Power Supply Oecoupl ing

An active power supply d ecoupli ng network consisting of 0 1 through 06 provides a high degree o f isolation between the M46 3K and the +/-25 volts u p ply rails. The t r~ n s i Slor s 05 and 0 6 serve as the current monilors ~ n d w111 limit the current flowing through the pass trans iSl o r s 03 and Q4 1n the event that excessive powers u p ply dem ~nds shOUld a -tee a s a result o f component f &quot; ilur e.

**FREOUENCY RESPONSE CHARACTER1ST I CS**

.&quot; III ! I!

**., I ! I'**

I, I I -, i I LOW FREQUENCY section CUT/ BOOST: t IS dB.

FREQUENCY; 25 &amp; 400 Hz.

**III I I**

&quot;&quot;. ~&quot;' II'&quot; ~ilOk4(llo,

**:1 I**

I ' i Iii 1., I I / I I iii \(I,. III IIi i ~1 1 !li,). 1 -, I: i Iii vii 'lll)&quot;

**III**

1\1I lli III, i !II: / i!

MID FREQUENCY section -,

I I,,Q l i\i I I!I',, ! II

CUT/BOOST: t I S ae. -a

**I: P!, \ ' I'I!I**

FREQUENCY: 0.4 &amp; 6.4 kHz. ! j !, Q: 2.

l 00 ~ 1,~ 10_ 10.JOI,&lt;OO

**FREQUENCY RESPONSE CHARACTERISTICS**

H46}1e SUBHASTER MQQULE

**'II IIIII.I'**

HIGH FREOUENCY section

CUT/BOOS T: tI S d B.

FREQUENCY: 1.6 &amp; 25 kHz.

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVnFhTl9qUXdjN2M/view?resourcekey=0-sTK9rCY1RIVXz6_Vyzphqg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVnFhTl9qUXdjN2M&resourcekey=0-sTK9rCY1RIVXz6_Vyzphqg" width="240" alt="1974 - M463K - 463-04-015 - ENG SUBMA STER MODULE.jpg"></a><br><sub>1974|7 · 463-04-015 - ENG SUBMA STER MODULE · <a href="MECHANICAL/1974%20-%20M463K%20-%20463-04-015%20-%20ENG%20SUBMA%20STER%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV1RYUlpFRkxsb3c/view?resourcekey=0-_p7oA58xLEZmwH6HJ-0nPA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV1RYUlpFRkxsb3c&resourcekey=0-_p7oA58xLEZmwH6HJ-0nPA" width="240" alt="1974 - M463K - 463-04-016 - OUTPUT AMP UPPER LEGEND.jpg"></a><br><sub>1974|7 · 463-04-016 - OUTPUT AMP UPPER LEGEND · <a href="MECHANICAL/1974%20-%20M463K%20-%20463-04-016%20-%20OUTPUT%20AMP%20UPPER%20LEGEND%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMTJPeE1IejlfTk0/view?resourcekey=0-FWL6hgMZkgRB4dLJxlwaHg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMTJPeE1IejlfTk0&resourcekey=0-FWL6hgMZkgRB4dLJxlwaHg" width="240" alt="1979 - M463K - 463-04-016 - CONTROL COM X-ZO.jpg"></a><br><sub>1979|12 · 463-04-016 - CONTROL COM X-ZO · <a href="MECHANICAL/1979%20-%20M463K%20-%20463-04-016%20-%20CONTROL%20COM%20X-ZO%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbk05VEU0UDRqTjA/view?resourcekey=0-3wVqlRS6lhjNSsetUKPLHQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbk05VEU0UDRqTjA&resourcekey=0-3wVqlRS6lhjNSsetUKPLHQ" width="240" alt="1974 - M463K - 4-126-02-001 - EQUALIZER FILTER ECALE AMPLIFIER SCHEMATIC.jpg"></a><br><sub>1974|7 · 4-126-02-001 - EQUALIZER FILTER ECALE AMPLIFIER SCHEMATIC</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdkpmLS1nbzM2RkE/view?resourcekey=0-GZCDO7Y-RwgqJ1dT1OC8Zg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdkpmLS1nbzM2RkE&resourcekey=0-GZCDO7Y-RwgqJ1dT1OC8Zg" width="240" alt="1974 - M463K - 4-126-02-001 - IOOCP OECP ICK ECABIKED COMC NED VALUE VALUE.jpg"></a><br><sub>1974|7 · 4-126-02-001 - IOOCP OECP ICK ECABIKED COMC NED VALUE VALUE</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZVp5akc4NkVIczg/view?resourcekey=0-hyKJp-vtEqZ9M2pIIBi2Mw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZVp5akc4NkVIczg&resourcekey=0-hyKJp-vtEqZ9M2pIIBi2Mw" width="240" alt="1974 - M463K - 4-126-06-001 - SSMODLKD USON.jpg"></a><br><sub>1974|7 · 4-126-06-001 - SSMODLKD USON</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKc2hqZFNXZDBTNjA/view?resourcekey=0-a9ZUBGpX9FG9qHh3NQVbTw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKc2hqZFNXZDBTNjA&resourcekey=0-a9ZUBGpX9FG9qHh3NQVbTw" width="240" alt="1974 - M463K - 4-126-06-001 - SSNODECKD USOH CATT.jpg"></a><br><sub>1974|7 · 4-126-06-001 - SSNODECKD USOH CATT</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTWZZWGFPQms1TUU/view?resourcekey=0-W1I7qgehAto6Mh7rkivRIg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTWZZWGFPQms1TUU&resourcekey=0-W1I7qgehAto6Mh7rkivRIg" width="240" alt="1974 - M463K - 4-136-06-018 - PIN LISSCOD ICKD USED.jpg"></a><br><sub>1974|7 · 4-136-06-018 - PIN LISSCOD ICKD USED · <a href="SCHEMATICS/1974%20-%20M463K%20-%204-136-06-018%20-%20PIN%20LISSCOD%20ICKD%20USED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQXVwLVhoajNhR1U/view?resourcekey=0-lXcS9BOEjsbvZ4A3Sdxn8w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQXVwLVhoajNhR1U&resourcekey=0-lXcS9BOEjsbvZ4A3Sdxn8w" width="240" alt="1974 - M463K - 4-141-02-001 - TORY SELECTED JAL VALE.jpg"></a><br><sub>1974|7 · 4-141-02-001 - TORY SELECTED JAL VALE · <a href="SCHEMATICS/1974%20-%20M463K%20-%204-141-02-001%20-%20TORY%20SELECTED%20JAL%20VALE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcC0xdk55SEpoMm8/view?resourcekey=0-GlGUxrvIXfEuoLBsp5mLOA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcC0xdk55SEpoMm8&resourcekey=0-GlGUxrvIXfEuoLBsp5mLOA" width="240" alt="1974 - M463K - 4-141-02-001.jpg"></a><br><sub>1974|7 · 4-141-02-001 · <a href="SCHEMATICS/1974%20-%20M463K%20-%204-141-02-001%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaEtPaTF0RnAyZms/view?resourcekey=0-WgMw6KployscV3PnLELDLA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaEtPaTF0RnAyZms&resourcekey=0-WgMw6KployscV3PnLELDLA" width="240" alt="1974 - M463K - 4-141-06-001 - ARE FACTORY SELECTED.jpg"></a><br><sub>1974|7 · 4-141-06-001 - ARE FACTORY SELECTED · <a href="SCHEMATICS/1974%20-%20M463K%20-%204-141-06-001%20-%20ARE%20FACTORY%20SELECTED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMDA2VVRwYmRwTlE/view?resourcekey=0-yqpL12IQbyEwBiu8T_D-qg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMDA2VVRwYmRwTlE&resourcekey=0-yqpL12IQbyEwBiu8T_D-qg" width="240" alt="1974 - M463K - 4-141-06-001 - OPL ZOO RII.jpg"></a><br><sub>1974|7 · 4-141-06-001 - OPL ZOO RII · <a href="SCHEMATICS/1974%20-%20M463K%20-%204-141-06-001%20-%20OPL%20ZOO%20RII%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT3VEZkwteWZqbWs/view?resourcekey=0-5CfYsRJElOdnehKGP71Gmw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT3VEZkwteWZqbWs&resourcekey=0-5CfYsRJElOdnehKGP71Gmw" width="240" alt="1974 - M463K - 463-01-010 - INSERT SUB INSERT JACKS FADER.jpg"></a><br><sub>1974|7 · 463-01-010 - INSERT SUB INSERT JACKS FADER · <a href="SCHEMATICS/1974%20-%20M463K%20-%20463-01-010%20-%20INSERT%20SUB%20INSERT%20JACKS%20FADER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdUVCWlNIc0VGdWc/view?resourcekey=0-l8lblB4yhKGa_XimOWSJbg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdUVCWlNIc0VGdWc&resourcekey=0-l8lblB4yhKGa_XimOWSJbg" width="240" alt="1974 - M463K - 463-01-010 - ZSOLO CONTROL SOLO COMMON CONTROL.jpg"></a><br><sub>1974|7 · 463-01-010 - ZSOLO CONTROL SOLO COMMON CONTROL · <a href="SCHEMATICS/1974%20-%20M463K%20-%20463-01-010%20-%20ZSOLO%20CONTROL%20SOLO%20COMMON%20CONTROL%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKREl3el9JaXRxUlE/view?resourcekey=0-JQunQ7xeMFQbPZtHTEPn-w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKREl3el9JaXRxUlE&resourcekey=0-JQunQ7xeMFQbPZtHTEPn-w" width="240" alt="1974 - M463K - 463-02-010 - SUB MASTER MODULE EKO.jpg"></a><br><sub>1974|7 · 463-02-010 - SUB MASTER MODULE EKO · <a href="SCHEMATICS/1974%20-%20M463K%20-%20463-02-010%20-%20SUB%20MASTER%20MODULE%20EKO%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbVlSeTFwOS1Kclk/view?resourcekey=0-Qjx7XfmobnvLJXxNHsNzGA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbVlSeTFwOS1Kclk&resourcekey=0-Qjx7XfmobnvLJXxNHsNzGA" width="240" alt="1974 - M463K - 8-109-02-001 - NOMINAL VALUE.jpg"></a><br><sub>1974|7 · 8-109-02-001 - NOMINAL VALUE</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSEFkNWFNSWFFUW8/view?resourcekey=0-4l30oN01U8oUz-uTM9Md-g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSEFkNWFNSWFFUW8&resourcekey=0-4l30oN01U8oUz-uTM9Md-g" width="240" alt="1974 - M463K - 8-109-02-001 - RII RIZ IGK.jpg"></a><br><sub>1974|7 · 8-109-02-001 - RII RIZ IGK</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLVlPZGMtSlpIejg/view?resourcekey=0-RFryXxunG8yyjQ8WAHmskA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLVlPZGMtSlpIejg&resourcekey=0-RFryXxunG8yyjQ8WAHmskA" width="240" alt="1974 - M463K - 8-109-02-002 - OUTPUT AMPLIFIER.jpg"></a><br><sub>1974|7 · 8-109-02-002 - OUTPUT AMPLIFIER</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMFV2NGp4a3VVaVU/view?resourcekey=0-6yFkbX2KL4ESKuzRDnTsbQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMFV2NGp4a3VVaVU&resourcekey=0-6yFkbX2KL4ESKuzRDnTsbQ" width="240" alt="1974 - M463K - 8-109-02-002 - RII RIZ.jpg"></a><br><sub>1974|7 · 8-109-02-002 - RII RIZ</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbXVMeXY4R2t0UmM/view?resourcekey=0-JViD_-GLklGtJJXPFuFrHQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbXVMeXY4R2t0UmM&resourcekey=0-JViD_-GLklGtJJXPFuFrHQ" width="240" alt="1974 - M463K - 8-109-06-001 - BOOSTER AMPLIFIER.jpg"></a><br><sub>1974|7 · 8-109-06-001 - BOOSTER AMPLIFIER</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeGVveW1WVnlCdTg/view?resourcekey=0-LI0qb3hJHvONwlYENI54Fw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeGVveW1WVnlCdTg&resourcekey=0-LI0qb3hJHvONwlYENI54Fw" width="240" alt="1974 - M463K - 8-109-06-001 - DRI ENC.jpg"></a><br><sub>1974|7 · 8-109-06-001 - DRI ENC</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb1daZFlKU1RRSGM/view?resourcekey=0-08ggQSH3dVT3rM-bvaofKg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb1daZFlKU1RRSGM&resourcekey=0-08ggQSH3dVT3rM-bvaofKg" width="240" alt="1974 - M463K - 8-109-06-002 - RAS COMPONENT LAYOUT.jpg"></a><br><sub>1974|7 · 8-109-06-002 - RAS COMPONENT LAYOUT</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVXlOMTNjSHNmMVk/view?resourcekey=0-2xu8AYykKJGb8wEaB41LRQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVXlOMTNjSHNmMVk&resourcekey=0-2xu8AYykKJGb8wEaB41LRQ" width="240" alt="1974 - M463K - 8-109-06-002.jpg"></a><br><sub>1974|7 · 8-109-06-002</sub></td></tr>
</table>

Not on Google Drive yet: `19xx - 4-126-02-001.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdm5WanZiM3ZpNVE/view?resourcekey=0-j8f4V73r_CYsJ9yeUE7__w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdm5WanZiM3ZpNVE&resourcekey=0-j8f4V73r_CYsJ9yeUE7__w" width="240" alt="1974 - M463K - 461-03-015 - NOTES LEGEND CONNECTOR PIN MOUNTED.jpg"></a><br><sub>1974|7 · 461-03-015 - NOTES LEGEND CONNECTOR PIN MOUNTED · <a href="PINOUTS/1974%20-%20M463K%20-%20461-03-015%20-%20NOTES%20LEGEND%20CONNECTOR%20PIN%20MOUNTED%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M463K - RTO-144 Connections.pdf`

## RTO-144 pinout

1 contacts (J4), 6 contacts (J6), 21 contacts (P1), 22 contacts (P2). Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 |  | unread |  | low |
| 3 |  | unread |  | low |
| 3 |  | unread |  | low |
| 4 | OUTPUTS | out |  | low |
| 5 |  | unread |  | low |
| 06 |  | unread |  | low |
| 6 | RIGHT OUTPUTS | out |  | low |
| 7 |  | unread |  | low |
| 12 |  | unread |  | low |
| 12 | OUTPUT | out |  | low |
| 13 |  | unread |  | low |
| 18 | CTL COM | ground |  | low |
| 19 |  | unread |  | low |
| 20 |  | unread |  | low |
| 21 |  | unread |  | low |
| 21 |  | unread |  | low |
| 22 |  | unread |  | low |
| D |  | unread |  | low |
| F |  | unread |  | low |
| N | OUTPUT | out |  | low |
| T |  | unread |  | low |
| U | SUB TALLY | control |  | low |
| W |  | unread |  | low |
| X |  | unread |  | low |
| Y | +24V | power |  | low |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZS1ES05MMEdYMjg/view?resourcekey=0-nHSLqo_FXQi8nwQVsGL1gQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZS1ES05MMEdYMjg&resourcekey=0-nHSLqo_FXQi8nwQVsGL1gQ" width="240" alt="1974 - M463K - P001 - Title Page.jpg"></a><br><sub>1974|7 · P001 - Title Page</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTEQ3SWVab3hsdzQ/view?resourcekey=0-I8Zh5aJi0q_u7BB6U7PXQw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTEQ3SWVab3hsdzQ&resourcekey=0-I8Zh5aJi0q_u7BB6U7PXQw" width="240" alt="1974 - M463K - P003 - 1-1.jpg"></a><br><sub>1974|7 · P003 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR05SLTN3TjNTQUU/view?resourcekey=0-5xj7PPp1zdLq7wjj3_m-qA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR05SLTN3TjNTQUU&resourcekey=0-5xj7PPp1zdLq7wjj3_m-qA" width="240" alt="1974 - M463K - P004 - 2-1.jpg"></a><br><sub>1974|7 · P004 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaGFOeEN3QW1NMG8/view?resourcekey=0-vAXf5u4wkc6ktGJpxTtb0A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaGFOeEN3QW1NMG8&resourcekey=0-vAXf5u4wkc6ktGJpxTtb0A" width="240" alt="1974 - M463K - P005 - 2-2.jpg"></a><br><sub>1974|7 · P005 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX3pTamhIWXQ5QUk/view?resourcekey=0-W-0lT2cl9vP9YhwxirkhZA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX3pTamhIWXQ5QUk&resourcekey=0-W-0lT2cl9vP9YhwxirkhZA" width="240" alt="1974 - M463K - P006 - 2-3.jpg"></a><br><sub>1974|7 · P006 - 2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMU11Rjg1NE9HbmM/view?resourcekey=0-fmpAGozsSN9owc6Lc6NZdA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMU11Rjg1NE9HbmM&resourcekey=0-fmpAGozsSN9owc6Lc6NZdA" width="240" alt="1974 - M463K - P007 - 2-4.jpg"></a><br><sub>1974|7 · P007 - 2-4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb2ZraU5ncmNpMWc/view?resourcekey=0-ZV4a02AF1Uy3nlmyoWBr0w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb2ZraU5ncmNpMWc&resourcekey=0-ZV4a02AF1Uy3nlmyoWBr0w" width="240" alt="1974 - M463K - P008 - 3-1.jpg"></a><br><sub>1974|7 · P008 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUG5JMmlEcG9YWGc/view?resourcekey=0-JPJye4VcvZE2WcHRzs8q1w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUG5JMmlEcG9YWGc&resourcekey=0-JPJye4VcvZE2WcHRzs8q1w" width="240" alt="1974 - M463K - P009 - 3-2.jpg"></a><br><sub>1974|7 · P009 - 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbUtPM2hEMzB0SnM/view?resourcekey=0-KtVf9WTuf9cPb5BEhcJxDQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbUtPM2hEMzB0SnM&resourcekey=0-KtVf9WTuf9cPb5BEhcJxDQ" width="240" alt="1974 - M463K - P010 - 4-1.jpg"></a><br><sub>1974|7 · P010 - 4-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTTExUTNGcDBhbjQ/view?resourcekey=0-juQXF2wC1lxNLg4nFRivtA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTTExUTNGcDBhbjQ&resourcekey=0-juQXF2wC1lxNLg4nFRivtA" width="240" alt="1974 - M463K - P011 - 4-2.jpg"></a><br><sub>1974|7 · P011 - 4-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWFQ3Z3ktNGh2MjA/view?resourcekey=0-7x6pTADD_n2yS4POJW1CDQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWFQ3Z3ktNGh2MjA&resourcekey=0-7x6pTADD_n2yS4POJW1CDQ" width="240" alt="1974 - M463K - P012 - 4-3.jpg"></a><br><sub>1974|7 · P012 - 4-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeU0zRjNUZnNMcTQ/view?resourcekey=0-2VZyjdfbcxSZE_HEB7b8Zg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeU0zRjNUZnNMcTQ&resourcekey=0-2VZyjdfbcxSZE_HEB7b8Zg" width="240" alt="1974 - M463K - P013 - 4-4.jpg"></a><br><sub>1974|7 · P013 - 4-4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOGtBaWRjMVpqbFk/view?resourcekey=0-TdEacBOSkxOXm9cH9Dss6w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOGtBaWRjMVpqbFk&resourcekey=0-TdEacBOSkxOXm9cH9Dss6w" width="240" alt="1974 - M463K - P014 - 4-5.jpg"></a><br><sub>1974|7 · P014 - 4-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY2xBam1pN1BtaW8/view?resourcekey=0-LD_QVhyG9Lw5W--2K8_sOQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY2xBam1pN1BtaW8&resourcekey=0-LD_QVhyG9Lw5W--2K8_sOQ" width="240" alt="1974 - M463K - P015 - 4-6.jpg"></a><br><sub>1974|7 · P015 - 4-6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb2p4NGhTVjAzck0/view?resourcekey=0-CQktihRmSc-tZjEtMNWRrQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb2p4NGhTVjAzck0&resourcekey=0-CQktihRmSc-tZjEtMNWRrQ" width="240" alt="1974 - M463K - P016 - 4-7.jpg"></a><br><sub>1974|7 · P016 - 4-7</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSEs1TGVBNENHNm8/view?resourcekey=0-MuhCXVc_AUGw9O5MKa38Uw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSEs1TGVBNENHNm8&resourcekey=0-MuhCXVc_AUGw9O5MKa38Uw" width="240" alt="1974 - M463K - P017 - 8-109.jpg"></a><br><sub>1974|7 · P017 - 8-109</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZTY0bUJTVDNsNUE/view?resourcekey=0-bnl2CDQW1Tmbp2V1puMgBg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZTY0bUJTVDNsNUE&resourcekey=0-bnl2CDQW1Tmbp2V1puMgBg" width="240" alt="1974 - M463K - P018 - 8-109-1-1.jpg"></a><br><sub>1974|7 · P018 - 8-109-1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN3ZZVnRaN2tkODg/view?resourcekey=0-qiQqac35uDvWLkcSugzR1w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN3ZZVnRaN2tkODg&resourcekey=0-qiQqac35uDvWLkcSugzR1w" width="240" alt="1974 - M463K - P019 - 8-109-1-2.jpg"></a><br><sub>1974|7 · P019 - 8-109-1-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSkJQOG5Dc0UxSW8/view?resourcekey=0-F64EFecj2jSKlwl6u2EqAg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSkJQOG5Dc0UxSW8&resourcekey=0-F64EFecj2jSKlwl6u2EqAg" width="240" alt="1974 - M463K - P020 - 8-109-2-1.jpg"></a><br><sub>1974|7 · P020 - 8-109-2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYy1WblpvbjlxM3c/view?resourcekey=0-Vj2bUB8ra6nWUGr8I5mBiQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYy1WblpvbjlxM3c&resourcekey=0-Vj2bUB8ra6nWUGr8I5mBiQ" width="240" alt="1974 - M463K - P021 - 8-109-2-2.jpg"></a><br><sub>1974|7 · P021 - 8-109-2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYXVBeVJER2ZTdzA/view?resourcekey=0-IgYFraX5f4HuFbAWJwGLAA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYXVBeVJER2ZTdzA&resourcekey=0-IgYFraX5f4HuFbAWJwGLAA" width="240" alt="1974 - M463K - P022 - 8-109-2-3.jpg"></a><br><sub>1974|7 · P022 - 8-109-2-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUzF4OERyVGFvcU0/view?resourcekey=0-JcK1FQARRsVoa2b1F7G7vQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUzF4OERyVGFvcU0&resourcekey=0-JcK1FQARRsVoa2b1F7G7vQ" width="240" alt="1974 - M463K - P023 - 8-109-2-4.jpg"></a><br><sub>1974|7 · P023 - 8-109-2-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWkVlVWxHdno0NE0/view?resourcekey=0-sDTvIAAzb5hv8TH11tGn3Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWkVlVWxHdno0NE0&resourcekey=0-sDTvIAAzb5hv8TH11tGn3Q" width="240" alt="1974 - M463K - P024 - 8-109-2-5.jpg"></a><br><sub>1974|7 · P024 - 8-109-2-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa0czbEh6YUxTbEE/view?resourcekey=0-XEZsNkLn7SdFxDDc12-tPg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa0czbEh6YUxTbEE&resourcekey=0-XEZsNkLn7SdFxDDc12-tPg" width="240" alt="1974 - M463K - P026 - 4-141 1-1.jpg"></a><br><sub>1974|7 · P026 - 4-141 1-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKczd0bHpDNjh4TVE/view?resourcekey=0-kNmITs38ID8QVi9zM3mtKw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKczd0bHpDNjh4TVE&resourcekey=0-kNmITs38ID8QVi9zM3mtKw" width="240" alt="1974 - M463K - P027 - 4-141 2-1.jpg"></a><br><sub>1974|7 · P027 - 4-141 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTHZHbTg0SWJreW8/view?resourcekey=0-mDME9LkUakKI8S-2QSeGRA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTHZHbTg0SWJreW8&resourcekey=0-mDME9LkUakKI8S-2QSeGRA" width="240" alt="1974 - M463K - P028 - 4-141 2-2.jpg"></a><br><sub>1974|7 · P028 - 4-141 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVjZVSWVRSVRYczA/view?resourcekey=0-kamRw63cppr8Cm3nWkCtZA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVjZVSWVRSVRYczA&resourcekey=0-kamRw63cppr8Cm3nWkCtZA" width="240" alt="1974 - M463K - P030 - 4-126 1-1.jpg"></a><br><sub>1974|7 · P030 - 4-126 1-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN3Z1cHIzOTE1c1k/view?resourcekey=0-I3wPD2kPs0fwFK2OcTT7SA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN3Z1cHIzOTE1c1k&resourcekey=0-I3wPD2kPs0fwFK2OcTT7SA" width="240" alt="1974 - M463K - P031 - 4-126 2-1.jpg"></a><br><sub>1974|7 · P031 - 4-126 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVU9RYjVfcllXN0E/view?resourcekey=0-gtf5fRdcwtSjcG7Z3mBylA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVU9RYjVfcllXN0E&resourcekey=0-gtf5fRdcwtSjcG7Z3mBylA" width="240" alt="1974 - M463K - P032 - 4-126 2-2.jpg"></a><br><sub>1974|7 · P032 - 4-126 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMGdjaVhmajFIeVk/view?resourcekey=0-BlOI_KinBQCzS81MayRr0w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMGdjaVhmajFIeVk&resourcekey=0-BlOI_KinBQCzS81MayRr0w" width="240" alt="1974 - M463K - P033 - 4-126 2-3.jpg"></a><br><sub>1974|7 · P033 - 4-126 2-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTzNIWDFyVDhSSzA/view?resourcekey=0-Kxr3_irdxefqDTMHLyBAWQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTzNIWDFyVDhSSzA&resourcekey=0-Kxr3_irdxefqDTMHLyBAWQ" width="240" alt="1974 - M463K - P034 - 6-1.jpg"></a><br><sub>1974|7 · P034 - 6-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa1MxMV85WXdzdGs/view?resourcekey=0-DGrRlv3TcKTA5H8tZta4hQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa1MxMV85WXdzdGs&resourcekey=0-DGrRlv3TcKTA5H8tZta4hQ" width="240" alt="1974 - M463K - P035 - 6-2.jpg"></a><br><sub>1974|7 · P035 - 6-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOVBrODhyS3hzVFU/view?resourcekey=0-Zpnb_Ea1w92bTN84ii32fw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOVBrODhyS3hzVFU&resourcekey=0-Zpnb_Ea1w92bTN84ii32fw" width="240" alt="1974 - M463K - P038 - LB463-02-010 001.jpg"></a><br><sub>1974|7 · P038 - LB463-02-010 001</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMXdsOHVWSmp3NlE/view?resourcekey=0-Azll0SiFh25Zsq_hAVqGEw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMXdsOHVWSmp3NlE&resourcekey=0-Azll0SiFh25Zsq_hAVqGEw" width="240" alt="1974 - M463K - P038 - LB463-02-010 002.jpg"></a><br><sub>1974|7 · P038 - LB463-02-010 002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYVN5RGx5dVhfWG8/view?resourcekey=0-NIXgsepYvBWpXYacfwZ16A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYVN5RGx5dVhfWG8&resourcekey=0-NIXgsepYvBWpXYacfwZ16A" width="240" alt="1974 - M463K - P038 - LB463-02-010 003.jpg"></a><br><sub>1974|7 · P038 - LB463-02-010 003</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN1pCbkpyckp0V0E/view?resourcekey=0-8bHFP51hmkMvt0rlsebskw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN1pCbkpyckp0V0E&resourcekey=0-8bHFP51hmkMvt0rlsebskw" width="240" alt="1974 - M463K - P038 - LB463-02-010 004.jpg"></a><br><sub>1974|7 · P038 - LB463-02-010 004</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVVU0MERIdHZtNm8/view?resourcekey=0-ebbc_laSkOIeL8ajx0jXkw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVVU0MERIdHZtNm8&resourcekey=0-ebbc_laSkOIeL8ajx0jXkw" width="240" alt="1974 - M463K - Submaster Module (2).pdf"></a><br><sub>1974|7 · Submaster Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYW1pc1hOVE9zLWc/view?resourcekey=0-BzQUZqDDKfkYb6Lqb6dQ4w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYW1pc1hOVE9zLWc&resourcekey=0-BzQUZqDDKfkYb6Lqb6dQ4w" width="240" alt="1974 - M463K - Submaster Module.pdf"></a><br><sub>1974|7 · Submaster Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVUFTSkdqVWh6Rzg/view?resourcekey=0-E9zVgnKdeq6OwvHC4MIWHg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVUFTSkdqVWh6Rzg&resourcekey=0-E9zVgnKdeq6OwvHC4MIWHg" width="240" alt="1979 - M463K - P002.jpg"></a><br><sub>1979|12 · P002</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVlhjeDFDYnViUEE/view?resourcekey=0-PDOxTUGRQG9kNJOEk6eR3w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVlhjeDFDYnViUEE&resourcekey=0-PDOxTUGRQG9kNJOEk6eR3w" width="240" alt="1983 - M463K - P025 - 4-141.jpg"></a><br><sub>1983|16 · P025 - 4-141</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTXZDZHVrQ0xjUk0/view?resourcekey=0-rC25pHe1mye2W7GncvXVfQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTXZDZHVrQ0xjUk0&resourcekey=0-rC25pHe1mye2W7GncvXVfQ" width="240" alt="1983 - M463K - P029 - 4-126.jpg"></a><br><sub>1983|16 · P029 - 4-126</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1974 - M463K - 4-141-02-001 - TORY SELECTED JAL VALE.kicad_sch](KICAD/1974%20-%20M463K%20-%204-141-02-001%20-%20TORY%20SELECTED%20JAL%20VALE.kicad_sch)
- [1974 - M463K - 4-141-02-001.kicad_sch](KICAD/1974%20-%20M463K%20-%204-141-02-001.kicad_sch)
- [1974 - M463K - 463-01-010 - INSERT SUB INSERT JACKS FADER.kicad_sch](KICAD/1974%20-%20M463K%20-%20463-01-010%20-%20INSERT%20SUB%20INSERT%20JACKS%20FADER.kicad_sch)
- [1974 - M463K - 463-01-010 - ZSOLO CONTROL SOLO COMMON CONTROL.kicad_sch](KICAD/1974%20-%20M463K%20-%20463-01-010%20-%20ZSOLO%20CONTROL%20SOLO%20COMMON%20CONTROL.kicad_sch)
- [1974 - M463K - 463-02-010 - SUB MASTER MODULE EKO.kicad_sch](KICAD/1974%20-%20M463K%20-%20463-02-010%20-%20SUB%20MASTER%20MODULE%20EKO.kicad_sch)
- [1974 - M463K - Submaster Module (2) p23.kicad_sch](KICAD/1974%20-%20M463K%20-%20Submaster%20Module%20(2)%20p23.kicad_sch)
- [1974 - M463K - Submaster Module (2) p49.kicad_sch](KICAD/1974%20-%20M463K%20-%20Submaster%20Module%20(2)%20p49.kicad_sch)
- [1974 - M463K - Submaster Module (2) p57.kicad_sch](KICAD/1974%20-%20M463K%20-%20Submaster%20Module%20(2)%20p57.kicad_sch)
- [1974 - M463K - Submaster Module p38.kicad_sch](KICAD/1974%20-%20M463K%20-%20Submaster%20Module%20p38.kicad_sch)
- [1974 - M463K - Submaster Module p49.kicad_sch](KICAD/1974%20-%20M463K%20-%20Submaster%20Module%20p49.kicad_sch)
- [1974 - M463K - Submaster Module p53.kicad_sch](KICAD/1974%20-%20M463K%20-%20Submaster%20Module%20p53.kicad_sch)
- [1974 - M463K - Submaster Module p57.kicad_sch](KICAD/1974%20-%20M463K%20-%20Submaster%20Module%20p57.kicad_sch)
- [19xx - 4-126-02-001.kicad_sch](KICAD/19xx%20-%204-126-02-001.kicad_sch)
- [M463K.kicad_sym](KICAD/M463K.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
