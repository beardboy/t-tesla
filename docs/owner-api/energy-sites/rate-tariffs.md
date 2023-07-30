# Rate Tariffs

## GET `api/1/energy_sites/{energy_site_id}/rate_tariffs`

Get a list of Time of Use plans provided by power companies.

### Response Body

```json
{
    "response": [
        {
            "tariffID": "CCA-SCE-PRIME",
            "description": "Clean Power Alliance - TOU-PRIME",
            "utility": "Clean Power Alliance",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "CCA-SCE-TOU-D4",
            "description": "Clean Power Alliance - TOU-D-4-9",
            "utility": "Clean Power Alliance",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "CCA-SCE-TOU-D5",
            "description": "Clean Power Alliance - TOU-D-5-8",
            "utility": "Clean Power Alliance",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "CPSF-E-TOU-A",
            "description": "Clean Power SF - E-TOU-A",
            "utility": "Clean Power SF",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "CPSF-E-TOU-B",
            "description": "Clean Power SF - E-TOU-B",
            "utility": "Clean Power SF",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "CPSF-E-TOU-C",
            "description": "Clean Power SF - E-TOU-C",
            "utility": "Clean Power SF",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "CPSF-E-TOU-D",
            "description": "Clean Power SF - E-TOU-D",
            "utility": "Clean Power SF",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "CPSF-EV2-A",
            "description": "Clean Power SF - EV2-A",
            "utility": "Clean Power SF",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "LADWP-R-1-A",
            "description": "Los Angeles Department of Water & Power - LADWP-R-1-A",
            "utility": "Los Angeles Department of Water & Power",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "LADWP-R-1-B",
            "description": "Los Angeles Department of Water & Power - LADWP-R-1-B",
            "utility": "Los Angeles Department of Water & Power",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "MCE-E-TOU-A",
            "description": "Marin Clean Energy (MCE) - E-TOU-A",
            "utility": "Marin Clean Energy",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "MCE-E-TOU-B",
            "description": "Marin Clean Energy (MCE) - E-TOU-B",
            "utility": "Marin Clean Energy",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "MCE-E-TOU-C",
            "description": "Marin Clean Energy (MCE) - E-TOU-C",
            "utility": "Marin Clean Energy",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "MCE-EV2-A",
            "description": "Marin Clean Energy (MCE) - EV2-A",
            "utility": "Marin Clean Energy",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "PCE-E-TOU-A",
            "description": "Peninsula Clean Energy - E-TOU-A",
            "utility": "Peninsula Clean Energy",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "PCE-E-TOU-B",
            "description": "Peninsula Clean Energy - E-TOU-B",
            "utility": "Peninsula Clean Energy",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "PCE-E-TOU-C",
            "description": "Peninsula Clean Energy - E-TOU-C",
            "utility": "Peninsula Clean Energy",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "PCE-EV2-A",
            "description": "Peninsula Clean Energy - EV2-A",
            "utility": "Peninsula Clean Energy",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "PECO-R",
            "description": "Residential",
            "utility": "PECO Energy Co",
            "country": "US",
            "state": "PA"
        },
        {
            "tariffID": "PECO-R-H",
            "description": "Residential - Electric Heat",
            "utility": "PECO Energy Co",
            "country": "US",
            "state": "PA"
        },
        {
            "tariffID": "PECO-R-TOU",
            "description": "Residential - Time of use",
            "utility": "PECO Energy Co",
            "country": "US",
            "state": "PA"
        },
        {
            "tariffID": "PEPCO-R",
            "description": "Residential",
            "utility": "Potomac Electric Power Co",
            "country": "US",
            "state": "DC"
        },
        {
            "tariffID": "PEPCO-R-PIV",
            "description": "Residential - Plug-in Vehicle Charging",
            "utility": "Potomac Electric Power Co",
            "country": "US",
            "state": "DC"
        },
        {
            "tariffID": "PGE-E-TOU-A",
            "description": "Pacific Gas & Electric Co - E-TOU-A",
            "utility": "Pacific Gas & Electric Co",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "PGE-E-TOU-B",
            "description": "Pacific Gas & Electric Co - E-TOU-B",
            "utility": "Pacific Gas & Electric Co",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "PGE-E-TOU-C",
            "description": "Pacific Gas & Electric Co - E-TOU-C",
            "utility": "Pacific Gas & Electric Co",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "PGE-E-TOU-D",
            "description": "Pacific Gas & Electric Co - E-TOU-D",
            "utility": "Pacific Gas & Electric Co",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "PGE-EV-B-TOU",
            "description": "Residential - Time of Use, Plug-In Electric Vehicle (NEM 2.0)",
            "utility": "Pacific Gas & Electric Co",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "PGE-EV2-A",
            "description": "Pacific Gas & Electric Co - EV2-A",
            "utility": "Pacific Gas & Electric Co",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "POGE-7",
            "description": "Residential",
            "utility": "Portland General Electric Co",
            "country": "US",
            "state": "OR"
        },
        {
            "tariffID": "POGE-7-TOU",
            "description": "Residential - Time of Use",
            "utility": "Portland General Electric Co",
            "country": "US",
            "state": "OR"
        },
        {
            "tariffID": "SCE-TOU-D-4_9",
            "description": "Southern California Edison Co - TOU-D-4-9",
            "utility": "Southern California Edison Co",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "SCE-TOU-D-5_8",
            "description": "Southern California Edison Co - TOU-D-5-8",
            "utility": "Southern California Edison Co",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "SCE-TOU-PRIME",
            "description": "Southern California Edison Co - TOU-PRIME",
            "utility": "Southern California Edison Co",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "SCL-RSB",
            "description": "Residential",
            "utility": "Seattle City Light",
            "country": "US",
            "state": "WA"
        },
        {
            "tariffID": "SCL-RSC",
            "description": "Residential",
            "utility": "Seattle City Light",
            "country": "US",
            "state": "WA"
        },
        {
            "tariffID": "SCL-RSH",
            "description": "Residential",
            "utility": "Seattle City Light",
            "country": "US",
            "state": "WA"
        },
        {
            "tariffID": "SCP-E-TOU-A",
            "description": "Sonoma Clean Power - E-TOU-A",
            "utility": "Sonoma Clean Power",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "SCP-E-TOU-B",
            "description": "Sonoma Clean Power - E-TOU-B",
            "utility": "Sonoma Clean Power",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "SCP-E-TOU-C",
            "description": "Sonoma Clean Power - E-TOU-C",
            "utility": "Sonoma Clean Power",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "SCP-EV2-A",
            "description": "Sonoma Clean Power - EV2-A",
            "utility": "Sonoma Clean Power",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "SDGE-DR-SES",
            "description": "San Diego Gas & Electric Co - DR-SES",
            "utility": "San Diego Gas & Electric Co",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "SDGE-EV-TOU",
            "description": "San Diego Gas & Electric Co - EV-TOU",
            "utility": "San Diego Gas & Electric Co",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "SDGE-EV-TOU2",
            "description": "San Diego Gas & Electric Co - EV-TOU2",
            "utility": "San Diego Gas & Electric Co",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "SDGE-EV-TOU5",
            "description": "San Diego Gas & Electric Co - EV-TOU5",
            "utility": "San Diego Gas & Electric Co",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "SDGE-TOU-DR",
            "description": "San Diego Gas & Electric Co - TOU-DR",
            "utility": "San Diego Gas & Electric Co",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "SDGE-TOU-DR1",
            "description": "San Diego Gas & Electric Co - TOU-DR1",
            "utility": "San Diego Gas & Electric Co",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "SDGE-TOU-DR2",
            "description": "San Diego Gas & Electric Co - TOU-DR2",
            "utility": "San Diego Gas & Electric Co",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "SMUD-R-TOD",
            "description": "Sacramento Municipal Util Dist - R-TOD",
            "utility": "Sacramento Municipal Util Dist",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "SP-E01",
            "description": "Residential - City",
            "utility": "Sask Power",
            "country": "CA",
            "state": "SK"
        },
        {
            "tariffID": "SP-E02",
            "description": "Residential - Town, Village and Urban Resort",
            "utility": "Sask Power",
            "country": "CA",
            "state": "SK"
        },
        {
            "tariffID": "SP-E03",
            "description": "Residential - Rural and Rural Resort",
            "utility": "Sask Power",
            "country": "CA",
            "state": "SK"
        },
        {
            "tariffID": "SVCE-E-TOU-A",
            "description": "Silicon Valley Clean Energy - E-TOU-A",
            "utility": "Silicon Valley Clean Energy",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "SVCE-E-TOU-B",
            "description": "Silicon Valley Clean Energy- E-TOU-B",
            "utility": "Silicon Valley Clean Energy",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "SVCE-E-TOU-C",
            "description": "Silicon Valley Clean Energy- E-TOU-C",
            "utility": "Silicon Valley Clean Energy",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "SVCP-E-TOU-D",
            "description": "Silicon Valley Clean Power - E-TOU-D",
            "utility": "Silicon Valley Clean Power",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "SVCP-EV-B-TOU",
            "description": "Silicon Valley Clean Power - EV-B-TOU",
            "utility": "Silicon Valley Clean Power",
            "country": "US",
            "state": "CA"
        },
        {
            "tariffID": "TECO-RS",
            "description": "Residential",
            "utility": "Tampa Electric Co",
            "country": "US",
            "state": "FL"
        },
        {
            "tariffID": "TECO-RSVP-1",
            "description": "Residential - Variable Pricing",
            "utility": "Tampa Electric Co",
            "country": "US",
            "state": "FL"
        },
        {
            "tariffID": "TH-R",
            "description": "Residential",
            "utility": "Toronto Hydro",
            "country": "CA",
            "state": "ON"
        },
        {
            "tariffID": "TH-RMU",
            "description": "Residential - Multi-Unit",
            "utility": "Toronto Hydro",
            "country": "CA",
            "state": "ON"
        },
        {
            "tariffID": "TH-RTOU",
            "description": "Residential - Time of Use",
            "utility": "Toronto Hydro",
            "country": "CA",
            "state": "ON"
        },
        {
            "tariffID": "TH-RTOUMU",
            "description": "Residential - Multi-Unit, Time of Use",
            "utility": "Toronto Hydro",
            "country": "CA",
            "state": "ON"
        }
    ],
    "count": 63
}
```
