# Privacy Policy for Furendo

**Effective Date:** January 1, 2025

## Introduction

Furendo ("we," "our," or "us") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, and safeguard your information when you use our mobile application.

## Information We Collect

### Camera Access

- **Purpose:** We request camera permission to allow you to take photos of pets for adoption listings
- **Usage:** Photos are used solely for creating and managing pet adoption posts
- **Storage:** Images are securely stored on Cloudinary cloud storage
- **Sharing:** Photos are only shared within the app for pet adoption purposes

### Location Access

- **Purpose:** We request location permissions (fine and coarse) to help you find pets and services near you, and to display your general location with pet listings
- **Usage:** Location data is used to:
  - Show nearby pet listings and services
  - Display general location information (city level) for pet adoption listings
  - Help users discover pets in their area
- **Storage:** Location data (latitude, longitude, city, state, country, zip code, and address if provided) is stored in our database and associated with:
  - User profiles (optional)
  - Pet listings (for adoption listings)
  - NGO locations (for verified organizations)
- **Sharing:** General location information (city/state level) is visible to other users for pet adoption matching purposes. Precise coordinates are not shared publicly.

### Storage Access

- **Purpose:** We request storage permissions (read and write external storage) to allow you to select existing photos from your device for pet listings
- **Usage:** Storage access is used to import photos from your device gallery for pet adoption posts
- **Storage:** Selected images are uploaded to Cloudinary and removed from temporary device storage after upload

### Notification Access

- **Purpose:** We request notification permissions to send you important updates about:
  - New messages in conversations
  - Pet listing status updates (approval, rejection, adoption)
  - Pet likes and interest
  - System notifications
- **Usage:** Notifications help keep you informed about activity on your account and pet listings
- **Storage:** Push notification tokens, device identifiers, and platform information are stored to deliver notifications. You can manage notification preferences in your account settings.

### Account Information

- **Registration Data:**
  - Email address (required)
  - Name (required)
  - Password (optional for Google Sign-In users)
  - Profile avatar/photo (optional)
- **Authentication:**
  - Google Sign-In integration for secure login
  - Email/password authentication (optional)
  - Google ID (for OAuth users)
- **Profile Data:**
  - Name, email, avatar URL and key
  - Location information (if provided)
  - Account creation and update timestamps
  - Email verification status

### Pet Listing Information

- Pet name, animal type, breed, age, gender, description
- Pet images (stored on Cloudinary)
- Pet location data (if provided)
- Pet adoption status and history
- Pet likes and interactions

### Messaging and Communication Data

- **Conversations:** Direct messages between users, conversation participants, and timestamps
- **Messages:** Message content, type (text, image, file, system), metadata, edit history
- **Usage:** Messages are stored to facilitate communication between pet adopters and listers

### Usage and Interaction Data

- Pet likes and favorites
- User blocks and blocking reasons
- User reports and pet reports (for safety and moderation)
- Support requests and feature requests
- Notification preferences and history
- Push notification tokens and device information

### Device Information

- Device identifier (optional, for push notifications)
- Platform information (iOS, Android)
- Push notification tokens (Expo push tokens)

## How We Use Your Information

- Provide pet adoption services and facilitate connections between adopters and pet owners
- Connect users with nearby pets and services based on location preferences
- Enable secure messaging between users interested in pet adoption
- Send important service notifications (messages, pet status updates, system announcements)
- Improve app functionality and user experience
- Ensure platform safety through moderation tools (blocking, reporting)
- Provide customer support and respond to support requests
- Send email notifications (verification emails, password resets, support ticket updates) via Resend

## Data Security

- All data is transmitted using secure HTTPS connections
- Images are stored on secure Cloudinary cloud infrastructure
- User passwords are hashed using industry-standard bcrypt encryption
- JWT tokens are used for secure authentication with short-lived access tokens (15 minutes) and longer-lived refresh tokens (7 days)
- We implement industry-standard security measures
- Regular security updates and monitoring

## Third-Party Services

- **Cloudinary:** For secure image storage and management
- **Google:** For authentication services (OAuth Sign-In)
- **Resend:** For sending transactional emails (verification, password resets, support communications)
- **Expo:** For push notification delivery services
- **Railway:** For app hosting and backend services
- **PostgreSQL:** For database storage (hosted on Railway infrastructure)

## Data Sharing and Disclosure

- **Public Profile Information:** Your name, avatar, and general location (city level) may be visible to other users for pet adoption purposes
- **Pet Listings:** Pet information and photos you post are visible to other users browsing the app
- **Messages:** Messages are private between conversation participants
- **We do not sell your personal data** to third parties
- **We may share data** with law enforcement if legally required
- **Service Providers:** We share data with third-party service providers (Cloudinary, Google, Resend, Expo) necessary to operate the service, under strict confidentiality agreements

## Your Rights

- **Access:** You can access your personal data through your account profile
- **Update:** You can update your profile information, including name, email, avatar, and location at any time
- **Deletion:** You can request deletion of your account and associated data through the account deletion process
- **Notification Preferences:** You can opt-out of non-essential communications and customize notification preferences in your account settings
- **Location:** You can choose whether to provide location data, though it may limit certain features
- **Push Notifications:** You can manage push notification permissions through your device settings

## Data Retention

- **Account Data:** Retained while your account is active. Deleted upon account deletion request.
- **Images:** Retained until you delete them or close your account. Images are permanently deleted from Cloudinary upon account deletion.
- **Location Data:** Retained while associated with an active account or pet listing. Deleted when account is deleted or pet listing is removed.
- **Messages:** Retained while conversations are active. Deleted when both participants leave the conversation or accounts are deleted.
- **Push Tokens:** Retained while your account is active. Deleted upon account deletion.
- **Support Requests:** Retained for customer service and legal purposes
- **Reports and Blocks:** Retained for safety and moderation purposes

## Children's Privacy

Our app is not intended for children under 13. We do not knowingly collect personal information from children under 13. If we become aware that we have collected personal information from a child under 13, we will take steps to delete such information.

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify users of any material changes through in-app notifications or email. The "Effective Date" at the top of this policy indicates when it was last updated.

## International Users

This app is hosted in the United States. By using our service, you consent to the transfer of your information to the United States. Data processing and storage occur in the United States.

## Contact Us

If you have questions about this Privacy Policy, wish to exercise your rights, or have concerns about your data, please contact us at:

- **Email:** rishabh.z3im@gmail.com
- **GitHub:** rastogi-rishabh

## Cookie and Tracking Policy

- We use secure tokens (JWT) for authentication, which are stored securely on your device
- We do not use tracking cookies or third-party analytics cookies
- We use Expo push tokens for notification delivery only
