# 📝 API Documentation

##  Account Information API
API Route = https://api-freefire.leakstudio.site/info?uid={uid}&region={region}&key={key}

**Endpoint:** `/info`
**key:** `@leakstudio`
**Method:** `GET`  

This Endpoint Retrieves Account Information based on the Specified Region and User ID.

### 📨 Request Example
```http
GET https://api-freefire.leakstudio.site/info?uid=663660642&region=bd&key=@leakstudio
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
    "AccountAvatarId": "https://dl-dir.leakstudio.site/icons/901027035.png",
    "AccountBPBadges": 91,
    "AccountBPID": 1001000079,
    "AccountBannerId": "https://dl-dir.leakstudio.site/icons/902027015.png",
    "AccountCreateTime": "20/01/2019 (11:28:45 AM)",
    "AccountEXP": 3939946,
    "AccountId": "663660642",
    "AccountLastLogin": "29/12/2024 (04:42:30 PM)",
    "AccountLevel": 73,
    "AccountLikes": 36129,
    "AccountName": "LSㅤNAYEM",
    "AccountRegion": "BD",
    "AccountSeasonId": 42,
    "AccountType": 1,
    "BrMaxRank": 223,
    "BrRankPoint": 5377,
    "CsMaxRank": 207,
    "CsRankPoint": 23,
    "EquippedWeapon": [
      "https://dl-dir.leakstudio.site/icons/907192407.png",
      "https://dl-dir.leakstudio.site/icons/912000003.png",
      "https://dl-dir.leakstudio.site/icons/914000002.png"
    ],
    "ReleaseVersion": "OB47",
    "ShowBrRank": true,
    "ShowCsRank": true,
    "Title": 904190035
  },
  "AccountProfileInfo": {
    "EquippedOutfit": [
      "https://dl-dir.leakstudio.site/icons/203035056.png",
      "https://dl-dir.leakstudio.site/icons/211033074.png",
      "https://dl-dir.leakstudio.site/icons/203033060.png",
      "https://dl-dir.leakstudio.site/icons/214033014.png",
      "https://dl-dir.leakstudio.site/icons/205033050.png",
      "https://dl-dir.leakstudio.site/icons/211033045.png",
      "https://dl-dir.leakstudio.site/icons/204033046.png"
    ],
    "EquippedSkills": [16, 706, 8, 1, 16, 1806, 8, 2, 16, 606, 8, 3, 16, 3406]
  },
  "GuildInfo": {
    "GuildCapacity": 55,
    "GuildID": "3001867085",
    "GuildLevel": 7,
    "GuildMember": 47,
    "GuildName": "LEAKㅤSTUDIO",
    "GuildOwner": 663660642
  },
  "GuildLeaderInfo": {
    "AccountAvatarId": "https://dl-dir.leakstudio.site/icons/901027035.png",
    "AccountBPBadges": 91,
    "AccountBPID": 1001000079,
    "AccountBannerId": "https://dl-dir.leakstudio.site/icons/902027015.png",
    "AccountCreateTime": "20/01/2019 (11:28:45 AM)",
    "AccountEXP": 3939946,
    "AccountId": "663660642",
    "AccountLastLogin": "29/12/2024 (04:42:30 PM)",
    "AccountLevel": 73,
    "AccountLikes": 36129,
    "AccountName": "LSㅤNAYEM",
    "AccountRegion": "BD",
    "AccountSeasonId": 42,
    "BrMaxRank": 223,
    "BrRankPoint": 5377,
    "CsMaxRank": 207,
    "CsRankPoint": 23,
    "EquippedWeapon": [
      "https://dl-dir.leakstudio.site/icons/907192407.png",
      "https://dl-dir.leakstudio.site/icons/912000003.png",
      "https://dl-dir.leakstudio.site/icons/914000002.png"
    ],
    "ShowBrRank": true,
    "ShowCsRank": true,
    "Title": 904190035
  },
  "creditScoreInfo": {
    "CreditScore": 100
  },
  "petInfo": {
    "id": "https://dl-dir.leakstudio.site/icons/1300000071.png",
    "isMarkedStar": true,
    "isSelected": true,
    "level": 7,
    "name": "Sarawat",
    "selectedSkillId": "https://dl-dir.leakstudio.site/icons/1315000006.png",
    "skinId": "https://dl-dir.leakstudio.site/icons/1310000074.png",
    "xp": 6005
  },
  "socialinfo": {
    "AccountLanguage": "Language_3",
    "AccountPreferMode": "Prefermode_BR",
    "AccountSignature": "GM - FreeFire Debug Server"
  }
}
```


# 🎫 Wishlist Items
API Route = https://ffinfo.ohxia.xyz/api/wishlistitems/{region}/{playerid}?key={key}

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
GET https://ffinfo.ohxia.xyz/api/wishlistitems/bd/12345678?key=@leakstudio
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
API Route = https://ffinfo.ohxia.xyz/api/guildinfo/{region}/{playerid}?key={key}

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
GET https://ffinfo.ohxia.xyz/api/guildinfo/bd/3001867085?key=@leakstudio
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
