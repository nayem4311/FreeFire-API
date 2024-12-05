# 📝 API Documentation

##  Account Information API
API Route = https://cdn.ohxia.xyz/{region}/{playerid}?key={key}

**Endpoint:** `api/`
**key:** `@leakstudio`
**Method:** `GET`  

This Endpoint Retrieves Account Information based on the Specified Region and User ID.

### 📨 Request Example
```http
GET https://cdn.ohxia.xyz/bd/663660642?key=XiaoNayem6811
```

### ☑️ Query Parameters

| Parameter | Type   | Required | Description                   |
|-----------|--------|----------|-------------------------------|
| `region`  | string | Yes      | The region code (`sg`, `bd`, `ind`, `br`,`id`, `tw`, `us`, `sac`, `th`, `me`, `pk`, `cis`).|
| `uid`     | int | Yes      | The user ID.                  |
| `key`     | string | Yes      | Join https://t.me/leakstudio to get Latest Key.                  |


📚 **Purpose of the API**  

The primary purpose of providing this free API is to enhance the Free Fire community experience. Garena Free Fire does not offer official account information APIs, so this custom solution aims to fill that gap, providing players and developers with valuable account data


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
# 😵 Error Responses
API might Show Error Response Upon Users' Inaccurate Requests!

### Error Instances and Solutions

- **Error Code:** 400
  - **Message:** Invalid region.
  - **Solution:** Make sure you are using a valid region code.

- **Error Code:** 429
  - **Message:** Abnormal Requests Detected. Please Avoid Misusing Info API for Visits or Your IP may get Blocked!
  - **Solution:** Avoid excessive requests or contact the API provider for assistance.

- **Error Code:** 500
  - **Message:** An error occurred while processing your request. Please Recheck Your ID & Region.
  - **Solution:** Double-check the provided user ID and region, and retry the request. If the issue persists, contact the API provider for support.

---

API Made By Mostafa Nayem (@leakstudio),
All Rights Reserved!
