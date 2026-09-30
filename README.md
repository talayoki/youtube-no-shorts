# Youtube-no-shorts

Custom uBlock Origin filters for hiding YouTube Shorts and other unwanted sections.

## Features

- Hide YouTube Shorts
- Remove Shorts from the YouTube navigation menu
- Hide Shorts shelves and recommendations
- Hide selected YouTube sections

## Installation

### 1. Install uBlock Origin

Install the **uBlock Origin** browser extension/plugin.

### 2. Open My filters

Go to:

**uBlock Origin → Dashboard → My filters**

### 3. Add the filters

Open [`youtube_hide_shorts.txt`](youtube_hide_shorts.txt) and copy the filters you want to use.

Paste them into **My filters**.

### 4. Apply changes

Click **Apply changes**, then reload the affected website.

## Browser compatibility

These filters use **uBlock Origin filter syntax**.

They should work on desktop browsers with compatible uBlock Origin support, including:

- Opera
- Opera GX
- Chrome
- Chromium-based browsers
- Firefox
- Other compatible browsers

### Mobile

Mobile support may vary. Some mobile browsers use different content-filtering implementations and may not support all uBlock Origin syntax, particularly procedural filters such as `:has-text()` and `:upward()`.

## Notes

YouTube frequently changes its website structure, so filters may stop working if the relevant elements or attributes change.

If you find a broken filter, feel free to open an issue or submit an update.

These are cosmetic filters. They hide matching elements from the page and do not modify the videos themselves.

## Disclaimer

This is an unofficial collection of user-created browser filters.

It is not affiliated with or endorsed by YouTube, Google or uBlock Origin.
