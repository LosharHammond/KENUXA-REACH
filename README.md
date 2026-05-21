# KENUXA REACH

**Distribution Intelligence and Audience Infrastructure Platform for African Businesses**

> Discover, organize, and activate real-world human networks. Africa's Structured Reach Graph.

---

## What is KENUXA REACH?

KENUXA REACH is not a social media tool. It is not an ad platform.

It is a **distribution intelligence** and **audience infrastructure platform** that helps African businesses:

- Discover where customers are (communities, groups, networks)
- Organize audience networks into structured distribution nodes
- Upload and activate their customer base
- Route messages through the best audience paths
- Build reusable distribution systems
- Grow network intelligence over time

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Next.js 16 App Router, TypeScript, Tailwind CSS |
| UI Components | Custom components |
| Backend | Next.js API Routes |
| Database | Supabase PostgreSQL |
| Auth | Supabase Auth |
| AI | Groq API (Llama 3 / Mixtral) |

---

## Quick Start

### 1. Install

```bash
cd kenuxa-reach
npm install
```

### 2. Set up Supabase

1. Go to [supabase.com](https://supabase.com) and create a project
2. In the SQL Editor, run `supabase/schema.sql`
3. Copy your project URL and anon key

### 3. Set up Groq AI

1. Go to [console.groq.com](https://console.groq.com) and get an API key

### 4. Configure Environment

```bash
cp .env.example .env.local
```

Edit `.env.local`:

```env
NEXT_PUBLIC_SUPABASE_URL=https://your-project.supabase.co
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-anon-key
SUPABASE_SERVICE_ROLE_KEY=your-service-role-key
GROQ_API_KEY=gsk_your_groq_key
```

### 5. Run

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

---

## Platform Architecture — 6 Engines

### Engine 1 — Network Discovery Engine
Discovers communities across Telegram, WhatsApp, Facebook, and local business groups.

### Engine 2 — Distribution Graph Engine
Converts communities into structured **distribution nodes** connected by audience overlap, geography, and business relevance.

### Engine 3 — Customer Activation Engine
Upload CSV customer lists, auto-segmented by behavior (active, dormant, high-value, repeat buyers).

### Engine 4 — Routing Intelligence Engine
AI (Groq) determines optimal audience pathways — trust scores, engagement history, geographic match.

### Engine 5 — Activation & Campaign Engine
Create campaigns across WhatsApp, Telegram, Email with rate limiting and anti-spam safeguards.

### Engine 6 — Network Growth Engine
Users contribute communities, verify nodes, earn reputation points.

---

## Key Routes

| Route | Description |
|-------|-------------|
| `/` | Landing page |
| `/dashboard` | Network overview, stats |
| `/explore` | Community Explorer |
| `/customers` | Customer Hub — import, segment |
| `/campaigns` | Activation Center — create campaigns |
| `/contribute` | Add communities to the graph |
| `/network` | Network Map — visual graph |
| `/settings` | Organization settings |

---

## Deployment (Vercel)

```bash
npm i -g vercel
vercel --prod
```

Set environment variables in Vercel project settings.

---

## Important — Responsible Messaging

KENUXA REACH generates **distribution plans only**. Sending messages requires your own:
- WhatsApp Business API integration
- Telegram Bot API
- Email provider

All outreach must be opt-in and consent-based.

---

Built for African Markets. Infrastructure for Reach Itself.
