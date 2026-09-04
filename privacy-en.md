---
title: ArmSound Privacy Policy
---


Last updated: 23 August 2026

## Summary

**ArmSound collects nothing about you.**

The app makes **no network requests** to detect, record, or play your motions.
Your arm motions and your history stay on
your Apple Watch and iPhone. Nothing is sent to anyone, including the developer.
There is no account to create.

**The one exception is in-app purchase.** When you buy or restore, the app talks
to Apple's App Store. This uses Apple's own mechanism (StoreKit), and **the
developer never receives your payment details** (see "In-app purchase" below).

## What is not collected

None of the following is collected, received, or stored:

- Name, email address, phone number, or any contact details
- Location
- Device identifiers or advertising identifiers
- Usage analytics or crash reports
- Contacts, photos, or calendars

## What stays on your device

The app works with the following, and **none of it leaves your devices.**

| What | Where | Why |
|---|---|---|
| Arm motion waveforms | App storage on the Watch and iPhone | To match your motions and play a sound |
| Whether a motion fired or not | Same | So you can review recent judgements and correct them with Learn / Ignore |
| Imported sound files | Same | To assign and play per motion |
| Settings (groups, thresholds) | Same | To determine behaviour |

The Apple Watch and iPhone exchange this data using Apple's WatchConnectivity.
**That exchange happens between your two devices and does not pass through any server.**

## Sensors and health data

The app reads **acceleration and rotation rate** from Core Motion. This is used
only to judge arm motion, and the readings stay on the device.

The app starts a **workout session** (HealthKit). This exists so that judging and
playback keep running when the screen turns off. It is not used to read heart rate
or any other health data. The only thing the app writes to HealthKit is the start
and end of that session, and no health data is ever sent anywhere.

## In-app purchase

Unlocking the paid features uses Apple's in-app purchase mechanism (StoreKit).

- **Apple handles the payment.** Your name, card number and address never pass
  through the app, and the developer never receives them.
- All the app does is **ask Apple whether the purchase exists**. Apple stores
  that answer on your device, signed, and the app reads it.
- **Nothing about your purchase is sent to a developer server.** There is no
  developer server.
- Only when you tap "Restore purchase" does the app ask Apple to check again.

For how Apple handles payments, see Apple's own privacy policy.

## Sharing with third parties

None. The app contains no third-party analytics, advertising, or SDKs.

## Deleting your data

Deleting the app removes all of the above from your device. Within the app you can
also delete individual motions, sounds, and judgement history.

## Children

No information is collected from users of any age.

## Changes

If this policy changes, the date at the top of this page will be updated.

## Contact

- GitHub Issues: https://github.com/888man/armsound-support/issues
