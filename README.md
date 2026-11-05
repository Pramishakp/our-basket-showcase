# Our Basket

**An offline-first shared shopping and household-spending app for Android.**

Our Basket helps households plan purchases together, keep using their shopping list without reliable internet, record purchase details, and understand spending over time.

> Portfolio showcase only. The application source code, Firebase configuration, signing credentials, and installable APK are kept private while the product is being prepared for release.

## Key features

- Shared household list with automatic Firebase synchronization
- Offline viewing, adding, editing, and purchase marking
- Automatic synchronization when connectivity returns
- Due dates, categories, preferred shops, search, and filters
- One-handed shopping interactions and compact mobile forms
- Purchase history with editable records
- Monthly and yearly spending reports
- Category and item-level spending insights
- Repeat-purchase suggestions and reminder notifications
- Estimated shop totals based on previous purchase prices
- Optional hand-off to Google Pay or PhonePe
- Email-based account recovery and household backup/restore
- Accessible touch targets, screen-reader labels, and reduced-motion support

## Technology

- TypeScript
- React Native
- Expo SDK 57
- Firebase Authentication
- Cloud Firestore
- AsyncStorage
- Expo Notifications, File System, Document Picker, and Sharing
- Android and Kotlin native project integration

## Architecture overview

![Our Basket architecture](architecture.svg)

The app follows an offline-first approach. Actions update the device immediately and are stored locally. When internet access is available, queued changes synchronize with the shared Firestore household. Firebase Authentication and Firestore security rules limit access to approved household members.

## My role

- Defined the product requirements and shopping workflows
- Directed the information architecture and UI/UX decisions
- Reviewed and refined forms for one-handed mobile use
- Tested internal Android builds on real devices
- Identified synchronization, notification, restore, and layout issues
- Iteratively improved the product based on household use
- Managed Firebase setup, security rules, recovery, and release preparation

## AI-assisted development

Our Basket was created using AI-assisted development technology. AI tools supported code generation, debugging, design exploration, documentation, and test iteration. Product decisions, requirements, workflow design, UI/UX direction, real-device testing, and final acceptance were led by **Pramisha K P**.

## Privacy and payments

The app does not handle payment credentials. Payment actions only open the selected payment application. Household data is protected through Firebase authentication and membership-based Firestore rules.

## Release status

Our Basket is currently in private Android testing and is being prepared for a future Google Play release.

Updated product screenshots will be added after the visual theme and icon system are finalized.

**Google Play:** Coming soon

## Source availability

The source repository is private while the product is under development. Selected recruiters or collaborators may be given access separately when appropriate.

