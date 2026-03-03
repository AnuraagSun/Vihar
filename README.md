# 🕉️ VIHAR - Complete Project Blueprint

## Brand Foundation

```
Name:        VIHAR (विहार)
Meaning:     Journey / Exploration / Monastery
Philosophy:  Rooted in Sanatan Dharma aesthetics
Audience:    Domestic tourists (India-first)
Launch:      Telangana (5 temples)
Budget:      $0 - Fully Open Source
```

---

## 1. BRAND GUIDELINES (Let me explain & define)

Brand guidelines are rules that keep your website looking and feeling consistent everywhere. Here's yours:

### Color Palette (Sanatan Dharma Inspired)

```
┌─────────────────────────────────────────────────────┐
│  COLOR          │  HEX       │  SYMBOLISM           │
├─────────────────────────────────────────────────────┤
│  Kesari/Saffron │  #FF6B00   │  Spirituality, Agni  │
│  Deep Maroon    │  #8B1A1A   │  Kumkum, Temples     │
│  Gold           │  #D4A017   │  Divinity, Prosperity│
│  Sandalwood     │  #F4E4C1   │  Purity, Background  │
│  Temple Stone   │  #4A3728   │  Heritage, Earth     │
│  Sacred Green   │  #2D5016   │  Nature, Wildlife    │
│  Deep Blue      │  #1A237E   │  Krishna, Depth      │
│  Ivory White    │  #FFF8F0   │  Shankh, Peace       │
└─────────────────────────────────────────────────────┘

Primary:    Kesari (#FF6B00) + Deep Maroon (#8B1A1A)
Secondary:  Gold (#D4A017) + Temple Stone (#4A3728)
Background: Sandalwood (#F4E4C1) / Ivory (#FFF8F0)
Accent:     Sacred Green (#2D5016) for verified badges
```

### Typography

```
Headings:    "Yatra One" (Google Font - Devanagari inspired)
Body:        "Poppins" (Clean, modern, multi-language support)
Accent:      "Tiro Devanagari Sanskrit" (For slokas/quotes)
```

### Design Motifs

```
- Mandala patterns as subtle backgrounds
- Temple gopuram silhouettes in headers
- Lotus border elements
- Rangoli-inspired dividers
- Om / Swastika / Trishul as subtle icons
- Diya (lamp) as loading animation
```

### Brand Voice

```
Tone:        Respectful, informative, warm, culturally proud
Language:    Simple English + local terms with explanations
Example:     "Welcome to Yadadri 🙏 — Where Lord Lakshmi 
             Narasimha resides atop the sacred hills of 
             Yadagirigutta"
```

---

## 2. TECH STACK (100% Free & Open Source)

```
┌──────────────────────────────────────────────────────────┐
│  LAYER              │  TECHNOLOGY        │  COST         │
├──────────────────────────────────────────────────────────┤
│  Frontend           │  Next.js 14 (React)│  FREE         │
│  Styling            │  Tailwind CSS      │  FREE         │
│  Backend / API      │  Next.js API Routes│  FREE         │
│  Database           │  PostgreSQL(Supabase)│ FREE (500MB)│
│  Authentication     │  Supabase Auth     │  FREE         │
│  File Storage       │  Supabase Storage  │  FREE (1GB)   │
│  Maps               │  Leaflet + OSM     │  FREE         │
│  Search             │  Meilisearch       │  FREE (self)  │
│  Hosting            │  Vercel            │  FREE         │
│  i18n (Languages)   │  next-intl         │  FREE         │
│  CMS (Content)      │  Markdown/MDX      │  FREE         │
│  Image Optimization │  Next/Image+Cloudinary│FREE(25GB)  │
│  Analytics          │  Umami (self-host) │  FREE         │
│  Version Control    │  GitHub            │  FREE         │
│  CI/CD              │  GitHub Actions    │  FREE         │
│  Offline Support    │  PWA + Service Worker│ FREE        │
│  State Management   │  Zustand           │  FREE         │
│  Email              │  Resend            │  FREE(100/day)│
├──────────────────────────────────────────────────────────┤
│  TOTAL MONTHLY COST                      │  ₹0           │
└──────────────────────────────────────────────────────────┘
```

---

## 3. COMPLETE SITEMAP

```
vihar.in/
│
├── / (Landing Page)
│   ├── Hero with temple video/image
│   ├── Search bar (prominent)
│   ├── "Discover" CTA → Map
│   ├── Featured temples
│   ├── Editor's photo picks
│   └── Festival calendar preview
│
├── /discover (Interactive Map)
│   ├── India political map (clickable states)
│   ├── State info cards on hover
│   └── Temple count per state
│
├── /discover/telangana (State Page - unique theme)
│   ├── Telangana district map (clickable)
│   ├── State-specific banner & colors
│   ├── Cultural intro
│   └── District-wise temple count
│
├── /discover/telangana/[district] (District Page)
│   ├── List of all temples
│   ├── Filter & sort options
│   └── Map view toggle
│
├── /temple/[slug] (Temple Detail Page) ⭐ CORE
│   ├── Hero gallery (editor picks with badge)
│   ├── Tabs: History | Geography | Wildlife
│   ├── Roadmap (interactive visit guide)
│   ├── Photo gallery (user uploaded)
│   ├── Best time to visit
│   ├── Festival calendar
│   ├── Do's and Don'ts
│   ├── Local food guide
│   ├── Nearby attractions
│   ├── Safety rating
│   ├── Verified hotels
│   ├── Verified tour guides
│   ├── Ticket information
│   ├── How to reach
│   ├── Offline download button
│   ├── Reviews & ratings
│   └── Share buttons
│
├── /hotels (Hotel Listings)
│   ├── Near specific temple
│   ├── Verified badge
│   └── Booking link (future: integrated)
│
├── /guides (Tour Guide Directory)
│   ├── Profile cards
│   ├── Certification badges
│   ├── Ratings & reviews
│   ├── Languages spoken
│   └── Contact / Book
│
├── /gallery (Community Photo Gallery)
│   ├── All temples combined
│   ├── Filter by temple/state
│   ├── Editor picks section
│   └── Upload CTA
│
├── /search?q=... (Search Results)
│
├── /auth/login
├── /auth/register
├── /auth/verify
│
├── /profile/[userId]
│   ├── My uploads
│   ├── My reviews
│   ├── Saved temples
│   └── Settings
│
├── /admin (Admin Dashboard)
│   ├── /admin/temples (CRUD)
│   ├── /admin/photos (Approve/Reject/Feature)
│   ├── /admin/hotels (Verify)
│   ├── /admin/guides (Verify/Certify)
│   ├── /admin/users (Manage)
│   ├── /admin/tickets (Manage)
│   ├── /admin/reviews (Moderate)
│   └── /admin/analytics
│
├── /about
├── /contact
├── /contribute (Open source contribution guide)
└── /offline (Service worker cached pages)
```

---

## 4. DATABASE SCHEMA

```sql
-- ============================================
-- VIHAR DATABASE SCHEMA (PostgreSQL/Supabase)
-- ============================================

-- ENUMS
CREATE TYPE user_role AS ENUM (
  'tourist', 'photographer', 'guide', 
  'hotel_owner', 'editor', 'temple_admin', 'super_admin'
);

CREATE TYPE verification_status AS ENUM (
  'pending', 'verified', 'rejected'
);

CREATE TYPE safety_level AS ENUM (
  'very_safe', 'safe', 'moderate', 'caution'
);

-- ============================================
-- USERS & AUTH
-- ============================================

CREATE TABLE users (
  id              UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  email           VARCHAR(255) UNIQUE,
  phone           VARCHAR(15) UNIQUE,
  full_name       VARCHAR(100) NOT NULL,
  avatar_url      TEXT,
  role            user_role DEFAULT 'tourist',
  preferred_lang  VARCHAR(10) DEFAULT 'en',
  is_verified     BOOLEAN DEFAULT FALSE,
  bio             TEXT,
  location        VARCHAR(100),
  created_at      TIMESTAMPTZ DEFAULT NOW(),
  updated_at      TIMESTAMPTZ DEFAULT NOW()
);

-- ============================================
-- GEOGRAPHY HIERARCHY
-- ============================================

CREATE TABLE states (
  id              SERIAL PRIMARY KEY,
  name            VARCHAR(100) NOT NULL,
  name_local      VARCHAR(100),         -- తెలంగాణ
  slug            VARCHAR(100) UNIQUE NOT NULL,
  map_svg_path    TEXT,                  -- SVG path data for map
  theme_config    JSONB,                 -- unique colors/fonts per state
  description     TEXT,
  capital         VARCHAR(100),
  languages       TEXT[],
  image_url       TEXT,
  created_at      TIMESTAMPTZ DEFAULT NOW()
);

CREATE TABLE districts (
  id              SERIAL PRIMARY KEY,
  state_id        INT REFERENCES states(id) ON DELETE CASCADE,
  name            VARCHAR(100) NOT NULL,
  name_local      VARCHAR(100),
  slug            VARCHAR(100) NOT NULL,
  map_svg_path    TEXT,
  description     TEXT,
  image_url       TEXT,
  UNIQUE(state_id, slug)
);

-- ============================================
-- TEMPLES / PLACES (CORE ENTITY)
-- ============================================

CREATE TABLE temples (
  id              UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  district_id     INT REFERENCES districts(id),
  
  -- Basic Info
  name            VARCHAR(200) NOT NULL,
  name_local      VARCHAR(200),
  slug            VARCHAR(200) UNIQUE NOT NULL,
  deity           VARCHAR(200),
  denomination    VARCHAR(100),          -- Shaiva, Vaishnava, Shakta
  significance    TEXT,
  
  -- Detailed Content (stored as rich markdown)
  history         TEXT,
  geography       TEXT,
  wildlife        TEXT,
  architecture    TEXT,
  mythology       TEXT,
  
  -- Location
  latitude        DECIMAL(10, 8),
  longitude       DECIMAL(11, 8),
  address         TEXT,
  pincode         VARCHAR(10),
  
  -- Visit Information
  opening_time    TIME,
  closing_time    TIME,
  best_months     INT[],                -- [10,11,12,1,2]
  avg_visit_hours DECIMAL(3,1),
  dress_code      TEXT,
  
  -- Ratings
  safety_rating   safety_level DEFAULT 'safe',
  avg_user_rating DECIMAL(2,1) DEFAULT 0,
  total_reviews   INT DEFAULT 0,
  
  -- Status
  is_published    BOOLEAN DEFAULT FALSE,
  is_featured     BOOLEAN DEFAULT FALSE,
  
  -- Meta
  created_by      UUID REFERENCES users(id),
  created_at      TIMESTAMPTZ DEFAULT NOW(),
  updated_at      TIMESTAMPTZ DEFAULT NOW()
);

-- Full text search index
CREATE INDEX idx_temples_search ON temples 
  USING GIN(to_tsvector('english', name || ' ' || COALESCE(deity,'') || ' ' || COALESCE(significance,'')));

-- ============================================
-- TEMPLE ROADMAP (Visit Guide)
-- ============================================

CREATE TABLE temple_roadmap_stops (
  id              UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  temple_id       UUID REFERENCES temples(id) ON DELETE CASCADE,
  stop_number     INT NOT NULL,
  title           VARCHAR(200) NOT NULL,
  title_local     VARCHAR(200),
  description     TEXT,
  type            VARCHAR(50),           -- 'shrine','mandapam','tank','view_point'
  estimated_time  INT,                   -- minutes
  latitude        DECIMAL(10, 8),
  longitude       DECIMAL(11, 8),
  image_url       TEXT,
  is_must_visit   BOOLEAN DEFAULT TRUE,
  tips            TEXT,
  UNIQUE(temple_id, stop_number)
);

-- ============================================
-- DOS AND DONTS
-- ============================================

CREATE TABLE temple_guidelines (
  id              UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  temple_id       UUID REFERENCES temples(id) ON DELETE CASCADE,
  type            VARCHAR(5) CHECK (type IN ('do', 'dont')),
  guideline       TEXT NOT NULL,
  guideline_local TEXT,
  icon            VARCHAR(50),
  priority        INT DEFAULT 0
);

-- ============================================
-- PHOTOS
-- ============================================

CREATE TABLE photos (
  id              UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  temple_id       UUID REFERENCES temples(id) ON DELETE CASCADE,
  uploaded_by     UUID REFERENCES users(id),
  
  image_url       TEXT NOT NULL,
  thumbnail_url   TEXT,
  caption         VARCHAR(500),
  
  -- Moderation
  status          verification_status DEFAULT 'pending',
  is_editor_pick  BOOLEAN DEFAULT FALSE,   -- green badge
  reviewed_by     UUID REFERENCES users(id),
  reviewed_at     TIMESTAMPTZ,
  
  -- Metadata
  camera_info     VARCHAR(200),
  taken_at        DATE,
  
  created_at      TIMESTAMPTZ DEFAULT NOW()
);

CREATE INDEX idx_photos_temple ON photos(temple_id, status);

-- ============================================
-- FESTIVALS & EVENTS
-- ============================================

CREATE TABLE festivals (
  id              UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  temple_id       UUID REFERENCES temples(id) ON DELETE CASCADE,
  name            VARCHAR(200) NOT NULL,
  name_local      VARCHAR(200),
  description     TEXT,
  month           INT,                   -- 1-12
  start_date      DATE,                  -- specific date if known
  end_date        DATE,
  duration_days   INT DEFAULT 1,
  is_major        BOOLEAN DEFAULT FALSE,
  special_rituals TEXT,
  expected_crowd  VARCHAR(20),           -- 'low','medium','high','extreme'
  image_url       TEXT
);

-- ============================================
-- LOCAL FOOD
-- ============================================

CREATE TABLE local_foods (
  id              UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  temple_id       UUID REFERENCES temples(id) ON DELETE CASCADE,
  name            VARCHAR(200) NOT NULL,
  name_local      VARCHAR(200),
  description     TEXT,
  type            VARCHAR(20),           -- 'prasadam','street_food','restaurant'
  is_vegetarian   BOOLEAN DEFAULT TRUE,
  price_range     VARCHAR(20),           -- 'free','₹10-50','₹50-200'
  where_to_find   TEXT,
  image_url       TEXT
);

-- ============================================
-- NEARBY ATTRACTIONS
-- ============================================

CREATE TABLE nearby_attractions (
  id              UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  temple_id       UUID REFERENCES temples(id) ON DELETE CASCADE,
  linked_temple_id UUID REFERENCES temples(id),  -- if it's another temple
  name            VARCHAR(200) NOT NULL,
  type            VARCHAR(50),           -- 'temple','waterfall','fort','museum'
  distance_km     DECIMAL(5,1),
  travel_time     VARCHAR(50),           -- '30 mins by car'
  description     TEXT,
  latitude        DECIMAL(10, 8),
  longitude       DECIMAL(11, 8),
  image_url       TEXT
);

-- ============================================
-- TRANSPORT / HOW TO REACH
-- ============================================

CREATE TABLE transport_options (
  id              UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  temple_id       UUID REFERENCES temples(id) ON DELETE CASCADE,
  mode            VARCHAR(20),           -- 'air','rail','bus','car','auto'
  from_location   VARCHAR(200),          -- 'Hyderabad'
  description     TEXT,
  distance_km     DECIMAL(6,1),
  estimated_time  VARCHAR(50),
  estimated_cost  VARCHAR(50),
  frequency       VARCHAR(100),          -- 'Every 30 mins'
  tips            TEXT
);

-- ============================================
-- HOTELS
-- ============================================

CREATE TABLE hotels (
  id              UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  temple_id       UUID REFERENCES temples(id),
  
  name            VARCHAR(200) NOT NULL,
  slug            VARCHAR(200) UNIQUE,
  description     TEXT,
  address         TEXT,
  latitude        DECIMAL(10, 8),
  longitude       DECIMAL(11, 8),
  phone           VARCHAR(15),
  email           VARCHAR(255),
  website         TEXT,
  
  price_min       INT,                   -- per night in INR
  price_max       INT,
  amenities       TEXT[],               -- ['wifi','parking','ac','food']
  room_types      JSONB,
  
  distance_from_temple DECIMAL(4,1),    -- km
  
  -- Verification
  verification_status verification_status DEFAULT 'pending',
  verified_by     UUID REFERENCES users(id),
  verified_at     TIMESTAMPTZ,
  
  -- Ratings
  avg_rating      DECIMAL(2,1) DEFAULT 0,
  total_reviews   INT DEFAULT 0,
  
  images          TEXT[],
  is_active       BOOLEAN DEFAULT TRUE,
  
  owner_id        UUID REFERENCES users(id),
  created_at      TIMESTAMPTZ DEFAULT NOW()
);

-- ============================================
-- TOUR GUIDES
-- ============================================

CREATE TABLE tour_guides (
  id              UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  user_id         UUID REFERENCES users(id) UNIQUE,
  
  display_name    VARCHAR(100) NOT NULL,
  bio             TEXT,
  experience_years INT,
  languages       TEXT[],               -- ['Telugu','Hindi','English']
  specialization  TEXT[],               -- ['History','Architecture','Spiritual']
  
  -- Certification
  certification_board VARCHAR(200),
  certification_id    VARCHAR(100),
  certification_doc   TEXT,             -- uploaded document URL
  
  -- Verification
  verification_status verification_status DEFAULT 'pending',
  verified_by     UUID REFERENCES users(id),
  verified_at     TIMESTAMPTZ,
  
  -- Service Details
  temples_covered UUID[],              -- array of temple IDs
  price_per_hour  INT,
  price_per_day   INT,
  phone           VARCHAR(15),
  whatsapp        VARCHAR(15),
  
  -- Ratings
  avg_rating      DECIMAL(2,1) DEFAULT 0,
  total_reviews   INT DEFAULT 0,
  total_tours     INT DEFAULT 0,
  
  avatar_url      TEXT,
  is_available    BOOLEAN DEFAULT TRUE,
  created_at      TIMESTAMPTZ DEFAULT NOW()
);

-- ============================================
-- TICKETS
-- ============================================

CREATE TABLE tickets (
  id              UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  temple_id       UUID REFERENCES temples(id) ON DELETE CASCADE,
  
  ticket_type     VARCHAR(100),         -- 'General','VIP Darshan','Special Pooja'
  description     TEXT,
  price           INT,                  -- INR, 0 for free
  currency        VARCHAR(3) DEFAULT 'INR',
  
  availability    VARCHAR(20),          -- 'daily','weekends','festivals_only'
  booking_url     TEXT,                 -- external link if available
  booking_method  VARCHAR(50),          -- 'online','counter','both'
  
  notes           TEXT,                 -- 'Carry ID proof'
  is_active       BOOLEAN DEFAULT TRUE,
  
  updated_by      UUID REFERENCES users(id),
  updated_at      TIMESTAMPTZ DEFAULT NOW()
);

-- ============================================
-- REVIEWS & RATINGS
-- ============================================

CREATE TABLE reviews (
  id              UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  
  -- Polymorphic: can review temple, hotel, or guide
  entity_type     VARCHAR(20) CHECK (entity_type IN ('temple','hotel','guide')),
  entity_id       UUID NOT NULL,
  
  user_id         UUID REFERENCES users(id),
  rating          INT CHECK (rating BETWEEN 1 AND 5),
  title           VARCHAR(200),
  body            TEXT,
  
  visit_date      DATE,
  visited_with    VARCHAR(50),          -- 'family','solo','friends','couple'
  
  is_approved     BOOLEAN DEFAULT FALSE,
  helpful_count   INT DEFAULT 0,
  
  created_at      TIMESTAMPTZ DEFAULT NOW()
);

CREATE INDEX idx_reviews_entity ON reviews(entity_type, entity_id);

-- ============================================
-- SAVED / WISHLIST
-- ============================================

CREATE TABLE saved_temples (
  user_id         UUID REFERENCES users(id),
  temple_id       UUID REFERENCES temples(id),
  saved_at        TIMESTAMPTZ DEFAULT NOW(),
  PRIMARY KEY (user_id, temple_id)
);

-- ============================================
-- TRANSLATIONS (i18n)
-- ============================================

CREATE TABLE translations (
  id              UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  entity_type     VARCHAR(20),          -- 'temple','food','guideline'
  entity_id       UUID,
  field_name      VARCHAR(50),          -- 'name','description','history'
  language_code   VARCHAR(10),          -- 'te','hi','ta','kn','ml','bn'
  translated_text TEXT NOT NULL,
  is_verified     BOOLEAN DEFAULT FALSE,
  translated_by   UUID REFERENCES users(id),
  UNIQUE(entity_type, entity_id, field_name, language_code)
);
```

---

## 5. COMPLETE USER ROLES & PERMISSIONS

```
┌──────────────────────────────────────────────────────────────┐
│  ROLE           │  PERMISSIONS                               │
├──────────────────────────────────────────────────────────────┤
│  Tourist        │  Browse, Search, Discover map, Save,       │
│  (Default)      │  Review, Rate, Upload photos, Share        │
│                 │  Download offline data                     │
├──────────────────────────────────────────────────────────────┤
│  Photographer   │  All Tourist + Bulk upload, Portfolio page │
│                 │  Get credited for editor picks             │
├──────────────────────────────────────────────────────────────┤
│  Tour Guide     │  All Tourist + Create guide profile,       │
│                 │  List services, Respond to reviews         │
├──────────────────────────────────────────────────────────────┤
│  Hotel Owner    │  All Tourist + List hotel, Update rooms,   │
│                 │  Respond to reviews, Upload hotel photos   │
├──────────────────────────────────────────────────────────────┤
│  Temple Admin   │  All Tourist + Edit their temple's info,   │
│  (Temple staff) │  Update timings/tickets, Upload photos     │
│                 │  with VERIFIED badge, Post announcements   │
├──────────────────────────────────────────────────────────────┤
│  Editor         │  All Tourist + Approve/Reject photos,      │
│                 │  Mark editor picks, Edit temple content,   │
│                 │  Verify translations, Moderate reviews     │
├──────────────────────────────────────────────────────────────┤
│  Super Admin    │  EVERYTHING + Verify hotels/guides,        │
│  (You)          │  Manage editors, System config, Analytics, │
│                 │  Add states/districts, User management     │
└──────────────────────────────────────────────────────────────┘
```

---

## 6. FEATURE PRIORITY MATRIX

```
P0 - MVP (Launch with these)
════════════════════════════
✅ Landing page with search
✅ Discover map (India → State → District → Temples)
✅ Temple detail page (history, geography, wildlife)
✅ Photo gallery with editor pick badges
✅ Temple roadmap (visit guide)
✅ Do's and Don'ts
✅ Best time to visit
✅ How to reach
✅ User authentication (email + Google)
✅ Basic admin panel
✅ Responsive design (mobile-first)
✅ Telugu + English language support

P1 - Phase 2 (Within 1 month of launch)
════════════════════════════════════════
🔶 Festival calendar
🔶 Local food guide
🔶 Nearby attractions
🔶 User reviews & ratings
🔶 Photo upload by users
🔶 Photo moderation system
🔶 Verified tour guide listings
🔶 Ticket information
🔶 Safety ratings
🔶 Save/Wishlist temples
🔶 Share functionality
🔶 Hindi language support

P2 - Phase 3 (Within 3 months)
═══════════════════════════════
🔷 Verified hotel listings
🔷 Offline access (PWA)
🔷 All Indian language support
🔷 Advanced search & filters
🔷 User profiles & activity
🔷 Tour guide booking
🔷 Analytics dashboard
🔷 Crowd density (user-reported)
🔷 Budget estimator
🔷 Trip planner / itinerary
🔷 Blog / Travel stories
🔷 Push notifications
```

---

## 7. 5 TELANGANA TEMPLES FOR LAUNCH

```
┌──────────────────────────────────────────────────────────────┐
│  #  │  TEMPLE                    │  DISTRICT     │  DEITY   │
├──────────────────────────────────────────────────────────────┤
│  1  │  Yadadri Sri Lakshmi       │  Yadadri      │  Narasimha│
│     │  Narasimha Swamy Temple    │  Bhuvanagiri  │          │
├──────────────────────────────────────────────────────────────┤
│  2  │  Bhadrachalam Sri Rama     │  Bhadradri    │  Rama    │
│     │  Temple                     │  Kothagudem   │          │
├──────────────────────────────────────────────────────────────┤
│  3  │  Vemulawada Sri Raja       │  Rajanna      │  Shiva   │
│     │  Rajeshwara Temple         │  Sircilla     │          │
├──────────────────────────────────────────────────────────────┤
│  4  │  Basara Gnana Saraswati   │  Nirmal       │Saraswati │
│     │  Temple                     │               │          │
├──────────────────────────────────────────────────────────────┤
│  5  │  Thousand Pillar Temple    │  Hanamkonda   │  Shiva,  │
│     │  (Rudreshwara)             │               │  Vishnu, │
│     │                             │               │  Surya   │
└──────────────────────────────────────────────────────────────┘
```

**Please confirm these 5 or suggest replacements.**

---

## 8. STATE THEME SYSTEM (Telangana Example)

```javascript
// Each state gets a unique cultural theme
const telanganaTheme = {
  name: "Telangana",
  nameLocal: "తెలంగాణ",
  
  colors: {
    primary: "#D4A017",     // Bathukamma gold
    secondary: "#E85D26",   // Bonalu vermillion  
    accent: "#2D5016",      // Deccan plateau green
    background: "#FFF8F0",  // Cotton white
    text: "#3D2B1F",        // Nirmal wood brown
  },
  
  pattern: "cheriyal_scroll",  // Background motif
  
  culturalElements: {
    artForm: "Cheriyal Scroll Painting",
    fabric: "Pochampally Ikat",
    festival: "Bathukamma",
    dance: "Perini Sivatandavam",
    icon: "Charminar silhouette",
  },
  
  welcomeMessage: "స్వాగతం! తెలంగాణకు స్వాగతం",
  
  font: {
    heading: "Mandali",     // Telugu Google Font
    body: "Poppins",
  }
};
```

---

## 9. PROJECT STRUCTURE

```
vihar/
├── 📁 public/
│   ├── 📁 maps/
│   │   ├── india.svg
│   │   ├── telangana.svg
│   │   └── districts/
│   ├── 📁 images/
│   │   ├── temples/
│   │   ├── icons/
│   │   └── patterns/
│   ├── 📁 fonts/
│   ├── manifest.json          # PWA
│   └── sw.js                  # Service Worker
│
├── 📁 src/
│   ├── 📁 app/                # Next.js App Router
│   │   ├── layout.tsx         # Root layout
│   │   ├── page.tsx           # Landing page
│   │   ├── 📁 [locale]/       # i18n wrapper
│   │   │   ├── 📁 discover/
│   │   │   │   ├── page.tsx              # India map
│   │   │   │   ├── 📁 [stateSlug]/
│   │   │   │   │   ├── page.tsx          # State map
│   │   │   │   │   └── 📁 [districtSlug]/
│   │   │   │   │       └── page.tsx      # Temple list
│   │   │   ├── 📁 temple/
│   │   │   │   └── 📁 [templeSlug]/
│   │   │   │       ├── page.tsx          # Temple detail
│   │   │   │       ├── 📁 photos/
│   │   │   │       ├── 📁 roadmap/
│   │   │   │       └── 📁 reviews/
│   │   │   ├── 📁 hotels/
│   │   │   ├── 📁 guides/
│   │   │   ├── 📁 gallery/
│   │   │   ├── 📁 search/
│   │   │   ├── 📁 auth/
│   │   │   │   ├── login/
│   │   │   │   └── register/
│   │   │   ├── 📁 profile/
│   │   │   │   └── [userId]/
│   │   │   ├── 📁 admin/
│   │   │   │   ├── dashboard/
│   │   │   │   ├── temples/
│   │   │   │   ├── photos/
│   │   │   │   ├── hotels/
│   │   │   │   ├── guides/
│   │   │   │   └── users/
│   │   │   ├── 📁 about/
│   │   │   └── 📁 contact/
│   │   └── 📁 api/            # API Routes
│   │       ├── temples/
│   │       ├── photos/
│   │       ├── reviews/
│   │       ├── guides/
│   │       ├── hotels/
│   │       ├── search/
│   │       ├── auth/
│   │       └── admin/
│   │
│   ├── 📁 components/
│   │   ├── 📁 ui/             # Reusable UI components
│   │   │   ├── Button.tsx
│   │   │   ├── Card.tsx
│   │   │   ├── Badge.tsx      # Verified & Editor Pick
│   │   │   ├── Modal.tsx
│   │   │   ├── Tabs.tsx
│   │   │   ├── Rating.tsx
│   │   │   ├── SearchBar.tsx
│   │   │   ├── LanguageSwitch.tsx
│   │   │   └── LoadingDiya.tsx # Diya animation loader
│   │   ├── 📁 maps/
│   │   │   ├── IndiaMap.tsx
│   │   │   ├── StateMap.tsx
│   │   │   ├── TempleMap.tsx
│   │   │   └── RoadmapMap.tsx
│   │   ├── 📁 temple/
│   │   │   ├── TempleHero.tsx
│   │   │   ├── TempleHistory.tsx
│   │   │   ├── TempleRoadmap.tsx
│   │   │   ├── TempleGuidelines.tsx
│   │   │   ├── TempleFestivals.tsx
│   │   │   ├── TempleFood.tsx
│   │   │   └── TempleTransport.tsx
│   │   ├── 📁 photo/
│   │   │   ├── PhotoGrid.tsx
│   │   │   ├── PhotoCard.tsx   # With badges
│   │   │   └── PhotoUpload.tsx
│   │   ├── 📁 layout/
│   │   │   ├── Header.tsx
│   │   │   ├── Footer.tsx
│   │   │   ├── Sidebar.tsx
│   │   │   └── MobileNav.tsx
│   │   └── 📁 admin/
│   │       ├── AdminSidebar.tsx
│   │       ├── DataTable.tsx
│   │       └── StatsCard.tsx
│   │
│   ├── 📁 lib/
│   │   ├── supabase.ts        # Supabase client
│   │   ├── auth.ts            # Auth helpers
│   │   ├── utils.ts           # Utility functions
│   │   └── constants.ts       # App constants
│   │
│   ├── 📁 hooks/
│   │   ├── useAuth.ts
│   │   ├── useTemple.ts
│   │   ├── useSearch.ts
│   │   ├── useOffline.ts
│   │   └── useTranslation.ts
│   │
│   ├── 📁 store/              # Zustand stores
│   │   ├── authStore.ts
│   │   ├── searchStore.ts
│   │   └── offlineStore.ts
│   │
│   ├── 📁 i18n/
│   │   ├── config.ts
│   │   └── 📁 messages/
│   │       ├── en.json
│   │       ├── te.json        # Telugu
│   │       ├── hi.json        # Hindi
│   │       ├── ta.json        # Tamil
│   │       ├── kn.json        # Kannada
│   │       ├── ml.json        # Malayalam
│   │       ├── bn.json        # Bengali
│   │       ├── mr.json        # Marathi
│   │       ├── gu.json        # Gujarati
│   │       ├── pa.json        # Punjabi
│   │       ├── or.json        # Odia
│   │       └── ur.json        # Urdu
│   │
│   ├── 📁 styles/
│   │   ├── globals.css
│   │   ├── themes/
│   │   │   └── telangana.css
│   │   └── patterns/          # Mandala, Rangoli SVGs
│   │
│   └── 📁 types/
│       ├── temple.ts
│       ├── user.ts
│       ├── photo.ts
│       └── index.ts
│
├── 📁 supabase/
│   ├── migrations/
│   ├── seed.sql               # Initial data for 5 temples
│   └── config.toml
│
├── .env.local
├── .env.example
├── next.config.js
├── tailwind.config.ts
├── tsconfig.json
├── package.json
├── LICENSE                    # Open source license
├── CONTRIBUTING.md            # How to contribute
└── README.md
```

---

## 10. WIREFRAME DESCRIPTIONS

### Landing Page
```
┌──────────────────────────────────────────────────┐
│  🕉️ VIHAR          [Search...]    [🌐 EN] [👤]  │
├──────────────────────────────────────────────────┤
│                                                  │
│    ╔══════════════════════════════════════════╗   │
│    ║  "Discover the Sacred Heart of India"   ║   │
│    ║                                          ║   │
│    ║  [🔍 Search temples, cities, deities...] ║  │
│    ║                                          ║   │
│    ║  [🗺️ Discover on Map]  [🎲 Surprise Me] ║  │
│    ╚══════════════════════════════════════════╝   │
│                                                  │
│  ── Featured Temples ──────────────────────────  │
│  ┌─────┐ ┌─────┐ ┌─────┐ ┌─────┐ ┌─────┐      │
│  │Yada │ │Bhad │ │Vemu │ │Basa │ │1000P│      │
│  │dri  │ │racha│ │lawa │ │ra   │ │illar│      │
│  └─────┘ └─────┘ └─────┘ └─────┘ └─────┘      │
│                                                  │
│  ── Editor's Photo Picks ──────────────────────  │
│  ┌──────────┐ ┌──────────┐ ┌──────────┐        │
│  │ 📸  ✅   │ │ 📸  ✅   │ │ 📸  ✅   │        │
│  │ green    │ │ green    │ │ green    │        │
│  │ badge    │ │ badge    │ │ badge    │        │
│  └──────────┘ └──────────┘ └──────────┘        │
│                                                  │
│  ── Upcoming Festivals ───────────────────────   │
│  🎪 Brahmotsavam @ Yadadri    │  Dec 15-23      │
│  🪔 Karthika Deepotsavam      │  Nov 27         │
│                                                  │
│  ── Quick Stats ──────────────────────────────   │
│  🛕 5 Temples │ 📸 200+ Photos │ 🧭 12 Guides  │
│                                                  │
├──────────────────────────────────────────────────┤
│  Footer: About | Contact | Contribute | GitHub   │
│  Made with 🙏 for Bharat                        │
└──────────────────────────────────────────────────┘
```

### Discover Map Page
```
┌──────────────────────────────────────────────────┐
│  🕉️ VIHAR    [Search...]              [🌐] [👤] │
├──────────────────────────────────────────────────┤
│                                                  │
│  "Tap on a state to explore its temples"         │
│                                                  │
│         ┌─────────────────────┐                  │
│         │                     │                  │
│         │     🇮🇳 INDIA MAP    │                  │
│         │    (Interactive SVG) │                  │
│         │                     │                  │
│         │   Telangana glows   │                  │
│         │   on hover with     │                  │
│         │   temple count: 5   │                  │
│         │                     │                  │
│         └─────────────────────┘                  │
│                                                  │
│  ┌─ Hover Card ──────────────┐                   │
│  │ తెలంగాణ Telangana        │                   │
│  │ 🛕 5 Temples  📸 200+    │                   │
│  │ "Land of Bathukamma"     │                   │
│  │ [Explore →]              │                   │
│  └───────────────────────────┘                   │
│                                                  │
└──────────────────────────────────────────────────┘
```

---

## NEXT STEPS - WHAT I NEED FROM YOU

```
┌──────────────────────────────────────────────────────┐
│  #  │  ACTION ITEM                    │  STATUS      │
├──────────────────────────────────────────────────────┤
│  1  │  Confirm the 5 temples above    │  ⏳ WAITING  │
│  2  │  Send me your logo file         │  ⏳ WAITING  │
│  3  │  Create a GitHub repository     │  ⏳ WAITING  │
│  4  │  Create Supabase account        │  ⏳ WAITING  │
│     │  (supabase.com - free)          │              │
│  5  │  Create Cloudinary account      │  ⏳ WAITING  │
│     │  (cloudinary.com - free)        │              │
│  6  │  Create Vercel account          │  ⏳ WAITING  │
│     │  (vercel.com - free)            │              │
│  7  │  Confirm color palette above    │  ⏳ WAITING  │
│  8  │  Confirm state themes concept   │  ⏳ WAITING  │
│  9  │  Any specific design references │  ⏳ WAITING  │
│     │  (websites you like the look of)│              │
│ 10  │  Shall I start coding Phase 1?  │  ⏳ WAITING  │
└──────────────────────────────────────────────────────┘
```

**Once you confirm items 1-8, I will immediately start delivering working code file by file.** We'll build this like a real FAANG sprint — structured, tested, and production-ready. 🚀
