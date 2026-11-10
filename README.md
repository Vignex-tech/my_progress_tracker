# My Progress Tracker

A single-page daily schedule tracker for AI, robotics and interview prep.

- Live clock with the current block, countdown and next block
- Focus timer (90/50/25 minute focus, 5/15 minute breaks)
- Reminders at every block change, with optional sound and voice
- Daily log: LeetCode, Hugging Face modules, project hours, system design, mock scores
- Weekly skill check-ins with a trend line

Open `index.html` in a browser. Progress saves in the browser's local storage.

## Use it on your phone

1. Turn on GitHub Pages: repo Settings, Pages, deploy from branch `main`, folder `/ (root)`.
2. Open `https://vignex-tech.github.io/my_progress_tracker/` on your phone.
3. Android Chrome: menu, Add to Home screen. iPhone Safari: Share, Add to Home Screen.

Reminders, sound and vibration run while the app is open. Keep it open or pinned during the day.

## Android app (APK)

Every push to `main` builds an APK on GitHub (Actions tab, "Build Android APK"). Download `my-progress-tracker.apk` from the newest entry under Releases on your phone and install it (allow "install unknown apps" for your browser). The app schedules a phone notification at the start of every block, even when the app is closed.

## Skill tests

The Skills tab runs a 30-question test (five per skill, easy to hard) and turns the score into a 1 to 10 rating for each of six skills. Take the baseline test first, then retest every 5, 7, 10 or 30 days. Each test shows the change since the last one and lists the questions you got wrong with the right answers.

## Block alarm

With "Alarm when a block ends" switched on, the end of each block rings until you stop it and asks you to mark the block done. In the Android app the phone also rings for about 18 seconds when the app is closed. Switch it off for a short alert instead.
