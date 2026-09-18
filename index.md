# Rocky — privacy policy

_Last updated: 18 September 2026_

Rocky is a personal assistant app built by one person for their own household. It is distributed only
through Google Play **internal testing** and is not offered to the public.

## Who runs it

Rocky has no company behind it and no shared servers. The app talks to **a server the user runs
themselves**, on their own computer at home, reached over their own private network (Tailscale). There is
no Rocky account, no sign-up, and no hosted backend operated by anyone else.

## What the app collects

**Nothing is collected by the developer.** The app sends no analytics, no crash reporting, no advertising
identifiers, and no usage data anywhere. There are no third-party SDKs for tracking or ads.

What the app *handles* — and where it goes:

| Data | Why | Where it goes |
|---|---|---|
| What the user types or says to Rocky | To answer and to act on it | The user's own server; kept in a database file on their own machine |
| Microphone audio | The voice screen turns speech into text | Handled by **Android's own speech recognition** on the device. Rocky receives only the resulting text and never stores or transmits audio |
| Notifications | Reminders and check-ins the user asked for | Sent by the user's own server to their own phone |
| Household data the user enters (shopping lists, pantry, recipes, notes, reminders) | The features themselves | The user's own server only |

## Third parties

The user's own server may send text to **Anthropic's Claude** to produce Rocky's replies, under the user's
own subscription and Anthropic's terms. It may also fetch public information on the user's behalf — web
searches and the weather for their town. The app itself contacts nothing but the user's own server.

Android's speech recognition and text-to-speech are provided by the device and governed by the device
maker's and Google's own policies.

## Permissions

- **Microphone** — only while the voice screen is open, to turn speech into text.
- **Notifications** — to show the reminders and check-ins the user set up.
- **Internet** — to reach the user's own server.
- **Alarms** — to show time-based reminders.

## Keeping and deleting data

All data lives on the user's own server and phone. Deleting the app removes its local copy; deleting the
database file on their own machine removes the rest. There is nothing held by the developer to request or
delete, because nothing is held by the developer.

## Children

Rocky is not intended for children and is not distributed publicly.

## Changes

If this policy changes, the updated version replaces this page.

## Contact

Questions about this policy: the developer, via the email address on the Play listing.
