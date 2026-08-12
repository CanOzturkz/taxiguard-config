# TaxiGuard — Privacy Policy

_Last updated: 12 July 2026_

TaxiGuard ("the app") helps passengers estimate legal taxi fares and detect overcharging. This policy explains what data the app uses and how.

## Data we collect and how it is used

### Location data
- The app uses your device's **precise location** to: center the map, calculate a route and fare estimate to your chosen destination, and measure distance/time **during an active trip** that you start yourself.
- While a trip is active, location tracking runs as a **foreground service with a visible notification** and continues while your screen is off. Tracking **stops when you end the trip** or close the app.
- Precise location data is processed **on your device** and is never uploaded. The only location-derived data that leaves your device is the **coarse (~110 m), anonymous** trip statistics described below — and only if sharing is enabled.

### Trip history
- Trip summaries (date, distance, duration, fare estimate, and the amount you enter for a price check) are stored **on your device**. You can delete them at any time from the Trip History screen ("Clear history").

### Anonymous trip statistics (can be turned off)
- To map taxi overcharging hotspots and improve fare estimates, the app sends an **anonymous statistics record** when a trip ends: city, taxi type, distance, duration, waiting time, the legal fare estimate, the amount asked (if you used the price check), the verdict, and **coarse** pickup/drop-off coordinates rounded to ~110 m (neighbourhood level — deliberately too imprecise to identify an address).
- To improve measurement accuracy, the same record also includes a **GPS-quality summary** (number of location fixes, average accuracy, signal gaps), your **device model and OS version** (to tune accuracy per device — it does not identify you), and whether a **bridge or tunnel toll** was detected on the trip (to verify toll detection in the field).
- Records contain **no name, e-mail, phone number, or account** — only a random installation identifier that cannot be linked to you.
- Data is stored on Supabase infrastructure in the **EU (Frankfurt)**. See [Supabase Privacy](https://supabase.com/privacy).
- Anonymous statistics are **automatically deleted after 90 days**.
- You can turn this off anytime: **Trip History → "Share anonymous trip stats"**. When off, nothing is sent.

### Crash reports (diagnostics)
- If the app crashes, an **anonymous crash report** is sent to Sentry (Functional Software, Inc.) so we can fix the bug. A report contains technical diagnostics only: the error and stack trace, app version, device model and OS version.
- Crash reports contain **no location data**, no trip contents, no names and no identifiers, and are used solely for fixing defects. Reports are processed on Sentry's **EU (Germany) infrastructure**. See [Sentry's Privacy Policy](https://sentry.io/privacy/).

### Data sent to third parties
To provide its features, the app sends limited data to the following services:
- **Google Maps Platform** (Google LLC): your coordinates and destination text are sent to Google's Directions, Places and Maps services to compute routes, address suggestions and display the map. See [Google's Privacy Policy](https://policies.google.com/privacy).
- **Exchange-rate service** (open.er-api.com): the app fetches currency rates. No personal data is sent.
- **Tariff configuration** (GitHub): the app fetches an updated taxi-tariff file. No personal data is sent.
- **Crash reporting** (Sentry): anonymous crash diagnostics as described above.
- **Address lookup for complaints** (OpenStreetMap Nominatim): only when you open the "File a complaint" feature, the trip's pickup/drop-off coordinates may be sent to Nominatim to convert them into a readable street name. No identifiers are sent. See the [OSMF Privacy Policy](https://wiki.osmfoundation.org/wiki/Privacy_Policy).
- **Anonymous trip statistics** (Supabase, EU): as described above; optional and can be turned off in the app.

## What we do NOT do
- No account or sign-up; we do not collect names, emails or identifiers.
- No advertising, no analytics SDKs, no tracking across apps.
- No sale or sharing of personal data.

## Data retention and deletion
All app data (trip history, settings) lives on your device and is removed when you clear the app's storage or uninstall the app.

## Children
The app is not directed at children under 13 and collects no personal information.

## Changes
We may update this policy; the latest version is always available at this URL.

## Contact
Questions: **baysansasyonel1907@gmail.com**
