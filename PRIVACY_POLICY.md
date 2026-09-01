# Privacy Policy for Coral Villa

**Last Updated:** September 1, 2026

Welcome to **Coral Villa** ("we," "our," or "us"). We respect your privacy and are committed to protecting any information generated through your play of Coral Villa (the "Game"). This Privacy Policy explains how data is collected, used, and safeguarded when you play the Game on web browsers, Android devices, desktop platforms, or Reddit.

---

## 1. Information We Collect

### A. Local Save Data
Coral Villa is designed with a privacy-first, local-storage model. Your game progress, level completions, unlocked villa structures, high scores, coins, pearls, premium pass status, and game settings are saved locally on your device (using Browser LocalStorage, IndexedDB, or local save files). Cora Villa also generates a random installation identifier that is stored on your device.

**On Reddit**, your game save is additionally mirrored to Reddit's servers (Reddit's managed Redis) so your progress and purchased items follow your Reddit account across devices and survive a cleared browser cache. The server copy is refreshed with every important game event (level completion, purchase, villa build, pass claim) and is deleted when you reset all progress, when the server copy has been inactive for 180 days, or when you request data removal.

### B. Optional Account & Cloud-Save Data
Signing in is optional. If you choose to sign in with Google OAuth or email/password (via Supabase Authentication), we use the account to:
- authenticate you,
- store a sanitized copy of your game save,
- keep your progress in sync across devices, and
- associate cloud data with your account.

We never receive your Google password. Google sign-in is handled by Google OAuth; email/password sign-in is handled by Supabase Auth.

### C. Analytical & Gameplay Data
Anonymous gameplay analytics is opt-in and disabled by default. When enabled, we may collect coarse, non-personally identifiable events such as app start, level start, level win/loss, purchase, and lifecycle events to debug issues and improve game balance. Analytics does not include passwords, payment credentials, save contents, or precise location data. You can disable analytics at any time in the in-game Settings.

### D. Payment & In-App Purchase Information
If you choose to make in-game purchases, your transaction is processed directly by the platform's payment provider:

- **On Reddit**, purchases are made with Reddit Gold through Reddit's payment system. The transaction is handled entirely by Reddit, subject to [Reddit's privacy policy](https://www.redditinc.com/policies/privacy-policy) and [Reddit's User Agreement](https://www.redditinc.com/policies/user-agreement). Coral Villa only learns which product you purchased (to deliver it to your game) — it never sees your payment method.
- **On Android (Google Play)**, in-app purchases (coins, hearts, extra lives, boosters, and the Tide Pass Premium reward track) are purchased and fulfilled through Google Play Billing:
  - [Google Play privacy policy](https://policies.google.com/privacy)
- **On other platforms** (such as Itch.io or via Stripe Checkout), the transaction is processed by those providers:
  - [Itch.io Privacy Policy](https://itch.io/docs/legal/privacy)
  - [Stripe Privacy Policy](https://stripe.com/privacy)

The store records only the item, price, and a transaction identifier needed to fulfill your order. **Coral Villa does not collect, receive, or store your credit card numbers, banking details, or billing addresses.**

#### Tide Pass Premium (one-time, 14-day)
The Tide Pass Premium reward track is a **one-time in-app purchase** that unlocks the premium reward track for 14 days from the time of purchase. It **does not auto-renew**, and there are no recurring charges. Buying it again simply extends the premium window. Because it is a single, non-recurring purchase, there is no cancellation or auto-renewal flow. Refunds follow the applicable store's refund policy (Google Play or the platform you purchased through).

#### Restoring Purchases
On Android, already-owned non-consumable purchases (such as Tide Pass Premium) can be restored from the store receipt when you reinstall the app or sign in on a new device.

---

## 2. How We Use Information

Any non-personal or local data processed by the Game is used strictly for:
- Maintaining and restoring your game progress.
- Synchronizing progress across your devices (when you are signed in).
- Optimizing game performance, balance, and user experience.
- Fixing bugs and preventing technical glitches.

We do **not** sell, trade, rent, or monetize your personal data.

---

## 3. Data Sharing & Third-Party Services

The Game may run on third-party hosting platforms (such as Itch.io, GitHub Pages, Google Play, or Vercel). These platforms may collect standard web server logs (such as IP address, browser type, and access times) in accordance with their respective privacy policies.

### Leaderboard Data
**On Reddit**, the in-game global leaderboard stores a small amount of data on Reddit's servers (in Reddit's managed Redis): your Reddit user ID, your chosen display name (which defaults to your Reddit username), your best score, level, and win streak. Leaderboard entries are removed when a Reddit account is deleted, and entries with no activity expire automatically after 30 days.

**On other platforms**, when you are signed in, the in-game leaderboard stores a player-selected nickname, scores, level information, win streak, avatar seed, and timestamps on our hosting provider's servers (Supabase), associated with your account. Leaderboard entries are public gameplay data, so please do not enter personal information into a nickname. You may play without participating in the online leaderboard.

---

## 4. Children's Privacy (COPPA Compliance)

Coral Villa is a family-friendly game. We do not knowingly collect or solicit personal information from children under the age of 13 (or under 16 in certain jurisdictions). If you believe a child has provided us with personal information, please contact us so we can promptly delete it.

---

## 5. Data Control & Deletion

Your save game data is stored locally on your device, so you have complete control over your data at all times:
- Clear your game progress by clearing your browser cache/cookies for the site or by resetting your local save in the in-game settings menu.
- Deleting the Game or clearing local site data permanently removes all local progress from your device.
- **On Reddit**, the in-game "Reset all progress" option also deletes your cloud save from Reddit's servers, and you can request data removal at any time by contacting us (Section 7). Server saves with no activity are automatically deleted after 180 days.
- **When signed in to a cloud account**, deleting your account removes your cloud save and leaderboard entries from our servers. Cloud-save access is restricted to your account, and you can request account deletion at any time by contacting us (Section 7).

---

## 6. Retention & Security

Cloud data is retained while your account exists or until deletion is processed. Row-level security limits cloud-save access to the owning account; leaderboard reads are public, while leaderboard writes are restricted to the matching account identity. Data in transit is protected using industry-standard encryption.

---

## 7. Updates to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices or game features. Any updates will be published in this repository with a revised "Last Updated" date.

---

## 8. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or your data privacy, please contact us at:

📧 **Email:** PluvianDev@outlook.com