# GB Repeaters <img src="https://raw.githubusercontent.com/AxiomYT/repeaters/master/AMSAT-Logo-only.jpg" width="200" height="60" align="right"/>

This is a JSON formatted list of amateur radio repeaters.
Please submit pull requests with any updates.

Format:
```json
  {
    "NAME": "GB3ED",
    "CHANNEL": "RB14",
    "TX": 433.35,
    "RX": 434.95,
    "MODE": "AD",
    "LOCATION": "IO85JW",
    "LOCATION NAME": "EDINBURGH",
    "AREA": "SCO",
    "CTCSS": "94.8Hz/DMR1",
    "WEBSITE": "https://www.dmrscotland.co.uk/",
    "KEEPER": "GM4GZW",
    "LATITUDE": 55.94,
    "LONGITUDE": -3.21,
    "STATUS": "OPERATIONAL"
  },
```

# Satellites

This is a JSON formatted list of amateur radio satellites.
Please submit pull requests with any updates.

Format:
```JSON
    {
    "Satellite": "AO-1 (Oscar-1)",
    "Number": 214,
    "Uplink": "",
    "Downlink": "",
    "Beacon": 144.983,
    "Mode": "CW",
    "Callsign": "",
    "Status": "r"
  },
```

# Key

## Satellite Status

* (\*) - Active  
* D - Deep space  
* F - Failure  
* I - Inactive  
* N	- Non-amateur  
* R - Re-entered  
* T - To be launched  
* U - Unknown  
* W - Weather sat  


## Modes
* A - Analogue Voice
* D - D-STAR
* AD - Analogue + D-star
* M - DMR
* F - Yaesu Fusion
* P - P25
* N - NXDN
* T - TV
* X - AX25

## Area

* WM - Wales and Marches
* SE - South-East, England
* MID - Midlands, England
* SW - South-West, England
* SCO - Scotland
* NOR - North England
* NI - Northern Ireland

## Channel

[Channelisation Key](https://github.com/AxiomYT/repeaters/blob/master/Channelisation%20Key.xlsx)

## RSGB Band Plan

[Band Plan](https://github.com/AxiomYT/repeaters/blob/master/rsgb_band_plan_2019%20(1).xls)

## Packet List

[Digital Packet List](https://github.com/AxiomYT/repeaters/blob/master/packetlist.xls)

## GB3 Callsign Allocation

[GB3✗✗ Callsign Allocation](https://github.com/AxiomYT/repeaters/blob/master/GH3%20Callsign%20Allocation.xlsx)

# Acknoledgement

Feel free to reference the files directly from your app. E.g. https://raw.githubusercontent.com/AxiomYT/repeaters/master/gb.json
