### Will create a SQLite DB from MTG Arena logs

###### output_log.txt quick reference
- line num: 1637: `<== PlayerInventory.GetFormats(7)`
  - all formats, banned cards for each format and all sets in each format
  ```
  [
    {
      "name": "Cascade",
      "sets": [
        "ANA",
        "DAR",
        "M19",
        "RIX",
        "W17",
        "XLN",
        "GRN",
        "G18",
        "RNA",
        "WAR"
      ],
      "bannedCards": [
        "Lavinia, Azorius Renegade",
        "Teferi, Time Raveler",
        "Nexus of Fate"
      ],
      "cardCountRestriction": "None"
    }
  ]
  ```
- line num: 2020: `<== Deck.GetDeckListsV3(8)`
  - all user decks
```
[
  {
    "cardSkins": null,
    "id": "2eb29844-8ad7-4e55-b91e-92a50b4d4c01",
    "name": "Boros Angels",
    "description": "",
    "format": "Standard",
    "deckTileId": 65961,
    "mainDeck": [
      65961,
      4,
      67015,
      10
    ],
    "sideboard": []
]
```
- line num: 2401: `<== Event.GetCombinedRankInfo(10)`
  - user rankings info
```
{
  "playerId": "AOSA2JCMNNEKDIYA27RRZDRJOA",
  "constructedSeasonOrdinal": 5,
  "constructedClass": "Gold",
  "constructedLevel": 3,
  "constructedStep": 3,
  "constructedMatchesWon": 71,
  "constructedMatchesLost": 100,
  "constructedMatchesDrawn": 0,
  "limitedSeasonOrdinal": 5,
  "limitedClass": "Bronze",
  "limitedLevel": 4,
  "limitedStep": 0,
  "limitedMatchesWon": 0,
  "limitedMatchesLost": 0,
  "limitedMatchesDrawn": 0,
  "constructedPercentile": 0.0,
  "constructedLeaderboardPlace": 0,
  "limitedPercentile": 0.0,
  "limitedLeaderboardPlace": 0
}
```
