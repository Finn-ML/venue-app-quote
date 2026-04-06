# Development Agreement

**NYC Venue Discovery App — MVP**

---

**Developer:** Finn Howard, Grow Smart AI (growsmartai.co.uk)
**Client:** Jacob Zachary-Laskaris
**Date:** March 2026

---

## 1. Scope of Work

Development of a mobile application (iOS & Android) for discovering, reviewing, and saving venues in New York City.

### Included Features

| # | Feature | Description |
|---|---------|-------------|
| 1 | Interactive NYC Map | Venue markers, user location, map navigation |
| 2 | Search & Discovery | Search bar, filters, venue results with photos |
| 3 | Venue Pages | Full venue info, photos, hours, Google ratings at launch |
| 4 | Auth & Accounts | Sign up, login, SMS verification, password reset |
| 5 | User Profiles & Follows | Profile page, avatar, bio, follow/unfollow, follower & following counts |
| 6 | Reviews & Tags | Numerical score, optional label tagging, bookmark as alternative to review |
| 7 | Custom Lists | Create, save, and manage personal venue lists |
| 8 | Notification Bell | Activity notifications from follows and reviews |
| 9 | Push Notifications | Real-time native push alerts for activity and updates |
| 10 | Core Infrastructure | Database (Supabase), hosting, object storage, API layer |
| 11 | App Store Deployment | Full iOS & Android setup, submission, and approval |
| 12 | Admin Dashboard | In-app content moderation, user management, analytics overview |

---

## Appendix: Feature Detail

### 1. Interactive Map
- Full-screen map centred on NYC
- Venue markers with category indicators
- User's live location indicator
- Tap marker → opens venue detail sheet
- Smooth pan, zoom, and map navigation

### 2. Search & Discovery
- Search bar with real-time filtering
- Search results displayed as a scrollable list with venue photos
- Tap result → navigates to venue on map or opens venue page
- Filter by category/tags (e.g. bars, clubs, rooftops, late-night)

### 3. Venue Pages
- Full venue detail view (bottom sheet or full page)
- Venue name, address, category, photos
- Opening hours, phone number, website
- Google ratings pulled at launch (transitioned to in-app ratings over time)
- Venue tags (e.g. "great cocktails", "rooftop", "live music")
- Save to list / bookmark action
- Write a review action

### 4. User Authentication & Accounts
- Sign up with phone number + password
- Login / logout
- SMS verification
- Password reset flow
- Session management and secure token handling

### 5. User Profiles & Social
- Profile page: avatar, display name, bio
- View own reviews, saved lists, followers/following
- Follow / unfollow other users
- Follower and following counts
- View other users' profiles and their public reviews

### 6. Reviews & Ratings
- Numerical score (e.g. 1–5 or 1–10)
- Optional label/tag selection per review (e.g. "vibes", "music", "drinks")
- Bookmark as a lightweight alternative to a full review
- Reviews visible on venue pages
- User's review history visible on their profile

### 7. Custom Lists
- Create named lists (e.g. "Friday Night Spots", "Date Night")
- Save any venue to one or more lists
- View and manage lists from profile
- Remove venues from lists

### 8. Notifications
- In-app notification bell with activity feed
- Notifications for: new followers, reviews on saved venues, follows
- Native push notifications (iOS + Android)
- Real-time delivery via Supabase Realtime or push service

### 9. Core Infrastructure
- Database: Supabase (PostgreSQL) — user data, reviews, lists, follows
- Auth: Supabase Auth with SMS provider
- Storage: Supabase Object Storage for user avatars and uploaded images
- API Layer: Supabase Edge Functions / REST API
- Venue Data: Google Places API (cached aggressively to minimise cost)
- SMS: Twilio for verification and password reset

### 10. Admin Dashboard
- In-app admin panel accessible to authorised admin accounts
- Content moderation: approve/deny/remove venues and reviews
- User management: view users, suspend accounts, manage reports
- Analytics overview: total users, reviews, venues, activity trends

### 11. App Store Deployment
- Full iOS build, App Store submission, and approval process
- Full Android build, Google Play submission, and approval process
- Developer will assist with Apple Developer and Google Play account setup

---

### Not Included (Phase 2+)
- Full scrollable activity feed
- Real-time friends map
- Check-in system
- AI / algorithmic recommendations
- Venue owner profiles

---

## 2. Timeline

**Estimated duration:** 8–10 weeks from design kick-off.

| Phase | Duration | Description |
|-------|----------|-------------|
| Design | ~2 weeks | UI/UX design, mockup review, design sign-off |
| Build | ~4–5 weeks | Core development, feature implementation |
| QA & Testing | ~1–2 weeks | Bug testing, quality assurance, user testing |
| Launch | ~1 week | App store submission, deployment, go-live |

---

## 3. Payment

**Total project cost: $13,400 USD**

| Phase | % | Amount | Trigger |
|-------|---|--------|---------|
| Design Phase | 25% | $3,350 | On signing this agreement |
| Build Phase | 25% | $3,350 | Design sign-off |
| Delivery & Launch | 25% | $3,350 | QA complete + app live |
| Final Payment | 25% | $3,350 | After 2-week post-launch support period |

Payment via bank transfer. Invoice provided for each phase.

---

## 4. Post-Launch Support

- **2 weeks** of post-launch bug fixing and support included at no extra cost.
- Any issues that fall within the agreed MVP scope will be resolved at no charge.
- After the 2-week period, additional work is available via hourly support packs at a rate to be agreed.

---

## 5. What the Client Provides

- Mockups / design references and feedback during design phase
- App Store & Google Play developer accounts (Developer will assist with setup)
- Timely feedback and sign-off at each phase to maintain timeline
- Venue data or confirmation of data source approach (e.g. Google Places API)

---

## 6. Ownership & IP

- Upon full payment, all custom code and assets developed for this project are owned by the Client.
- Third-party libraries and services remain under their respective licenses.
- Developer retains the right to reference the project in their portfolio.

---

## 7. Third-Party Running Costs

The following ongoing costs are the Client's responsibility after launch. Estimated monthly costs are provided in a separate document.

- Hosting & database (Supabase)
- Google Places API (venue data)
- SMS verification service (e.g. Twilio)
- App store developer fees (Apple $99/yr, Google $25 one-time)

---

## 8. Confidentiality

Both parties agree to keep project details, business plans, and proprietary information confidential.

---

## 9. Agreement

By signing below, both parties agree to the terms outlined in this document. This agreement becomes effective on the date of the last signature.

| | Name | Date | Signature |
|---|------|------|-----------|
| **Developer** | Finn Howard | | |
| **Client** | Jacob Zachary-Laskaris | | |

---

*Grow Smart AI — growsmartai.co.uk*
