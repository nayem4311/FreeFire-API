# 📝 API Documentation

##  Account Information API
API Route = https://url/info?uid={uid}&region={region}&key={key}

**Get Access:** https://leakstudio.site

**Endpoint:** `/info`
**key:** `@freefirelikeinfo`
**Method:** `GET`  

This Endpoint Retrieves Account Information based on the Specified Region and User ID.

### 📨 Request Example
```http
GET https://url/info?uid=12345678&region=bd&key=@freefirelikeinfo
```

### ☑️ Query Parameters

| Parameter | Type   | Required | Description                   |
|-----------|--------|----------|-------------------------------|
| `region`  | string | Yes      | The region code (`sg`, `bd`, `ind`, `br`,`id`, `tw`, `us`, `na`, `sac`, `th`, `vn`, `me`, `pk`, `cis`, `eu`).|
| `uid`     | int | Yes      | The user ID.                  |
| `key`     | string | Yes      | Join https://t.me/freefirelikeinfo to get Latest Key.                  |


📚 **API Purpose**

The goal of this free API is to enrich the Free Fire community by offering access to account data that is not available through official channels. Since Garena Free Fire does not provide an official account information API, this custom solution serves as a valuable resource for players and developers seeking detailed account data.


# 📁 Additional Information

- This API response Does not Represent the Actual Structure Received from the Official Garena Server.
- The Response structure is simplified in an User-Friendly Structure for the ease of understanding for Anyone at any level of Programming.

### 💬 Example of a Successful Reponse May Look Like this,
```json
{
  "AccountInfo": {
    "AccountAvatarId": 902000291,
    "AccountBPBadges": 8,
    "AccountBPID": 1001000089,
    "AccountBannerId": 901000261,
    "AccountCreateTime": "20/01/2019 (05:28:45 PM)",
    "AccountEXP": 4166666,
    "AccountId": "663660642",
    "AccountLastLogin": "15/10/2025 (07:26:13 AM)",
    "AccountLevel": 74,
    "AccountLikes": 62851,
    "AccountName": "LSㅤRAMIL",
    "AccountPinID": "910000013",
    "AccountRegion": "BD",
    "AccountSeasonId": 47,
    "AccountType": 1,
    "BrMaxRank": 320,
    "BrRankPoint": 3430,
    "CsMaxRank": 313,
    "CsRankPoint": 48,
    "EquippedWeapon": [907105025, 912034001, 914000002],
    "ReleaseVersion": "OB50",
    "ShowBrRank": true,
    "ShowCsRank": true,
    "Title": "6 Years Old",
    "primeInfo": {
      "primeLevel": 8,
      "uid": "663660642"
    }
  },
  "AccountProfileInfo": {
    "CharacterID": 102000007,
    "EquippedOutfit": [211033021, 204050001, 203000182, 214034012, 205034044],
    "EquippedSkills": [
      "Rafael",
      "Jota",
      "Misha",
      "K"
    ]
  },
  "GuildInfo": {
    "GuildCapacity": 55,
    "GuildID": "3001867085",
    "GuildLevel": 7,
    "GuildMember": 38,
    "GuildName": "LEAKㅤSTUDIO",
    "GuildOwner": 663660642
  },
  "GuildLeaderInfo": {
    "AccountAvatarId": 902000291,
    "AccountBPBadges": 8,
    "AccountBPID": 1001000089,
    "AccountBannerId": 901000261,
    "AccountCreateTime": "20/01/2019 (05:28:45 PM)",
    "AccountEXP": 4166666,
    "AccountId": "663660642",
    "AccountLastLogin": "15/10/2025 (07:26:13 AM)",
    "AccountLevel": 74,
    "AccountLikes": 62851,
    "AccountName": "LSㅤRAMIL",
    "AccountPinID": "910000013",
    "AccountRegion": "BD",
    "AccountSeasonId": 47,
    "BrMaxRank": 320,
    "BrRankPoint": 3430,
    "CsMaxRank": 313,
    "CsRankPoint": 48,
    "EquippedWeapon": [907105025, 912034001, 914000002],
    "ShowBrRank": true,
    "ShowCsRank": true,
    "Title": "6 Years Old"
  },
  "api_usage": "6/300",
  "creditScoreInfo": {
    "CreditScore": 100,
    "periodicSummaryEndTime": "18/10/2025 (07:26:15 AM)",
    "periodicSummaryStartTime": "15/10/2025 (07:26:15 AM)"
  },
  "petInfo": {
    "id": 1300000071,
    "isMarkedStar": true,
    "isSelected": true,
    "level": 7,
    "name": "Sarawat",
    "original_name": "Poring",
    "selectedSkillId": 1315000006,
    "skinId": 1310000074,
    "xp": 6005
  },
  "socialinfo": {
    "AccountLanguage": "Language_3",
    "AccountPreferMode": "Prefermode_BR",
    "AccountSignature": "Game Master - FreeFire TW-CN Region"
  }
}
```


# 🎫 Wishlist Items
API Route = https://url/wishlist/{region}/{uid}&key={key}

**Endpoint:** `api/wishlistitems`
**key:** `@`
**Method:** `GET`  

### ☑️ Query Parameters

| Parameter | Type   | Required | Description                   |
|-----------|--------|----------|-------------------------------|
| `region`  | string | Yes      | The region code (`sg`, `bd`, `ind`, `br`,`id`, `tw`, `us`, `na`, `sac`, `th`, `vn`, `me`, `pk`, `cis`, `eu`).|
| `uid`     | int | Yes      | The user ID.                  |
| `key`     | string | Yes      | Join https://t.me/freefirelikeinfo to get Latest Key.                  |

### 📨 Request Example
```http
GET  https://url/wishlist/bd/663660642&key=@freefirelikeinfo
```
### 💬 Response Example
```json
{
  "WishListItem": [
    {
      "ItemID": "203000036",
      "Date": "2024-25-05, 11:30 PM"
    },
    {
      "ItemID": "203000207",
      "Date": "2024-25-05, 11:30 PM"
    },
    {
      "ItemID": "203000321",
      "Date": "2024-25-05, 11:30 PM"
    },
    {
      "ItemID": "203000431",
      "Date": "2024-25-05, 11:30 PM"
    },
    {
      "ItemID": "203000744",
      "Date": "2024-25-05, 11:30 PM"
    },
    {
      "ItemID": "203038056",
      "Date": "2024-25-05, 11:30 PM"
    },
    {
      "ItemID": "203038057",
      "Date": "2024-25-05, 11:30 PM"
    }
  ]
}
```


# 👨‍👨‍👦‍👦 Guild Information
API Route =  https://url/guild/{region}/{guild_id}&key={key}

**Endpoint:** `api/guildinfo`
**key:** `@freefirelikeinfo`
**Method:** `GET`  
**Description:** Retrieve detailed information about FreeFire guilds by querying this API with the guild's region and ID. Receive data such as guild name, creation date, level, member count, and more in JSON format.

### ☑️ Query Parameters

| Parameter | Type   | Required | Description                   |
|-----------|--------|----------|-------------------------------|
| `region`  | string | Yes      | The region code (`sg`, `bd`, `ind`, `br`,`id`, `tw`, `us`, `na`, `sac`, `th`, `vn`, `me`, `pk`, `cis`, `eu`).|
| `guild_id`     | int | Yes      | The user ID.                  |
| `key`     | string | Yes      | Join https://t.me/freefirelikeinfo to get Latest Key.                  |

### 📨 Request Example
```http
GET  https://url/guild/bd/3001867085&key=@freefirelikeinfo
```
### 💬 Response Example
```json
{
  "GuildInfo": {
    "GuildActivityPoint": "4277769",
    "GuildCapacity": 55,
    "GuildCreateTime": "2020-10-01 11:30 PM",
    "GuildCurrentMembers": 52,
    "GuildId": "3001867085",
    "GuildLeaderUID": "663660642",
    "GuildLevel": 7,
    "GuildName": "LEAKㅤSTUDIO",
    "GuildPastGlory": "3421989",
    "GuildRegion": "BD",
    "GuildSlogan": "We Don't Play, We Slay!",
    "GuildWeeklyActivityPoint": 87472
  }
}
```





# 😵 Error Responses
API may return error responses for inaccurate requests.

**Error Codes and Solutions:**
- **400 (Invalid region)**: Ensure you are using a valid region code.
- **429 (Excessive requests)**: Reduce request frequency to avoid being blocked. Contact the provider if needed.
- **500 (Request error)**: Verify your user ID and region, then try again. Contact the provider if the issue persists.

---

API Made By Mostafa Nayem (@leakstudio),
All Rights Reserved!
