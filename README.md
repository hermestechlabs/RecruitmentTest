# Hermes Tech Labs Recruitment Test

Thank you for taking the time to do our technical test. It consists of two parts:

* Part One: The Hermes Tech Lab Jam (**to prepare in advance of your interview**)
* Part Two: Interview questions (on the day of the interview)

Part One: The Hermes Tech Lab Jam (to be prepared in advance)
------

#### Allocated time: On the day of the interview 30mins to showcase your solution

The business problem you are trying to solve is as follows:

Couriers sometimes receive parcels with incomplete labels. The postocde is present on the label but the address details are incomplete and so they need to be able to retrieve the full address to allow them to deliver the parcel.  

The task is develop an application that solves the problem for the courier.

To help you we have developed a Hermes Address Lookup API. The specification is detailed below:

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
| Latitude      | Coordinate that specifies the north–south position of specified postcode | Number | 
| Longitude     | Coordinate that specifies the east–west position of specified postcode | Number | 
| Addresses      | A list of 1..n address in the specified postcode | Array |
| Address      | an address contained in a comma-delimited string representing address lines 1 to5, City, County | String |

### Platform Choice

Feel free to use whatever frameworks / libraries / packages you like.

We're looking for creativity here.


### Presenting

You will have 30mins at the interview to walk through your solution and answer questions


Part Two: Interview Questions (on the day of the interview). Duration 1 hour
------

We will ask you a series of questions to find out more about you and what makes you tick.

