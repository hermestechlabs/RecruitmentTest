# Hermes Tech Labs Recruitment Test

Thank you for taking the time to do our technical test. It consists of two parts:

* [Part One: The Hermes Tech Lab Jam]
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
| Latitude      | yes | Your allocated api key | 
| Longitude     | yes | Your allocated api key | 
| Addresses      | yes | Your allocated api key |


### Platform Choice

You can create the application as either a web application or mobile application in any of the following platforms:

* Java, PHP, Ruby, Python. Node.js or JavaScript for web applications
* iOS, Android or Windows Mobile for mobile applications 
* HTML5, CSS3 and JavaScript for hybrid mobile

### Task Requirements

Please complete the user stories below.
Your code should compile and run in one step.
Feel free to use whatever frameworks / libraries / packages you like.

#### User Story

As a user running the application...
* I can view a list of addresses in a user submitted postcode. For example, LS1 4PR
* So that I know which address are within the postcode I specifiy

As a user running the application...
* I can select an address from the results retrieved and view the full address
So that I know exactly the full address for my chosen address

As a user running the application...
I view my chosen address on a map using the GPS returned in the resultsto find my current postcode to retrieve restaurant results
So that I dont need to type it in

Acceptance criteria

For the known outcode se19, results are returned
The Name, Cuisine Types and Rating of the restaurant are displayed

Part Two: Technical Questions
------


API key
tyElc9AiYEC-2ojG_brpXg5734
