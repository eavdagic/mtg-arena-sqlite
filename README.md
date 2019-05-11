### Will create a SQLite DB from MTG Arena logs

#### Reference Guide to output_log.txt
Locations (line numbers) and examples of JSON objects in logs
- **line num: 1637: `<== PlayerInventory.GetFormats(7)`**
  - all formats, banned cards for each format and all sets in each format
- **line num: 2020: `<== Deck.GetDeckListsV3(8)`**
  - all user decks
- **line num: 2401: `<== Event.GetCombinedRankInfo(10)`**
  - user rankings info
- **line num: 2427: `<== PlayerInventory.GetRewardSchedule(11)`**
  - Rewards schedule
- **line num: 2740: `<== PlayerInventory.GetPlayerCardsV3(12)`**
  - user owned cards and count
