# Gedcom Samples
 A collection of  GED files for use in GEDCOM projects.  Useful for performance testing, as well as different output from different GEOCOM file generators.

GED Name | # People | Timeframe | Addresses | Unique Surnames | Author | Soure
---      | ---:      |---:        |---:        |---: | --- | ---
[basic](basic.ged) | 5 | 1923-2006 | 10 | 3 | Darren Jeffrey | Legacy (Fictional)
[Bronte](bronte.ged) | 14 | 1744-1861 | 7 | 6 | |webtreeprint
[input](input.ged)  | 15 | ?-? | 12 | 8 | Louis Mallez | hand coded
[shakespeare](shakespeare.ged) | 31 | 1490-1674 | 4 | 10 | |webtreeprint
[bourbon](sample-bourbon/bourbon.ged) | 303| 1601-1775 | 66 | 81 | Yannick VOYEAUD | ANCESTRIS
[kennedy](sample-kennedy/kennedy.ged) | 208 | 1727-1999 | 83 | 73 | |  ANCESTRIS
[royal92](royal92.ged) |3,010 |534-1992 |669 | 421 |Denis R. Reid|Personal Ancestral 2.2
[pres2020](pres2020.ged) |2,322 |1016-2018 |842 |873 | Paul E Stobbe |Family Tree Maker
[IvarKingOfDublin](ivar/IvarKingOfDublin.ged) | 1,288 | 794-1302 | 563 | 558 | Darren Jeffrey | Legacy / FamilySearch
[WilliamLongsword](longsword/WilliamLongsword.ged) | 203,154 | | | 60,584 | Darren Jeffrey | Legacy / FamilySearch
**External** | 
[xavier](https://github.com/lesfleursdelanuitdev/ligneous-gedcom/blob/main/testdata/xavier.ged) | 312 | 1894-| ||[ligneous-gedcom](https://github.com/lesfleursdelanuitdev/ligneous-gedcom)|Gramps
[tree1](https://github.com/lesfleursdelanuitdev/ligneous-gedcom/blob/main/testdata/tree1.ged) | 1040 | | | |[ligneous-gedcom](https://github.com/lesfleursdelanuitdev/ligneous-gedcom)| webtrees
[gracis](https://github.com/lesfleursdelanuitdev/ligneous-gedcom/blob/main/testdata/gracis.ged) | 580 | | ||[ligneous-gedcom](https://github.com/lesfleursdelanuitdev/ligneous-gedcom)|Gramps
[jeffersondemo](https://github.com/neelsmith/GedCom.jl/blob/main/test/data/jeffersondemo.ged)| 24||||[gedcom.jl](https://github.com/neelsmith/GedCom.jl)|Ancestry.com Family Trees
## basic
A fictional set of families for drawing geo lines across the ocean.

## Bronte
A simple file featuring the Brontë family of writers.
https://en.wikipedia.org/wiki/Bront%C3%AB_family 

## input
France locations with embedded GPS locations

## shakespeare
### William Shakespeare and family
The family tree of the famous author, back to his grandfather Richard.


## pres2020
### US Presidents and their relatives
An excellent collection of the presidents of the US, with their ancestors and descendants. From 1016 to 2018

## bourbon
https://voyeaud.org/Genealogie.php
This includes photos as references to a few of the individuals

## kennedy
### Kennedy Family
Kennedy family from 1727-1999 include their immigration 
This includes photos as references to a few of the individuals

## royal92
### Kings and Queens of Europe
The Kings and Queens of Europe including Great Britain.
This lead to an interesting discovery on github [using Neo4j with Gedcom](https://github.com/neo4j-examples/discoveraurafree/blob/fc19b3ddfba1026ecab83d541216ba994bde6cde/week-18.adoc)

This file contains instances of 12 familial relations which were extracted from royal92.ged, a widely-distributed public domain GEDCOM file containing information on 3,010 individuals and 1,422 families of European royalty. The 12 relations are those used originally in (Hinton 1986).  The data parsed used to convert the code was modified from code distributed on with (Yang et al, 2017).

 Comment from original data source on http://www.daml.org/2001/01/gedcom/ 
 - _royal92.ged is a public domain GEDCOM file containing information on 3010 individuals and 1422 families of European royalty. royal92.daml was produced using ged2daml._

#### From the header:
25 Dec 92

_You may make this Royal GEDCOM available available to whomever.
As you know this is a work in process and have received suggestions,
corrections and additions from all over the planet...
some even who claim to be descended from Charlemange, himself!_

_The weakest part of the Royals is in the French and Spanish lines.
I found that many of the French Kings had multiple mistresses whose
descendants claimed noble titles, and the Throne itself in some
cases.  I have had the hardest time finding good published sources
for French and Spanish Royalty._

_If you do post it to a BBS or send it around, I would appreciate
it if you'd append a message to the effect that I would welcome
comments and suggestions and possible sources to improve
the database._

_Since the Royals had so many names and many titles it was difficult
to "fill in the blanks" with their name.  In the previous version,
I included all their titles, names, monikers in the notes._

_Thanks for your interest.   Denis Reid_


## IvarKingOfDublin
### Ivar King of Dulbin
From 794 to 1302
Ivar King of Dulbin

This was pulled from FamilySearch on Dec 25, 2025 using Legend 10.0.  Manual adjustment of 5 year dates where required to bring the qaulity up.
https://en.wikipedia.org/wiki/%C3%8Dmar

## WilliamLongsword
### William Longsword Count of Rouen
 - 203154 people
 - 90085 Families
 - 65486 Unique Surnames
 - 86071 Locations
 - 531235 Citations
 - 29+ million lines

 From to
https://en.wikipedia.org/wiki/William_Longsword

 People included
- Guillaume 'Longue-Épée' de Normandie comte de Rouen  Known As William Longsword Count of Rouen
- William 'the Conqueror' /of Normandy/
- Richard I 'the Lionheart' (https://en.wikipedia.org/wiki/Richard_I_of_England)
- Richard II Ferte /Fresnel/ [Richard the Good](https://en.wikipedia.org/wiki/Richard_II,_Duke_of_Normandy)
- 681 'Sir' 
- 446 'Lady'
- 5 Kings & 1 Queen
  -  King Magnus Eriksson, Kinga Árpád-házi, Kinga Countess of Oppeln, King Ferdinand II D'Aragon, King Cathal Domhnall O'Riley
Queen Of Armenia

This was pulled from FamilySearch on Dec 28, 2025 using Legend 10.0.  It took 47 hours to geocode (using the maximum of 1 request per second)

