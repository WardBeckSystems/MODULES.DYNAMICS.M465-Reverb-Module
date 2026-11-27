# M465 Reverb Module · Dynamics

Ward-Beck Systems M465, 1974|7. Wiki page: [M465 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M465.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 111 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 24 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 11 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 244 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 29 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 71 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [3 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1974 - M465 - 5.jpg](MANUALS/1974%20-%20M465%20-%205.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** |  |
| &nbsp;&nbsp;Return | Send: 15 dB ±0.5 dB _ 33 dB ±0.5 dB; t ±0.25 dB from 20 Hz to 20 kHz. o {. |
| **Frequency response** | Noise: |
| **Return** | Send: 80 dB S/ N 85 dB S/N (20 Hz to 20 kHz) be ]ow nomina] operating s igna ] Teve 1 |
| **Harmonic distortion** | Less than 0.25% from 20 Hz to 20 kHz at +28 dBm output Teve 1 or Tess Less than 0.1% at kHz at +28 dBm output_ Source Impedances: 600 ohm or Tess, balanced |
| **Input impedances** | 600 ohm, baLanced |
| **Input levels** | 10 dBm nomina ] +30 dBm maximum. |
| **Output impedances** |  |
| &nbsp;&nbsp;Return | Send: Less than 200 ohm, balanced 600 ohm, balanced |
| **Load impedances** |  |
| &nbsp;&nbsp;Return | 3,000 ohm minimum, each output, balanced _ 600 ohm, balanced. |
| &nbsp;&nbsp;Output levels |  |
| &nbsp;&nbsp;Return | Send: -10 dBm nomina], +30 dBm maximum_ +8 dBm nomina ] +24 dBm maximum |
| **Phasing** | Input and output terminals desi grated by numbers are in phase |

## Circuit description

From [1979 - M465 - Reverb Module.pdf](MANUALS/1979%20-%20M465%20-%20Reverb%20Module.pdf) pages 5-7 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The M46 S REVE RB MODULE is designed to be used i nco njunc tion with a nell te rnel r eve rbe r e t t cn chamber. The Module is divided into a REVERB SEND (RS) and a REVERB RETURN (RR) section.

Re verb Send Originating f rOIl theRe verb Send Milling bus, the signal enters the Module at pins 6/F. The pete nt t oee t e r RI/R 2 serves a s the RS MASTER Level control. The 8 ~ 109 C Booster AlfIpl if 1e r raises the COllbined o r Ml u d signal to standard line level.

Amplifier. I t is cal1brated t o read ° A vu Meter is connected tot he output oft he B-109C Booster vu with pins 4/ 0 and / or S/ E terMinated Into 600 ohMS and producing a n output level of +8 dBM.

Switch SWS allows to feed the pre fade Reve rb Sends i gnal tot he SOLO output atp ins 9/ 1(.

Rever b Return The Returns i gnal frOM there ve r beret f on c h&quot; Mbe r I s applied to pins 15/ 5. Fro &quot; here, 1t continues tot he ' RR ON' switch SW7. A Fa der Insert isp r ovid e d between pins l3 /P and 121N. The 8 -109 Booster Amplifier recovers the no. ina l 15 dB -i n ha ndl oss incurred by the fader and develops sufficient additional power tod rivet he PAN and output circuit ry. The outputs i gnal oft he 8 ~109 amplifier is routed via PANs witch SW3 and PAN control R5 through R8 to the LEFT and RIGHT outputs atp ins 16/T and 17/U respectively. In addition, a DIRECT output isp rovid e dat pins 111M.

A FOLD8AC I(output is made available atp ins 8/J. Switch 5W6 facilitates p r efa de o r post fade source selection fort he

FDlDBACI(output. Potent i ome t e r R3/ R4 serves a s the FOlOBACI(

level control, followed by switch SW2.

SW4 switches the pre fade Re verb Returns i gna l t o the SOLO output.

Power Supply Oecoupli ng An active power supply dec ou pl ing network consisting of 01 through 06 pr ovt de s.a high degree of isolation between the M465 and the !25 volt supply rails. Transistors 05 lind 06 serve a s current monitors and will limit the current flo w1ng through the pass t r e ns t s tors OJ and Q4 in the event excessive power supply demandS should arise as ares u lt of component failure.

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeE54OGtBaHVCX0U/view?resourcekey=0-jiefPWDm-Qb4vMMwahN0Xw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeE54OGtBaHVCX0U&resourcekey=0-jiefPWDm-Qb4vMMwahN0Xw" width="240" alt="1974 - M465 - 461-03-015 - MOUNTED OVER PIN ILSS.jpg"></a><br><sub>1974|7 · 461-03-015 - MOUNTED OVER PIN ILSS · <a href="MECHANICAL/1974%20-%20M465%20-%20461-03-015%20-%20MOUNTED%20OVER%20PIN%20ILSS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKclBPOW1qMlBuaW8/view?resourcekey=0-1uY4moBRw7iGnYqlKF4JEA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKclBPOW1qMlBuaW8&resourcekey=0-1uY4moBRw7iGnYqlKF4JEA" width="240" alt="1974 - M465 - 465-04-004 - REVERB MODULE FRONT PANEL.jpg"></a><br><sub>1974|7 · 465-04-004 - REVERB MODULE FRONT PANEL · <a href="MECHANICAL/1974%20-%20M465%20-%20465-04-004%20-%20REVERB%20MODULE%20FRONT%20PANEL%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMWVqaDVGNUswQTA/view?resourcekey=0-7-17cxUQOPPbzM7N85__zA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMWVqaDVGNUswQTA&resourcekey=0-7-17cxUQOPPbzM7N85__zA" width="240" alt="1974 - M465 - 465-04-004 - SOLO OUTPUT BUS NOTE THAT THE.jpg"></a><br><sub>1974|7 · 465-04-004 - SOLO OUTPUT BUS NOTE THAT THE · <a href="MECHANICAL/1974%20-%20M465%20-%20465-04-004%20-%20SOLO%20OUTPUT%20BUS%20NOTE%20THAT%20THE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1gNFOZ2eSCOc1GttnhyJGS9wuthDUxXj6/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1gNFOZ2eSCOc1GttnhyJGS9wuthDUxXj6" width="240" alt="19xx - M465 - DOC - 465-03-002 - UNC NOIE.jpg"></a><br><sub>19xx - M465 - DOC - 465-03-002 - UNC NOIE · <a href="MECHANICAL/19xx%20-%20M465%20-%20DOC%20-%20465-03-002%20-%20UNC%20NOIE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `1974 - 465-03-001 - M455 & M465 EXTRUSION - DRN DM - ISS 9.jpg`

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNEswa2lvSHpXZTg/view?resourcekey=0-jppAqzjs4z7OziSQ9Q-wrQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNEswa2lvSHpXZTg&resourcekey=0-jppAqzjs4z7OziSQ9Q-wrQ" width="240" alt="1974 - M465 - 4-109-02-001.jpg"></a><br><sub>1974|7 · 4-109-02-001 · <a href="SCHEMATICS/1974%20-%20M465%20-%204-109-02-001%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR1ZYVWtQSWZlRUk/view?resourcekey=0-F-Hg6Zsi5YCiKhsA_D3aXw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR1ZYVWtQSWZlRUk&resourcekey=0-F-Hg6Zsi5YCiKhsA_D3aXw" width="240" alt="1974 - M465 - 4-109-02-004 - BOOSTER AMPLIFIER ICKD.jpg"></a><br><sub>1974|7 · 4-109-02-004 - BOOSTER AMPLIFIER ICKD · <a href="SCHEMATICS/1974%20-%20M465%20-%204-109-02-004%20-%20BOOSTER%20AMPLIFIER%20ICKD%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQzJ5NjRZUDJDaDg/view?resourcekey=0-KKweXFsXSw8Mh9oKov9z7A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQzJ5NjRZUDJDaDg&resourcekey=0-KKweXFsXSw8Mh9oKov9z7A" width="240" alt="1974 - M465 - 4-109-06-001 - BLACK OSS MOD ICKD USED.jpg"></a><br><sub>1974|7 · 4-109-06-001 - BLACK OSS MOD ICKD USED · <a href="SCHEMATICS/1974%20-%20M465%20-%204-109-06-001%20-%20BLACK%20OSS%20MOD%20ICKD%20USED%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMUtSME9iTkhHa2M/view?resourcekey=0-7u7IHBUY7BBAhRQibhE_ZQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMUtSME9iTkhHa2M&resourcekey=0-7u7IHBUY7BBAhRQibhE_ZQ" width="240" alt="1974 - M465 - 4-109-06-004 - MOD ICKD USED.jpg"></a><br><sub>1974|7 · 4-109-06-004 - MOD ICKD USED · <a href="SCHEMATICS/1974%20-%20M465%20-%204-109-06-004%20-%20MOD%20ICKD%20USED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLUF1cTVZbWZLT0k/view?resourcekey=0-0_u9rG-AH3U3doCncstJ2A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLUF1cTVZbWZLT0k&resourcekey=0-0_u9rG-AH3U3doCncstJ2A" width="240" alt="1974 - M465 - 4-132-06-001.jpg"></a><br><sub>1974|7 · 4-132-06-001 · <a href="SCHEMATICS/1974%20-%20M465%20-%204-132-06-001%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOHVIOWRiWTA2TTA/view?resourcekey=0-X9OAQqQCJgUA4uY1B65ssg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOHVIOWRiWTA2TTA&resourcekey=0-X9OAQqQCJgUA4uY1B65ssg" width="240" alt="1974 - M465 - 465-01-001.jpg"></a><br><sub>1974|7 · 465-01-001 · <a href="SCHEMATICS/1974%20-%20M465%20-%20465-01-001%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOG9ZamZOTDJjMEk/view?resourcekey=0-K4AejY9--zRwUZz8QqWckw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOG9ZamZOTDJjMEk&resourcekey=0-K4AejY9--zRwUZz8QqWckw" width="240" alt="1974 - M465 - 465-02-001 - AND ALL CAPACITO UNLESS OTHEPISE SPECIFIED.jpg"></a><br><sub>1974|7 · 465-02-001 - AND ALL CAPACITO UNLESS OTHEPISE SPECIFIED · <a href="SCHEMATICS/1974%20-%20M465%20-%20465-02-001%20-%20AND%20ALL%20CAPACITO%20UNLESS%20OTHEPISE%20SPECIFIED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU2ZtUzhqNDlsaEU/view?resourcekey=0-spV9I2_ePnom2WeR4GyKpA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU2ZtUzhqNDlsaEU&resourcekey=0-spV9I2_ePnom2WeR4GyKpA" width="240" alt="1974 - M465 - 465-02-001 - REVERB MODULE ISCALE SCHEMATIC.jpg"></a><br><sub>1974|7 · 465-02-001 - REVERB MODULE ISCALE SCHEMATIC · <a href="SCHEMATICS/1974%20-%20M465%20-%20465-02-001%20-%20REVERB%20MODULE%20ISCALE%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOE83cEk1cnlfVEE/view?resourcekey=0-SeIJ9kdkMCdT8fPBs7Jccw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOE83cEk1cnlfVEE&resourcekey=0-SeIJ9kdkMCdT8fPBs7Jccw" width="240" alt="1974 - M465 - 465-02-001.jpg"></a><br><sub>1974|7 · 465-02-001 · <a href="SCHEMATICS/1974%20-%20M465%20-%20465-02-001%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKclk0RWszYkNCVEk/view?resourcekey=0-_mO5wVD5jqJlSaUVBLDuPw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKclk0RWszYkNCVEk&resourcekey=0-_mO5wVD5jqJlSaUVBLDuPw" width="240" alt="1974 - M465 - 74042-02-011.jpg"></a><br><sub>1974|7 · 74042-02-011 · <a href="SCHEMATICS/1974%20-%20M465%20-%2074042-02-011%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbVlSeTFwOS1Kclk/view?resourcekey=0-Qjx7XfmobnvLJXxNHsNzGA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbVlSeTFwOS1Kclk&resourcekey=0-Qjx7XfmobnvLJXxNHsNzGA" width="240" alt="1974 - M465 - 8-109-02-001 - NOMINAL VALUE.jpg"></a><br><sub>1974|7 · 8-109-02-001 - NOMINAL VALUE · <a href="SCHEMATICS/1974%20-%20M465%20-%208-109-02-001%20-%20NOMINAL%20VALUE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSEFkNWFNSWFFUW8/view?resourcekey=0-4l30oN01U8oUz-uTM9Md-g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSEFkNWFNSWFFUW8&resourcekey=0-4l30oN01U8oUz-uTM9Md-g" width="240" alt="1974 - M465 - 8-109-02-001 - RII RIZ IGK.jpg"></a><br><sub>1974|7 · 8-109-02-001 - RII RIZ IGK · <a href="SCHEMATICS/1974%20-%20M465%20-%208-109-02-001%20-%20RII%20RIZ%20IGK%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOURQbURtdkpXekk/view?resourcekey=0--3FgDo-BiCoFLT5N5iSwhQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOURQbURtdkpXekk&resourcekey=0--3FgDo-BiCoFLT5N5iSwhQ" width="240" alt="1974 - M465 - 8-109-02-004 - NOMINAL VALUE (2).jpg"></a><br><sub>1974|7 · 8-109-02-004 - NOMINAL VALUE (2) · <a href="SCHEMATICS/1974%20-%20M465%20-%208-109-02-004%20-%20NOMINAL%20VALUE%20(2)%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWkxSZ0k5akpna28/view?resourcekey=0-pX-NFSFrOykzjQ-UKarXNw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWkxSZ0k5akpna28&resourcekey=0-pX-NFSFrOykzjQ-UKarXNw" width="240" alt="1974 - M465 - 8-109-02-004 - NOMINAL VALUE.jpg"></a><br><sub>1974|7 · 8-109-02-004 - NOMINAL VALUE · <a href="SCHEMATICS/1974%20-%20M465%20-%208-109-02-004%20-%20NOMINAL%20VALUE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbXVMeXY4R2t0UmM/view?resourcekey=0-JViD_-GLklGtJJXPFuFrHQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbXVMeXY4R2t0UmM&resourcekey=0-JViD_-GLklGtJJXPFuFrHQ" width="240" alt="1974 - M465 - 8-109-06-001 - BOOSTER AMPLIFIER.jpg"></a><br><sub>1974|7 · 8-109-06-001 - BOOSTER AMPLIFIER · <a href="SCHEMATICS/1974%20-%20M465%20-%208-109-06-001%20-%20BOOSTER%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeGVveW1WVnlCdTg/view?resourcekey=0-LI0qb3hJHvONwlYENI54Fw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeGVveW1WVnlCdTg&resourcekey=0-LI0qb3hJHvONwlYENI54Fw" width="240" alt="1974 - M465 - 8-109-06-001 - DRI ENC.jpg"></a><br><sub>1974|7 · 8-109-06-001 - DRI ENC · <a href="SCHEMATICS/1974%20-%20M465%20-%208-109-06-001%20-%20DRI%20ENC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVlhheEZoMmswZWs/view?resourcekey=0-_WKNV23e-aodqfdDmojWHg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVlhheEZoMmswZWs&resourcekey=0-_WKNV23e-aodqfdDmojWHg" width="240" alt="1974 - M465 - 8-109-06-004 - BOOSTER AMPLIFIER.jpg"></a><br><sub>1974|7 · 8-109-06-004 - BOOSTER AMPLIFIER · <a href="SCHEMATICS/1974%20-%20M465%20-%208-109-06-004%20-%20BOOSTER%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTHVoU2pGS1ZnMHM/view?resourcekey=0-HOXlcrRcauG4IXFo4R0tNw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTHVoU2pGS1ZnMHM&resourcekey=0-HOXlcrRcauG4IXFo4R0tNw" width="240" alt="1974 - M465 - 8-109-06-004.jpg"></a><br><sub>1974|7 · 8-109-06-004 · <a href="SCHEMATICS/1974%20-%20M465%20-%208-109-06-004%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZTZ6Zk5LQXRMV2s/view?resourcekey=0-i_wFJ_aTEsk20JC4TSOZAA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZTZ6Zk5LQXRMV2s&resourcekey=0-i_wFJ_aTEsk20JC4TSOZAA" width="240" alt="1974 - M465 - B 465-01-001 - M465 - REVERB MODULE - FUNCTIONAL DIAGRAM.jpg"></a><br><sub>1974|7 · B 465-01-001 - M465 - REVERB MODULE - FUNCTIONAL DIAGRAM · <a href="SCHEMATICS/1974%20-%20M465%20-%20B%20465-01-001%20-%20M465%20-%20REVERB%20MODULE%20-%20FUNCTIONAL%20DIAGRAM%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1kC2Ye7wLfE9DZv34LsHOYHQm1yxYXDs9/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1kC2Ye7wLfE9DZv34LsHOYHQm1yxYXDs9" width="240" alt="19xx - M465 - DOC - 465-02-001 - NOIES AND ALL CAPACITORS INAF ALL RESISTORS.png"></a><br><sub>19xx - M465 - DOC - 465-02-001 - NOIES AND ALL CAPACITORS INAF ALL RESISTORS · <a href="SCHEMATICS/19xx%20-%20M465%20-%20DOC%20-%20465-02-001%20-%20NOIES%20AND%20ALL%20CAPACITORS%20INAF%20ALL%20RESISTORS%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `1977 - 4-132-06-001 - REVERB MODULE PCB LAYOUT - DRN DM - ISS 4.jpg`, `1977 - 465-01-001 - REVERB MODULE FUNCTIONAL DIAGRAM - DRN P. MAHONEY - ENG RKB - ISS 3.jpg`, `1978 - 8-109-02-001 - 8-109 BOOSTER AMPLIFIER SCHEMATIC - DRN GEB - ENG MRW - ISS 1.jpg`, `1978 - 8-109-02-004 - 8-109C BOOSTER AMPLIFIER SCHEMATIC - DRN GEB - ENG MRW - ISS 1.jpg`, `1982 - 465-02-003 - M465B REVERB MODULE SCHEMATIC - DRN JEI - ENG PA - ISS 2.png`, `1982 - 465-02-003 - M465B REVERB MODULE SCHEMATIC - DRN JET - ENG PA - ISS 2.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN3Vkb1Q2SkE2Rlk/view?resourcekey=0-ZjAeTbffPv2uaJPzTAmZIg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN3Vkb1Q2SkE2Rlk&resourcekey=0-ZjAeTbffPv2uaJPzTAmZIg" width="240" alt="1974 - M465 - 465-04-003 - CONNECTOR REAR VIEW CALE.jpg"></a><br><sub>1974|7 · 465-04-003 - CONNECTOR REAR VIEW CALE · <a href="PINOUTS/1974%20-%20M465%20-%20465-04-003%20-%20CONNECTOR%20REAR%20VIEW%20CALE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M465 - RTO-144 Connections.pdf`

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it); 1 to check (`conflicts`). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

**To check:**

- disagree REV SEND OUT 2: kept insert port; inserts says no partner (send / return) named
- insert guessed: 'P1' assumed REV SEND OUT to the reverb device, RETURN IN back from it; (M465: 1974 - M465 - 465-04-003 - CONNECTOR REAR VIEW CALE.jpg)

**Inserts:** REVERB SEND/RETURN: REV SEND OUT 1 → RETURN IN · RR FADER: TO RR FADER → FROM RR FADER

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | INTERNAL CONNECTION | other |  | high |
| 2 | INTERNAL CONNECTION | other |  | high |
| 3 | INTERNAL CONNECTION | other |  | high |
| 4 | REV SEND OUT | insert_send | REV SEND OUT 1 | high |
| 5 | REV SEND OUT | insert_send | REV SEND OUT 2 | high |
| 6 | REV SEND IN | in | REV SEND IN | high |
| 7 | N/C | nc |  | high |
| 8 | FB OUT | out | FB OUT | high |
| 9 | SOLO OUT | out | SOLO OUT | high |
| 10 | N/C | nc |  | high |
| 11 | RR OUT DIRECT | out | RR OUT DIRECT | high |
| 12 | FROM RR FADER | insert_return | FROM RR FADER | high |
| 13 | TO RR FADER | insert_send | TO RR FADER | high |
| 14 | INTERNAL CONNECTION | other |  | high |
| 15 | RETURN IN | insert_return | RETURN IN | high |
| 16 | RR OUT LEFT | out | RR OUT LEFT L | high |
| 17 | RR OUT RIGHT | out | RR OUT RIGHT R | high |
| 18 | CONTROL COMMON | ground |  | high |
| 19 | -25 V | power |  | high |
| 20 | 25 V COM | ground |  | high |
| 21 | +25 V | power |  | high |
| 22 | CHASSIS | ground |  | high |
| A | INTERNAL CONNECTION | other |  | high |
| B | INTERNAL CONNECTION | other |  | high |
| C | INTERNAL CONNECTION | other |  | high |
| D | REV SEND OUT | insert_send | REV SEND OUT 1 | high |
| E | REV SEND OUT | insert_send | REV SEND OUT 2 | high |
| F | REV SEND IN | in | REV SEND IN | high |
| H | N/C | nc |  | high |
| J | FB OUT | out | FB OUT | high |
| K | SOLO OUT | out | SOLO OUT | high |
| L | N/C | nc |  | high |
| M | RR OUT DIRECT | out | RR OUT DIRECT | high |
| N | FROM RR FADER | insert_return | FROM RR FADER | high |
| P | TO RR FADER | insert_send | TO RR FADER | high |
| R | INTERNAL CONNECTION | other |  | high |
| S | RETURN IN | insert_return | RETURN IN | high |
| T | RR OUT LEFT | out | RR OUT LEFT L | high |
| U | RR OUT RIGHT | out | RR OUT RIGHT R | high |
| V | SOLO CONTROL | control_in | SOLO CTL | high |
| W | N/C | nc |  | high |
| X | 24V COM | ground |  | high |
| Y | +24 V | power |  | high |
| Z | N/C | nc |  | high |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcTk1TUZUcVlFdWs/view?resourcekey=0-GdO0cs2m3SwqEiN9zZBJQw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcTk1TUZUcVlFdWs&resourcekey=0-GdO0cs2m3SwqEiN9zZBJQw" width="240" alt="1974 - M465 - 1.jpg"></a><br><sub>1974|7 · 1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRE1GYkpoalA5V2c/view?resourcekey=0-8osFzchsmqgWwn78LauzLg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRE1GYkpoalA5V2c&resourcekey=0-8osFzchsmqgWwn78LauzLg" width="240" alt="1974 - M465 - 10.jpg"></a><br><sub>1974|7 · 10</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYThOTmZjT2tuQnM/view?resourcekey=0-d9cD69SYBUntIp-e91wFiw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYThOTmZjT2tuQnM&resourcekey=0-d9cD69SYBUntIp-e91wFiw" width="240" alt="1974 - M465 - 11.jpg"></a><br><sub>1974|7 · 11</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMjVIVE4yazUzUms/view?resourcekey=0-heGBVgaJ8vI-pFHWctfQcw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMjVIVE4yazUzUms&resourcekey=0-heGBVgaJ8vI-pFHWctfQcw" width="240" alt="1974 - M465 - 12.jpg"></a><br><sub>1974|7 · 12</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSG5iZFlXUWhzWVE/view?resourcekey=0-pWxIQMzOljbk26O-7LaVLg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSG5iZFlXUWhzWVE&resourcekey=0-pWxIQMzOljbk26O-7LaVLg" width="240" alt="1974 - M465 - 13.jpg"></a><br><sub>1974|7 · 13</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMDBPWUpyTnVNajQ/view?resourcekey=0-Jo17ukwBg9XL5UfeYns1FQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMDBPWUpyTnVNajQ&resourcekey=0-Jo17ukwBg9XL5UfeYns1FQ" width="240" alt="1974 - M465 - 14.jpg"></a><br><sub>1974|7 · 14</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdlJKVnBSRmsza3c/view?resourcekey=0-hdzCDN_9msCN04kF8MA7Sg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdlJKVnBSRmsza3c&resourcekey=0-hdzCDN_9msCN04kF8MA7Sg" width="240" alt="1974 - M465 - 15.jpg"></a><br><sub>1974|7 · 15</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUFRiR05OdmNSUFk/view?resourcekey=0-UOXVlXXgLsPDPoVPhkmxEA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUFRiR05OdmNSUFk&resourcekey=0-UOXVlXXgLsPDPoVPhkmxEA" width="240" alt="1974 - M465 - 16.jpg"></a><br><sub>1974|7 · 16</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKc3U0NUQ5NTU0QTg/view?resourcekey=0-s4f6QtWR-kO8cM70S1pjPQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKc3U0NUQ5NTU0QTg&resourcekey=0-s4f6QtWR-kO8cM70S1pjPQ" width="240" alt="1974 - M465 - 17.jpg"></a><br><sub>1974|7 · 17</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNy1LeTVFd09ianM/view?resourcekey=0-MX-nkuOGOGjfkh9pYP-7Kg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNy1LeTVFd09ianM&resourcekey=0-MX-nkuOGOGjfkh9pYP-7Kg" width="240" alt="1974 - M465 - 18.jpg"></a><br><sub>1974|7 · 18</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV3poNksxM2N1dEU/view?resourcekey=0-nZioiOKWPbD55JCpSYXiMQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV3poNksxM2N1dEU&resourcekey=0-nZioiOKWPbD55JCpSYXiMQ" width="240" alt="1974 - M465 - 2.jpg"></a><br><sub>1974|7 · 2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOHZRTXlkc2JMQ3M/view?resourcekey=0-tg9npU-BqsAWSdc0jedgDA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOHZRTXlkc2JMQ3M&resourcekey=0-tg9npU-BqsAWSdc0jedgDA" width="240" alt="1974 - M465 - 4.jpg"></a><br><sub>1974|7 · 4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVkRMY01WY19OREU/view?resourcekey=0-3PXOf6dO2brQ0bFaaRmjug" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVkRMY01WY19OREU&resourcekey=0-3PXOf6dO2brQ0bFaaRmjug" width="240" alt="1974 - M465 - 5.jpg"></a><br><sub>1974|7 · 5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKc0RKNjA0SEt6aVk/view?resourcekey=0-vXLmdtHukF2ZqL9Js3EtBg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKc0RKNjA0SEt6aVk&resourcekey=0-vXLmdtHukF2ZqL9Js3EtBg" width="240" alt="1974 - M465 - 50001.jpg"></a><br><sub>1974|7 · 50001</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTC1rWmIxaWxRQ2M/view?resourcekey=0-Bh-DEeoqgsqeif-caL3Onw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTC1rWmIxaWxRQ2M&resourcekey=0-Bh-DEeoqgsqeif-caL3Onw" width="240" alt="1974 - M465 - 6.jpg"></a><br><sub>1974|7 · 6</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVDlJTXg4NUhVOGc/view?resourcekey=0-qis4KzFfon5mRpqGNJEE2w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVDlJTXg4NUhVOGc&resourcekey=0-qis4KzFfon5mRpqGNJEE2w" width="240" alt="1974 - M465 - 7.jpg"></a><br><sub>1974|7 · 7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNy1kR2tzNjRreWc/view?resourcekey=0-YVVFFlxW6S-Ehig_5d-8tA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNy1kR2tzNjRreWc&resourcekey=0-YVVFFlxW6S-Ehig_5d-8tA" width="240" alt="1974 - M465 - 8.jpg"></a><br><sub>1974|7 · 8</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM1hMdS1WS2JaX00/view?resourcekey=0-vn1ruV2UlNKmVrAfwzubTA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM1hMdS1WS2JaX00&resourcekey=0-vn1ruV2UlNKmVrAfwzubTA" width="240" alt="1974 - M465 - 9.jpg"></a><br><sub>1974|7 · 9</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKazlReUhMc0JzbG8/view?resourcekey=0-taYwPSGaiCrRGPYgih78Sw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKazlReUhMc0JzbG8&resourcekey=0-taYwPSGaiCrRGPYgih78Sw" width="240" alt="1974 - M465 - P001 - Title Page.jpg"></a><br><sub>1974|7 · P001 - Title Page</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbW5JdEN2QWJlYlE/view?resourcekey=0-4tlXPCcfnpZm7pbY6-h2NQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbW5JdEN2QWJlYlE&resourcekey=0-4tlXPCcfnpZm7pbY6-h2NQ" width="240" alt="1974 - M465 - P003 - 1-1.jpg"></a><br><sub>1974|7 · P003 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX2djZmRENVZwMFE/view?resourcekey=0-gbfWL9h0feMxUxM7lD3-xA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX2djZmRENVZwMFE&resourcekey=0-gbfWL9h0feMxUxM7lD3-xA" width="240" alt="1974 - M465 - P004 - 1-2.jpg"></a><br><sub>1974|7 · P004 - 1-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcHludHdFRlk2ZTQ/view?resourcekey=0-qbLDFGyp3tIP17zL5dY3pQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcHludHdFRlk2ZTQ&resourcekey=0-qbLDFGyp3tIP17zL5dY3pQ" width="240" alt="1974 - M465 - P005 - 2-1.jpg"></a><br><sub>1974|7 · P005 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS05iSzE2YW16b0U/view?resourcekey=0-t91En2nQgt-NfJ27ZVlwTg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS05iSzE2YW16b0U&resourcekey=0-t91En2nQgt-NfJ27ZVlwTg" width="240" alt="1974 - M465 - P005 - 2-2.jpg"></a><br><sub>1974|7 · P005 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeXVldG5odk1nYzg/view?resourcekey=0-BsAsAQ-Ma3ekttwGFNM2yw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeXVldG5odk1nYzg&resourcekey=0-BsAsAQ-Ma3ekttwGFNM2yw" width="240" alt="1974 - M465 - P006 - 3-1.jpg"></a><br><sub>1974|7 · P006 - 3-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSTV1UHByS0FuM28/view?resourcekey=0-n_aoHRjRrZzilPU_1JTvDw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSTV1UHByS0FuM28&resourcekey=0-n_aoHRjRrZzilPU_1JTvDw" width="240" alt="1974 - M465 - P007 - 3-2.jpg"></a><br><sub>1974|7 · P007 - 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLVc0Uy1aQUJ2eVU/view?resourcekey=0-dax5mBqH5p-pLHW190LI9Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLVc0Uy1aQUJ2eVU&resourcekey=0-dax5mBqH5p-pLHW190LI9Q" width="240" alt="1974 - M465 - P008 - 3-3.jpg"></a><br><sub>1974|7 · P008 - 3-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKanQ4cHVvX0REakk/view?resourcekey=0-Zjr33UvIaNFIPfELHHP9Hg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKanQ4cHVvX0REakk&resourcekey=0-Zjr33UvIaNFIPfELHHP9Hg" width="240" alt="1974 - M465 - P009 - 8-109.jpg"></a><br><sub>1974|7 · P009 - 8-109</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWGRrU1hsc3oyR3M/view?resourcekey=0-3x6PyvUO4VPDoXC9DNGPAA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWGRrU1hsc3oyR3M&resourcekey=0-3x6PyvUO4VPDoXC9DNGPAA" width="240" alt="1974 - M465 - P010 - 8-109-1-1.jpg"></a><br><sub>1974|7 · P010 - 8-109-1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdVBteFA5V09KbmM/view?resourcekey=0-HABgyTguTCME4biQGJ5IWQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdVBteFA5V09KbmM&resourcekey=0-HABgyTguTCME4biQGJ5IWQ" width="240" alt="1974 - M465 - P011 - 8-109-1-2.jpg"></a><br><sub>1974|7 · P011 - 8-109-1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa293TDlxWFJIQjA/view?resourcekey=0-dlsRpaOUbKuGvBy6qH9V6Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa293TDlxWFJIQjA&resourcekey=0-dlsRpaOUbKuGvBy6qH9V6Q" width="240" alt="1974 - M465 - P012 - 8-109-1-3.jpg"></a><br><sub>1974|7 · P012 - 8-109-1-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKck0ya24zeDFFdm8/view?resourcekey=0-8PtKGQrP_xn1Ct-4ejGhcA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKck0ya24zeDFFdm8&resourcekey=0-8PtKGQrP_xn1Ct-4ejGhcA" width="240" alt="1974 - M465 - P013 - 8-109-2-1.jpg"></a><br><sub>1974|7 · P013 - 8-109-2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTjl2WFNtcS0zZzQ/view?resourcekey=0-jpyA44m0lHWbdSFZNfoBig" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTjl2WFNtcS0zZzQ&resourcekey=0-jpyA44m0lHWbdSFZNfoBig" width="240" alt="1974 - M465 - P014 - 8-109-2-2.jpg"></a><br><sub>1974|7 · P014 - 8-109-2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcURXV0x4QzhUTkU/view?resourcekey=0-JHQNGZ2iPSmHfzL7eyttvg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcURXV0x4QzhUTkU&resourcekey=0-JHQNGZ2iPSmHfzL7eyttvg" width="240" alt="1974 - M465 - P015 - 8-109-2-3.jpg"></a><br><sub>1974|7 · P015 - 8-109-2-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM0w1NXhZb0NHUEk/view?resourcekey=0-6XA95zGD6dwHscUk7gB80A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM0w1NXhZb0NHUEk&resourcekey=0-6XA95zGD6dwHscUk7gB80A" width="240" alt="1974 - M465 - P016 - 8-109-2-4.jpg"></a><br><sub>1974|7 · P016 - 8-109-2-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUmp0UHR3c1N0elE/view?resourcekey=0-XYgz2J5QzJC-tROf9xclOQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUmp0UHR3c1N0elE&resourcekey=0-XYgz2J5QzJC-tROf9xclOQ" width="240" alt="1974 - M465 - P017 - 8-109-2-5.jpg"></a><br><sub>1974|7 · P017 - 8-109-2-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSVc1WXR6bXdZRUU/view?resourcekey=0-IpQfAyFSV_u_m7S-nlodAQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSVc1WXR6bXdZRUU&resourcekey=0-IpQfAyFSV_u_m7S-nlodAQ" width="240" alt="1974 - M465 - Reverb Module.pdf"></a><br><sub>1974|7 · Reverb Module</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ0pFTjBNSXppNFE/view?resourcekey=0-UkfQe7JQK6c7sRyvRC3aTA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ0pFTjBNSXppNFE&resourcekey=0-UkfQe7JQK6c7sRyvRC3aTA" width="240" alt="1977 - M465 - 3.jpg"></a><br><sub>1977|10 · 3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb2FzaEx3TFBGUWs/view?resourcekey=0-YTF6wyEY0a4SVvSFNApBUw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb2FzaEx3TFBGUWs&resourcekey=0-YTF6wyEY0a4SVvSFNApBUw" width="240" alt="1979 - M465 - P002.jpg"></a><br><sub>1979|12 · P002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQWc1ZkFPRjVIcEE/view?resourcekey=0-3hgyLf_R1VYzzw2Bx5Z8Fg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQWc1ZkFPRjVIcEE&resourcekey=0-3hgyLf_R1VYzzw2Bx5Z8Fg" width="240" alt="1979 - M465 - Reverb Module.pdf"></a><br><sub>1979|12 · Reverb Module</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1974 - M465 - 4-109-02-001.kicad_sch](KICAD/1974%20-%20M465%20-%204-109-02-001.kicad_sch)
- [1974 - M465 - 4-109-02-004 - BOOSTER AMPLIFIER ICKD.kicad_sch](KICAD/1974%20-%20M465%20-%204-109-02-004%20-%20BOOSTER%20AMPLIFIER%20ICKD.kicad_sch)
- [1974 - M465 - 465-01-001.kicad_sch](KICAD/1974%20-%20M465%20-%20465-01-001.kicad_sch)
- [1974 - M465 - 465-02-001 - AND ALL CAPACITO UNLESS OTHEPISE SPECIFIED.kicad_sch](KICAD/1974%20-%20M465%20-%20465-02-001%20-%20AND%20ALL%20CAPACITO%20UNLESS%20OTHEPISE%20SPECIFIED.kicad_sch)
- [1974 - M465 - 465-02-001 - REVERB MODULE ISCALE SCHEMATIC.kicad_sch](KICAD/1974%20-%20M465%20-%20465-02-001%20-%20REVERB%20MODULE%20ISCALE%20SCHEMATIC.kicad_sch)
- [1974 - M465 - 465-02-001.kicad_sch](KICAD/1974%20-%20M465%20-%20465-02-001.kicad_sch)
- [1974 - M465 - 74042-02-011.kicad_sch](KICAD/1974%20-%20M465%20-%2074042-02-011.kicad_sch)
- [1974 - M465 - 8-109-02-001 - NOMINAL VALUE.kicad_sch](KICAD/1974%20-%20M465%20-%208-109-02-001%20-%20NOMINAL%20VALUE.kicad_sch)
- [1974 - M465 - 8-109-02-001 - RII RIZ IGK.kicad_sch](KICAD/1974%20-%20M465%20-%208-109-02-001%20-%20RII%20RIZ%20IGK.kicad_sch)
- [1974 - M465 - 8-109-02-004 - NOMINAL VALUE (2).kicad_sch](KICAD/1974%20-%20M465%20-%208-109-02-004%20-%20NOMINAL%20VALUE%20(2).kicad_sch)
- [1974 - M465 - 8-109-02-004 - NOMINAL VALUE.kicad_sch](KICAD/1974%20-%20M465%20-%208-109-02-004%20-%20NOMINAL%20VALUE.kicad_sch)
- [1974 - M465 - B 465-01-001 - M465 - REVERB MODULE - FUNCTIONAL DIAGRAM.kicad_sch](KICAD/1974%20-%20M465%20-%20B%20465-01-001%20-%20M465%20-%20REVERB%20MODULE%20-%20FUNCTIONAL%20DIAGRAM.kicad_sch)
- [1974 - M465 - Reverb Module p2.kicad_sch](KICAD/1974%20-%20M465%20-%20Reverb%20Module%20p2.kicad_sch)
- [1974 - M465 - Reverb Module p28.kicad_sch](KICAD/1974%20-%20M465%20-%20Reverb%20Module%20p28.kicad_sch)
- [1974 - M465 - Reverb Module p32.kicad_sch](KICAD/1974%20-%20M465%20-%20Reverb%20Module%20p32.kicad_sch)
- [1975 - M465 - 465-01-001 - DIRECT OUT PAN.kicad_sch](KICAD/1975%20-%20M465%20-%20465-01-001%20-%20DIRECT%20OUT%20PAN.kicad_sch)
- [1977 - 465-01-001 - REVERB MODULE FUNCTIONAL DIAGRAM - DRN P. MAHONEY - ENG RKB - ISS 3.kicad_sch](KICAD/1977%20-%20465-01-001%20-%20REVERB%20MODULE%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20P.%20MAHONEY%20-%20ENG%20RKB%20-%20ISS%203.kicad_sch)
- [1978 - 8-109-02-001 - 8-109 BOOSTER AMPLIFIER SCHEMATIC - DRN GEB - ENG MRW - ISS 1.kicad_sch](KICAD/1978%20-%208-109-02-001%20-%208-109%20BOOSTER%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20GEB%20-%20ENG%20MRW%20-%20ISS%201.kicad_sch)
- [1978 - 8-109-02-004 - 8-109C BOOSTER AMPLIFIER SCHEMATIC - DRN GEB - ENG MRW - ISS 1.kicad_sch](KICAD/1978%20-%208-109-02-004%20-%208-109C%20BOOSTER%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20GEB%20-%20ENG%20MRW%20-%20ISS%201.kicad_sch)
- [1979 - M465 - Reverb Module p2.kicad_sch](KICAD/1979%20-%20M465%20-%20Reverb%20Module%20p2.kicad_sch)
- [1979 - M465 - Reverb Module p21.kicad_sch](KICAD/1979%20-%20M465%20-%20Reverb%20Module%20p21.kicad_sch)
- [1979 - M465 - Reverb Module p23.kicad_sch](KICAD/1979%20-%20M465%20-%20Reverb%20Module%20p23.kicad_sch)
- [1979 - M465 - Reverb Module p28.kicad_sch](KICAD/1979%20-%20M465%20-%20Reverb%20Module%20p28.kicad_sch)
- [1979 - M465 - Reverb Module p32.kicad_sch](KICAD/1979%20-%20M465%20-%20Reverb%20Module%20p32.kicad_sch)
- [1982 - 465-02-003 - M465B REVERB MODULE SCHEMATIC - DRN JEI - ENG PA - ISS 2.kicad_sch](KICAD/1982%20-%20465-02-003%20-%20M465B%20REVERB%20MODULE%20SCHEMATIC%20-%20DRN%20JEI%20-%20ENG%20PA%20-%20ISS%202.kicad_sch)
- [1982 - 465-02-003 - M465B REVERB MODULE SCHEMATIC - DRN JET - ENG PA - ISS 2.kicad_sch](KICAD/1982%20-%20465-02-003%20-%20M465B%20REVERB%20MODULE%20SCHEMATIC%20-%20DRN%20JET%20-%20ENG%20PA%20-%20ISS%202.kicad_sch)
- [19xx - M465 - DOC - 465-02-001 - NOIES AND ALL CAPACITORS INAF ALL RESISTORS.kicad_sch](KICAD/19xx%20-%20M465%20-%20DOC%20-%20465-02-001%20-%20NOIES%20AND%20ALL%20CAPACITORS%20INAF%20ALL%20RESISTORS.kicad_sch)
- [M465.kicad_sym](KICAD/M465.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
