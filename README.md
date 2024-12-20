# 📝 API Documentation

##  Account Information API
API Route = https://ffinfo.ohxia.xyz/api/{region}/{playerid}?key={key}

**Endpoint:** `api/`
**key:** `@leakstudio`
**Method:** `GET`  

This Endpoint Retrieves Account Information based on the Specified Region and User ID.

### 📨 Request Example
```http
GET https://ffinfo.ohxia.xyz/api/bd/12345678?key=@leakstudio
```

### ☑️ Query Parameters

| Parameter | Type   | Required | Description                   |
|-----------|--------|----------|-------------------------------|
| `region`  | string | Yes      | The region code (`sg`, `bd`, `ind`, `br`,`id`, `tw`, `us`, `sac`, `th`, `me`, `pk`, `cis`).|
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
  "data": {
    "AccountInfo": {
      "AccountAvatarId": "https://cdn.ohxia.xyz/item-icon?itemID=901027035.png",
      "AccountBPBadges": 100,
      "AccountBPID": 1001000079,
      "AccountBannerId": "https://cdn.ohxia.xyz/item-icon?itemID=902027015.png",
      "AccountCreateTime": "20-01-2019 05:28 PM",
      "AccountEXP": 3906521,
      "AccountId": "123456789",
      "AccountLastLogin": "05-12-2024 01:57 PM",
      "AccountLevel": 73,
      "AccountLikes": 33687,
      "AccountName": "LSㅤNAYEM",
      "AccountRegion": "BD",
      "AccountSeasonId": 42,
      "AccountType": 1,
      "BrMaxRank": 221,
      "BrRankPoint": 4244,
      "CsMaxRank": 206,
      "CsRankPoint": 19,
      "EquippedWeapon": [
        "https://cdn.ohxia.xyz/item-icon?itemID=907192407.png",
        "https://cdn.ohxia.xyz/item-icon?itemID=912000003.png",
        "https://cdn.ohxia.xyz/item-icon?itemID=914000002.png"
      ],
      "ReleaseVersion": "OB47",
      "ShowBrRank": true,
      "ShowCsRank": true,
      "Title": 904190035
    },
    "AccountProfileInfo": {
      "EquippedOutfit": [
        "https://cdn.ohxia.xyz/item-icon?itemID=214034012.png",
        "https://cdn.ohxia.xyz/item-icon?itemID=205034046.png",
        "https://cdn.ohxia.xyz/item-icon?itemID=211033021.png",
        "https://cdn.ohxia.xyz/item-icon?itemID=204000882.png",
        "https://cdn.ohxia.xyz/item-icon?itemID=211000168.png",
        "https://cdn.ohxia.xyz/item-icon?itemID=203000182.png"
      ],
      "EquippedSkills": [16, 706, 8, 1, 16, 2405, 8, 2, 16, 606, 8, 3, 16, 3406]
    },
    "GuildInfo": {
      "GuildCapacity": 55,
      "GuildID": "3001867085",
      "GuildLevel": 7,
      "GuildMember": 52,
      "GuildName": "LEAKㅤSTUDIO",
      "GuildOwner": 123456789
    },
   "GuildLeaderInfo": {
      "AccountAvatarId": "https://cdn.ohxia.xyz/item-icon?itemID=901027035.png",
      "AccountBPBadges": 46,
      "AccountBPID": 1001000079,
      "AccountBannerId": "https://cdn.ohxia.xyz/item-icon?itemID=902027015.png",
      "AccountCreateTime": "20-01-2019 05:28 PM",
      "AccountEXP": 3921048,
      "AccountId": "663660642",
      "AccountLastLogin": "13-12-2024 08:31 AM",
      "AccountLevel": 73,
      "AccountLikes": 34451,
      "AccountName": "LSㅤNAYEM",
      "AccountRegion": "BD",
      "AccountSeasonId": 42,
      "BrMaxRank": 222,
      "BrRankPoint": 4906,
      "CsMaxRank": 207,
      "CsRankPoint": 23,
      "EquippedWeapon": [
        "https://cdn.ohxia.xyz/item-icon?itemID=907104701.png",
        "https://cdn.ohxia.xyz/item-icon?itemID=912000003.png",
        "https://cdn.ohxia.xyz/item-icon?itemID=914000002.png"
      ],
      "ShowBrRank": true,
      "ShowCsRank": true,
      "Title": 904190035
    },
    "creditScoreInfo": {
      "creditScore": 100
    },
    "petInfo": {
      "exp": 6005,
      "id": "https://cdn.ohxia.xyz/item-icon?itemID=1300000071.png",
      "isMarkedStar": true,
      "isSelected": true,
      "level": 7,
      "name": "Poring",
      "selectedSkillId": "https://cdn.ohxia.xyz/item-icon?itemID=1315000006.png",
      "skinId": "https://cdn.ohxia.xyz/item-icon?itemID=1310000074.png"
    },
    "socialinfo": {
      "AccountLanguage": "Language_3",
      "AccountPreferMode": "Prefermode_BR",
      "AccountSignature": "GM - Leak Studio Server"
    }
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
