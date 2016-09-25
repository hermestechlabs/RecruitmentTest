# Hermes Tech Labs Recruitment Test

Thank you for taking the time to do our technical test. It consists of two parts:

* Part One: The Hermes Tech Lab Jam
* Part Two: Some technical questions

Part One: Hermes Tech Lab Jam
------
The task is to create an address application or a mobile app that allows the user to enter a postcode as a search parameter. The application should then return a a list of addresses for that postcode. The user should then be able to select one of the addresses from the results list and a map of the selected address is displayed along with the full address details.

To do this you will use the Hermes Address Lookup API. The specification is detailed below:

### Hermes Postal Addresses for a single postcode

To returns a list of addresses for a postcode.

Request
```
GET https://hermes-test.apigee.net/v1/address/{postcode}?apikey={apikey}
```
| Name       | Required           | Description  |   Type |
| ------------- | ------------- | ----- | ----- |
| apikey      | yes | Your allocated api key | text |


Your api key is:

```
SUzeWOQSyvYmHtNpE60uryI4NDGNHSBk
```

Example Response:

```
{
  "Latitude": 53.7958984375,
  "Longitude": -1.5486608743667603,
  "Addresses": [
    "1 Aire Street, , , , , Leeds, West Yorkshire",
    "2 Aire Street, , , , , Leeds, West Yorkshire",
    "3 Aire Street, , , , , Leeds, West Yorkshire"
  ]
}
```


Part Two: Technical Questions
------


API key
tyElc9AiYEC-2ojG_brpXg5734
