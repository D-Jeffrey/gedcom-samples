# Gedcom Samples
 A set of GED files for GEDCOM projects, useful for performance testing and comparing outputs from various GEDCOM generators. This collection also features `geo_code.csv` files compatible with [geo_gedcom](https:github.comcolin0brassgeo_gedcom) and [gedcom-to-visualmap](https:github.comD-Jeffreygedcom-to-visualmap).  The geo_code.csv has a timestamp, so if you are leveraging it wiht geocom-to-visualmap then check the `Cache Only` checkbox for a quick load within the need to reverifying the addresses.

This included 'Famous Family Trees'.

GED Name | # People | Timeframe | Addresses | Unique Surnames | Author | Soure
---      | ---:      |---:        |---:        |---: | --- | ---
[basic](basic.ged) | 5 | 1923-2006 | 10 | 3 | Darren Jeffrey | Legacy (Fictional)
[Bronte](bronte.ged) | 14 | 1744-1861 | 7 | 6 | |webtreeprint
[input](input.ged)  | 15 | ?-? | 12 | 8 | Louis Mallez | hand coded
[shakespeare](shakespeare.ged) | 31 | 1490-1674 | 4 | 10 | |webtreeprint
[bach](bach.ged) | 33 | 1550-1871 | 0 | 8 | PAF 2.2
[bourbon](sample-bourbonbourbon.ged) | 303| 820-1775 | 66 | 81 | Yannick VOYEAUD | ANCESTRIS
[kennedy](sample-kennedykennedy.ged) | 208 | 1727-1999 | 83 | 73 | |  ANCESTRIS
[washington](washingtonwashington.ged) | 529 | 1391-1799 | 301 | 88| | FamilyOrigins 
[IvarKingOfDublin](ivarIvarKingOfDublin.ged) | 1,288 | 794-1302 | 563 | 558 | Darren Jeffrey | Legacy  FamilySearch
[pres2020](prespres2020.ged) |2,322 |1016-2018 |842 |873 | Paul E Stobbe |Family Tree Maker
[royal92](royalroyal92.ged) |3,010 |534-1992 |669 | 421 |Denis R. Reid|Personal Ancestral 2.2
[Queen](queenQueen.ged) |4,683 |4004BC-1926|871|1024|M M Wardle| RootsMagic 8
[Habsburg](habsHabsburg.ged) |34,020|1-2007|6722|7902|| Family Tree Maker 20
[WilliamLongsword](longswordWilliamLongsword.ged) | 203,154 | 860-2020 | 60,584 | 57040| Darren Jeffrey | Legacy  FamilySearch
**GED files in other Github** | | |||**Repo**
[xavier](https:github.comlesfleursdelanuitdevligneous-gedcomblobmaintestdataxavier.ged) | 312 | 1894-| ||[ligneous-gedcom](https:github.comlesfleursdelanuitdevligneous-gedcom)|Gramps
[tree1](https:github.comlesfleursdelanuitdevligneous-gedcomblobmaintestdatatree1.ged) | 1040 | | | |[ligneous-gedcom](https:github.comlesfleursdelanuitdevligneous-gedcom)| webtrees
[gracis](https:github.comlesfleursdelanuitdevligneous-gedcomblobmaintestdatagracis.ged) | 580 | | ||[ligneous-gedcom](https:github.comlesfleursdelanuitdevligneous-gedcom)|Gramps
[jeffersondemo](https:github.comneelsmithGedCom.jlblobmaintestdatajeffersondemo.ged)| 24||||[gedcom.jl](https:github.comneelsmithGedCom.jl)|Ancestry.com Family Trees
## basic
Imaginary families used for testing oceanic geolines and family relationships.

## Bronte
This GED file provides a straightforward genealogical record of the Brontë family, renowned for producing acclaimed writers such as Charlotte, Emily, and Anne Brontë. You can expect to find information on Patrick Brontë, the family patriarch, as well as the siblings and possibly additional relatives, offering a concise view of the family structure that influenced some of English literature’s most celebrated works.
https:en.wikipedia.orgwikiBront%C3%AB_family 

## input
The GED file includes various locations in France, each accompanied by embedded GPS coordinates.

## shakespeare
### William Shakespeare and family
The Shakespeare GED file offers a comprehensive family tree of William Shakespeare, tracing his lineage back to his grandfather Richard Shakespeare. This genealogical record highlights key family members, including William’s father, John Shakespeare, and mother, Mary Arden, as well as siblings and descendants. Explore the ancestry and familial context of William Shakespeare, gaining insight into the environment that influenced his works and legacy.
https:www.shakespeare.org.ukexplore-shakespeareshakespediawilliam-shakespearewilliam-shakespeares-family


## pres2020
### US Presidents and their relatives
The Pres2020 GED file presents a comprehensive compilation of U.S. presidents along with their ancestors and descendants, spanning from 1016 to 2018. This resource meticulously documents familial relationships, providing detailed information such as names, birth and death dates, and connections among relatives. In addition to tracing presidential lineages, the file highlights significant family milestones and may include notable events, locations, and migration patterns that shaped the history of the presidential families.

https:www.ourfamtree.orgattachList_of_US_Presidents_by_Genealogical_Relationship.pdf
https:en.wikipedia.orgwikiAncestral_background_of_presidents_of_the_United_States

## bourbon
https:voyeaud.orgGenealogie.php
This includes photos as references to a few of the individuals

## kennedy
### Kennedy Family
Kennedy family from 1727-1999 include their immigration 
This includes photos as references to a few of the individuals
https:en.wikipedia.orgwikiKennedy_family

## royal92
### Kings and Queens of Europe

The Kings and Queens of Europe including Great Britain.

AKA `famous family trees/royalty/Royal92-Famous+European+Royalty+Gedcom.ged`

This lead to an interesting discovery on github [using Neo4j with Gedcom](https:github.comneo4j-examplesdiscoveraurafreeblobfc19b3ddfba1026ecab83d541216ba994bde6cdeweek-18.adoc)

This file contains instances of 12 familial relations which were extracted from royal92.ged, a widely-distributed public domain GEDCOM file containing information on 3,010 individuals and 1,422 families of European royalty. The 12 relations are those used originally in (Hinton 1986).  The data parsed used to convert the code was modified from code distributed on with (Yang et al, 2017).

 Comment from original data source on http:www.daml.org200101gedcom 
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

## washington
### George Washington and descendants
George Washington and descendants GED file
This GEDCOM file contains a comprehensive genealogical record of George Washington, the first President of the United States, and his extended family. The file documents his ancestors, immediate family members, and descendants through detailed birth, marriage, and death records. This _had_ a lot of post death BAPL records.

- https:www.archives.comgenealogypresident-washington.html
- https:www.mountvernon.orggeorge-washingtonfamily
- https:en.wikipedia.orgwikiWashington_family


## IvarKingOfDublin
### Ivar King of Dulbin
This GEDCOM file, sourced from FamilySearch, offers a thorough genealogical record of Ivar, King of Dublin, charting his lineage and descendants from 794 to 1302. The file documents significant events in his life and reign, as well as his family relationships through detailed birth, marriage, and death entries. Additional notes in the file provide context about Ivar's titles, alternate names, and relevant historical events, delivering valuable insight for researchers interested in the Dublin royal lineage.

This was pulled from FamilySearch on Dec 25, 2025 using Legend 10.0.  Manual adjustment of 5 year dates where required to bring the qaulity up.

https:en.wikipedia.orgwiki%C3%8Dmar

## Queen
### Queen of the World
Queens along with King

- Queen of England
- Queen of the Britons
- Gurandukht (Queen) of ABKHAZIA
- Blanche d' ARTOIS Regent Queen of NAVARRE
- Athalia of ISRAEL (9th Queen) of JUDAH
- Azubah (Queen) of JUDEA
- Queen of the SWEDES
- Audur IVARSDOTTIR (Queen) of HOLMGARD
- Danpi (Queen of DENMARK)
- Henuttawy (I; Queen) of EGYPT (Hanttwy)
- Baktwernel (Queen) of EGYPT
- Nubkhas (Queen) of EGYPT
- Mentuhotep (Queen) of EGYPT
- Sancha Alfonsez (Queen) of LEON
- Cleopatra Selene (Queen) of LIBYA
- Cleopatra VII (Queen) of EGYPT
- Libya (Queen) of EGYPT
- Theoclea ZENOBIA (Queen) of PALMYRA
- Cleopatra I of SYRIA (Queen of EGYPT) (al-SURIYAH)
- Queen Amalaberge "Queen of Thurgia" Ostrogoths
- Queen Frigida of Ossory
- Emma `the Flower' of NORMANDY (Regent Queen of ENGLAND)
- Canute `the Great' (King) of DENMARK & ENGLAND
- Gyrid (Gunhilda Cyrid Gynrithe) (Queen) OLAFSDOTTIR
- Anna Morgause (Queen) of GODODDIN
- Boadicea (Queen) of ICENIANS
#### Kings
- Mellobaude de Toxandrie, King of Worms
- Chilperich King Of Burgundy
- Gundicus King Of Burgundy
- Atanarich King Of The West Goths
- Charibert I King of Franks
- I King Of Germany Henry
- King Of Italy Carloman
- Donnchad KING OF MUNSTER
- King Of Neustria & Burgundy Theuderic
- Coel I King Cole
- Alphonso II King of Aragon The Chaste Berenger
- King Wihtgar of the Isles of Wright
- King Maelaithgen of Ossory
- Anmchad Mac Con Cherca King of Ossory
- Faelan MacCrundmael King of Osraige (Ossory)
- King Dunghal Macfearghal
- King Daimine, Rí na Orgaill, mac Caipre Argait
- Bernard I CAROLING King of Italy
- Genebald King Of The Salic Franks
- Dagobert II King Of The Salic Franks
- Donnchad KING OF MUNSTER
- King Of Neustria & Burgundy Theuderic
- Owain Finddu ap Macsen King of Cernyw
- David King of Israel
- Solomon King of Israel
- Jacob King of Goshen
- Nahor King of Ur and Agade
- Serug King of Ur and Agade
- Reu King of Lagash
- Peleg King of Babylon
- Eber King of Babylon
- Coel I King Cole
- Ithon ap CAMBER King in BRITAIN
- Sancho II Abarca GARCES King of PAMPLONA
- Owain ap Gruffudd  King of Gwynedd, north Wales
- Gruffudd ap Cynan  King of Gwynedd
- WALTER I  Lord Giffard Earl Buckingham De BOLEBEC
- Bridget PAKINGTON

## Habsburg
### Habsburg
Germany 

https://habsburg-dynasty.com/family-tree/


## WilliamLongsword
### William Longsword Count of Rouen
 - 203154 people
 - 90085 Families
 - 65486 Unique Surnames
 - 86071 Locations
 - 531235 Citations
 - 29+ million lines

 From 860 to 2020 but not a complete record of all linage during that time.
https:en.wikipedia.orgwikiWilliam_Longsword

 People included
- Guillaume 'Longue-Épée' de Normandie comte de Rouen  Known As William Longsword Count of Rouen
- William 'the Conqueror' of Normandy
- [Richard I 'the Lionheart'](https:en.wikipedia.orgwikiRichard_I_of_England)
- Richard II Ferte Fresnel [Richard the Good](https:en.wikipedia.orgwikiRichard_II,_Duke_of_Normandy)
- 681 'Sir' 
- 446 'Lady'
- 5 Kings & 1 Queen
  - King Magnus Eriksson
  - Kinga Árpád-házi
  - Kinga Countess of Oppeln
  - King Ferdinand II D'Aragon
  - King Cathal Domhnall O'Riley
  - Queen Of Armenia

This was pulled from FamilySearch on Dec 28, 2025 using Legend 10.0 which too about 2 days to get this extraction.  

This file is so far the hardest to process, taking about 47 hours to geocode (using the maximum of 1 request per second) and resulting in a hit rate of 56%.  It also identify bad date processing practices (for example if the year is not include, a date exists wihtout the year).

