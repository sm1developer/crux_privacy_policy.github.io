Privacy Policy for Crux
Effective Date: March 26, 2026

TL;DR: We steal absolutely nothing. Crux runs 100% offline. We do not have servers, databases, or analytics frameworks. Your data never leaves the physical hardware of your smartphone.

1. The Data We Collect
To provide you with highly personalized digital footprints and daily briefs, Crux locally processes the following data classes:

App Usage Statistics: Core screen-time duration per application.
Notification Content: The titles, timestamps, package names, and textual bodies of incoming notifications.
2. How We Store Your Data
Your data is immediately routed into a deeply encrypted Android SQLite Database (`secure_vault.db`) explicitly locked within the Application Sandbox (`/data/data/com.appverse.crux/databases/`). It is impossible for third-party applications to access this secure vault. We do not back up this database to the cloud. If you uninstall Crux, all intercepted data is permanently destroyed.

3. Offline On-Device Machine Learning
Crux evaluates your usage and notifications utilizing the Google ML Kit API. We strictly utilize the on-device, natively executing Natural Language Processing (NLP) bindings. Textual data is analyzed algorithmically by your phone's processor to extract dates, financial triggers, and addresses. Your data is never offloaded to external LLMs (Large Language Models) or Cloud inference APIs.

4. Third-Party Access
We do not share, sell, or transmit any data to marketing entities, crash analytic reporters, or data brokers. The application is completely devoid of external logging endpoints (such as Firebase Analytics or Sentry).

5. Prominent Disclosure & Consent
Upon initial launch, Crux prompts the user with an explicit prominent disclosure regarding the necessity of the `NotificationListenerService` and `UsageStatsManager` Android System APIs. Operating these APIs signifies direct user consent for local processing.

6. Contact Us
sm1appdeveloper@gmail.com For privacy questions or requests, please contact support.



