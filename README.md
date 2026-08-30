# Calm Bills

A calm, smart bill tracker Flutter app inspired by the visual direction in the design mockup.

## Included
- Overview dashboard with due-this-month summary
- Smart insight cards
- Upcoming bills timeline
- Add/edit bill flow
- Monthly recurring or one-time bills
- Paid-this-month tracking
- Notes, auto-pay, reminder toggles
- Demo bank connection mapping screen
- Local storage with SharedPreferences

## Run locally
1. Install Flutter.
2. Run `flutter create .` only if you are dropping these files into an empty folder.
3. Run `flutter pub get`
4. Run `flutter run`

## Important note about bank connections
The app includes a **bank connections screen and account-mapping flow**, but it currently uses demo data.
To go live, add a backend and integrate Plaid or Teller.
See `BANK_INTEGRATION.md`.

## Recommended next steps
- Add push notifications for reminders
- Replace demo bank accounts with Plaid or Teller
- Add onboarding, app icon, and App Store screenshots
- Test on iPhone and Android devices
