## Android Push Notifications Setup

### Basic Setup
- Install expo-notifications & build
- Request permissions
- Create notification channel (Android)
- Set notification handler (foreground display behavior)
- Add google-services.json to project root & reference in app.json
- Upload FCM V1 service account key to EAS

### Local Notifications
- Schedule notifications via Notifications.scheduleNotificationAsync()

### Remote Notifications
- Generate & log Expo push token on mount
- Test via cURL or Expo's push notification tool

### Reactive Notifications
- Handle foreground notifications via addNotificationReceivedListener
- Handle notification taps via addNotificationResponseReceivedListener
- Handle cold start taps via getLastNotificationResponse
- Parse notification data and navigate accordingly
