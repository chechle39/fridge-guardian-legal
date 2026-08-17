---
title: Privacy Policy — Frescovo
permalink: /privacy/
---

# Privacy Policy — Frescovo

_Last updated: 2026-08-17_

Frescovo ("the app") helps you track food expiry dates in your fridge, get AI-powered recipe
suggestions, and recognize food/receipts from photos. This page explains what data we collect,
how we use it, and where it is stored.

## 1. Data we collect

| Data type | Details |
| --- | --- |
| Food information | Item name, expiry date, quantity, unit, category, storage location (fridge/freezer/pantry), price (if entered manually or scanned from a receipt) |
| Usage history | Items marked as consumed or wasted, used to build waste-reduction statistics |
| Photos | Photos of food or receipts you take for automatic recognition |
| Account information | When signing in with Google: your email, display name, and Google account identifier |
| Shared fridge | The 6-character invite code when you create or join a shared-fridge group |
| Purchases | Purchase records for AI credit packs bought through Google Play (product, transaction token, credits granted) |
| App activity | Which app features you use and when, recorded as a request log (your account identifier, the feature called, and a timestamp) |

The app is **usable immediately without signing in** — only AI features (photo recognition,
recipe suggestions) require Google sign-in.

## 2. Where data is sent

- **Food/receipt photos** are sent to the **Google Gemini API** for ingredient recognition and
  recipe suggestions. We **do not store photos** on our servers — they are only forwarded for
  processing and discarded immediately after we receive the result.
- **Sign-in information** (email, name, account identifier) comes from **Google Sign-In** when
  you choose to sign in with your Google account.
- **Purchases** are processed by **Google Play Billing**. We never see or store your payment
  details; we only receive a confirmation that a purchase is valid.

## 3. Where data is stored

- On your device: a local SQLite database (works offline).
- On our server: a PostgreSQL database (used to sync your data across your own devices and
  between members of a shared fridge).

## 4. Who data is shared with

- **Members of the same "shared fridge"** (if you join a group via an invite code) can see
  each other's food list — this is an intentional feature of the app, not a data leak.
- We **do not sell** and **do not share** your data with any third party other than Google
  (Gemini API for photo processing, Google Sign-In for authentication, Google Play for
  purchases).

## 5. How we use app activity data

We record which features are called and when, to understand how the app is used and to keep it
running reliably. This data is used **only by us**, is never sold or shared, and is deleted
together with your account.

## 6. Data / account deletion

You can delete your account and all associated data (food items, usage history, purchased AI
credits, sign-in information, activity records) directly in the app (Profile → Delete account),
or if you don't have the app installed or can't sign in, see instructions at
[chechle39.github.io/fridge-guardian-legal/delete-account/](https://chechle39.github.io/fridge-guardian-legal/delete-account/).

## 7. Contact

For any privacy questions, please contact: **lethanhtuan70995@gmail.com**
