# Project Overview

## Escape

Travel Deals

## Project Description

Plan you next vacation, search for hotels all around the world.

- Get the latest hotel information, rates, room type, amenities list and other hotel information.

-  Search thousands of hotels and resorts  on the website.

-  Explore our large list of gorgeous hotels and resorts.

## Api and Data Sample

#### Amadeus

The Amadeus site:
(https://developers.amadeus.com/self-service/category/hotel/api-doc/hotel-search)

#### JSON Data

#### Postman

![alt text]https://developers.amadeus.com/self-service/category/hotel/api-doc/hotel-search/api-reference"postman json data")

---
{
    "data": [
        {
            "type": "hotel-offers",
            "hotel": {
                "type": "hotel",
                "hotelId": "WWPARVLP",
                "chainCode": "WW",
                "dupeId": "700018106",
                "name": "VILLA PANTHEON",
                "rating": "4",
                "cityCode": "PAR",
                "latitude": 48.84917,
                "longitude": 2.34615,
                "hotelDistance": {
                    "distance": 0.6,
                    "distanceUnit": "KM"
                },
                "address": {
                    "lines": [
                        "41, RUE DES ECOLES"
                    ],
                    "postalCode": "75005",
                    "cityName": "PARIS",
                    "countryCode": "FR"
                },
                "contact": {
                    "phone": "33-1-53109595",
                    "fax": "33-1-53109596"
                },
                "description": {
                    "lang": "en",
                    "text": "The Villa Panthéon Paris is one of the Latin Quarter's top hotels. Paris' centre has a romantic charm, and the Saint Germain district on the left bank of the Seine is one of the most evocative areas of the capital. The district offers the cultural delights of Le Sorbonne, Notre-Dame, and Ile Saint-Louis.\r\r\rGuests to the Villa Panthéon Paris can relax in the great traditions of the English club atmosphere where the copper glow of the bar mixes with the warm leather of the club lounges. The Villa Panthéon Paris is part of the Worldhotels First Class Collection.\r\r\rThe intimate details of the Villa Panthéon's 59 rooms and 2 suites form a relaxing haven for guests. Exotic wood floors, leather armchairs, and thick cloth drapes create a luxurious atmosphere. Modern amenities and room service breakfast and lunch are available.\r\r\rIf you are looking at the top hotels Paris' centre can offer, why not look at our rates and availability for the Villa Panthéon Paris?"
                },
                "amenities": [
                    "MEETING_ROOMS",
                    "RESTAURANT",
                    "DISABLED_FACILITIES",
                    "ACC_ELEVATORS",
                    "ACC_RM_WCHAIR",
                    "ACC_WCHAIR",
                    "BABY-SITTING",
                    "KIDS_WELCOME",
                    "ELEVATOR",
                    "INT_HOTSPOTS",
                    "WIFI",
                    "LAUNDRY_SVC",
                    "MASSAGE",
                    "PETS_ALLOWED",
                    "AIR_CONDITIONING",
                    "HAIR_DRYER",
                    "MINIBAR",
                    "MOVIE_CHANNELS",
                    "NONSMOKING_RMS",
                    "PC_HOOKUP_INRM",
                    "PHONE-DIR_DIAL",
                    "ROOM_SERVICE",
                    "TELEVISION",
                    "FIRST_AID_STAF",
                    "INT_ROOM_ENTRY",
                    "EMERG_LIGHTING",
                    "FIRE_DETECTORS",
                    "EXTINGUISHERS",
                    "FIRE_SAFETY",
                    "SMOKE_DETECTOR",
                    "SPRINKLERS",
                    "VIDEO_SURVEIL",
                    "FITNESS_CENTER"
                ],
                "media": [
                    {
                        "uri": "http://uat.multimediarepository.testing.amadeus.com/cmr/retrieve/hotel/2A8259BD94CD45C1801F4220B696E3A9",
                        "category": "EXTERIOR"
                    }
                ]
            },
            "available": true,
            "offers": [
                {
                    "id": "9C658D49784A02F04C3BE95F4AAA420856EE645A2CC06F669187ED2009389B2F",
                    "checkInDate": "2020-04-27",
                    "checkOutDate": "2020-04-28",
                    "rateCode": "PK3",
                    "rateFamilyEstimated": {
                        "code": "PKG",
                        "type": "P"
                    },
                    "commission": {
                        "percentage": "10.00"
                    },
                    "room": {
                        "type": "A1K",
                        "typeEstimated": {
                            "category": "DELUXE_ROOM",
                            "beds": 1,
                            "bedType": "KING"
                        },
                        "description": {
                            "lang": "EN",
                            "text": "RATE TAX INCLUSIVE-PKG TAX INCLUSIVE \nDeluxe-mini bar-jacuzzi-marble tile-balcony-upgraded amenities-\nsitting area"
                        }
                    },
                    "guests": {
                        "adults": 1
                    },
                    "price": {
                        "currency": "USD",
                        "base": "120.00",
                        "total": "130.00",
                        "variations": {
                            "average": {
                                "base": "120.00"
                            },
                            "changes": [
                                {
                                    "startDate": "2020-04-27",
                                    "endDate": "2020-04-28",
                                    "base": "120.00"
                                }
                            ]
                        }
                    },
                    "policies": {
                        "guarantee": {
                            "acceptedPayments": {
                                "creditCards": [
                                    "VI",
                                    "CA",
                                    "AX"
                                ],
                                "methods": [
                                    "CREDIT_CARD"
                                ]
                            }
                        },
                        "paymentType": "guarantee",
                        "cancellation": {
                            "numberOfNights": 1,
                            "deadline": "2020-04-25T23:00:00+02:00"
                        }
                    }
                }
            ],
            "self": "https://test.api.amadeus.com/v2/shopping/hotel-offers/by-hotel?hotelId=WWPARVLP&adults=1&paymentPolicy=NONE&view=FULL"
        }


## Wireframe

### Desktop



### Mobile



## MVP/Post MVP

### MVP

- Find an external API to access food recipes data.
- Render data from API on the page.
- Style the page as indicated on the wireframe.
- Add search funtionallity, allowing the user to search hotels.
- Render results on the page with all the hotel information.

---

### Post MVP

- Add a second API.




## Project Schedule

| Day             | Deliverable                                          | Status   |
| --------------- | ---------------------------------------------------- | -------- |
| April 27th      | Project Prompt, Wireframes / Priority Matrix         |Incomplete|
| April 28th      | Core Application Structure                           |Incomplete|
| April 29th      | API and JS functionality                             |Incomplete|
| April 30th      | Clickable Model Search                               |Incomplete|
| April 30th      | Rendering functionality                              |Incomplete|
| April 30th      | MVP                                                  |Incomplete|
| May 1th         | Present                                              |Incomplete|

## Priority Matrix





## Timeframes

| Component                           | Priority | Estimated Time | Time Invested | Actual Time |
| ----------------------------------- | :------: | :------------: | :-----------: | :---------: |
| Research APIs                       |    L     |      hrs       |     hrs       |    hrs      |
| Wireframes/Priority Matrix          |    L     |      hrs       |     hrs       |    hrs      |
| Testing API & JSON Data             |    M     |      hrs       |     hrs       |    hrs      |
| Basic HTML and Basic CSS            |    M     |      hrs       |     hrs       |    hrs      |
| Setting up API, CDNs and Test Calls |    M     |      hrs       |     hrs       |    hrs      |
| JavaScript DOM Manipulation         |    H     |      hrs       |     hrs       |    hrs      |
| Testing and Debugging               |    H     |      hrs       |     hrs       |    hrs      |
| JS Functions and Handlers           |    H     |      hrs       |     hrs       |    hrs      |
| Applys CSS FlexBox                  |    H     |      hrs       |     hrs       |    hrs      |
| Site interactivity JS & FlexBox     |    H     |      hrs       |     hrs       |    hrs      |
| Total                               |    H     |      hrs       |     hrs       |    hrs      |

## Code Snippet



```


```

## Change Log


