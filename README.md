# personalization
A simple standard for the transmission of person, location, device, and other context data so that personalized content can be returned.

| Field                       | Description                                     | Type      | Example          |
| --------------------------- |------------------------------------------------ | --------- | ---------------- |
| person.name.first           | User first name                                 | string    | Daenerys         |
| person.name.middle          | User middle name                                | string    |                  |
| person.name.middleInitial   | User middle initial                             | string    |                  |
| person.name.last            | User last name                                  | string    | Targaryen        |
| person.age                  | User age                                        | integer   | 32               |
| person.ageRange             | User age range                                  | int range | Consider using 0-11, 12–17, 18–24, 25–34, 35–44, 45–54, 55–64, 65-74, 75-120 |
| person.dob                  | User data of birth in YYYYMMDD                  | string    | 20100123         |
| person.hairColor            | User hair color                                 | string    | consider using brown,blonde,bald,black,auburn,red,gray,white,other but dyed hair could also be red,green,purple,orange,etc |
| person.smile                | Whether the person has a smile                  | boolean   | Use confidence not value |
| person.facialHair           | Whether the person has facial hair              |           | Use confidence not value |
| person.facialHair.moustache | Whether the person has a moustache              |           | Use confidence not value |
| person.facialHair.beard     | Whether the person has a beard                  |           | Use confidence not value |
| person.facialHair.sideburns | Whether the person has sideburns                |           | Use confidence not value |
| person.glasses              | Whether the person has glasses                  |           | Use confidence not value |
| person.glasses.sun          | Whether the person has sun glasses              |           | Use confidence not value |
| person.glasses.reading      | Whether the person has reading glasses          |           | Use confidence not value |
| person.makeup.eye           | Whether the person has eye makeup               |           | Use confidence not value |
| person.makeup.lip           | Whether the person has lipstick                 |           | Use confidence not value |
| person.emotion.anger        | Confidence the person is angry                  | string    |                  |
| person.emotion.contempt     | Confidence the person has contempt              | string    |                  |
| person.emotion.disgust      | Confidence the person is disgusted              | string    |                  |
| person.emotion.fear         | Confidence the person is afraid                 | string    |                  |
| person.emotion.happiness    | Confidence the person is happy                  | string    |                  |
| person.emotion.neutral      | Confidence the person has neutral emotion       | string    |                  |
| person.emotion.sadness      | Confidence the person is sad                    | string    |                  |
| person.emotion.surprise     | Confidence the person is surprised              | string    |                  |
| person.emotion.confused     | Confidence the person is confused               | string    |                  |
| person.addressLine1         | User first address line                         | string    |                  |
| person.addressLine2         | User second address line                        | string    |                  | 
| person.addressLine3         | User third address line                         | string    |                  |
| person.city                 | User address city                               | string    |                  |
| person.region               | User region/state. This can be abbreviated.     | string    | GA               |
| person.countryCode          | User address country code ISO 3166-1 alpha-2    | string    | US               |
| person.phone                | User phone. We aren't saying which type         | string    | 404-555-1212     |
| person.phone.mobile         | User mobile phone                               | string    |                  |   
| person.phone.home           | User home phone                                 | string    |                  | 
| person.phone.work           | User work phone                                 | string    |                  |



