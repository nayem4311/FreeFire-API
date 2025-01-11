# 📝 API Documentation

##  Account Information API
API Route = https://api-freefire.leakstudio.site/info?uid={uid}&region={region}&key={key}

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
| `region`  | string | Yes      | The region code (`sg`, `bd`, `ind`, `br`,`id`, `tw`, `us`, `na`, `sac`, `th`, `vn`, `me`, `pk`, `cis` ).|
| `uid`     | int | Yes      | The user ID.                  |
| `key`     | string | Yes      | Join https://t.me/leakstudio to get Latest Key.                  |


📚 **API Purpose**

The goal of this free API is to enrich the Free Fire community by offering access to account data that is not available through official channels. Since Garena Free Fire does not provide an official account information API, this custom solution serves as a valuable resource for players and developers seeking detailed account data.


# 📁 Additional Information

- This API response Does not Represent the Actual Structure Received from the Official Garena Server.
- The Response structure is simplified in an User-Friendly Structure for the ease of understanding for Anyone at any level of Programming.
- All images related to item IDs shown by the API response (e.g., avatars, banners, outfits, weapons) are available at `https://cdn.ohxia.xyz/item-icon?itemID={item_id}.png` for the convenience of API users in their development projects.


### 💬 Example of a Successful Reponse May Look Like this,
```json
{
  "AccountInfo": {
    "AccountAvatarId": "https://dl-dir.leakstudio.site/icons/901045005.png",
    "AccountBPBadges": 104,
    "AccountBPID": 1001000079,
    "AccountBannerId": "https://dl-dir.leakstudio.site/icons/902000154.png",
    "AccountCreateTime": "06/12/2017 (09:19:29 PM)",
    "AccountEXP": 1957062,
    "AccountId": "12345678",
    "AccountLastLogin": "30/12/2024 (02:57:37 PM)",
    "AccountLevel": 66,
    "AccountLikes": 3402716,
    "AccountName": "FB:ㅤ@GMRemyX",
    "AccountRegion": "SG",
    "AccountSeasonId": 42,
    "AccountType": 1,
    "BrMaxRank": 212,
    "BrRankPoint": 2323,
    "CsMaxRank": 219,
    "CsRankPoint": 88,
    "EquippedWeapon": [
      "https://dl-dir.leakstudio.site/icons/907103421.png",
      "https://dl-dir.leakstudio.site/icons/912041002.png",
      "https://dl-dir.leakstudio.site/icons/914047002.png"
    ],
    "ReleaseVersion": "OB47",
    "Role": 4,
    "ShowBrRank": true,
    "ShowCsRank": true,
    "Title": 904090023,
    "hasElitePass": true
  },
  "AccountProfileInfo": {
    "EquippedOutfit": [
      "https://dl-dir.leakstudio.site/icons/205000059.png",
      "https://dl-dir.leakstudio.site/icons/211047009.png",
      "https://dl-dir.leakstudio.site/icons/211001242.png",
      "https://dl-dir.leakstudio.site/icons/203047007.png",
      "https://dl-dir.leakstudio.site/icons/204000884.png",
      "https://dl-dir.leakstudio.site/icons/214047001.png"
    ],
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
    "AccountAvatarId": "https://dl-dir.leakstudio.site/icons/901045005.png",
    "AccountBPBadges": 104,
    "AccountBPID": 1001000079,
    "AccountBannerId": "https://dl-dir.leakstudio.site/icons/902000154.png",
    "AccountCreateTime": "06/12/2017 (09:19:29 PM)",
    "AccountEXP": 1957062,
    "AccountId": "12345678",
    "AccountLastLogin": "30/12/2024 (02:57:37 PM)",
    "AccountLevel": 66,
    "AccountLikes": 3402716,
    "AccountName": "FB:ㅤ@GMRemyX",
    "AccountRegion": "SG",
    "AccountSeasonId": 42,
    "BrMaxRank": 212,
    "BrRankPoint": 2323,
    "CsMaxRank": 219,
    "CsRankPoint": 88,
    "EquippedWeapon": [
      "https://dl-dir.leakstudio.site/icons/907103421.png",
      "https://dl-dir.leakstudio.site/icons/912041002.png",
      "https://dl-dir.leakstudio.site/icons/914047002.png"
    ],
    "ShowBrRank": true,
    "ShowCsRank": true,
    "Title": 904090023
  },
  "creditScoreInfo": {
    "CreditScore": 100
  },
  "petInfo": {
    "id": "https://dl-dir.leakstudio.site/icons/1300000071.png",
    "isSelected": true,
    "level": 7,
    "name": "SiNo",
    "selectedSkillId": "https://dl-dir.leakstudio.site/icons/1315000009.png",
    "skinId": "https://dl-dir.leakstudio.site/icons/1310000071.png",
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
