# Privacy Policy for FlowBoard

Last updated: November 21, 2025

## Introduction

FlowBoard ("we", "our", or "the app") is committed to protecting your privacy. This Privacy Policy explains how we handle your information when you use our iPad task management application.

## Data Collection and Storage

### Local Data Storage
- **All task data is stored locally on your device** using SwiftData.
- Task information (titles, descriptions, priorities, due dates, tags, and subtasks) is stored in an SQLite database on your iPad.
- **We do not collect, transmit, or store any of your personal data on our own external servers.**
- **We do not have access to your task data.**

### App Group Sharing
- Task data is shared between the main app, widget extension, and share extension using iOS App Groups.
- This sharing happens exclusively on your device and does not involve any external servers.

## AI Features and Data Processing

FlowBoard includes premium AI-powered features that utilize third-party services to provide intelligent task management capabilities.

### Third-Party AI Providers
We use **Google Gemini** as our AI provider for all intelligent features, including:
- Natural language task parsing and creation.
- Project planning and breakdown.
- Workload analysis and insights.
- Smart scheduling suggestions.

### Data Transmitted to AI Providers
When you explicitly use an AI feature (e.g., by tapping the "AI Assistant" button, sending a message in the chat, or using a Siri command for AI), the following data may be sent to Google:
- **User Prompts**: The text you enter or speak (e.g., "Plan my wedding", "Add task to call mom").
- **Task Context**: For features like "Workload Analysis" or "Smart Scheduling", a subset of your existing task titles, priorities, and due dates may be sent to the AI provider to generate insights.

### Data Usage and Privacy
- **Processing Only**: Data sent to Google Gemini is used solely for the purpose of generating the requested response.
- **No Training**: We access these services via their APIs, which are subject to enterprise agreements that typically prevent your data from being used to train their models.
- **Security**: All data is transmitted securely via HTTPS.
- **Retention**: Data is not stored by FlowBoard on any external server. Google may retain data for a limited period for abuse monitoring, as per their privacy policy.

Please review the privacy policy of our AI partner:
- [Google Privacy Policy](https://policies.google.com/privacy)
- [Google Generative AI Terms](https://ai.google.dev/terms)

## Data We Do NOT Collect

We do not collect:
- Personal identification information (name, email, etc.).
- Usage analytics or statistics.
- Location data.
- Device information.

## In-App Purchases and Subscriptions

### Subscription Information
FlowBoard offers an optional premium subscription that unlocks AI-powered features. Subscription information is handled by Apple through the App Store.

### Payment Processing
- All payment processing is handled by Apple through the App Store
- We do not collect, store, or have access to your payment information
- Apple manages all billing, refunds, and subscription management
- Your subscription status is verified through StoreKit (Apple's framework) on your device

### Data Associated with Subscriptions
- We only verify whether you have an active subscription to enable premium features
- No personal or payment information is transmitted to our servers
- Subscription status is stored locally on your device

## Voice Recognition and Microphone Access

### Permissions
FlowBoard's premium AI features include Voice Mode, which requires:
- **Microphone Access**: To capture your voice input
- **Speech Recognition**: To convert your speech to text

### How We Use These Permissions
- Voice input is processed locally on your device using Apple's Speech Recognition framework
- Transcribed text may be sent to Google Gemini for AI processing (only when using AI features)
- We do not record, store, or transmit audio files
- All voice processing happens in real-time and is not saved

### Disabling Voice Features
- You can deny microphone permission and still use all other app features
- Voice features are entirely optional and only available with FlowBoard Premium

## Notifications

- FlowBoard requests permission to send local notifications for task reminders.
- These notifications are generated locally on your device.

## iCloud and CloudKit

- **Currently, CloudKit synchronization is explicitly disabled.**
- All data remains local to your device.

## Data Security

- Your task data is protected by your device's built-in iOS security features.
- We recommend enabling device passcode/biometric authentication.

## Children's Privacy

FlowBoard does not knowingly collect or store data from anyone, including children under the age of 13.

## Your Rights and Choices

### Data Access and Deletion
- All your task data is stored locally on your device
- You can view and manage all your data within the App
- To delete all data, uninstall the App or use the "Delete All Tasks" feature in Settings

### Opting Out of AI Features
- AI features are only activated when you explicitly use them
- You can choose not to subscribe to FlowBoard Premium to avoid all AI processing
- Free version does not use any third-party AI services

### Revoking Permissions
You can revoke microphone and speech recognition permissions at any time through:
iOS Settings → FlowBoard → Permissions

## California Privacy Rights (CCPA)

If you are a California resident, you have the right to:
- Know what personal information we collect (see "Data Collection" section)
- Request deletion of your personal information
- Opt-out of the sale of personal information (we do not sell your data)

Note: Since FlowBoard does not collect personal information beyond what's processed locally, these rights are automatically protected.

## European Privacy Rights (GDPR)

If you are in the European Economic Area, you have rights under GDPR including:
- Right to access your data
- Right to rectification
- Right to erasure ("right to be forgotten")
- Right to data portability
- Right to object to processing

Note: Since all data is stored locally on your device, you have direct control over your data at all times.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Material changes will be communicated through:
- Updating the "Last updated" date at the top
- In-app notification upon first launch after update
- Email notification (if we have your contact information)

Your continued use of FlowBoard after changes constitutes acceptance of the updated Privacy Policy.

## Contact Us

If you have any questions about this Privacy Policy, please contact us at:
- **Email**: prajwalpp1@gmail.com
- **GitHub**: https://github.com/prajwalp/flowboard/issues
- **Support**: https://github.com/prajwalp/flowboard/blob/main/.github/SUPPORT.md

