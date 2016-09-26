# Hermes Tech Labs Recruitment Test

Thank you for taking the time to do our technical test. It consists of two parts:

* Part One: The Hermes Tech Lab Jam
* Part Two: Some technical questions

Part One: The Hermes Tech Lab Jam
------

#### Allocated time: 3 hours
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
Examples Request:
```
GET https://hermes-test.apigee.net/v1/address/LS1 4PR?apikey=SUzeWOQSyvYmHtNpE60uryI4NDGNHSBk
```
Example 200 Response:

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
| Name       | Description      | Type  |  
| ------------- | ------------- | ----- | 
| Latitude      | Coordinate that specifies the north–south position of specified postcode | text | 
| Longitude     | Coordinate that specifies the east–west position of specified postcode | text | 
| Addresses      | A list of 1..n address in the specified postcode | array |
| Address      | an address contained in the array addresses | array |
| Address[0]      | first line of address | text |


### Platform Choice

You can create the application as either a web application or mobile app in any of the following platforms:

* Java, PHP, Ruby, Python. Node.js or JavaScript for web applications
* iOS, Android or Windows Mobile for mobile applications 
* HTML5, CSS3 and JavaScript for hybrid mobile

### Task Requirements

Please complete the user stories below.
Your code should compile and run in one step.
Feel free to use whatever frameworks / libraries / packages you like.

#### User Story

As a user running the application...
* I can enter a psotcode and view a list of addresses for my specified postcode. For example, LS1 4PR
* So that I know which address are within the postcode I have specified

As a user running the application...
* I can select an address from the results retrieved and view the full address details
* So that I know exactly the full address for my chosen address

**Bonus** As a user running the application...
* I view my chosen address on a map using the GPS (lon/ lat co-ords) returned in the result
* So that I can find my address on a map



Part Two: Technical Questions
------
