# Failed Concert Poster Extractions Report

*Analysis of 122 posters where extraction completely failed*

This report analyzes posters where the AI extraction returned completely empty results, helping identify patterns in extraction failures and data quality issues.

**Report Categories:**
- 🚨 **Extraction Failures**: Good ground truth data but complete extraction failure
- ⚠️ **Partial GT Data**: Some ground truth available but extraction failed  
- 📝 **Incomplete Labeling**: Very little ground truth data available


## Failed Extraction Analysis

### Overview
- **Total Failed Extractions:** 122
- **Extraction Failures:** 4 (had sufficient GT data)
- **Partial GT Data:** 118 (some GT data available)
- **Incomplete Labeling:** 0 (very little GT data)

### Failure Categories
- 🚨 **Extraction Failures:** Posters with good ground truth data but complete extraction failure
- ⚠️ **Partial GT Data:** Posters with some ground truth data but failed extraction
- 📝 **Incomplete Labeling:** Posters that may not have been properly labeled

### Ground Truth Data Availability by Field

| Field | Available GT | Percentage |
|-------|--------------|------------|
| ✅ Dates | 122/122 | 100.0% |
| ✅ Times | 122/122 | 100.0% |
| ❌ Venue | 4/122 | 3.3% |
| ❌ Title | 4/122 | 3.3% |
| ❌ Artists | 4/122 | 3.3% |
| ❌ City | 4/122 | 3.3% |
| ❌ Mode | 4/122 | 3.3% |
| ❌ Contact No | 4/122 | 3.3% |
| ❌ Contact Email | 1/122 | 0.8% |
| ❌ Streaming Url | 0/122 | 0.0% |

**Legend:**
- ✅ **Good availability** (70%+ of failed cases have GT data)
- ⚠️ **Partial availability** (30-69% of failed cases have GT data)  
- ❌ **Poor availability** (<30% of failed cases have GT data)

---


---

## ❌ Poster #1 - 🚨 **EXTRACTION FAILURE**

**File Name:** `CT-Sangeet Baithak #46-Shri. Prathamesh Choudhury (Vocal)-.jpg`  
**Available GT Fields:** 8/10

This poster has sufficient ground truth data but extraction completely failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-Sangeet%20Baithak%20%2346-Shri.%20Prathamesh%20Choudhury%20%28Vocal%29-.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-Sangeet%20Baithak%20%2346-Shri.%20Prathamesh%20Choudhury%20%28Vocal%29-.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | November 17, 2024 | ✅ |
| Times | ❌ *Empty* | 6:00 PM to 8:00 PM | ✅ |
| Venue | ❌ *Empty* | SJR Equinox, Electronic City Phase 1, Bengaluru | ✅ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | Sangeet Baithak #46 | ✅ |
| Artists | ❌ *Empty* | Shri. Prathamesh Choudhury (Vocal) | ✅ |
| City | ❌ *Empty* | Bengaluru | ✅ |
| Mode | ❌ *Empty* | Offline | ✅ |
| Contact No | ❌ *Empty* | 9845817900 / 9739917900 | ✅ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "672ee8452426c41d1b6fdccd"
  },
  "Date": "November 17, 2024",
  "EndDate": "November 17, 2024",
  "Time": "6:00 PM to 8:00 PM",
  "Venue": "SJR Equinox, Electronic City Phase 1, Bengaluru",
  "StreamingUrl": "",
  "Title": "Sangeet Baithak #46",
  "Artists": "Shri. Prathamesh Choudhury (Vocal)",
  "OtherArtists": "Vid. Anand HS (Tabla), Vid. Alok Sarkar (Harmonium)",
  "Type": "Hindustani",
  "City": "Bengaluru",
  "Locality": "Electronic City",
  "Mode": "Offline",
  "Contactno": "9845817900 / 9739917900",
  "Contactemail": "",
  "ContactWeb": "",
  "Status": "Approved",
  "Poster": "CT-Sangeet Baithak #46-Shri. Prathamesh Choudhury (Vocal)-.jpg",
  "__v": 0
}
```

</details>


---

## ❌ Poster #2 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67cec13df4e510d8511f29b0--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67cec13df4e510d8511f29b0--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67cec13df4e510d8511f29b0--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-10 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67cec13df4e510d8511f29b0"
  },
  "Date": "2025-03-10",
  "EndDate": "2025-03-10",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67cec13df4e510d8511f29b0--.jpg"
}
```

</details>


---

## ❌ Poster #3 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67cec3e4f4e510d8511f2dfd--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67cec3e4f4e510d8511f2dfd--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67cec3e4f4e510d8511f2dfd--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-10 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67cec3e4f4e510d8511f2dfd"
  },
  "Date": "2025-03-10",
  "EndDate": "2025-03-10",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67cec3e4f4e510d8511f2dfd--.jpg"
}
```

</details>


---

## ❌ Poster #4 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67cec409f4e510d8511f2eb7--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67cec409f4e510d8511f2eb7--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67cec409f4e510d8511f2eb7--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-10 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67cec409f4e510d8511f2eb7"
  },
  "Date": "2025-03-10",
  "EndDate": "2025-03-10",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67cec409f4e510d8511f2eb7--.jpg"
}
```

</details>


---

## ❌ Poster #5 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67cec41bf4e510d8511f2ebe--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67cec41bf4e510d8511f2ebe--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67cec41bf4e510d8511f2ebe--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-10 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67cec41bf4e510d8511f2ebe"
  },
  "Date": "2025-03-10",
  "EndDate": "2025-03-10",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67cec41bf4e510d8511f2ebe--.jpg"
}
```

</details>


---

## ❌ Poster #6 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67cfdda3f4e510d8511f349b--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67cfdda3f4e510d8511f349b--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67cfdda3f4e510d8511f349b--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-11 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67cfdda3f4e510d8511f349b"
  },
  "Date": "2025-03-11",
  "EndDate": "2025-03-11",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67cfdda3f4e510d8511f349b--.jpg"
}
```

</details>


---

## ❌ Poster #7 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67d01658f4e510d8511f3589--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d01658f4e510d8511f3589--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d01658f4e510d8511f3589--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-11 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67d01658f4e510d8511f3589"
  },
  "Date": "2025-03-11",
  "EndDate": "2025-03-11",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67d01658f4e510d8511f3589--.jpg"
}
```

</details>


---

## ❌ Poster #8 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67d016bff4e510d8511f3590--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d016bff4e510d8511f3590--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d016bff4e510d8511f3590--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-11 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67d016bff4e510d8511f3590"
  },
  "Date": "2025-03-11",
  "EndDate": "2025-03-11",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67d016bff4e510d8511f3590--.jpg"
}
```

</details>


---

## ❌ Poster #9 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67d263cc23068f2c9440e3ec--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d263cc23068f2c9440e3ec--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d263cc23068f2c9440e3ec--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-13 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67d263cc23068f2c9440e3ec"
  },
  "Date": "2025-03-13",
  "EndDate": "2025-03-13",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "672c53ce8f7ccba25159bbf1"
  },
  "__v": 0,
  "Poster": "CT-67d263cc23068f2c9440e3ec--.jpg"
}
```

</details>


---

## ❌ Poster #10 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67d264f523068f2c9440e3ff--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d264f523068f2c9440e3ff--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d264f523068f2c9440e3ff--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-13 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67d264f523068f2c9440e3ff"
  },
  "Date": "2025-03-13",
  "EndDate": "2025-03-13",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "672c53ce8f7ccba25159bbf1"
  },
  "__v": 0,
  "Poster": "CT-67d264f523068f2c9440e3ff--.jpg"
}
```

</details>


---

## ❌ Poster #11 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67d28acd23068f2c9440e42a--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d28acd23068f2c9440e42a--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d28acd23068f2c9440e42a--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-13 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67d28acd23068f2c9440e42a"
  },
  "Date": "2025-03-13",
  "EndDate": "2025-03-13",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67d28acd23068f2c9440e42a--.jpg"
}
```

</details>


---

## ❌ Poster #12 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67d28aeb23068f2c9440e42d--.jpeg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d28aeb23068f2c9440e42d--.jpeg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d28aeb23068f2c9440e42d--.jpeg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-13 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67d28aeb23068f2c9440e42d"
  },
  "Date": "2025-03-13",
  "EndDate": "2025-03-13",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67d28aeb23068f2c9440e42d--.jpeg"
}
```

</details>


---

## ❌ Poster #13 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67d28ba123068f2c9440e430--.jpeg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d28ba123068f2c9440e430--.jpeg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d28ba123068f2c9440e430--.jpeg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-13 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67d28ba123068f2c9440e430"
  },
  "Date": "2025-03-13",
  "EndDate": "2025-03-13",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67d28ba123068f2c9440e430--.jpeg"
}
```

</details>


---

## ❌ Poster #14 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67d28c1323068f2c9440e43a--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d28c1323068f2c9440e43a--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d28c1323068f2c9440e43a--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-13 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67d28c1323068f2c9440e43a"
  },
  "Date": "2025-03-13",
  "EndDate": "2025-03-13",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67d28c1323068f2c9440e43a--.jpg"
}
```

</details>


---

## ❌ Poster #15 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67d28c2323068f2c9440e43d--.jpeg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d28c2323068f2c9440e43d--.jpeg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d28c2323068f2c9440e43d--.jpeg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-13 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67d28c2323068f2c9440e43d"
  },
  "Date": "2025-03-13",
  "EndDate": "2025-03-13",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67d28c2323068f2c9440e43d--.jpeg"
}
```

</details>


---

## ❌ Poster #16 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67d28c4023068f2c9440e440--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d28c4023068f2c9440e440--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d28c4023068f2c9440e440--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-13 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67d28c4023068f2c9440e440"
  },
  "Date": "2025-03-13",
  "EndDate": "2025-03-13",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67d28c4023068f2c9440e440--.jpg"
}
```

</details>


---

## ❌ Poster #17 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67d28c6623068f2c9440e443--.jpeg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d28c6623068f2c9440e443--.jpeg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d28c6623068f2c9440e443--.jpeg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-13 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67d28c6623068f2c9440e443"
  },
  "Date": "2025-03-13",
  "EndDate": "2025-03-13",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67d28c6623068f2c9440e443--.jpeg"
}
```

</details>


---

## ❌ Poster #18 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67d28cc323068f2c9440e44d--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d28cc323068f2c9440e44d--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d28cc323068f2c9440e44d--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-13 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67d28cc323068f2c9440e44d"
  },
  "Date": "2025-03-13",
  "EndDate": "2025-03-13",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67d28cc323068f2c9440e44d--.jpg"
}
```

</details>


---

## ❌ Poster #19 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67d28cea23068f2c9440e450--.jpeg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d28cea23068f2c9440e450--.jpeg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d28cea23068f2c9440e450--.jpeg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-13 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67d28cea23068f2c9440e450"
  },
  "Date": "2025-03-13",
  "EndDate": "2025-03-13",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67d28cea23068f2c9440e450--.jpeg"
}
```

</details>


---

## ❌ Poster #20 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67d3b8da4a50939660da7e6f--.png`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d3b8da4a50939660da7e6f--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d3b8da4a50939660da7e6f--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-14 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67d3b8da4a50939660da7e6f"
  },
  "Date": "2025-03-14",
  "EndDate": "2025-03-14",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "672c53ce8f7ccba25159bbf1"
  },
  "__v": 0,
  "Poster": "CT-67d3b8da4a50939660da7e6f--.png"
}
```

</details>


---

## ❌ Poster #21 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67d3b9034a50939660da7e72--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d3b9034a50939660da7e72--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d3b9034a50939660da7e72--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-14 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67d3b9034a50939660da7e72"
  },
  "Date": "2025-03-14",
  "EndDate": "2025-03-14",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "672c53ce8f7ccba25159bbf1"
  },
  "__v": 0,
  "Poster": "CT-67d3b9034a50939660da7e72--.jpg"
}
```

</details>


---

## ❌ Poster #22 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67d3b99e4a50939660da7e7a--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d3b99e4a50939660da7e7a--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d3b99e4a50939660da7e7a--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-14 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67d3b99e4a50939660da7e7a"
  },
  "Date": "2025-03-14",
  "EndDate": "2025-03-14",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "672c53ce8f7ccba25159bbf1"
  },
  "__v": 0,
  "Poster": "CT-67d3b99e4a50939660da7e7a--.jpg"
}
```

</details>


---

## ❌ Poster #23 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67d439704a50939660da7f8b--.png`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d439704a50939660da7f8b--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d439704a50939660da7f8b--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-14 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67d439704a50939660da7f8b"
  },
  "Date": "2025-03-14",
  "EndDate": "2025-03-14",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "670e803985d561733135aad5"
  },
  "__v": 0,
  "Poster": "CT-67d439704a50939660da7f8b--.png"
}
```

</details>


---

## ❌ Poster #24 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67d922bc60dc24d86d2159e2--.JPG`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d922bc60dc24d86d2159e2--.JPG?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67d922bc60dc24d86d2159e2--.JPG?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-18 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67d922bc60dc24d86d2159e2"
  },
  "Date": "2025-03-18",
  "EndDate": "2025-03-18",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67d922bc60dc24d86d2159e2--.JPG"
}
```

</details>


---

## ❌ Poster #25 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67daae7860dc24d86d216cce--.PNG`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67daae7860dc24d86d216cce--.PNG?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67daae7860dc24d86d216cce--.PNG?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-19 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67daae7860dc24d86d216cce"
  },
  "Date": "2025-03-19",
  "EndDate": "2025-03-19",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67daae7860dc24d86d216cce--.PNG"
}
```

</details>


---

## ❌ Poster #26 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67daae8e60dc24d86d216cd1--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67daae8e60dc24d86d216cd1--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67daae8e60dc24d86d216cd1--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-19 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67daae8e60dc24d86d216cd1"
  },
  "Date": "2025-03-19",
  "EndDate": "2025-03-19",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67daae8e60dc24d86d216cd1--.jpg"
}
```

</details>


---

## ❌ Poster #27 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbc53c60dc24d86d216da1--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbc53c60dc24d86d216da1--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbc53c60dc24d86d216da1--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbc53c60dc24d86d216da1"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "672c53ce8f7ccba25159bbf1"
  },
  "__v": 0,
  "Poster": "CT-67dbc53c60dc24d86d216da1--.jpg"
}
```

</details>


---

## ❌ Poster #28 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbd8f060dc24d86d216e3a--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbd8f060dc24d86d216e3a--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbd8f060dc24d86d216e3a--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbd8f060dc24d86d216e3a"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbd8f060dc24d86d216e3a--.jpg"
}
```

</details>


---

## ❌ Poster #29 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbd93c60dc24d86d216e3d--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbd93c60dc24d86d216e3d--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbd93c60dc24d86d216e3d--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbd93c60dc24d86d216e3d"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbd93c60dc24d86d216e3d--.jpg"
}
```

</details>


---

## ❌ Poster #30 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbdd4160dc24d86d216e7f--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbdd4160dc24d86d216e7f--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbdd4160dc24d86d216e7f--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbdd4160dc24d86d216e7f"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbdd4160dc24d86d216e7f--.jpg"
}
```

</details>


---

## ❌ Poster #31 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbdd4560dc24d86d216e82--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbdd4560dc24d86d216e82--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbdd4560dc24d86d216e82--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbdd4560dc24d86d216e82"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbdd4560dc24d86d216e82--.jpg"
}
```

</details>


---

## ❌ Poster #32 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbdef960dc24d86d216e90--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbdef960dc24d86d216e90--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbdef960dc24d86d216e90--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbdef960dc24d86d216e90"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbdef960dc24d86d216e90--.jpg"
}
```

</details>


---

## ❌ Poster #33 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbdfc760dc24d86d216eb3--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbdfc760dc24d86d216eb3--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbdfc760dc24d86d216eb3--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbdfc760dc24d86d216eb3"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbdfc760dc24d86d216eb3--.jpg"
}
```

</details>


---

## ❌ Poster #34 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbdff560dc24d86d216eb6--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbdff560dc24d86d216eb6--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbdff560dc24d86d216eb6--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbdff560dc24d86d216eb6"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbdff560dc24d86d216eb6--.jpg"
}
```

</details>


---

## ❌ Poster #35 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbe05160dc24d86d216eb9--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe05160dc24d86d216eb9--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe05160dc24d86d216eb9--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbe05160dc24d86d216eb9"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbe05160dc24d86d216eb9--.jpg"
}
```

</details>


---

## ❌ Poster #36 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbe05b60dc24d86d216ebc--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe05b60dc24d86d216ebc--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe05b60dc24d86d216ebc--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbe05b60dc24d86d216ebc"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbe05b60dc24d86d216ebc--.jpg"
}
```

</details>


---

## ❌ Poster #37 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbe11960dc24d86d216ec2--.png`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe11960dc24d86d216ec2--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe11960dc24d86d216ec2--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbe11960dc24d86d216ec2"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbe11960dc24d86d216ec2--.png"
}
```

</details>


---

## ❌ Poster #38 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbe14460dc24d86d216ec5--.png`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe14460dc24d86d216ec5--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe14460dc24d86d216ec5--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbe14460dc24d86d216ec5"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbe14460dc24d86d216ec5--.png"
}
```

</details>


---

## ❌ Poster #39 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbe15860dc24d86d216ec8--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe15860dc24d86d216ec8--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe15860dc24d86d216ec8--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbe15860dc24d86d216ec8"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbe15860dc24d86d216ec8--.jpg"
}
```

</details>


---

## ❌ Poster #40 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbe19160dc24d86d216ecb--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe19160dc24d86d216ecb--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe19160dc24d86d216ecb--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbe19160dc24d86d216ecb"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbe19160dc24d86d216ecb--.jpg"
}
```

</details>


---

## ❌ Poster #41 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbe39f60dc24d86d216ece--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe39f60dc24d86d216ece--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe39f60dc24d86d216ece--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbe39f60dc24d86d216ece"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbe39f60dc24d86d216ece--.jpg"
}
```

</details>


---

## ❌ Poster #42 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbe44b60dc24d86d216edc--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe44b60dc24d86d216edc--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe44b60dc24d86d216edc--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbe44b60dc24d86d216edc"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbe44b60dc24d86d216edc--.jpg"
}
```

</details>


---

## ❌ Poster #43 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbe4cf60dc24d86d216edf--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe4cf60dc24d86d216edf--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe4cf60dc24d86d216edf--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbe4cf60dc24d86d216edf"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbe4cf60dc24d86d216edf--.jpg"
}
```

</details>


---

## ❌ Poster #44 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbe52860dc24d86d216ee2--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe52860dc24d86d216ee2--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe52860dc24d86d216ee2--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbe52860dc24d86d216ee2"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbe52860dc24d86d216ee2--.jpg"
}
```

</details>


---

## ❌ Poster #45 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbe5ad60dc24d86d216ee5--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe5ad60dc24d86d216ee5--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe5ad60dc24d86d216ee5--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbe5ad60dc24d86d216ee5"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbe5ad60dc24d86d216ee5--.jpg"
}
```

</details>


---

## ❌ Poster #46 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbe5eb60dc24d86d216ef3--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe5eb60dc24d86d216ef3--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe5eb60dc24d86d216ef3--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbe5eb60dc24d86d216ef3"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbe5eb60dc24d86d216ef3--.jpg"
}
```

</details>


---

## ❌ Poster #47 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbe5f360dc24d86d216ef6--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe5f360dc24d86d216ef6--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe5f360dc24d86d216ef6--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbe5f360dc24d86d216ef6"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbe5f360dc24d86d216ef6--.jpg"
}
```

</details>


---

## ❌ Poster #48 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbe64960dc24d86d216f04--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe64960dc24d86d216f04--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe64960dc24d86d216f04--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbe64960dc24d86d216f04"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbe64960dc24d86d216f04--.jpg"
}
```

</details>


---

## ❌ Poster #49 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbe67460dc24d86d216f07--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe67460dc24d86d216f07--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe67460dc24d86d216f07--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbe67460dc24d86d216f07"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbe67460dc24d86d216f07--.jpg"
}
```

</details>


---

## ❌ Poster #50 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbe6d860dc24d86d216f0a--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe6d860dc24d86d216f0a--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe6d860dc24d86d216f0a--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbe6d860dc24d86d216f0a"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbe6d860dc24d86d216f0a--.jpg"
}
```

</details>


---

## ❌ Poster #51 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbe73960dc24d86d216f0d--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe73960dc24d86d216f0d--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe73960dc24d86d216f0d--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbe73960dc24d86d216f0d"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbe73960dc24d86d216f0d--.jpg"
}
```

</details>


---

## ❌ Poster #52 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbe7b660dc24d86d216f10--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe7b660dc24d86d216f10--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe7b660dc24d86d216f10--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbe7b660dc24d86d216f10"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbe7b660dc24d86d216f10--.jpg"
}
```

</details>


---

## ❌ Poster #53 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbe7f960dc24d86d216f13--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe7f960dc24d86d216f13--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe7f960dc24d86d216f13--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbe7f960dc24d86d216f13"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbe7f960dc24d86d216f13--.jpg"
}
```

</details>


---

## ❌ Poster #54 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbe8df60dc24d86d216f1e--.png`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe8df60dc24d86d216f1e--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbe8df60dc24d86d216f1e--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbe8df60dc24d86d216f1e"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbe8df60dc24d86d216f1e--.png"
}
```

</details>


---

## ❌ Poster #55 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbeabb60dc24d86d216f33--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbeabb60dc24d86d216f33--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbeabb60dc24d86d216f33--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbeabb60dc24d86d216f33"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbeabb60dc24d86d216f33--.jpg"
}
```

</details>


---

## ❌ Poster #56 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbeae860dc24d86d216f36--.png`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbeae860dc24d86d216f36--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbeae860dc24d86d216f36--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbeae860dc24d86d216f36"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbeae860dc24d86d216f36--.png"
}
```

</details>


---

## ❌ Poster #57 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbeb4160dc24d86d216f39--.png`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbeb4160dc24d86d216f39--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbeb4160dc24d86d216f39--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbeb4160dc24d86d216f39"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbeb4160dc24d86d216f39--.png"
}
```

</details>


---

## ❌ Poster #58 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbeb5560dc24d86d216f3c--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbeb5560dc24d86d216f3c--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbeb5560dc24d86d216f3c--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbeb5560dc24d86d216f3c"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbeb5560dc24d86d216f3c--.jpg"
}
```

</details>


---

## ❌ Poster #59 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbeb8160dc24d86d216f3f--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbeb8160dc24d86d216f3f--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbeb8160dc24d86d216f3f--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbeb8160dc24d86d216f3f"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbeb8160dc24d86d216f3f--.jpg"
}
```

</details>


---

## ❌ Poster #60 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbebc760dc24d86d216f42--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbebc760dc24d86d216f42--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbebc760dc24d86d216f42--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbebc760dc24d86d216f42"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbebc760dc24d86d216f42--.jpg"
}
```

</details>


---

## ❌ Poster #61 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbebff60dc24d86d216f45--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbebff60dc24d86d216f45--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbebff60dc24d86d216f45--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbebff60dc24d86d216f45"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbebff60dc24d86d216f45--.jpg"
}
```

</details>


---

## ❌ Poster #62 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbec7960dc24d86d216f6b--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbec7960dc24d86d216f6b--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbec7960dc24d86d216f6b--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbec7960dc24d86d216f6b"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbec7960dc24d86d216f6b--.jpg"
}
```

</details>


---

## ❌ Poster #63 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbec9460dc24d86d216f6e--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbec9460dc24d86d216f6e--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbec9460dc24d86d216f6e--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbec9460dc24d86d216f6e"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbec9460dc24d86d216f6e--.jpg"
}
```

</details>


---

## ❌ Poster #64 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbecb260dc24d86d216f71--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbecb260dc24d86d216f71--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbecb260dc24d86d216f71--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbecb260dc24d86d216f71"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbecb260dc24d86d216f71--.jpg"
}
```

</details>


---

## ❌ Poster #65 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbecbc60dc24d86d216f74--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbecbc60dc24d86d216f74--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbecbc60dc24d86d216f74--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbecbc60dc24d86d216f74"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbecbc60dc24d86d216f74--.jpg"
}
```

</details>


---

## ❌ Poster #66 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbecd060dc24d86d216f77--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbecd060dc24d86d216f77--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbecd060dc24d86d216f77--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbecd060dc24d86d216f77"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbecd060dc24d86d216f77--.jpg"
}
```

</details>


---

## ❌ Poster #67 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbecf860dc24d86d216f7a--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbecf860dc24d86d216f7a--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbecf860dc24d86d216f7a--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbecf860dc24d86d216f7a"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbecf860dc24d86d216f7a--.jpg"
}
```

</details>


---

## ❌ Poster #68 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbed0b60dc24d86d216f7d--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbed0b60dc24d86d216f7d--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbed0b60dc24d86d216f7d--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbed0b60dc24d86d216f7d"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbed0b60dc24d86d216f7d--.jpg"
}
```

</details>


---

## ❌ Poster #69 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbed6760dc24d86d216f80--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbed6760dc24d86d216f80--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbed6760dc24d86d216f80--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbed6760dc24d86d216f80"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbed6760dc24d86d216f80--.jpg"
}
```

</details>


---

## ❌ Poster #70 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbed6d60dc24d86d216f83--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbed6d60dc24d86d216f83--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbed6d60dc24d86d216f83--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbed6d60dc24d86d216f83"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbed6d60dc24d86d216f83--.jpg"
}
```

</details>


---

## ❌ Poster #71 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbed8960dc24d86d216f91--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbed8960dc24d86d216f91--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbed8960dc24d86d216f91--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbed8960dc24d86d216f91"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbed8960dc24d86d216f91--.jpg"
}
```

</details>


---

## ❌ Poster #72 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbed9460dc24d86d216f94--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbed9460dc24d86d216f94--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbed9460dc24d86d216f94--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbed9460dc24d86d216f94"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbed9460dc24d86d216f94--.jpg"
}
```

</details>


---

## ❌ Poster #73 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbf72e60dc24d86d216fc2--.PNG`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbf72e60dc24d86d216fc2--.PNG?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbf72e60dc24d86d216fc2--.PNG?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbf72e60dc24d86d216fc2"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "670e803985d561733135aad5"
  },
  "__v": 0,
  "Poster": "CT-67dbf72e60dc24d86d216fc2--.PNG"
}
```

</details>


---

## ❌ Poster #74 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbf76760dc24d86d216fcb--.PNG`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbf76760dc24d86d216fcb--.PNG?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbf76760dc24d86d216fcb--.PNG?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbf76760dc24d86d216fcb"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "670e803985d561733135aad5"
  },
  "__v": 0,
  "Poster": "CT-67dbf76760dc24d86d216fcb--.PNG"
}
```

</details>


---

## ❌ Poster #75 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbf7f160dc24d86d216fd1--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbf7f160dc24d86d216fd1--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbf7f160dc24d86d216fd1--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbf7f160dc24d86d216fd1"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbf7f160dc24d86d216fd1--.jpg"
}
```

</details>


---

## ❌ Poster #76 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbf81160dc24d86d216fd4--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbf81160dc24d86d216fd4--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbf81160dc24d86d216fd4--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbf81160dc24d86d216fd4"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbf81160dc24d86d216fd4--.jpg"
}
```

</details>


---

## ❌ Poster #77 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbf81c60dc24d86d216ff4--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbf81c60dc24d86d216ff4--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbf81c60dc24d86d216ff4--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbf81c60dc24d86d216ff4"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbf81c60dc24d86d216ff4--.jpg"
}
```

</details>


---

## ❌ Poster #78 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbf83a60dc24d86d216fff--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbf83a60dc24d86d216fff--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbf83a60dc24d86d216fff--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbf83a60dc24d86d216fff"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbf83a60dc24d86d216fff--.jpg"
}
```

</details>


---

## ❌ Poster #79 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbfab460dc24d86d217005--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfab460dc24d86d217005--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfab460dc24d86d217005--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbfab460dc24d86d217005"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbfab460dc24d86d217005--.jpg"
}
```

</details>


---

## ❌ Poster #80 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbfabe60dc24d86d217008--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfabe60dc24d86d217008--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfabe60dc24d86d217008--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbfabe60dc24d86d217008"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbfabe60dc24d86d217008--.jpg"
}
```

</details>


---

## ❌ Poster #81 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbfb4860dc24d86d21700e--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfb4860dc24d86d21700e--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfb4860dc24d86d21700e--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbfb4860dc24d86d21700e"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbfb4860dc24d86d21700e--.jpg"
}
```

</details>


---

## ❌ Poster #82 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbfb5160dc24d86d217011--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfb5160dc24d86d217011--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfb5160dc24d86d217011--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbfb5160dc24d86d217011"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbfb5160dc24d86d217011--.jpg"
}
```

</details>


---

## ❌ Poster #83 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbfb6060dc24d86d217014--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfb6060dc24d86d217014--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfb6060dc24d86d217014--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbfb6060dc24d86d217014"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbfb6060dc24d86d217014--.jpg"
}
```

</details>


---

## ❌ Poster #84 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbfb7060dc24d86d217017--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfb7060dc24d86d217017--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfb7060dc24d86d217017--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbfb7060dc24d86d217017"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbfb7060dc24d86d217017--.jpg"
}
```

</details>


---

## ❌ Poster #85 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbfb7860dc24d86d21701a--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfb7860dc24d86d21701a--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfb7860dc24d86d21701a--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbfb7860dc24d86d21701a"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbfb7860dc24d86d21701a--.jpg"
}
```

</details>


---

## ❌ Poster #86 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbfb9a60dc24d86d217028--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfb9a60dc24d86d217028--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfb9a60dc24d86d217028--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbfb9a60dc24d86d217028"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbfb9a60dc24d86d217028--.jpg"
}
```

</details>


---

## ❌ Poster #87 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbfba360dc24d86d21702b--.png`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfba360dc24d86d21702b--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfba360dc24d86d21702b--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbfba360dc24d86d21702b"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbfba360dc24d86d21702b--.png"
}
```

</details>


---

## ❌ Poster #88 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbfbbd60dc24d86d21702e--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfbbd60dc24d86d21702e--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfbbd60dc24d86d21702e--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbfbbd60dc24d86d21702e"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbfbbd60dc24d86d21702e--.jpg"
}
```

</details>


---

## ❌ Poster #89 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dbfc9060dc24d86d217037--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfc9060dc24d86d217037--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dbfc9060dc24d86d217037--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dbfc9060dc24d86d217037"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dbfc9060dc24d86d217037--.jpg"
}
```

</details>


---

## ❌ Poster #90 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dc07ae60dc24d86d21707b--.png`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc07ae60dc24d86d21707b--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc07ae60dc24d86d21707b--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dc07ae60dc24d86d21707b"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "672c53ce8f7ccba25159bbf1"
  },
  "__v": 0,
  "Poster": "CT-67dc07ae60dc24d86d21707b--.png"
}
```

</details>


---

## ❌ Poster #91 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dc0f4f60dc24d86d217091--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc0f4f60dc24d86d217091--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc0f4f60dc24d86d217091--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dc0f4f60dc24d86d217091"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dc0f4f60dc24d86d217091--.jpg"
}
```

</details>


---

## ❌ Poster #92 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dc0f5260dc24d86d217093--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc0f5260dc24d86d217093--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc0f5260dc24d86d217093--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dc0f5260dc24d86d217093"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dc0f5260dc24d86d217093--.jpg"
}
```

</details>


---

## ❌ Poster #93 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dc0fa760dc24d86d217097--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc0fa760dc24d86d217097--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc0fa760dc24d86d217097--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dc0fa760dc24d86d217097"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dc0fa760dc24d86d217097--.jpg"
}
```

</details>


---

## ❌ Poster #94 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dc0fe360dc24d86d21709a--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc0fe360dc24d86d21709a--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc0fe360dc24d86d21709a--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dc0fe360dc24d86d21709a"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dc0fe360dc24d86d21709a--.jpg"
}
```

</details>


---

## ❌ Poster #95 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dc108d60dc24d86d21709d--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc108d60dc24d86d21709d--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc108d60dc24d86d21709d--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dc108d60dc24d86d21709d"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dc108d60dc24d86d21709d--.jpg"
}
```

</details>


---

## ❌ Poster #96 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dc10a960dc24d86d2170a0--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc10a960dc24d86d2170a0--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc10a960dc24d86d2170a0--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dc10a960dc24d86d2170a0"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dc10a960dc24d86d2170a0--.jpg"
}
```

</details>


---

## ❌ Poster #97 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dc10e060dc24d86d2170a3--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc10e060dc24d86d2170a3--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc10e060dc24d86d2170a3--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dc10e060dc24d86d2170a3"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dc10e060dc24d86d2170a3--.jpg"
}
```

</details>


---

## ❌ Poster #98 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dc143660dc24d86d2170b1--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc143660dc24d86d2170b1--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc143660dc24d86d2170b1--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dc143660dc24d86d2170b1"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dc143660dc24d86d2170b1--.jpg"
}
```

</details>


---

## ❌ Poster #99 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dc155560dc24d86d2170b4--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc155560dc24d86d2170b4--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc155560dc24d86d2170b4--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dc155560dc24d86d2170b4"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dc155560dc24d86d2170b4--.jpg"
}
```

</details>


---

## ❌ Poster #100 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dc436c60dc24d86d2170e6--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc436c60dc24d86d2170e6--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dc436c60dc24d86d2170e6--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-20 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dc436c60dc24d86d2170e6"
  },
  "Date": "2025-03-20",
  "EndDate": "2025-03-20",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dc436c60dc24d86d2170e6--.jpg"
}
```

</details>


---

## ❌ Poster #101 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dce0fb60dc24d86d217114--.JPG`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dce0fb60dc24d86d217114--.JPG?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dce0fb60dc24d86d217114--.JPG?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-21 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dce0fb60dc24d86d217114"
  },
  "Date": "2025-03-21",
  "EndDate": "2025-03-21",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dce0fb60dc24d86d217114--.JPG"
}
```

</details>


---

## ❌ Poster #102 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dce51d60dc24d86d21714a--.png`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dce51d60dc24d86d21714a--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dce51d60dc24d86d21714a--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-21 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dce51d60dc24d86d21714a"
  },
  "Date": "2025-03-21",
  "EndDate": "2025-03-21",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "670e803985d561733135aad5"
  },
  "__v": 0,
  "Poster": "CT-67dce51d60dc24d86d21714a--.png"
}
```

</details>


---

## ❌ Poster #103 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dcec4b60dc24d86d2171db--.JPG`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dcec4b60dc24d86d2171db--.JPG?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dcec4b60dc24d86d2171db--.JPG?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-21 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dcec4b60dc24d86d2171db"
  },
  "Date": "2025-03-21",
  "EndDate": "2025-03-21",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dcec4b60dc24d86d2171db--.JPG"
}
```

</details>


---

## ❌ Poster #104 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dceee460dc24d86d2171ed--.JPG`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dceee460dc24d86d2171ed--.JPG?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dceee460dc24d86d2171ed--.JPG?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-21 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dceee460dc24d86d2171ed"
  },
  "Date": "2025-03-21",
  "EndDate": "2025-03-21",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "670e803985d561733135aad5"
  },
  "__v": 0,
  "Poster": "CT-67dceee460dc24d86d2171ed--.JPG"
}
```

</details>


---

## ❌ Poster #105 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dcef0460dc24d86d2171f8--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dcef0460dc24d86d2171f8--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dcef0460dc24d86d2171f8--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-21 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dcef0460dc24d86d2171f8"
  },
  "Date": "2025-03-21",
  "EndDate": "2025-03-21",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "670e803985d561733135aad5"
  },
  "__v": 0,
  "Poster": "CT-67dcef0460dc24d86d2171f8--.jpg"
}
```

</details>


---

## ❌ Poster #106 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dcef1660dc24d86d2171fb--.PNG`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dcef1660dc24d86d2171fb--.PNG?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dcef1660dc24d86d2171fb--.PNG?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-21 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dcef1660dc24d86d2171fb"
  },
  "Date": "2025-03-21",
  "EndDate": "2025-03-21",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "670e803985d561733135aad5"
  },
  "__v": 0,
  "Poster": "CT-67dcef1660dc24d86d2171fb--.PNG"
}
```

</details>


---

## ❌ Poster #107 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dcef2b60dc24d86d21720e--.PNG`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dcef2b60dc24d86d21720e--.PNG?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dcef2b60dc24d86d21720e--.PNG?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-21 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dcef2b60dc24d86d21720e"
  },
  "Date": "2025-03-21",
  "EndDate": "2025-03-21",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "670e803985d561733135aad5"
  },
  "__v": 0,
  "Poster": "CT-67dcef2b60dc24d86d21720e--.PNG"
}
```

</details>


---

## ❌ Poster #108 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dd113b60dc24d86d2173fe--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dd113b60dc24d86d2173fe--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dd113b60dc24d86d2173fe--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-21 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dd113b60dc24d86d2173fe"
  },
  "Date": "2025-03-21",
  "EndDate": "2025-03-21",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dd113b60dc24d86d2173fe--.jpg"
}
```

</details>


---

## ❌ Poster #109 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dd114e60dc24d86d21740d--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dd114e60dc24d86d21740d--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dd114e60dc24d86d21740d--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-21 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dd114e60dc24d86d21740d"
  },
  "Date": "2025-03-21",
  "EndDate": "2025-03-21",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dd114e60dc24d86d21740d--.jpg"
}
```

</details>


---

## ❌ Poster #110 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dd134460dc24d86d217440--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dd134460dc24d86d217440--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dd134460dc24d86d217440--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-21 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dd134460dc24d86d217440"
  },
  "Date": "2025-03-21",
  "EndDate": "2025-03-21",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "66d9736b6fb38cd84df49053"
  },
  "__v": 0,
  "Poster": "CT-67dd134460dc24d86d217440--.jpg"
}
```

</details>


---

## ❌ Poster #111 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dd43bf60dc24d86d2174f6--.png`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dd43bf60dc24d86d2174f6--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dd43bf60dc24d86d2174f6--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-21 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dd43bf60dc24d86d2174f6"
  },
  "Date": "2025-03-21",
  "EndDate": "2025-03-21",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "672c53ce8f7ccba25159bbf1"
  },
  "__v": 0,
  "Poster": "CT-67dd43bf60dc24d86d2174f6--.png"
}
```

</details>


---

## ❌ Poster #112 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dd43e560dc24d86d2174fc--.png`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dd43e560dc24d86d2174fc--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dd43e560dc24d86d2174fc--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-21 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dd43e560dc24d86d2174fc"
  },
  "Date": "2025-03-21",
  "EndDate": "2025-03-21",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "672c53ce8f7ccba25159bbf1"
  },
  "__v": 0,
  "Poster": "CT-67dd43e560dc24d86d2174fc--.png"
}
```

</details>


---

## ❌ Poster #113 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dd43f660dc24d86d2174ff--.png`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dd43f660dc24d86d2174ff--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dd43f660dc24d86d2174ff--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-21 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dd43f660dc24d86d2174ff"
  },
  "Date": "2025-03-21",
  "EndDate": "2025-03-21",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "672c53ce8f7ccba25159bbf1"
  },
  "__v": 0,
  "Poster": "CT-67dd43f660dc24d86d2174ff--.png"
}
```

</details>


---

## ❌ Poster #114 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dd441560dc24d86d21750a--.PNG`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dd441560dc24d86d21750a--.PNG?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dd441560dc24d86d21750a--.PNG?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-21 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dd441560dc24d86d21750a"
  },
  "Date": "2025-03-21",
  "EndDate": "2025-03-21",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "672c53ce8f7ccba25159bbf1"
  },
  "__v": 0,
  "Poster": "CT-67dd441560dc24d86d21750a--.PNG"
}
```

</details>


---

## ❌ Poster #115 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dd51b360dc24d86d217551--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dd51b360dc24d86d217551--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dd51b360dc24d86d217551--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-21 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dd51b360dc24d86d217551"
  },
  "Date": "2025-03-21",
  "EndDate": "2025-03-21",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "672c53ce8f7ccba25159bbf1"
  },
  "__v": 0,
  "Poster": "CT-67dd51b360dc24d86d217551--.jpg"
}
```

</details>


---

## ❌ Poster #116 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dd618560dc24d86d2175dc--.png`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dd618560dc24d86d2175dc--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dd618560dc24d86d2175dc--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-21 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dd618560dc24d86d2175dc"
  },
  "Date": "2025-03-21",
  "EndDate": "2025-03-21",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "670e803985d561733135aad5"
  },
  "__v": 0,
  "Poster": "CT-67dd618560dc24d86d2175dc--.png"
}
```

</details>


---

## ❌ Poster #117 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-67dd618f60dc24d86d2175df--.png`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dd618f60dc24d86d2175df--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-67dd618f60dc24d86d2175df--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-03-21 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67dd618f60dc24d86d2175df"
  },
  "Date": "2025-03-21",
  "EndDate": "2025-03-21",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "670e803985d561733135aad5"
  },
  "__v": 0,
  "Poster": "CT-67dd618f60dc24d86d2175df--.png"
}
```

</details>


---

## ❌ Poster #118 - 🚨 **EXTRACTION FAILURE**

**File Name:** `CT-Test COncert-TRICHUR BROTHERS; EDAPALLY AJITH; TRICHUR MOHAN; KOVAI SURESH-.40`  
**Available GT Fields:** 9/10

This poster has sufficient ground truth data but extraction completely failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-Test%20COncert-TRICHUR%20BROTHERS%3B%20EDAPALLY%20AJITH%3B%20TRICHUR%20MOHAN%3B%20KOVAI%20SURESH-.40?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-Test%20COncert-TRICHUR%20BROTHERS%3B%20EDAPALLY%20AJITH%3B%20TRICHUR%20MOHAN%3B%20KOVAI%20SURESH-.40?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | April 13, 2025 | ✅ |
| Times | ❌ *Empty* | 10:57 PM | ✅ |
| Venue | ❌ *Empty* | No. 16/1, 2nd Main Road, Gavipuram Extn. | ✅ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | Test COncert | ✅ |
| Artists | ❌ *Empty* | TRICHUR BROTHERS; EDAPALLY AJITH; TRICHUR MOHAN; KOVAI SURESH | ✅ |
| City | ❌ *Empty* | Bangalore | ✅ |
| Mode | ❌ *Empty* | Offline | ✅ |
| Contact No | ❌ *Empty* | 08296043179 | ✅ |
| Contact Email | ❌ *Empty* | KARAM@microsoft.com | ✅ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67eec50de7913ee65402cc7d"
  },
  "Date": "April 13, 2025",
  "EndDate": "",
  "Time": "10:57 PM",
  "EndTime": null,
  "Venue": "No. 16/1, 2nd Main Road, Gavipuram Extn.",
  "StreamingUrl": "",
  "Title": "Test COncert",
  "Artists": "TRICHUR BROTHERS; EDAPALLY AJITH; TRICHUR MOHAN; KOVAI SURESH",
  "OtherArtists": "EE FF GG HH",
  "Type": "Hindustani",
  "City": "Bangalore",
  "Locality": "",
  "Mode": "Offline",
  "Contactno": "08296043179",
  "Contactemail": "KARAM@microsoft.com",
  "ContactWeb": "",
  "Status": "Rejected",
  "Poster": "CT-Test COncert-TRICHUR BROTHERS; EDAPALLY AJITH; TRICHUR MOHAN; KOVAI SURESH-.40",
  "__v": 0
}
```

</details>


---

## ❌ Poster #119 - 🚨 **EXTRACTION FAILURE**

**File Name:** `CT-Taalmagic Sangeet Baithak #48-Ust. Hafiz Bale Khan (Sitar), Anand HS (Tabla), Alok Sarkar (Harmonium)-.jpg`  
**Available GT Fields:** 8/10

This poster has sufficient ground truth data but extraction completely failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-Taalmagic%20Sangeet%20Baithak%20%2348-Ust.%20Hafiz%20Bale%20Khan%20%28Sitar%29%2C%20Anand%20HS%20%28Tabla%29%2C%20Alok%20Sarkar%20%28Harmonium%29-.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-Taalmagic%20Sangeet%20Baithak%20%2348-Ust.%20Hafiz%20Bale%20Khan%20%28Sitar%29%2C%20Anand%20HS%20%28Tabla%29%2C%20Alok%20Sarkar%20%28Harmonium%29-.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | April 27, 2025 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | SJR Equinox, Electronic City Phase 1, Bengaluru | ✅ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | Taalmagic Sangeet Baithak #48 | ✅ |
| Artists | ❌ *Empty* | Ust. Hafiz Bale Khan (Sitar), Anand HS (Tabla), Alok Sarkar (Harmonium) | ✅ |
| City | ❌ *Empty* | Bengaluru | ✅ |
| Mode | ❌ *Empty* | Offline | ✅ |
| Contact No | ❌ *Empty* | 9845817900 | ✅ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "67f0bb69e7913ee65402daab"
  },
  "Date": "April 27, 2025",
  "EndDate": "April 27, 2025",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "SJR Equinox, Electronic City Phase 1, Bengaluru",
  "StreamingUrl": "",
  "Title": "Taalmagic Sangeet Baithak #48",
  "Artists": "Ust. Hafiz Bale Khan (Sitar), Anand HS (Tabla), Alok Sarkar (Harmonium)",
  "OtherArtists": "",
  "Type": "Hindustani",
  "City": "Bengaluru",
  "Locality": "Electronic City Phase 1",
  "Mode": "Offline",
  "Contactno": "9845817900",
  "Contactemail": "",
  "ContactWeb": "",
  "Status": "Approved",
  "Poster": "CT-Taalmagic Sangeet Baithak #48-Ust. Hafiz Bale Khan (Sitar), Anand HS (Tabla), Alok Sarkar (Harmonium)-.jpg",
  "__v": 0
}
```

</details>


---

## ❌ Poster #120 - 🚨 **EXTRACTION FAILURE**

**File Name:** `CT-Sangeet Baithak # 48-Ust. Hafiz Bale Khan (Vocal), Anand HS (Tabla), Alok Sarkar (Harmonium)-.jpg`  
**Available GT Fields:** 8/10

This poster has sufficient ground truth data but extraction completely failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-Sangeet%20Baithak%20%23%2048-Ust.%20Hafiz%20Bale%20Khan%20%28Vocal%29%2C%20Anand%20HS%20%28Tabla%29%2C%20Alok%20Sarkar%20%28Harmonium%29-.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-Sangeet%20Baithak%20%23%2048-Ust.%20Hafiz%20Bale%20Khan%20%28Vocal%29%2C%20Anand%20HS%20%28Tabla%29%2C%20Alok%20Sarkar%20%28Harmonium%29-.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | April 27, 2025 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | SJR Equinox, Electronic City Phase 1, Bengaluru | ✅ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | Sangeet Baithak # 48 | ✅ |
| Artists | ❌ *Empty* | Ust. Hafiz Bale Khan (Vocal), Anand HS (Tabla), Alok Sarkar (Harmonium) | ✅ |
| City | ❌ *Empty* | Bengaluru  | ✅ |
| Mode | ❌ *Empty* | Offline | ✅ |
| Contact No | ❌ *Empty* | 9845817900 | ✅ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "6809dee43fdf731124e5e571"
  },
  "Date": "April 27, 2025",
  "EndDate": "April 27, 2025",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "SJR Equinox, Electronic City Phase 1, Bengaluru",
  "StreamingUrl": "",
  "Title": "Sangeet Baithak # 48",
  "Artists": "Ust. Hafiz Bale Khan (Vocal), Anand HS (Tabla), Alok Sarkar (Harmonium)",
  "OtherArtists": "",
  "Type": "Hindustani",
  "City": "Bengaluru ",
  "Locality": "Electronic City",
  "Mode": "Offline",
  "Contactno": "9845817900",
  "Contactemail": "",
  "ContactWeb": "",
  "Status": "Approved",
  "Poster": "CT-Sangeet Baithak # 48-Ust. Hafiz Bale Khan (Vocal), Anand HS (Tabla), Alok Sarkar (Harmonium)-.jpg",
  "__v": 0
}
```

</details>


---

## ❌ Poster #121 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-68399e797bbc23057341d209--.png`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-68399e797bbc23057341d209--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-68399e797bbc23057341d209--.png?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-05-30 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "68399e797bbc23057341d209"
  },
  "Date": "2025-05-30",
  "EndDate": "2025-05-30",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "670e803985d561733135aad5"
  },
  "__v": 0,
  "Poster": "CT-68399e797bbc23057341d209--.png"
}
```

</details>


---

## ❌ Poster #122 - ⚠️ **PARTIAL GT DATA**

**File Name:** `CT-683be8a77bbc230573421d59--.jpg`  
**Available GT Fields:** 2/10

This poster has some ground truth data but extraction failed.

![Poster Image](https://shmediadata.blob.core.windows.net/shposters/CT-683be8a77bbc230573421d59--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)

*[Download Original Image](https://shmediadata.blob.core.windows.net/shposters/CT-683be8a77bbc230573421d59--.jpg?sv=2024-11-04&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-04-02T01:12:21Z&st=2025-04-03T17:12:21Z&spr=https&sig=d3M73kg7zZlOvDMHlakxysKKvlyqMcGsiODx%2B9deV2Q%3D)*

### Field-by-Field Comparison

| Field | Extracted | Ground Truth | GT Available |
|-------|-----------|--------------|--------------|
| Dates | ❌ *Empty* | 2025-06-01 | ✅ |
| Times | ❌ *Empty* | 6:00 PM | ✅ |
| Venue | ❌ *Empty* | *Empty* | ❌ |
| Streaming Url | ❌ *Empty* | *Empty* | ❌ |
| Title | ❌ *Empty* | *Empty* | ❌ |
| Artists | ❌ *Empty* | *Empty* | ❌ |
| City | ❌ *Empty* | *Empty* | ❌ |
| Mode | ❌ *Empty* | *Empty* | ❌ |
| Contact No | ❌ *Empty* | *Empty* | ❌ |
| Contact Email | ❌ *Empty* | *Empty* | ❌ |

<details>
<summary><strong>📋 View Raw Data</strong></summary>

**Extraction Result:**
```json
{
  "dates": [],
  "times": [],
  "venue": null,
  "streaming_url": null,
  "title": null,
  "artists": [],
  "city": null,
  "mode": null,
  "contact_no": [],
  "contact_email": []
}
```

**Ground Truth:**
```json
{
  "_id": {
    "$oid": "683be8a77bbc230573421d59"
  },
  "Date": "2025-06-01",
  "EndDate": "2025-06-01",
  "Time": "6:00 PM",
  "EndTime": null,
  "Venue": "To be entered",
  "StreamingUrl": "To be entered",
  "Title": "To be entered",
  "Artists": "To be entered",
  "OtherArtists": "To be entered",
  "Type": "To be entered",
  "City": "To be entered",
  "Locality": "To be entered",
  "Mode": "To be entered",
  "Contactno": "To be entered",
  "Contactemail": "To be entered",
  "ContactWeb": "To be entered",
  "Status": "Rejected",
  "CreatedBy": {
    "$oid": "670e803985d561733135aad5"
  },
  "__v": 0,
  "Poster": "CT-683be8a77bbc230573421d59--.jpg"
}
```

</details>


---

## Report Information

- **Generated:** From 892 total evaluation results
- **Failed Extractions:** 122 posters with completely empty extraction
- **Analysis Focus:** Understanding extraction failure patterns and data quality
- **Failure Rate:** 13.7% of all posters

---

*This report was automatically generated to help improve poster extraction accuracy.*
