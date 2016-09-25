# Hermes Tech Labs Recruitment Test

Thank you for taking the time to do our technical test. It consists of two parts:

* Part One: The Hermes Tech Lab Jam
* Part Two: Some technical questions

Part One: Hermes Tech Lab Jam
------
The task is to create an application that accepts a postcode as a search parameter. The application should then return a list of addresses for that postcode. The user should then be able to select one of the addresses from the results list and a map of the selected address is displayed along with the full address details.

To do this you will use the Hermes Address Lookup API. The specification is detailed below:

### Hermes Postal Addresses for a single postcode

Returns a list of addresses for a postcode.

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
### Platform Choice

You can create the application as either a web application or mobile application in any of the following platforms:

Java, PHP, Ruby, Python. Node.js or JavaScript for web applications
iOS, Android or Windows Mobile for mobile applications or HTML5, CSS3 and JavaScript for hybrid mobile

Part Two: Technical Questions
------


API key
tyElc9AiYEC-2ojG_brpXg5734
