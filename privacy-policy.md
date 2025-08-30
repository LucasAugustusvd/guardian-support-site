---
layout: default
title: Privacy Policy
---

# Privacy Policy — Guardian
**Effective date:** 2025-08-30  
*(Update this date when you make changes.)*

Guardian (the “App”) helps you notify trusted contacts and opted-in nearby users when you need help, and visualize recent alert clusters to plan safer routes. We take privacy seriously and collect only what we need to provide these features.

---

## Summary (Plain English)
- We collect your **phone number**, **device push token**, and **location** (when you use alert/nearby features).
- For **trusted contacts**, we use **phone numbers** you submit to match other Guardian users. We do **not** use contact names on the server.
- Alert locations are stored so we can notify others nearby and build an anonymized **heatmap**.
- We **do not sell** your data. We do **not share** it for advertising.

---

## Data We Collect

### You provide
- **Phone number** — used to link your device and deliver contact/nearby alerts.
- **Trusted contacts’ phone numbers** — used **only** to determine which of your contacts also use Guardian so they can be notified during alerts.

### Collected automatically
- **Device push token (APNs)** — required to send notifications.
- **Location** — when you trigger an alert, we use your current location to notify contacts and opted-in users within ~250 m. If you opt-in to receive nearby alerts, your last location (coarse/coarse-ish) may be used to determine proximity.
- **Basic app events** — e.g., registration, alert creation, delivery results.

### Optional content
- **Heatmap/Recent Alerts** — We store alert coordinates and timestamps to show clusters. The heatmap is **aggregate** and **does not** show names or phone numbers.

---

## How We Use Data
- **Alerts:** Send notifications to your chosen contacts and opted-in nearby users within a set radius (e.g., 250 m).
- **Nearby Alerts:** If you opt-in, we may notify you when someone nearby triggers an alert.
- **Heatmap:** Aggregate recent alerts (no names/phones) so users can see areas with higher recent activity.
- **App operations & safety:** Fraud prevention, abuse mitigation, service functionality.

---

## Contacts Handling
- You may add contacts in the app. We transmit those **phone numbers** to our backend to match with other registered users.  
- On our server, we convert contact numbers to **irreversible hashes** for storage (we do not store contact names server-side).  
- You can remove contacts at any time within the app.

---

## Data Retention
- **Device registrations**: kept while the app is active; stale tokens may be removed after ~90 days.
- **Alerts & coordinates**: kept for a limited period to power the heatmap and troubleshooting (e.g., **30 days**), then deleted or aggregated.  
  *(Adjust this period if your implementation differs.)*

---

## Sharing
We share data only with:
- **Apple Push Notification Service (APNs)** to deliver notifications.
- **Service providers** we use to host the backend and databases (e.g., Render, PostgreSQL). They process data on our behalf.

We do **not** sell your personal data.

---

## Security
- Transport security via TLS.
- Limited access to production systems.
- We regularly review auth keys and rotate credentials.

No method is 100% secure, but we work to protect your information.

---

## International Transfers
Data may be processed and stored in countries other than where you live (e.g., EU/US), subject to appropriate safeguards.

---

## Your Choices & Rights
- **Permissions**: You may disable Location or Notifications in iOS Settings (functionality will be limited).
- **Access/Deletion**: Email us at **[privacy@yourdomain.com](mailto:privacy@yourdomain.com)** to request access or deletion. We may need to verify your identity (e.g., from the device associated with your phone number).
- **Opt-in Nearby**: You can toggle nearby alerts in the app at any time.

If you are in the EEA/UK, you may have additional rights under GDPR (access, correction, erasure, restriction, portability, objection). Contact us to exercise them.

---

## Children
Guardian is not directed to children under 13 (or the relevant age in your region). If you believe a child provided us data, contact us to remove it.

---

## Changes to this Policy
We may update this policy from time to time. We will update the “Effective date” and, when material, notify you in the app.

---

## Contact Us
- **Privacy:** [privacy@yourdomain.com](mailto:privacy@yourdomain.com)  
- **Support:** [support@yourdomain.com](mailto:support@yourdomain.com)

