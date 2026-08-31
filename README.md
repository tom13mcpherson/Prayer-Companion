# Prayer Companion

A private Firebase web app with Google sign-in and three simple sections: Pray, All names, and Celebrate.

## Firebase project

`the-prayer-app-8cd65`

## Deploy

From this folder, authenticate Firebase CLI and run:

```bash
npx firebase-tools deploy --only hosting
```

Firestore data is stored beneath `/users/{uid}/names`, matching the published user-isolation rules.
