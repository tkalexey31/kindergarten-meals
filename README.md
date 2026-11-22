# Kindergarten meals

A small web app for parents to track kindergarten meal payments in Romania.

Mark the days your child stayed home, and the app shows how much you owe for meals or how much you paid ahead. It works in English, Romanian and Ukrainian.

**Open the app:** https://tkalexey31.github.io/kindergarten-meals/

## What it does

- School days count as attended by default. Tap a day to mark it absent or closed.
- Romanian public holidays are marked as closed automatically, including Orthodox Easter and Pentecost.
- Keeps a list of your payments and shows the balance.
- Supports a price change from a chosen month, so older months keep the old price.
- Shows the kindergarten's payment details with copy buttons and builds the payment reference from the child's name and group.
- Adds a monthly payment reminder to Google Calendar.

## Privacy

Everything you enter stays in the browser on your phone. There is no account, no server, no cookies and no analytics. The page loads nothing from other sites, fonts included.

## Install on your phone

**iPhone:** open the link in Safari, tap ••• next to the address bar (or Share at the bottom on older iOS), then Add to Home Screen. Do it before entering data, because the Home Screen app keeps its own storage separate from Safari.

**Android:** open the link in Chrome, tap ⋮, then Add to Home screen.

## Moving to a new phone

Settings → Backup → Copy backup. On the new phone, paste the code into the same box and tap Restore.

## For developers

The whole app is one file, `index.html`, with no build step and no dependencies. Fonts (Nunito and Baloo 2, SIL Open Font License) are embedded in the file.

To run it locally, open `index.html` in a browser.

The default payment details belong to Grădinița cu P.P. Licurici in Cluj-Napoca. Parents from another kindergarten can change them in Settings.
