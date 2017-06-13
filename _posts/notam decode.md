itle         : 民航常用的网站
Author        : 我有快乐
Logo          : True

[TITLE]

# Notam Decode
NOTAM start life as messages on the Aeronautical Fixed System (AFS). They are received centrally at the UK NOTAM office at London Heathrow from originators within the UK and from foreign NOTAM offices. AIS staff check and edit the NOTAM if necessary and
they are then placed in the transmit queue for transmission to all UK NOTAM recipients. T
hese include ATC offices, some airlines, briefing services etc.

There is no central world-wide NOTAM database, databases are built up individually by users from the incoming message stream. ICAO NOTAM format

The format of NOTAM is defined in Annex 15 to the International Convention on Civil Aviation. An explanation of the format can be found here. Here is a typical NOTAM and its decode.

A1484/02 NOTAMN
Q) EGTT/QMRXX/IV/NBO/A/000/999/5129N00028W005
A) EGLL
B) 0208231540
C) 0210310500 EST
E) RWY 09R/27L DUE WIP NO CENTRELINE, TDZ OR SALS LIGHTIN
G AVBL

Notam Decoder

A1484/02 – one letter to indicate the Series, a 4-digit NOTAM number followed by a stroke and two digits to indicate the year.

NOTAMN – Suffix N Indicates this is a new NOTAM. Other options are R for NOTAM replacing another or C for one cancelling anot
Q) EGTT/QMRXX/IV/NBO/A/000/999/5129N00028W005

This is the “Q” or qualifier line, it always starts Q) and contains the following fields, each separated by a stroke.FIR (here EGTT, London FIR)

NOTAM Code, a 5 letter code starting with Q, defined in Annexe 15. Here 
 QMR indicates that it concerns a Runway. 
 XX indicates that remaining detail is in Plain Language. In this particular case the text shows that certain runway lighting is unavailable. Strictly speaking under ICAO rules this should have appeared as separate NOTAM for each type of lighting. 
 QLCAS is the code for centreline lighting u/s 
 QLZAS is the code for Touch Down Zone lighting u/s and 
 QLAAS is the code for Approach Lighting u/s (note in all cases AS indicates unserviceable). 

The use of QMRXX here is a sensible compromise that reduces the number of NOTAM from three to one. A full list of codes is included in ICAO document 8126 (Aeronautical Info rmation Services Manual).

 IV – Indicates that this is significant for IFR and VFR traffic 
 NBO – indicates for immediate attention of aircraft operators, for inclusion in PIB’s and Operationally significant for IFR flights

 * A – Indicates scope, here Aerodrome, others are E (en-route) or
 * W (nav warning)000/999 – lower and upper limits expressed as a flight leve his case it has been left as the default as it is not applicable.
   5129N00028W005 – Indicates the geographical centre and radius of influence, always this number of digits. In this case the radius is
5 n.m.

 A) EGLL – ICAO indicator of the aerodrome or FIR (London Heathrow) can include more than one FIR
 B) 0208231540 – Date/time group (UTC) when this NOTAM becomes effective
 C) 0210310500 EST – Date/time group (UTC) when the NOTAM ceases to be effective. Note “EST” means “estimated” (NOT Eastern
Standard Time!). All NOTAM with EST remain in force until cancelled or replaced.
 E) RWY 09R/27L DUE WIP NO CENTRELINE, TDZ OR SALS LIGHTING AVBL – text of the notam using ICAO abbreviations.Decode of this is “Runway 09/27 due to work in progress no centreline, touchdown zone or simple approach lighting system available”

Here’s the whole thing again

A1484/02 NOTAMN
Q) EGTT/QMRXX/IV/NBO/A/000/999/5129N00028W005

A) EGLL

B) 0208231540

C) 0210310500 EST

E) RWY 09R/27L DUE WIP NO CENTRELINE, TDZ OR SALS LIGHTIN

G AVBL

and here’s the same thing as it appears in the PIB produced by ANAISAGA : FROM 02/08/23 15:40 TO 02/10/31 05:00 EST A1484/02
E)RWY 09R/27L DUE WIP NO CENTRELINE, TDZ OR SALS LIGHTING AVBL

You can see that the Q line is omitted entirely, A) has been stripped out because it appears as the header to the section and B) and C) have been reformatted and placed in the first line. AGA has been derived from the Q Code “QMR” (see Annex 15)

