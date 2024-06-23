# Countries API

This API provides information about countries, including details like country names, codes, population, geography, language and more. It can be used for applications that require geographical and demographic data about countries.

## API Endpoint

The Countries API can be accessed at the following endpoint:

[Countries API](https://restcountries.com/v3.1/all)

`GET - https://restcountries.com/v3.1/all`

### Response Data

```  
[{
    "name": {
      "common": "India",
      "official": "Republic of India",
      "nativeName": {
        "eng": {
          "official": "Republic of India",
          "common": "India"
        },
        "hin": {
          "official": "भारत गणराज्य",
          "common": "भारत"
        },
        "tam": {
          "official": "இந்தியக் குடியரசு",
          "common": "இந்தியா"
        }
      }
    },
    "tld": [
      ".in"
    ],
    "cca2": "IN",
    "ccn3": "356",
    "cca3": "IND",
    "cioc": "IND",
    "independent": true,
    "status": "officially-assigned",
    "unMember": true,
    "currencies": {
      "INR": {
        "name": "Indian rupee",
        "symbol": "₹"
      }
    },
    "idd": {
      "root": "+9",
      "suffixes": [
        "1"
      ]
    },
    "capital": [
      "New Delhi"
    ],
    "altSpellings": [
      "IN",
      "Bhārat",
      "Republic of India",
      "Bharat Ganrajya",
      "இந்தியா"
    ],
    "region": "Asia",
    "subregion": "Southern Asia",
    "languages": {
      "eng": "English",
      "hin": "Hindi",
      "tam": "Tamil"
    },
    "translations": {
      "ara": {
        "official": "جمهورية الهند",
        "common": "الهند"
      },
      "bre": {
        "official": "Republik India",
        "common": "India"
      },
      "ces": {
        "official": "Indická republika",
        "common": "Indie"
      },
      "cym": {
        "official": "Republic of India",
        "common": "India"
      },
      "deu": {
        "official": "Republik Indien",
        "common": "Indien"
      },
      "est": {
        "official": "India Vabariik",
        "common": "India"
      },
      "fin": {
        "official": "Intian tasavalta",
        "common": "Intia"
      },
      "fra": {
        "official": "République de l'Inde",
        "common": "Inde"
      },
      "hrv": {
        "official": "Republika Indija",
        "common": "Indija"
      },
      "hun": {
        "official": "Indiai Köztársaság",
        "common": "India"
      },
      "ita": {
        "official": "Repubblica dell'India",
        "common": "India"
      },
      "jpn": {
        "official": "インド共和国",
        "common": "インド"
      },
      "kor": {
        "official": "인도 공화국",
        "common": "인도"
      },
      "nld": {
        "official": "Republiek India",
        "common": "India"
      },
      "per": {
        "official": "جمهوری هندوستان",
        "common": "هند"
      },
      "pol": {
        "official": "Republika Indii",
        "common": "Indie"
      },
      "por": {
        "official": "República da Índia",
        "common": "Índia"
      },
      "rus": {
        "official": "Республика Индия",
        "common": "Индия"
      },
      "slk": {
        "official": "Indická republika",
        "common": "India"
      },
      "spa": {
        "official": "República de la India",
        "common": "India"
      },
      "srp": {
        "official": "Република Индија",
        "common": "Индија"
      },
      "swe": {
        "official": "Republiken Indien",
        "common": "Indien"
      },
      "tur": {
        "official": "Hindistan Cumhuriyeti",
        "common": "Hindistan"
      },
      "urd": {
        "official": "جمہوریہ بھارت",
        "common": "بھارت"
      },
      "zho": {
        "official": "印度共和国",
        "common": "印度"
      }
    },
    "latlng": [
      20,
      77
    ],
    "landlocked": false,
    "borders": [
      "BGD",
      "BTN",
      "MMR",
      "CHN",
      "NPL",
      "PAK"
    ],
    "area": 3287590,
    "demonyms": {
      "eng": {
        "f": "Indian",
        "m": "Indian"
      },
      "fra": {
        "f": "Indienne",
        "m": "Indien"
      }
    },
    "flag": "🇮🇳",
    "maps": {
      "googleMaps": "https://goo.gl/maps/WSk3fLwG4vtPQetp7",
      "openStreetMaps": "https://www.openstreetmap.org/relation/304716"
    },
    "population": 1380004385,
    "gini": {
      "2011": 35.7
    },
    "fifa": "IND",
    "car": {
      "signs": [
        "IND"
      ],
      "side": "left"
    },
    "timezones": [
      "UTC+05:30"
    ],
    "continents": [
      "Asia"
    ],
    "flags": {
      "png": "https://flagcdn.com/w320/in.png",
      "svg": "https://flagcdn.com/in.svg",
      "alt": "The flag of India is composed of three equal horizontal bands of saffron, white and green. A navy blue wheel with twenty-four spokes — the Ashoka Chakra — is centered in the white band."
    },
    "coatOfArms": {
      "png": "https://mainfacts.com/media/images/coats_of_arms/in.png",
      "svg": "https://mainfacts.com/media/images/coats_of_arms/in.svg"
    },
    "startOfWeek": "monday",
    "capitalInfo": {
      "latlng": [
        28.6,
        77.2
      ]
    },
    "postalCode": {
      "format": "######",
      "regex": "^(\\d{6})$"
    }
  },
  {..... more }
]
```


# Airport Data

This API provides information about Airports Code, including details like City names, country codes, coordinates, timezone,  language and more.

## API Endpoint

The Airport Api can be accessed at the following endpoint:

[Countries API](https://api.travelpayouts.com/data/en/cities.json)

`GET - https://api.travelpayouts.com/data/en/cities.json`

### Response Data

```  
[
    ....
  {
    "name_translations": {
      "en": "Mumbai"
    },
    "cases": {
      "su": "Mumbai"
    },
    "country_code": "IN",
    "code": "BOM",
    "time_zone": "Asia/Kolkata",
    "name": "Mumbai",
    "coordinates": {
      "lat": 19.095509,
      "lon": 72.87497
    }
  },
    .....
]
```



# Airplane Data

This API provides information about Airplane Code, and name

## API Endpoint

The Airplane Api can be accessed at the following endpoint:

[Countries API](https://api.travelpayouts.com/data/planes.json)

`GET - https://api.travelpayouts.com/data/planes.json`

### Response Data

```  
[
    ....
  {
    "code": "JST",
    "name": "British Aerospace Jetstream 31/32/41"
  },
  {
    "code": "JU5",
    "name": "Junkers Ju52"
  },
  {
    "code": "L10",
    "name": "Lockheed L-1011 Tristar"
  },
    .....
]
```





# Universites Data 

This API provides information about Universites name, country, web page url, and domain

## API Endpoint

The Universites Api can be accessed at the following endpoint:

[Countries API](http://universities.hipolabs.com/search?country=India)

`GET - http://universities.hipolabs.com/search?country={name}`

`GET - http://universities.hipolabs.com/search?country=United+States`

### Response Data

```  
[
    ....
   {
    "name": "Harvard University",
    "alpha_two_code": "US",
    "country": "United States",
    "web_pages": [
      "http://www.harvard.edu/"
    ],
    "state-province": null,
    "domains": [
      "harvard.edu"
    ]
  },
    .....
]
```
