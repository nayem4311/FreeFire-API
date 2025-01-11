# 📝 API Documentation

##  Account Information API
API Route = https://accinfo.leakstudio.site/info?uid={uid}&region={region}&key={key}

**Endpoint:** `/info`
**key:** `@leakstudio`
**Method:** `GET`  

This Endpoint Retrieves Account Information based on the Specified Region and User ID.

### 📨 Request Example
```http
GET https://accinfo.leakstudio.site/info?uid=663660642&region=bd&key=@leakstudio
```

### ☑️ Query Parameters

| Parameter | Type   | Required | Description                   |
|-----------|--------|----------|-------------------------------|
| `region`  | string | Yes      | The region code (`sg`, `bd`, `ind`, `br`,`id`, `tw`, `us`, `na`, `sac`, `th`, `vn`, `me`, `pk`, `cis` , `eu`).|
| `uid`     | int | Yes      | The user ID.                  |
| `key`     | string | Yes      | Join https://t.me/leakstudio to get Latest Key.                  |


📚 **API Purpose**

The goal of this free API is to enrich the Free Fire community by offering access to account data that is not available through official channels. Since Garena Free Fire does not provide an official account information API, this custom solution serves as a valuable resource for players and developers seeking detailed account data.


# 📁 Additional Information

- This API response Does not Represent the Actual Structure Received from the Official Garena Server.
- The Response structure is simplified in an User-Friendly Structure for the ease of understanding for Anyone at any level of Programming.

### 💬 Example of a Successful Reponse May Look Like this,
```json
{
  "AccountInfo": {
    "AccountAvatarId": 902000154,
    "AccountBPBadges": 34,
    "AccountBPID": 1001000080,
    "AccountBannerId": 901045005,
    "AccountCreateTime": "06/12/2017 (09:19:29 PM)",
    "AccountEXP": 1963009,
    "AccountId": "12345678",
    "AccountLastLogin": "11/01/2025 (07:17:35 AM)",
    "AccountLevel": 66,
    "AccountLikes": 3403821,
    "AccountName": "FB:ㅤ@GMRemyX",
    "AccountRegion": "SG",
    "AccountSeasonId": 43,
    "AccountType": 1,
    "BrMaxRank": 211,
    "BrRankPoint": 2136,
    "CsMaxRank": 220,
    "CsRankPoint": 108,
    "EquippedWeapon": [907103421, 912041002, 914047001],
    "ReleaseVersion": "OB47",
    "Role": 4,
    "ShowBrRank": true,
    "ShowCsRank": true,
    "Title": 904090023
  },
  "AccountProfileInfo": {
    "EquippedOutfit": [211047026, 203047016, 204000884, 211001242, 214047001, 205047007],
    "EquippedSkills": [16, 706, 8, 1, 16, 3806, 8, 2, 16, 2506, 8, 3, 16, 1706]
  },
  "GuildInfo": {
    "GuildCapacity": 55,
    "GuildID": "60893361",
    "GuildLevel": 7,
    "GuildMember": 50,
    "GuildName": "MᴜᴍᴍʏEᴠᴀTᴇᴀᴍ",
    "GuildOwner": 12345678
  },
  "GuildLeaderInfo": {
    "AccountAvatarId": 902000154,
    "AccountBPBadges": 34,
    "AccountBPID": 1001000080,
    "AccountBannerId": 901045005,
    "AccountCreateTime": "06/12/2017 (09:19:29 PM)",
    "AccountEXP": 1963009,
    "AccountId": "12345678",
    "AccountLastLogin": "11/01/2025 (07:17:35 AM)",
    "AccountLevel": 66,
    "AccountLikes": 3403821,
    "AccountName": "FB:ㅤ@GMRemyX",
    "AccountRegion": "SG",
    "AccountSeasonId": 43,
    "BrMaxRank": 211,
    "BrRankPoint": 2136,
    "CsMaxRank": 220,
    "CsRankPoint": 108,
    "EquippedWeapon": [907103421, 912041002, 914047001],
    "ShowBrRank": true,
    "ShowCsRank": true,
    "Title": 904090023
  },
  "creditScoreInfo": {
    "CreditScore": 100
  },
  "petInfo": {
    "id": 1300000071,
    "isSelected": true,
    "level": 7,
    "name": "SiNo",
    "selectedSkillId": 1315000009,
    "skinId": 1310000071,
    "xp": 6000
  },
  "socialinfo": {
    "AccountLanguage": "Language_English",
    "AccountPreferMode": "Prefermode_BR",
    "AccountSignature": "FB & YT GM Remy | TikTok :gmremyx | IG GM Remy"
  }
}
```


# 🎫 Wishlist Items
API Route = https://wishlist.leakstudio.site/api/wishlistitems/{region}/{playerid}?key={key}

**Endpoint:** `api/wishlistitems`
**key:** `@leakstudio`
**Method:** `GET`  

### ☑️ Query Parameters

| Parameter | Type   | Required | Description                   |
|-----------|--------|----------|-------------------------------|
| `region`  | string | Yes      | The region code (`sg`, `bd`, `ind`, `br`,`id`, `tw`, `us`, `sac`, `th`, `me`, `pk`, `cis`).|
| `uid`     | int | Yes      | The user ID.                  |
| `key`     | string | Yes      | Join https://t.me/leakstudio to get Latest Key.                  |

### 📨 Request Example
```http
GET  https://wishlist.leakstudio.site/wishlistitems/bd/12345678?key=@leakstudio
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
API Route =  https://guild.leakstudio.site/api/guildinfo/{region}/{playerid}?key={key}

**Endpoint:** `api/guildinfo`
**key:** `@leakstudio`
**Method:** `GET`  
**Description:** Retrieve detailed information about FreeFire guilds by querying this API with the guild's region and ID. Receive data such as guild name, creation date, level, member count, and more in JSON format.

### ☑️ Query Parameters

| Parameter | Type   | Required | Description                   |
|-----------|--------|----------|-------------------------------|
| `region`  | string | Yes      | The region code (`sg`, `bd`, `ind`, `br`,`id`, `tw`, `us`, `sac`, `th`, `me`, `pk`, `cis`).|
| `uid`     | int | Yes      | The user ID.                  |
| `key`     | string | Yes      | Join https://t.me/leakstudio to get Latest Key.                  |

### 📨 Request Example
```http
GET  https://guild.leakstudio.site/api/guildinfo/bd/3001867085?key=@leakstudio
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
