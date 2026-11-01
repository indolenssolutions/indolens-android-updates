# Indolens SMS: shop phone setup (one page)

**You need:**
- the shop's Android phone with the shop SIM inserted;
- the `IndolensSMS-<version>.apk` file;
- a **6-digit pairing code** from the Indolens admin (valid for 5 minutes).

## 1. Install
1. Copy the APK to the phone (WhatsApp, USB or a download link) and tap it.
2. If Android asks, allow **Install unknown apps** for the app you opened it from (Files, Chrome, WhatsApp).
3. If Play Protect warns about an unknown app, tap **More details → Install anyway**.
4. If Play Protect **blocks** the install (no "Install anyway"; this happens to sideloaded apps that use SMS):
   open **Play Store → profile icon → Play Protect → ⚙ → turn off "Scan apps with Play Protect"**, install
   (or update) Indolens SMS, then turn scanning back on. Ask the admin if you are unsure.

## 2. Pair the phone
1. Open **Indolens SMS** and tap **START SERVICE**.
2. **Shop name:** type the shop name exactly as used in Indolens (e.g. `Indolens Anna Nagar`).
3. **Use this phone to send login OTPs:** tick this **only on the one main phone**. Leave it unticked on shop phones.
4. On the **PAIR WITH CODE** tab, enter the 6-digit code from the admin and tap **CONTINUE**.
5. Allow every permission Android asks for: **SMS**, **Phone** and **Notifications**.
6. The Home screen should show your **Shop** and **Role**, and the button now reads **STOP SERVICE**.

## 3. Keep it running (important)
- **Start on boot:** turn this switch **ON** on the Home screen.
- **Battery optimisation:** go to **Settings tab → Battery optimization** and allow the app to **not** be optimised.
- **Samsung:** Android **Settings → Apps → Indolens SMS → Battery → Unrestricted**. Also check **Settings → Battery → Background usage limits** and make sure Indolens SMS is **not** in "Sleeping apps" or "Deep sleeping apps".
- **Xiaomi / Redmi / Oppo / Vivo:** turn **Autostart** on for Indolens SMS, and set Battery saver to **No restrictions**.
- Keep the phone **charging** and on **mobile data or Wi-Fi**. Don't swipe away the "Listening to server events…" notification, and don't force-stop the app.

## 4. Choose the SIM (dual-SIM phones)
- In Android **Settings → Connections → SIM manager → SMS messages** (Samsung), or **Settings → SIM cards → SMS**, choose the **shop SIM**.
- Or, in the app: **Settings tab → Messages… → "If SIM number is not specified, use"** → pick the shop SIM.

## 5. Check
Ask the admin to send a test SMS. It appears under the **MESSAGES** tab as *Sent*, then *Delivered*.

## 6. Updates
When a new version is published the app shows **Update available** (at start-up, and a notification once a
day). Tap **Download & install**; the app checks the download before opening the Android installer. A
*required* update must be installed before the app can be used. If the installer says the app is blocked,
see step 1.4. The latest APK, a QR code and this guide are also in the Indolens web app under
**Settings → Indolens SMS app** (or **Store → Settings**).

---

### For the admin: getting a pairing code
On the already-paired **main (OTP) phone**: **Settings tab → Indolens server… → Login Code**. Enter the Indolens SMS
account password. A 6-digit code appears, valid for 5 minutes, one per new phone. The admin can also sign a phone in
with the account username and password (**SIGN IN** tab), but codes avoid sharing the password with shops.

**To re-pair or change the OTP phone:** **Settings tab → Indolens server… → Unregister device**, then pair again with
the correct OTP tick. Only one phone should have the OTP role. The tick only labels the phone (`[OTP]` in its name);
login OTPs go to the phone the Indolens tech team has pinned on the server, so tell them whenever the OTP phone
changes. Unregistering only unpairs the phone; the old entry stays on the server until the tech team deletes it.
