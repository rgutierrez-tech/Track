# Track: Lap Timer

**A GPS lap timer for track days, built for iPhone, Apple Watch and CarPlay.**

Draw a finish line once. From then on, Track times every lap on its own — no buttons, no setup at the pit wall — and shows you exactly where you gained or lost time.

Free. No ads, no account, no features locked behind a paywall.

<!-- Replace with your App Store link once the app is live:
[Download on the App Store](https://apps.apple.com/app/idXXXXXXXXXX)
-->

---

## Highlights

- **Automatic timing.** The clock starts and stops when you cross a line you drew on a satellite map.
- **Precise crossings.** Track calculates the instant your path crossed the line between GPS readings, instead of rounding to the nearest one.
- **A delta you can trust.** Your pace is compared with your reference lap at the same point on the track, not at the same second.
- **Sectors and splits.** Add intermediate lines to see where the time goes.
- **Video with telemetry.** Record your lap with lap time, delta, speed, g-forces and a live minimap burned into the image.
- **Analysis that finds the next second.** Braking map, scrubbable charts and a ghost lap against your best.
- **Apple Watch, CarPlay, Live Activities and widgets.** Glanceable everywhere, so you never have to pick up the phone.
- **Private by design.** Everything is processed on your iPhone. No sign-up, no analytics.

---

## Features

### Timing

- **Finish line, sectors and delta.** Track doesn't use a start button. The timer starts when you cross the finish line you drew and stops at the exact instant you cross it again.
- **Interpolated crossings.** Instead of splitting the lap at the GPS reading closest to the line, Track uses the readings just before and after the crossing and calculates the precise moment your path went through it.
- **Distance-based delta.** Comparing by distance keeps the number meaningful all the way down the straight, even after a slow corner exit.
- **Sectors.** Draw intermediate lines to get split times. If you miss one because you ran wide, the lap still closes at the finish.
- **Circuits and point-to-point.** A circuit closes one lap and starts the next at the same line. A point-to-point run — a hill climb, a timed stage — stops at the finish and waits for the next attempt.
- **Invalidate a lap.** Went off, lifted for a yellow flag or hit traffic? Mark the lap invalid. It keeps its telemetry but stops counting toward records and the ghost.

### The HUD

- One big number — the lap time — with the delta right below it and everything else at the edges, readable in the fraction of a second you can spare on a straight.
- Green is faster, red is slower, yellow is even. Saturated enough to survive direct sun on the windshield.
- A g-force bubble calculated from GPS and motion sensors, so it doesn't matter how the phone is mounted.
- Dedicated portrait and landscape layouts.
- Distinct haptics for every lap and for a personal best.

### Tracks

- Search for a circuit by name and see it in satellite view, where the painted line is clearly visible.
- Already at the circuit? Stand on the line, point the phone in your direction of travel and Track places the finish line right there, oriented with the compass.
- The layout draws itself: the first time you drive a track, Track saves the outline you followed and reuses it in the video minimap.
- Share a track by link, QR code or by bringing two iPhones together. The layout travels; your times don't.
- When you arrive, Track recognizes which of your tracks you're at and selects it for you.

### Garage

- A card for each car, with photo and color.
- Setup notes that explain your times a month later: tire pressures, brake pads front and rear, weight, power and year.
- Records are kept per car and per circuit. The card shows that car's record at the circuit you're at right now.

### Video with telemetry

- Lap time, color-coded delta, speed, g-forces and lap number, drawn frame by frame while you record. When you stop, the video is ready to post.
- A corner minimap traces the circuit as you drive, with a dot showing where you are.
- Optionally save the overlay on its own with a transparent background (HEVC with alpha) to drop over GoPro or helmet-cam footage in Final Cut Pro or Premiere.
- Videos go straight to your photo library. Nothing is uploaded anywhere.

### Analysis

- Every lap keeps its full trace: position, speed, accelerations and, with Apple Watch, heart rate.
- Charts you can scrub with your finger, with the values at each point.
- A braking and acceleration map, or a speed map, painted on the layout. Tap any point to see its data.
- Ghost lap: two laps running at the same time on the map, yours against the reference.
- Best times are always kept per circuit, plus lifetime totals: sessions, laps, distance and time on track.

### Free roam

Record a route and its telemetry without a finish line — the drive to the circuit or a club outing. See the full route painted by braking and acceleration, with distance, moving time, top and average speed, elevation gain and the weather at the time.

### Weather

Temperature, humidity, wind, pressure and last-hour rainfall at your exact location, saved with every session. Track suggests the track condition — dry, damp or wet — and you can correct it.

### Apple Watch and Health

- Lap time and delta on your wrist, with the background tinted green or red so you can read it without focusing.
- Every lap and every record arrives as a tap on your wrist.
- Heart rate and calories on a second page.
- Sessions are saved to the **Health app** as workouts, with heart rate and calories burned.

### Live Activities, CarPlay and widgets

- **Dynamic Island and Lock Screen:** the lap timer, the circuit sketch and the current sector stay visible with the phone put away. The system animates the clock, so it doesn't drain extra battery.
- **CarPlay:** open Track on the car's screen to see your tracks on a map, nearest first. Tap one, start the session, and the screen switches to the numbers that matter — lap, sector, delta, splits, last and best — updated at every line crossing. The running clock lives on the CarPlay Dashboard as a Live Activity.
- **Widget:** the layout of the last circuit you drove and your record there, on the Home Screen or in CarPlay.

### Siri and Shortcuts

Start a session hands-free: *"Start a track session in Track."* Track detects the circuit you're at and arms the timer with your primary car.

### iCloud

Tracks, cars and sessions sync through your private iCloud. Change iPhones and everything is still there. If iCloud is unavailable, Track keeps saving on the device.

### Languages and units

English, Spanish and Japanese. Metric or imperial units follow your iPhone's region, or you can choose in Settings.

---

## Requirements

| | |
|---|---|
| iPhone | iOS 17 or later |
| Live Activities and widgets | iOS 18 or later |
| Live Activity on the CarPlay Dashboard | iOS 26 or later |
| Apple Watch app | watchOS 10 or later |
| CarPlay | A CarPlay-compatible vehicle |

Track is an iPhone app. It doesn't run on iPad or Mac.

---

## Privacy

A driving log says where you were, when and how fast. Track treats it that way:

- No account and no sign-up.
- No analytics, no advertising, no tracking.
- Coordinates, telemetry, heart rate and videos are processed and stored on your iPhone, or in your private iCloud. There's no Track server in between.
- To show the weather, your location is sent to Apple Weather, operated by Apple. Nothing else leaves your device unless you choose to share a track.

Read the full [Privacy Policy](PRIVACY.md).

---

## Support

### Frequently asked questions

**The timer doesn't start when I cross the line.**
Check that the finish line spans the full width of the track — a car on the outside of a short line never crosses it. Wait until the GPS status shows it's ready, and give it a few seconds under open sky before your first lap.

**Does Track keep timing with the screen off or the phone locked?**
Yes. Once a session is running, timing continues in the background and the lap clock stays visible in the Dynamic Island and on the Lock Screen.

**Which location permission should I allow?**
*While Using the App* is enough. Track uses your location to time laps, recognize the circuit you're at and get the weather, and keeps timing in the background only while a session is running.

**Can I try Track without going to a circuit?**
Yes. Open the **Settings** app, go to **Track → Testing** and turn on **Demo mode**. Track will simulate a car lapping a test circuit so you can see the timer, the HUD, CarPlay and the analysis working.

**How do I use Track in CarPlay?**
Connect your iPhone to the car and open Track on the car's screen. Pick a track from the map and tap **Start Session**. The running lap clock appears on the CarPlay Dashboard.

**The weather card says the weather is unavailable.**
Weather comes from Apple Weather and needs an internet connection. Tap ↻ on the card to try again. Timing never depends on it: you can enter the conditions yourself and keep driving.

**Why does my video have no sound?**
While CarPlay is connected, video is recorded without audio. Apple doesn't allow apps to use the microphone while CarPlay is active.

**How do I see heart rate?**
Install Track on your Apple Watch from the Watch app on your iPhone and allow access to Health when Track asks. Heart rate appears on the watch and is saved with each lap.

**How do I restore my support purchase?**
In the Garage, open the menu at the top right, choose **Support Track**, and tap **Restore Purchases**.

**How do I delete my data?**
Delete tracks, cars or sessions inside the app. To remove everything, delete the app, then remove its iCloud data from **Settings → [your name] → iCloud → Manage Storage → Track**. Details are in the [Privacy Policy](PRIVACY.md).

### Contact

Found a bug or have a question? Email **YOUR-SUPPORT-EMAIL@example.com** or [open an issue](https://github.com/YOUR-USERNAME/YOUR-REPO/issues).

Please include your iPhone model, iOS version and, if it's about timing, a short description of the track and what happened.

---

## Supporting Track

Track is free and every feature works for everyone. If you enjoy it and want to help keep it going, there's an optional one-time purchase in the Garage menu. As a thank-you it unlocks five alternate app icons, an accent color of your choice and your signature in a corner of your videos. The green and red of the delta never change: they're information.

---

## Drive responsibly

Track is designed for closed circuits, track days and timed events where driving at speed is permitted. Always follow the rules of the venue and local traffic laws, and never interact with your phone while driving. Mount it securely and let the HUD, your Apple Watch or CarPlay do the talking.

---

## Credits

Weather data provided by Apple Weather ([data sources](https://weatherkit.apple.com/legal-attribution.html)). Maps by Apple Maps.

Apple, iPhone, Apple Watch, CarPlay, Siri, iCloud and Dynamic Island are trademarks of Apple Inc. Track is not affiliated with or endorsed by Apple.

© 2026 Rafael Gutierrez
