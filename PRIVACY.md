# Wardrobe privacy policy

_Last updated: November 13, 2026_

Wardrobe is an app for keeping track of your clothes and planning outfits. It
is made to keep your information with you: there is no Wardrobe account, no
Wardrobe server, and nothing is sent to the people who make Wardrobe.

## What stays on your device

Your wardrobe, photos, outfits, plans, wishlist and settings are stored on the
device you use Wardrobe on. Cutting out photos and recognizing clothes is done
on your device too; your photos are not uploaded anywhere to do it.

## Google accounts (optional)

If you connect a Google account, Wardrobe signs in with a Google client that
you create yourself in your own Google Cloud project. Wardrobe asks Google for
read-only access to:

- **Your calendars and their events** (`calendar.calendarlist.readonly`,
  `calendar.events.readonly`): to show the day's plans on Today, and to suggest
  outfits that suit them. You choose which calendars are shown.
- **Your email** (`gmail.readonly`): to find order confirmation emails from
  clothing shops, so the clothes you bought can be offered to you to add.
  Wardrobe searches only for order, receipt and shipping emails, and keeps only
  what it shows you about the clothes in them.
- **Your email address, name and profile picture** (`openid`, `email`,
  `profile`): to show which account is connected in Settings.

Wardrobe never changes, sends, deletes or shares anything in your Google
account. What it reads is used only to show you those features, on your
device. It is not sold, not used for advertising, not used to train AI models,
and not sent to anyone. The sign-in tokens are stored on your device and are
deleted when you disconnect the account in Settings. You can also remove
Wardrobe's access at any time at
[myaccount.google.com/permissions](https://myaccount.google.com/permissions).

Wardrobe's use and transfer of information received from Google APIs adheres to
the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

## Other services Wardrobe talks to

- **Your own sync server (optional):** if you sign in to a sync server, your
  wardrobe is kept in sync through it. It is a server you run yourself;
  nobody else can read it. If you leave error reports on, short error messages
  (no wardrobe data) are sent there too.
- **Weather:** to show the weather, your approximate location (from your
  device, or from your internet address through ip-api.com) is sent to
  OpenWeatherMap, either directly with your own key or through your sync
  server.
- **Downloads:** the on-device AI models are downloaded once from Hugging Face
  and GitHub, and app updates from GitHub.
- **Shops:** when you add a piece from a product link, Wardrobe opens that link
  to read the product's name and photos.

## Children

Wardrobe is not directed at children under 13.

## Changes

If this policy changes, the new version will be posted here with a new date.

## Contact

Questions about this policy: open an issue at
[github.com/Cummmies/Wardrobe-releases](https://github.com/Cummmies/Wardrobe-releases/issues).
