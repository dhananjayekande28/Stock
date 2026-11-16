# AI Trade Pro (Android demo)

This is a starter Android Studio project wrapping the existing AI Trade Pro HTML dashboard in an Android WebView.

## Important limitations
- The dashboard is DEMO-only. Prices and indicators are sample/calculated demo values, not live NSE/BSE data.
- No broker login, API key, order placement, or automated trading is included.
- Live data requires a licensed/authorized market-data provider and a secure backend.

## Build APK with GitHub Actions
1. Upload the contents of this folder to a GitHub repository's `main` branch.
2. Open the repository's **Actions** tab.
3. Select **Build Android APK** and press **Run workflow** (or wait for the push build).
4. Open the completed workflow run, scroll to **Artifacts**, and download `AI-Trade-Pro-debug-APK`.
5. Extract the downloaded artifact ZIP to get `app-debug.apk`.

## Build locally
Open this folder in Android Studio, allow Gradle sync, then choose Build > Build Bundle(s) / APK(s) > Build APK(s).
