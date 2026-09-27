# Cat Solitaire Privacy Policy

**Effective date: 2026-09-27**

Cat Solitaire ("the app" / "the game") is a single-player game that runs entirely
on your device. It **does not collect, upload, or share any personal
information**.

> [中文隐私政策 / Chinese version](../privacy.zh-CN/)

## What we collect

**Nothing.**

The app does not collect your name, email address, phone number, device
identifiers, location, photos, contacts, or any other personal information.
There is no sign-up or login in the game, and no account is ever created.

## Where your data is stored

Everything stays on your device, in the app's private storage:

| What | Where | Notes |
|---|---|---|
| Level progress, chapters, gold, cats you collected | App-private storage (`user://`) | Deleted when you uninstall |
| Language and sound settings | App-private storage | Deleted when you uninstall |
| Purchase unlock status | App-private storage — a **local cache only** | See the next section |

**The app never uploads your game progress or any other data to our servers.
We do not operate a server.**

### About that local unlock cache

Once a purchase is confirmed, the app writes a small flag to its own private
storage, so it can show you the unlocked state without asking the store on
every launch. That flag holds **only** the value "unlocked" — no receipt, no
account identifier, no device identifier.

It is a convenience cache, not the source of truth. If you delete it (by
uninstalling), the app asks the store again the next time you reach the unlock
screen, and your purchase is recognised from your store account.

## The only network request

The app contacts **your app store, and nothing else**, for exactly one purpose:
**to check whether you have purchased the in-app purchase.**

Which store that is depends on the device:

| Platform | Who it talks to | When it asks |
|---|---|---|
| Android | **Google Play** (provided by Google) | Once at launch |
| iOS | **Apple App Store / StoreKit** (provided by Apple) | **Only when you reach the unlock screen**, and when you tap "Restore Purchases" |

- **What it asks:** whether your store account owns a purchase of
  `cat_solitaire_full`
- **Our role:** we do not participate in, proxy, or store that data
- **On iOS we deliberately do not ask at launch.** Asking there would make
  Apple show a sign-in prompt every time you open the game, so we wait until
  you actually reach the unlock screen — the moment the answer matters.

We cannot see or obtain any of your account information.

## Permissions

The app requests **no runtime permissions** — it does not access the camera,
microphone, location, storage, or contacts.

## Children's privacy

Because the app collects no data whatsoever, it does not collect personal
information from children.

## Third-party services

The app integrates **no** third-party analytics, advertising, or crash-reporting
SDKs.

The only external component is your platform's in-app billing service —
**Google Play Billing** on Android, **Apple App Store / StoreKit** on iOS —
provided by Google or Apple respectively, and handled under their privacy
policies:

- **Google Privacy Policy**: <https://policies.google.com/privacy>
- **Apple Privacy Policy**: <https://www.apple.com/legal/privacy/>

It is invoked **only when you tap the purchase button yourself**, or when you
open the unlock screen.

## Purchases, refunds and restoring

The app offers one **non-consumable** in-app purchase: a one-time unlock of
chapters 2–6 and all 16 cats. It is not a subscription and does not renew.

- **Apple:** restore a purchase by tapping **Restore Purchases** on the unlock
  screen. For refunds, use Apple's
  [Report a Problem](https://reportaproblem.apple.com/).
- **Google:** restore by tapping **Restore Purchases** as well. For refunds,
  contact Google support directly:
  <https://support.google.com/googleplay/answer/2741495>

## Your rights

Because we collect no data, there is nothing to delete — no record of you
exists on any server of ours.

You can erase all of the game's data on your device at any time: **uninstall
the app**. That deletes your level progress, your settings, and the
system-backed-up game progress as well.

To remove a purchase record held by Google Play or Apple, contact Google or
Apple directly using the links above — we do not hold it.

## Changes

If this policy changes, the updated version will ship with the app and the
effective date at the top will be updated. Since the app collects no data,
policy changes cannot affect any information we hold about you.

## Contact

If you have questions about this policy, please contact us at
**kitterive@qq.com**.
