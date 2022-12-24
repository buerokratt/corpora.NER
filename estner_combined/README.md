# EstNER corpus

This is EstNER corpus that is combined from [new estner corpus](https://github.com/TartuNLP/EstNER_new) and [old estner corpus](https://metashare.ut.ee/repository/browse/estonian-ner-corpus/88d030c0acde11e2a6e4005056b40024f1def472ed254e77a8952e1003d9f81e/)

## Dataset statistics

The dataset is divided into training, development and test sets.

|           | Train         | Dev           | Test  | Total  |
|-----------| ------------- | ------------- | ----- | ------ |
| Documents | 603           | 34            | 54    | 691    |
| Sentences | 16966         | 3297          | 2797  | 23060  |
| Tokens    | 284807        | 49317         | 45853 | 379977 |

## Entities

### Contains

* PER - person names
* GPE - geopolitical entities
* LOC - geographical locations
* ORG - organizations
* PROD - products, things, works of art
* EVENT - events
* DATE - dates
* TIME - times
* TITLE - titles and professions.
* MONEY - monetary expressions
* PERCENT - percentages
* DOC_ORG - id of organisation document
* CARD - banking or similar card number
* IBAN - IBAN account number
* DOC_PER - Personal document number
* IDCODE - personal ID code
* EMAIL - email address
* TEL - phone number

### Entity statistics

|           | LEVEL 1   |           |        | LEVEL 2   |           |        | LEVEL 3   |           |        |
|-----------| ----------| --------- | -----  | ----------| --------- | ------ | ----------| --------- | -----  |
|**Entity** |**Train**  | **Dev**   |**Test**|**Train**  | **Dev**   |**Test**|**Train**  | **Dev**   |**Test**|
| PER       | 6165      | 751       | 1021   | 154       | 8         | 18     | 2         |           |        |
| LOC       | 777       | 149       | 96     | 83        | 13        | 8      | 1         | 1         |        |
| GPE       | 4630      | 843       | 710    | 1124      | 195       | 143    | 63        | 13        | 5      |
| ORG       | 4393      | 589       | 691    | 271       | 39        | 18     | 1         |           |        |
| PROD      | 1505      | 221       | 184    | 7         |           |        |           |           |        |
| EVENT     | 286       | 28        | 43     | 6         |           |        |           |           |        |
| DATE      | 2093      | 372       | 263    | 17        | 34        | 1      |           |           |        |
| TIME      | 559       | 45        | 36     |           |           |        |           |           |        |
| TITLE     | 2007      | 191       | 260    | 9         |           |        |           |           |        |
| MONEY     | 409       | 88        | 158    |           |           |        |           |           |        |
| PERCENT   | 212       | 73        | 59     | 1         |           |        |           |           |        |
| DOC_ORG   |           |           |        |           |           |        |           |           |        |
| CARD      |           |           |        |           |           |        |           |           |        |
| IBAN      |           |           |        |           |           |        |           |           |        |
| DOC_PER   |           |           |        |           |           |        |           |           |        |
| IDCODE    |           |           |        |           |           |        |           |           |        |
| EMAIL     |           |           |        |           |           |        |           |           |        |
| TEL       |           |           |        |           |           |        |           |           |        |


