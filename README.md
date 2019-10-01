# personalization
A simple standard for the transmission of user, location, device, and other context data so that personalized content can be returned.

| Field               | Description                                     | Type      | Example          |
| ------------------- |------------------------------------------------ | --------- | ---------------- |
| user.firstName      | User first name                                 | string    | Daenerys         |
| user.middleName     | User middle name                                | string    |                  |
| user.middleInitial  | User middle initial                             | string    |                  |
| user.lastName       | User last name                                  | string    | Targaryen        |
| user.age            | User age                                        | integer   | 32               |
| user.ageRange       | User age range                                  | int range | Consider using 0-11, 12–17, 18–24, 25–34, 35–44, 45–54, 55–64, 65-74, 75-120 |
| user.dob            | User data of birth in YYYYMMDD                  | string    | 20100123         |
| user.hairColor      | User hair color                                 | string    | consider using brown,blonde,bald,black,auburn,red,gray,white,other but dyed hair could also be red,green,purple,orange,etc |
| user.smile          | Whether the user has a smile                    | boolean   | Use confidence not value |
| user.beard          | Whether the user has a beard
| user.addressLine1   | User first address line                         | string    |                  |
| user.addressLine2   | User second address line                        | string    |                  | 
| user.addressLine3   | User third address line                         | string    |                  |
| user.city           | User address city                               | string    |                  |
| user.region         | User region/state. This can be abbreviated.     | string    | GA               |
| user.countryCode    | User address country code ISO 3166-1 alpha-2    | string    | US               |
| user.phone          | User phone. We aren't saying which type         | string    | 404-555-1212     |
| user.phone.mobile   | User mobile phone                               | string    |                  |   
| user.phone.home     | User home phone                                 | string    |                  | 
| user.phone.work     | User work phone                                 | string    |                  |
