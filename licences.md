---
title: Sources & licences
permalink: /licences/
description: The astronomy, archaeology and software behind Almanac – Ancient Cycles, and the licences that apply to them.
---

# Sources & licences

Almanac – Ancient Cycles
{: .meta}

Every date and alignment in Almanac is calculated on your iPhone from published astronomy and archaeology. This page lists those sources, as the app does under Personalize → Sources & licences, and reproduces the one open-source licence the app must carry.

## Astronomy

- **Sun, moon, seasons and Julian Day:** Jean Meeus, *Astronomical Algorithms*, 2nd edition (1998).
- **Long-term precession:** Vondrák, Capitaine & Wallace (2011, 2012), via ERFA. See the [ERFA licence](#erfa-licence) below.
- **ΔT, the slowing of Earth's spin:** Espenak & Meeus, *Five Millennium Canon of Solar Eclipses*.
- **Star positions and proper motions:** the Hipparcos catalogue, new reduction (van Leeuwen 2007).
- **The first morning Sirius is seen:** Gautschy (2011).

## Ancient sites

Each alignment's bearing and dates come from the surveys below. In the app, tap "Show the math" on any alignment to see its bearing, horizon height, tolerance and source. Several readings are contested, and the app says so where they are. Where no surveyed bearing has been published, the bearing is calculated and marked as low confidence.

### Stonehenge
Ruggles 1997, *Proceedings of the British Academy* 92, Table 7.

### Newgrange
Patrick 1974, *Nature* 249; Ray 1989, *Nature* 337.

### Maeshowe
Historic Environment Scotland (dates); Reijs, archaeocosmology.org (light window).

### Callanish
Higginbottom & Clay 2016, *Journal of Archaeological Science: Reports*.

### Chimney Rock
Malville, Eddy & Ambruster 1991, *Archaeoastronomy* 16.

### Chichén Itzá
Šprajc & Sánchez Nava 2013, *Estudios de Cultura Maya* 41.

### Teotihuacan
Šprajc 2000, *Latin American Antiquity* 11(4); Dow 1967; Aveni 2001, *Skywatchers*.

### Uaxactún, Group E
Šprajc 2021, *PLOS ONE* 16(4).

### Abu Simbel
Shaltout & Belmonte 2005, *Journal for the History of Astronomy* 36; Weyburne 2021, *ENiM* 14.

### Karnak
Shaltout & Belmonte 2005, *Journal for the History of Astronomy* 36.

### Angkor Wat
Magli 2016, arXiv:1604.05674.

### Machu Picchu
Kościuk & Ziółkowski 2020, *Teka* 16(4); Dearborn & White 1983, *Archaeoastronomy* 5.

### Göbekli Tepe
Magli 2016, *Nexus Network Journal* 18; Dietrich et al. 2013 (dates).

### Warren Field
Gaffney et al. 2013, *Internet Archaeology* 34.

### Goseck Circle
Schlosser, in Bertemes et al. 2004.

### Giza
Spence 2000, *Nature* 408; Rawlins & Pickering 2001, *Nature* 412; Nell & Ruggles 2014; Petrie; Dash; Badawy & Trimble 1964; Bauval 1993; Gantenbrink (shaft angles); Lehner 1985.

## Calendars

- **Maya:** the GMT correlation, 584283, in which the Long Count 13.0.0.0.0 fell on 21 December 2012.
- **Islamic:** the tabular (civil) calendar. Months that begin with an actual sighting of the new crescent can start a day or two apart.
- **Chinese:** modern astronomical rules, with leap months as published today.
- **Dates before 1582:** the Gregorian and Julian calendars extended backwards (proleptic).

## Illustrations

The calendar glyphs, wheels, site drawings and moon phases are schematic teaching illustrations made for Almanac. They are not epigraphic or survey records.

{% comment %}
  Artwork and photo credits go here once each image's source and licence is confirmed:
  the Home artworks, the aerial site overlays and the site photos. See docs/release-checklist.md
  in the app repo. List each one as: title or description, artist or maker, date, holding
  collection or source, and licence (for example "Public domain" or "CC BY-SA 4.0, photo: Name").
{% endcomment %}

## ERFA licence

Almanac's long-term precession is ported from [ERFA](https://github.com/liberfa/erfa) (`eraLtp`, `eraLtpecl`, `eraLtpequ`), which is distributed under the licence below.

```
Copyright (C) 2013-2023, NumFOCUS Foundation.
All rights reserved.

This library is derived, with permission, from the International
Astronomical Union's "Standards of Fundamental Astronomy" library,
available from http://www.iausofa.org.

The ERFA version is intended to retain identical functionality to
the SOFA library, but made distinct through different function and
file names, as set out in the SOFA license conditions.  The SOFA
original has a role as a reference standard for the IAU and IERS,
and consequently redistribution is permitted only in its unaltered
state.  The ERFA version is not subject to this restriction and
therefore can be included in distributions which do not support the
concept of "read only" software.

Although the intent is to replicate the SOFA API (other than
replacement of prefix names) and results (with the exception of
bugs;  any that are discovered will be fixed), SOFA is not
responsible for any errors found in this version of the library.

If you wish to acknowledge the SOFA heritage, please acknowledge
that you are using a library derived from SOFA, rather than SOFA
itself.


TERMS AND CONDITIONS

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions
are met:

1 Redistributions of source code must retain the above copyright
  notice, this list of conditions and the following disclaimer.

2 Redistributions in binary form must reproduce the above copyright
  notice, this list of conditions and the following disclaimer in
  the documentation and/or other materials provided with the
  distribution.

3 Neither the name of the Standards Of Fundamental Astronomy Board,
  the International Astronomical Union nor the names of its
  contributors may be used to endorse or promote products derived
  from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
"AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS
FOR A PARTICULAR PURPOSE ARE DISCLAIMED.  IN NO EVENT SHALL THE
COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT,
INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING,
BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT
LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN
ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.
```
