# site2 (Netlify deploy-drop ready)

## What this is
A mobile-first, high-conversion homepage for **BG’s Home & Auto Repair Services**.

## How to deploy
1. Zip the folder (or use the provided site2.zip).
2. Drag-and-drop the ZIP into Netlify Deploys (Deploy Drop).

## First thing to change
Open `index.html` and replace the placeholder phone number:
- Search for: `+1-000-000-0000` and `(000) 000-0000`
- Replace with your real number.

Optional: Set the phone number in one place by adding near the bottom script:
```js
window.BG_PHONE = "+1-770-555-1212";
window.BG_PHONE_PRETTY = "(770) 555-1212";
```

## Netlify Forms
The contact form is Netlify Forms compatible (`data-netlify="true"`).
Note: file uploads may require a paid Netlify plan. If uploads don’t work, tell customers to text photos.
