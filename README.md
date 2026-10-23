# TradeSaathi Trading Journal

An offline Android trading journal prototype. Trade records are stored locally on the device using Android SharedPreferences.

## Features
- Save BUY/LONG and SELL/SHORT trades
- Calculate trade P&L from entry, exit, and quantity
- View total P&L, win rate, and trade count
- Record stop loss, target, trading psychology, and notes
- Delete a trade
- No account or internet connection required in the app

## Build an APK using GitHub Actions
1. Upload the contents of this project to your GitHub repository (not the ZIP file itself).
2. Open the **Actions** tab in the repository.
3. Select **Build TradeSaathi APK** and press **Run workflow** (or push the files to `main`).
4. When the run completes, open the run and download the `TradeSaathi-debug-apk` artifact.
5. Extract the downloaded artifact ZIP to get `app-debug.apk`.

This is a debug APK for testing, not a Play Store release. Test calculations carefully before using it for financial records. P&L does not include brokerage, taxes, slippage, or option contract multipliers.
