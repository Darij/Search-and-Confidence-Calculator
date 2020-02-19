# Code Challange for FrameworkScience 

Design a REST API endpoint that provides auto-complete suggestions from a list of contacts.

## Getting Started
This code will be deployed in heroku, just run the following URL in the REST client of yor choice

### Prerequisites

Root url: (https://code-challange-fs-dario.herokuapp.com/)

Url required by challange: GET /suggestions?q={string}&rate_minimum={int}&verified_skills={string}

### Example

https://code-challange-fs-dario.herokuapp.com/suggestions?q=Bran&rate_minimum=620&verified_skills=facebook_advertising

```
Result exmaple
[
  {
    "_id": "5e4c448b6875f29549bdb088",
    "age": 33,
    "contact_email": "brandiecooke@tetak.com",
    "eyeColor": "green",
    "first_name": "Brandie",
    "guid": "0e5cfd92-c1e8-4b92-9233-39c4b0bcb337",
    "index": 14,
    "last_name": "Cooke",
    "min_rate": "$620.89",
    "score": 0.6666666666666666,
    "verified_skills": [
      "conversion_rate_optimization",
      "analytics_infrastructure",
      "podcast_advertising",
      "customer_acquisition_strategy",
      "linkedin_advertising"
    ]
  },
  {
    "_id": "5e4c448b2e1548fa5a3734ec",
    "age": 31,
    "contact_email": "heatheroconnor@tetak.com",
    "eyeColor": "green",
    "first_name": "Heather",
    "guid": "a587a1c5-f320-4053-87f2-530e1060d071",
    "index": 0,
    "last_name": "Oconnor",
    "min_rate": "$940.08",
    "score": 0.3333333333333333,
    "verified_skills": [
      "lifecycle_marketing",
      "user_referral_programs",
      "facebook_organic",
      "mailchimp",
      "facebook_advertising",
      "user_referral_programs",
      "podcast_advertising"
    ]
  },
 ]
```

## WAD (where's all the data)
Due to time constraints, a JSON file was created with random data.
(generated.json) is located in root of project

## Known Issues
 Due to time constraints the following feature were not implemented:
 * Query with any known parameter [Age, Eye-color, Email, etc.]
 * Accurately calculate the suggestion score
 * Autocompletion: The challange didnt specify if UI with javascript was required or to use data lists from HTML5 

## Built With

* [Flask](https://flask.palletsprojects.com/en/1.1.x/) - The web framework used
* [Python3.5]


## Authors

* **Dario Alberto Lopez Pesqueira** 


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Disclaimer

I will save the code and to my portfolio
