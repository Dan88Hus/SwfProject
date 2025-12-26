Marie wants to go to football games. She starts her own travel agency. Now she wants to de-
velop ABAP programs. Please help her.
- Program 1: Display flights to a specific location and time
- Program 2: Book a specific flight
- Program 3: Cancel a booking

<h6>Remarks:</h6>
- All repository objects come in one package (Name for package ZTG_## e.g.Use-
name DEVM2599 => ZTGM2599)
- Every repository object starts with ZTG_## (e.g. Username DEVM2599 =>
ZTGM2599_DATAELEMENT)
- Develops useful function modules
- Use meaningful messages (success/error)
- Use global data elements

<h4> Program 1: Display flights to a specific location and time</h4>
Name: ZTGM####_FLIGHTS e.g. DEVM2599 ZTGM2599_FLIGHTS

Input

 Parameters:
- SPFLI-CITYTO
- SFLIGHT-FLDATE </br>

Logic:
Show all bookable flights that match the destination and date

Output
- Display as an ALV grid!
- Fields
- SFLIGHT-CARRID
- SFLIGHT-CONNID
- SFLIGHT-FLDATE
- SFLIGHT-PRICE
- SPFLI-COUNTRYFR
- SPFLI-CITYFROM
- SPFLI-AIRPFROM
- SPFLI-COUNTRYTO
- SPFLI -CITYTO
- SPFLI-AIRPTO
- Free seats Business Class (own Dataelement with Label "Free Class B“
and calculate SFLIGH-SEATSMAX_B and SFLIGHT-SEATSOCC_B)
- Free seats first class (own Dataelement with Label "Free Class F“ and cal-
culate SFLIGH-SEATSMAX_F and SFLIGHT-SEATSOCC_F)
- Free seats economy (own Dataelement with Label "Free Class E“ and cal-
culate SFLIGH-SEATSMAX and SFLIGHT-SEATSOCC)
- Free weight (own Dataelement with Label "Free weight" and calculate
SAPLANE-WEIGHT and SBOOK-LUGGWEIGHT
