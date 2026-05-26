# Privacy Policy — Bingo Street (빙고 스트릿)

**Effective date: May 26, 2026**

Bingo Street ("the App") is a location-based photo bingo game you can start instantly without signing up. The App is designed around the principle of collecting no personal data. This policy explains what data the App handles and how it is protected.

## 1. Information We Collect

The App requires no account, and the operator (developer) collects no personally identifiable information about you. The App handles the following data, all of which is stored only on your device unless stated otherwise.

| Data | Where it is handled | Purpose | Sent to a server? |
|------|---------------------|---------|-------------------|
| Verification photos | On device (app sandbox) | Filling and recording bingo cells | Never |
| Location (optional) | May appear in photo metadata | Display in the local history screen | Never |
| Nickname · initial · color | On device | Profile and multiplayer display | Shown only to nearby devices (see §4) |
| Game history (board, results, time) | On device (SwiftData) | Viewing your records | Never |
| Crash logs | Apple | Stability improvements | Apple-standard, anonymous (see §5) |

The App does not collect your name, email, phone number, advertising identifiers, or tracking identifiers.

## 2. How Information Is Used

- **Verification photos** are used only to fill bingo cells and to display them on the results and history screens.
- **Location** may be embedded in a photo's metadata (EXIF) when you take it, and is used only to show "where it was taken" on the on-device history detail screen. It is never sent to any operator server.
- **Profile information (nickname, initial, color)** is used to distinguish players on the game screen and in nearby multiplayer.
- Collected information is never used for advertising, marketing, profiling, or model training.

## 3. No Third-Party Sharing

The App does not provide, sell, or share your data with any third party. The App uses no authentication/account server, no analytics SDK, no ad network, and no tracking SDK. Photos, location, and history handled by the App are not transmitted to anyone, including the operator.

As an exception, Apple may process standard crash/diagnostic logs at the operating-system level (see §5); these are anonymous.

## 4. Nearby Multiplayer (MultipeerConnectivity)

Multiplayer works only over local communication (Bluetooth / Wi-Fi) using Apple's MultipeerConnectivity framework — with no internet server and no central account.

- Game state such as "who filled which cell" syncs **only between nearby devices** in the same game.
- Profile display info (nickname, initial, color) is shown to nearby participants in the same game.
- **Original verification photos are not transmitted to other devices.**
- All communication happens within local proximity range and never passes through any external server.

## 5. Crash Logs

If you have opted in to sharing diagnostic data in your Apple device settings, Apple may provide standard crash and diagnostic logs to the operator. These logs are anonymous and used only to improve stability. Their processing is governed by Apple's [Privacy Policy](https://www.apple.com/legal/privacy/).

## 6. Data Retention and Deletion

- All App data — photos, history, and profile — is stored only on your device.
- You can delete individual game records from the history detail screen in the App.
- **Deleting the App** removes all local data it stored (including photos, history, and profile) from your device.
- Because no user data is stored on any operator server, no separate server-side deletion request is necessary.

## 7. Permissions

| Permission | Required? | Purpose |
|------------|-----------|---------|
| Camera (`NSCameraUsageDescription`) | Required | Capturing verification photos directly |
| Location (optional) | Optional | Recording location in photo metadata (for the history screen) |
| Local Network (`NSLocalNetworkUsageDescription`) | For multiplayer | Discovering and connecting to nearby devices (MultipeerConnectivity) |

The App **does not request photo-library (gallery) access.** Verification happens only through live capture; photos are never imported from your gallery. You can change permissions anytime in device settings; without camera permission, the photo-verification feature cannot be used.

## 8. Children's Privacy

The App has a 4+ age rating and collects no personal data, so it is safe for all ages, including children. The App does not knowingly collect personal information from children.

## 9. Contact

For questions about this policy, please contact us.

Email: [dev@bingostreet.app](mailto:dev@bingostreet.app)

## 10. Changes

If this policy changes, we will post the update and its effective date on this page. For material changes, we will provide notice in-app or on this page.
