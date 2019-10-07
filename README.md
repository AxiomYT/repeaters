# GB Repeaters

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
    "WEBSITE": "https://www.dmrscotland.co.uk/survey/",
    "KEEPER": "GM4GZW",
    "LATITUDE": 55.94,
    "LONGITUDE": -3.21,
    "STATUS": "OPERATIONAL"
  },
```

# Key

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

Feel free to reference the files directly from your app. E.g. https://raw.githubusercontent.com/AxiomYT/repeaters/master/gb.json
