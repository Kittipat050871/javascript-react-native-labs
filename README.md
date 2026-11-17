# JavaScript & React Native Labs (Coursework)

**Lab exercises for 1101103 Project in Scripting Language Application Development, Suranaree University of Technology (2026)**

Small practice projects completed while learning JavaScript, React Native (Expo), Next.js, and Firebase. They were the stepping stones for the [SUT FixIt](https://github.com/Kittipat050871/sut-fixit-app) team project.

> **Status:** Coursework. These are learning exercises, not finished applications.

## Contents

| Folder | What it covers |
|---|---|
| `Lab1-8/` | Expo / React Native labs 1–8: components, state, navigation, and Firebase (Auth, Firestore, Storage) |
| `NextJS-Store/` | Next.js mini store: pages, dynamic product routes (`[id].js`), cart page, shared layout |

## Run

```bash
# React Native labs
cd Lab1-8 && npm install && npx expo start

# Next.js store
cd NextJS-Store && npm install && npx next dev
```

## Note on Firebase config

`Lab1-8/App.js` contains a Firebase **web** config for a class lab project. Firebase web API keys are meant to be shipped in client apps and are not secret on their own; access is controlled by Firebase Security Rules. The lab project should still have locked-down rules or be deleted after the course.
