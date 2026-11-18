<h1 align="center">Mohamed Hedi Abdessalem</h1>

<p align="center"><strong>Full-stack software engineer</strong><br>
Mobile engineering · Payments · Trust &amp; safety · Cloud tooling</p>

<p align="center">
  <a href="#contribution-history">Contribution history</a> &nbsp;·&nbsp;
  <a href="#what-ive-built">What I’ve built</a> &nbsp;·&nbsp;
  <a href="#toolkit">Toolkit</a>
</p>

---

I build features from the mobile interface through the API and database. My work includes Stripe payment flows, AI-assisted moderation, real-time messaging, event ticketing, and visual tools for cloud architecture.

## Contribution history

![4,868 authored commits across four codebases. 1,261 in 2025 and 3,607 in 2026 through November 18. The line chart shows the running total by month.](./contribution-history.svg)

Each distinct commit I authored counts once, including commits on non-default branches. The total excludes merge commits and reflects the four codebases reviewed through November 18, 2026.

## What I’ve built

### <img src="./accomplishments/payments.svg" width="24" height="24" alt="" /> &nbsp; Payments, e-wallets & billing

- **Stripe payments** · Integrated Stripe PaymentSheet, webhooks, and Stripe Connect for payment confirmation, tips, transfers, organizer payouts, and refunds.
- **E-wallets** · Built e-wallet workflows for balances, transaction history, linked bank accounts, IBAN/BIC details, verification documents, and held event funds. Connected mobile payment screens to backend billing and account status.
- **Subscriptions & billing** · Implemented subscription tiers, usage limits, renewal discounts and plan changes, cancellation flows, and referral rewards. Worked on billing profiles, tax and commission data, and PDF and CSV records for subscriptions, tips, events, and referrals.

### <img src="./accomplishments/moderation.svg" width="24" height="24" alt="" /> &nbsp; AI moderation, verification & privacy

- **NSFW detection** · Built NSFW detection and moderation workflows for avatars, banners, galleries, posts, and chat uploads. Adapted an NSFWJS classifier with TensorFlow.js and Sharp, integrated Claude for text and media checks, and worked with Amazon Rekognition, Google Cloud Vision, and Sightengine for image and face validation.
- **Face verification & safety** · Implemented selfie and face checks, duplicate-face detection, blocked-media feedback, and safeguards for unsafe links, spam, and restricted contact details. Connected moderation outcomes to mobile upload and editing flows.
- **Account security & consent** · Built account onboarding and recovery, Infobip SMS verification flows, JWT session refresh, private gallery permissions, and Android screenshot protection. Connected the Laravel admin dashboard to the API and mobile app for real-time terms updates, versioned consent, and acceptance records.

### <img src="./accomplishments/messaging.svg" width="24" height="24" alt="" /> &nbsp; Real-time messaging & social features

- **Live chat** · Built direct and group messaging with GraphQL subscriptions, presence, typing indicators, read receipts, and Firebase Cloud Messaging push notifications. Made offline retries idempotent and improved inbox and media loading with batched MongoDB reads and indexed cursor pagination.
- **Chat media** · Built chat media capture, voice playback, link previews, and attachment sharing. Tracked upload progress across the app and API and normalized mobile recordings to seekable MP4 with FFmpeg.
- **Social feeds & profiles** · Developed personal and professional profiles, public and private galleries, and social feeds with posts, comments, reactions, polls, sharing, and classifieds. Implemented visibility rules and relationship-aware access across feeds and conversations.

### <img src="./accomplishments/events.svg" width="24" height="24" alt="" /> &nbsp; Events, discovery & mobile delivery

- **Event operations** · Built event discovery, invitations, ticketing and QR check-in, participant management, cancellation and refund flows, and post-event testimonials. Implemented organizer and moderator permissions and configurable release of private venue details.
- **Location-based discovery** · Developed proximity-ranked search, saved filters, and location autocomplete for profiles, professional listings, and events. Worked on opt-in native location scheduling, permissions, and deep links.
- **Mobile release delivery** · Maintained React Native features for Android and iOS, contributed native Kotlin and Objective-C code, and wired GitHub Actions and Gradle to build APKs and publish artifacts through a Laravel release API.

### <img src="./accomplishments/cloud.svg" width="24" height="24" alt="" /> &nbsp; Cloud storage, architecture & developer tooling

- **Media storage** · Built Amazon S3 storage flows for profile photos, galleries, post media, and chat attachments. Implemented background processing, thumbnail generation, and upload rollback, and added validation for CloudFront-hosted media.
- **Cloud architecture canvas** · Built an interactive architecture canvas with a searchable multi-cloud resource catalog, project-scoped designs, and an AWS SAM YAML preview. Added sample infrastructure inventory, alert history, and guided DevOps troubleshooting scenarios.
- **Authenticated workspaces** · Built a NestJS and PostgreSQL workspace with organization roles, project and environment records, persisted designs, and same-origin sign-in. Prototyped server registration, TCP reachability checks, and read-only Linux inspection over SSH with encrypted credentials and host-key verification.
- **Testing & CI** · Added unit, integration, API, load, and browser tests. Automated build and verification steps with GitHub Actions, including dependency audit checks.

## Toolkit

### Mobile

![React Native, Kotlin, Android, iOS](./toolkit/mobile.svg)

React Navigation · Jotai · Objective-C · Gradle · i18next

### Web & UI

![React, Next.js, Tailwind CSS, Framer Motion](./toolkit/web.svg)

Zustand · React Flow · Monaco Editor

### Backend & data

![TypeScript, NestJS, GraphQL, PostgreSQL](./toolkit/backend.svg)

JavaScript · Node.js · PHP · Laravel · REST · Apollo · WebSockets · MongoDB · Mongoose · Drizzle ORM

### AWS & cloud services

![Amazon S3, Amazon CloudFront, Firebase, Google Maps](./toolkit/cloud.svg)

AWS SDK · AWS SAM · Amazon Rekognition · Firebase Cloud Messaging · Google Places

### Payments & integrations

![Stripe, Stripe Connect, FFmpeg, Sharp](./toolkit/payments.svg)

Stripe PaymentSheet · Infobip

### AI & computer vision

![Anthropic Claude, Amazon Rekognition, Google Cloud Vision, TensorFlow.js](./toolkit/ai.svg)

Sightengine · NSFWJS

### Delivery & testing

![GitHub Actions, Docker, Vitest, Jest](./toolkit/delivery.svg)

Docker Compose · Linux · SSH · Playwright · Postman/Newman · Artillery
