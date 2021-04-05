## Headers
| UMIP-29    |                                                          |
|------------|----------------------------------------------------------|
| UMIP Title | Add USDTSLA, USDINX and USDICLN as price identifiers     |
| Authors    | chuseuiti                                                |
| Status     | Pending                                                  |
| Created    | April 4, 2020                                            |

## Summary
The DVM should support price requests for the USDTSLA, USDINX and USDICLN price index.

## Motivation
The DVM currently does not support the USDTSLA, USDINX and USDICLN index.

### Cost: 
Stock market data is free to query on https://www.alphavantage.co/documentation/ company backed by Y Combinator. While the information is not provided in real time, it provides the daily intraday data on a 1 minute frequency. Real time data is provided on the paid plan.

### Opportunity: 
Synthetic tokens that track stock market pairs as EUSDTSLA, USDINX and USDICLN could provide exposure to the US financial market thanks to the indexes and to be able to get exposure to a valuable stock as TSLA. 

## Technical Specification

The definition of this identifiers should be:

-----------------------------------------
- Identifier name: **USDTSLA**
- Base Currency: USD
- Stock: TSLA

-----------------------------------------

- Identifier name: **USDINX**
- Base Currency: USD
- Stock: INX

-----------------------------------------

- Identifier name: **USDICLN**
- Base Currency: USD
- Stock: ICLN

-----------------------------------------

- Source: hhttps://www.alphavantage.co/documentation/ 
- Result Processing: None
- Input Processing: None
- Price Steps: (4 decimals)
- Rounding:
- Scaling Decimals: 
- Pricing Interval: 1 min
- Dispute timestamp rounding: 

## Rationale


## Implementation


### Weekend timestamp


### Stock markets working hours

US market hours are 4:00am to 8:00pm Eastern Time.

### Price feed - liquidations and disputes


## Additional price feed providers

### FXMarketAPI


### FCS API


## Security considerations

