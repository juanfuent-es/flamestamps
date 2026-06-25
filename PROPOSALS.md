# Flame Stamps — Proposal Structure

## Overview

Flame Stamps is a mobile-first digital experience for Flame Tree Season. The project allows visitors to capture images, apply branded visual treatments, generate a downloadable stamp, and optionally contribute their creation to a collective campaign archive or public installation.

The proposal is divided into three possible development scopes:

1. **Core**
2. **Collective Gallery**
3. **Tree Installation**

Each scope can work as an independent delivery phase or as part of a progressive production roadmap.

---

# Proposal 1 — Core

## Title

**Core Campaign Platform**

## Proposal

A mobile-first web experience where users can capture or upload a photo, apply the Flame Tree Season visual system, select a shape and color treatment, generate a branded stamp, save it to their personal album, and download or share the final image.

This version focuses on creating a polished individual experience with enough backend structure to make the project useful for both users and the campaign team.

## Description

The Core version turns the visual prototype into a functional campaign platform. Users enter through a landing page, create their own Flame Stamp, and receive a downloadable image designed for social sharing, stories, wallpapers, or personal keepsakes.

The backend allows each stamp to become more than a visual output: it becomes a measurable participation record. This makes the experience useful for the brand, not only for the user.

## Includes

### User Experience

* Landing page / intro screen
* Mobile-first experience
* Desktop fallback with QR code to continue on mobile
* Camera capture or image upload
* Selection of branded shapes
* Selection of visual filters
* Selection of color treatments
* Stamp generation
* Personal album
* Downloadable image
* Native share support where available
* Optional QR, campaign URL or hashtag embedded in the exported image
* Basic interface animations for mobile

### Backend

* User/session structure
* Database for users, stamps and metadata
* Image storage
* Stamp records associated with user/session ID
* Basic admin dashboard
* Ability to delete images or user data if necessary
* Basic campaign data structure

### Campaign Data

* Total stamps created
* Total downloads
* Selected shapes
* Selected filters
* Selected colors
* Date/time of creation
* Device/session metadata
* Optional email/contact capture if required by campaign

## Technical Differentiators

* The stamp is not only a downloaded image; it is stored as campaign participation data.
* Each visual output can be associated with metadata such as shape, color, filter and timestamp.
* The backend allows the campaign team to review participation beyond basic analytics.
* The experience can support future extensions such as public galleries, moderation or installation feeds.
* The exported image can function as a campaign object: story, wallpaper, share card or QR-based invitation.

## Limits

This version does not include:

* Public collective gallery
* Public tree visualization
* Advanced moderation pipeline
* AI-based content review
* Responsive installation mode
* WebGL tree or particle system
* Multi-screen installation support
* Venue hardware setup
* On-site technical operation

## Estimated Development Time

**4 to 5 weeks**

Suggested breakdown:

* Week 1: Technical setup, UX mapping, visual system integration
* Week 2: Mobile interaction, camera/upload, filter and stamp generation
* Week 3: Backend, database, storage, user/session logic
* Week 4: Admin basics, album, export/share, QA
* Week 5: Buffer, polish, bug fixing and deployment

---

# Proposal 2 — Collective Gallery

## Title

**Collective Gallery + Moderation System**

## Proposal

An extended campaign platform where users can submit their stamps to a shared gallery. The campaign team can review, approve, reject and curate public submissions through an admin dashboard.

This version transforms individual participation into a collective visual archive for Flame Tree Season.

## Description

The Collective Gallery adds a public and curatorial layer to the Core experience. Users can decide whether their stamp becomes part of a shared campaign collection. Approved submissions can be displayed on a public gallery, used in campaign communications or prepared for a later installation.

This version introduces moderation, consent and content governance, making it suitable for public-facing participation.

## Includes

### Everything in Core

* Mobile stamp experience
* Backend
* Image storage
* User/session structure
* Personal album
* Admin dashboard
* Download/share/export

### Collective Participation

* “Submit to Gallery” flow
* Consent for public display
* Submission status: pending, approved, rejected
* Public/private stamp visibility
* Campaign gallery page
* Approved stamp feed
* Gallery filtering by shape, color, filter or date
* Basic gallery layout using the campaign visual system

### Moderation

* Admin review queue
* Approve submission
* Reject submission
* Delete submission
* Remove user data if necessary
* Basic flagging system
* Basic ban/block logic by user/session if needed

### Campaign Utility

* Curated archive of user-generated content
* Exportable list of approved stamps
* Exportable participation data
* Internal campaign dashboard
* Foundation for future installation or tree visualization

## Technical Differentiators

* User submissions are not published automatically.
* Public content passes through a moderation layer.
* The gallery creates a reusable campaign archive.
* Approved content can feed future visualizations, installations or social media campaigns.
* The system separates personal albums, internal archive and public-facing content.
* Consent is handled as part of the publication flow.

## Limits

This version does not include:

* Final tree installation
* Advanced WebGL visualization
* Particle animation system
* Full responsive installation mode
* Venue display setup
* Hardware procurement
* On-site support
* Advanced AI moderation unless added separately
* Full CRM integration unless added separately

## Estimated Development Time

**6 to 8 weeks**

Suggested breakdown:

* Week 1: Scope definition, technical architecture, visual system integration
* Week 2: Core stamp experience
* Week 3: Backend, storage, users/sessions, album
* Week 4: Submission flow, consent, metadata
* Week 5: Moderation dashboard and admin tools
* Week 6: Public gallery and approved content feed
* Week 7: QA, performance, device testing
* Week 8: Buffer, polish, deployment and handoff

---

# Proposal 3 — Tree Installation

## Title

**Living Tree Installation**

## Proposal

A public-facing installation where approved user stamps become part of a collective digital tree. The tree can be displayed on a dedicated screen, projection or venue display and updated with curated submissions from the campaign platform.

This version turns the campaign into a live participatory artwork.

## Description

The Tree Installation builds on the Core and Collective Gallery systems. Users create stamps on their phones, submit them to the campaign, and approved stamps are transformed into visual elements within a growing digital tree.

The installation can be designed as a full-screen browser experience for a specific display, venue or resolution. A more advanced version may include WebGL, particles, generative motion, responsive display modes and real-time or scheduled updates.

## Includes

### Everything in Core

* Mobile stamp creation
* Backend
* Image storage
* User/session logic
* Download/share
* Personal album
* Admin tools

### Everything in Collective Gallery

* Public submission
* Consent flow
* Moderation
* Approved gallery
* Public feed
* Curated campaign archive

### Installation Layer

* Collective tree visual system
* Approved stamp feed integration
* Display mode for one target screen/resolution
* Basic animation system
* Tree composition using approved stamps
* Periodic content refresh
* Fallback screen if no content is available
* Technical handoff documentation for display operation

### Optional Advanced Layer

* WebGL rendering
* Particle system
* Generative growth behavior
* Responsive installation layouts
* Multi-resolution support
* Idle/active display states
* Live campaign counter
* Location-based grouping
* Color/luminance-based composition
* More polished motion design

## Technical Differentiators

* The installation is powered by real user participation.
* Approved stamps become visual components in a collective artwork.
* The backend feed allows the installation to stay separate from the mobile experience.
* Moderation protects the public display from unsafe or unwanted content.
* The visual system can use metadata such as color, shape, date or source location to organize the tree.
* The installation can evolve over time as more people participate.

## Limits

This version does not automatically include:

* Hardware purchase
* Screens, projectors or media players
* Venue internet setup
* On-site technician
* Travel
* Legal review
* Official translation review
* Cloud service costs
* Long-term campaign operation
* Multiple venue deployments unless scoped separately

## Estimated Development Time

**8 to 10 weeks**

Suggested breakdown:

* Week 1: Technical planning, installation concept, display constraints
* Week 2: Core stamp experience
* Week 3: Backend, storage, users/sessions, album
* Week 4: Submission, consent and metadata
* Week 5: Moderation dashboard and approved feed
* Week 6: Collective gallery and installation data structure
* Week 7: Tree visualization prototype
* Week 8: Display mode, animation, integration and QA
* Week 9: Performance testing, visual polish, fallback states
* Week 10: Buffer, deployment, documentation and handoff

---

# Recommended Roadmap

## Phase 1 — Core

Deliver a polished, functional campaign experience that allows users to create, save and share Flame Stamps.

## Phase 2 — Collective Gallery

Extend the platform into a moderated public archive of user-generated stamps.

## Phase 3 — Tree Installation

Transform the approved gallery into a public digital tree or installation.

---

# Key Strategic Difference Between Proposals

## Core

The user creates a personal stamp.

## Collective Gallery

The campaign collects, moderates and curates stamps from many users.

## Tree Installation

The curated stamps become a public participatory artwork.

---

# Important Production Notes

* The current prototype should be treated as a visual and conceptual reference, not as the final production platform.
* A production build requires clear definition of data, consent, moderation and deployment responsibilities.
* If user images are stored, the project should include privacy copy, consent flows and a deletion mechanism.
* If images are displayed publicly, moderation should be included before publication.
* If the installation is physical, venue, hardware and support responsibilities should be defined separately.
* Instagram or social media sharing should be handled through native sharing, downloadable images, campaign URLs and hashtags rather than depending on social media API integrations.
* The backend is a key value layer: it turns each stamp into both a user-facing image and a measurable campaign participation record.
