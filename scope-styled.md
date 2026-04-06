---
pdf_options:
  format: A4
  margin: 30mm 25mm
  printBackground: true
stylesheet: |
  body { font-family: 'Helvetica Neue', Arial, sans-serif; color: #1a1a1a; line-height: 1.6; font-size: 14px; }
  h1 { font-size: 24px; border-bottom: 2px solid #1a1a1a; padding-bottom: 8px; margin-top: 0; }
  h2 { font-size: 18px; color: #333; margin-top: 28px; }
  h3 { font-size: 15px; color: #555; }
  table { border-collapse: collapse; width: 100%; margin: 12px 0; font-size: 13px; }
  th, td { border: 1px solid #ddd; padding: 8px 10px; text-align: left; }
  th { background: #f5f5f5; font-weight: 600; }
  code { background: #f0f0f0; padding: 2px 5px; border-radius: 3px; font-size: 13px; }
  hr { border: none; border-top: 1px solid #ddd; margin: 20px 0; }
  strong { color: #111; }
  em { color: #666; }
---
# Project Scope — NYC Venue Discovery App (MVP)

**Client:** Jacob Zachary-Laskaris
**Developer:** Finn Howard, Grow Smart AI
**Version:** 1.0 — March 2026

---

## Overview

A mobile app (iOS & Android) for discovering, reviewing, and saving nightlife venues in New York City. Built with React Native (Expo) and Supabase.

---

## What's Included

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
- Sign up with email + password
- Login / logout
- Email verification
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
- **Database:** Supabase (PostgreSQL) — user data, reviews, lists, follows
- **Auth:** Supabase Auth with email provider
- **Storage:** Supabase Object Storage for user avatars and uploaded images
- **API Layer:** Supabase Edge Functions / REST API
- **Venue Data:** Google Places API (cached aggressively to minimise cost)
- **Email:** Transactional email service (Resend) for verification and password reset

### 10. App Store Deployment
- Full iOS build, App Store submission, and approval process
- Full Android build, Google Play submission, and approval process
- App icons, splash screens, and store listing assets
- Developer will assist with Apple Developer and Google Play account setup

---

## What's NOT Included (Phase 2+)

These features are scoped for future development and are not part of this MVP:

| Feature | Description |
|---------|-------------|
| Activity Feed | Full scrollable feed of friends' activity |
| Real-time Friends Map | See friends' locations live on the map |
| Check-in System | Check in at venues with notifications to friends |
| Admin Dashboard | Backend admin panel for content/user management |
| AI Recommendations | Algorithmic venue suggestions based on behaviour |
| Venue Owner Profiles | Paid venue accounts with profile control |
| Auto Check-in | Location-based automatic check-in detection |
| In-app Messaging | Direct messaging between users |
| Monetisation Layer | Payment processing, premium features |

These can be quoted separately when ready for Phase 2.

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React Native (Expo) — single codebase for iOS + Android |
| Backend | Supabase (PostgreSQL, Auth, Storage, Realtime, Edge Functions) |
| Maps | React Native Maps + Google Places API |
| Email | Resend (transactional) |
| Push Notifications | Expo Push / Firebase Cloud Messaging |
| Deployment | EAS Build (Expo Application Services) |

---

## Timeline

| Phase | Duration | What Happens |
|-------|----------|-------------|
| Design | ~2 weeks | UI/UX design, wireframes, mockup review, design sign-off |
| Build | ~4–5 weeks | Core feature development, API integration, testing during build |
| QA & Testing | ~1–2 weeks | Bug fixing, device testing, performance review |
| Launch | ~1 week | App store submissions, deployment, go-live |

**Total: 8–10 weeks from kick-off**

---

## Payment

| Phase | % | Amount | Trigger |
|-------|---|--------|---------|
| Design | 25% | $3,350 | On signing agreement |
| Build | 25% | $3,350 | Design sign-off |
| Delivery & Launch | 50% | $6,700 | QA complete + app live |

**Total: $13,400 USD**

---

## Post-Launch

- 2 weeks of bug fixing and support included at no extra cost
- Covers any issues within the agreed MVP scope
- After 2-week period, additional work available at an agreed hourly rate

---

## Running Costs (Client's Responsibility)

| Phase | Est. Monthly Cost |
|-------|-------------------|
| Development | $0 |
| Early launch (0–500 users) | $0–70 |
| Growth (500–5,000 users) | $95–265 |

Full running costs breakdown provided in a separate document.

---

*Grow Smart AI — growsmartai.co.uk*
