# ![LOGO](logo.png) vs **flow**ground Connector

## Description

A generated **flow**ground connector for the vs API (version 1.1).

Generated from: https://api.apis.guru/v2/specs/sheetlabs.com/vedic-society/1.1/swagger.json<br/>
Generated at: 2019-05-07T17:44:02+03:00

## API Description

This API returns data regarding the descriptions of almost all nouns in vedic literature. The results are JSON objects that contain the word transliterated to roman, the word in nagari, the meaning of the word, and the category the word belongs to.

## Authorization

This API does not require authorization.

## Actions

### Fetch all records from the database

### Fetch all words in a specific category

#### Input Parameters
* `category` - _required_ - Click to select from a list
    Possible values: grass, plant, tree, animal, bird, cattle, fish, insect, snake, worm, building, chariot, food, grain, metal, object, ship, weapon, war, number, distance, time, weight, mountain, place, river, astronomy, disease, literature, medicine, poison, subject, dicing, games, music, clothing, hair, ornament, law, morals, agriculture, caste, family, occupation, priest, royalty, trade, tribe.

### Fetch all meanings that contain a specific string

#### Input Parameters
* `description` - _required_ - The string you are looking for in the word meaning, for example, chariot. Wildcards allowed; example: char*.

### Fetch the meaning of a specific word

#### Input Parameters
* `word` - _required_ - The Sanskrit word transliterated into English, for example, rajan. Wildcards allowed; example: *aj*.

## License

**flow**ground :- Telekom iPaaS / sheetlabs-com-vedic-society-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
