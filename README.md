## This API returns a random insult, compliment, or word

## Root directory
'https://shielded-headland-00998.herokuapp.com'

## API Endpoints
- 'GET  /api/v1/insults'

- Successful response:
```
{
  "data": {
      "id": "7",
      "type": "insult",
      "attributes": {
            "insult_phrase": "You have miles to go before you reach mediocre."
            }
      }
}
```
- 'GET  /api/v1/compliments'

- Successful response:
```
{
  "data": {
      "id": "12",
      "type": "compliment",
      "attributes": {
            "compliment_phrase": "You were cool way before hipsters were cool."
            }
        }
}
```
- 'GET  /api/v1/words'

- Successful response:
```
{
  "data": {
      "id": "9",
      "type": "word",
      "attributes": {
            "word": "Hand"
            }
      }
}
```
