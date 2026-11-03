# Zynapse

Small steps. A little support.

![Zynapse promotional artwork with the Ribbon Sprout emblem, an amber fox and a winding paper path.](assets/images/zynapse-cover.webp)

Zynapse is a local-first habit recovery tracker for people who want to reduce or leave an unwanted habit. Track your days, get support during cravings, reflect in a journal, and grow alongside a fox companion.

This is the public product and support repository. The application source is maintained separately and is not published here.

[Website](https://zynapse.zynoks.com/) · [Getting started](guides/GETTING_STARTED.md) · [Help](SUPPORT.md)

## Product status

Zynapse is in development. This repository is for product information, feature guides, screenshots and support. App distribution is managed separately from GitHub.

The current Android preview includes local tracking, coping tools, journaling, progress and the fox companion. iPhone, iPad and desktop availability have not been confirmed. The [website](https://zynapse.zynoks.com/) is a product site, not a browser version of the tracker.

See [development status](RELEASE_NOTES.md) for the scope of verification.

## What you can do

These features are implemented in the current Android preview; they are not claims of a stable public launch.

- Track preset or custom habits, streaks and estimated savings. The free interface supports up to three habits.
- Log cravings, moods and slips. Recording a slip and resetting a streak are separate choices.
- Open breathing, grounding, urge-surfing and timer tools when you need support.
- Write journal entries and save your reasons for making a change.
- Review recorded activity, craving intensity, triggers and coping-tool use in Progress.
- Make recovery plans, daily commitments and messages for your future self.
- Earn levels and cosmetic rewards, and interact with a growing fox companion.
- Choose English, French or Arabic, and light or dark appearance.

Core tracking works locally without an account. Optional account backup, subscriptions, rewarded ads and device services have additional configuration and verification limits; they are not advertised as production-ready services. Read the [FAQ](guides/FAQ.md).

## Inside the app

The images below are real captures of the unmodified Android 1.0.0 build 9 preview in an isolated emulator. The profile and activity are demonstration data. The cover above is generated promotional illustration, not a screenshot.

<p>
  <img src="assets/screenshots/android-home.png" alt="Zynapse Home in the Android preview, showing the isolated Demo profile and a newly created social media habit." width="240" />
  <img src="assets/screenshots/android-tools.png" alt="Zynapse Tools in the Android preview, showing relief exercises and coping shortcuts." width="240" />
  <img src="assets/screenshots/android-journal.png" alt="Zynapse Journal in the Android preview, showing a clearly identified demonstration journal entry." width="240" />
</p>

[Image provenance and generation prompt](assets/IMAGES.md)

## Your first few minutes

1. Choose your name, language, currency and appearance. Add a habit and its daily baseline.
2. Follow the short app guide, or replay it later from Settings.
3. Use Home for your selected habit, the **+** button to record activity, and Tools for support.
4. Open Journal to reflect and Progress to review what you have recorded.

[Full walkthrough](guides/GETTING_STARTED.md)

## Your data

Settings offers a partial JSON export of habits, journal and profile. **It is not a complete backup, and there is no in-app import for that export.** Do not clear app storage or reset data expecting this file to restore everything. Optional account snapshots are not a verified production backup service.

See [backup and restore](guides/BACKUP_AND_RESTORE.md) and [troubleshooting](guides/TROUBLESHOOTING.md).

## Current limitations

- Broader physical-device, compact-screen and language coverage is still being tested.
- Switching into or out of Arabic may require fully closing and reopening the app to apply layout direction.
- Savings are estimates based on your entered baseline. Progress reflects recorded activity, not a medical assessment or a guarantee of recovery.
- Some craving totals differ across screens and remain under review.
- Cloud snapshots do not merge simultaneous changes across devices. Production sync, purchases and ads are unverified.
- Complete local backup and restore are not available.

## Support and rights

Use [GitHub Issues](https://github.com/zynoksy/zynapse-app/issues) for reproducible bugs and feature requests, or email [contact@zynoks.com](mailto:contact@zynoks.com). Never post passwords, tokens, private journal text, exports or personal contact details in an issue.

[Support guide](SUPPORT.md) · [Product privacy policy](https://zynapse.zynoks.com/privacy) · [Product terms](https://zynapse.zynoks.com/terms) · [Rights and credits](RIGHTS.md)

This repository does not grant an open-source license to the application. Third-party rights remain with their respective owners. Zynapse is a tracking and reflection tool, not a replacement for professional care.
