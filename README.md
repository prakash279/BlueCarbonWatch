# BlueCarbonWatch

BlueCarbonWatch (BCW) is a participatory monitoring platform designed to protect mangrove forests and coastal ecosystems. It empowers local communities, researchers, and authorities by combining geospatial data, AI-assisted validation, and citizen reporting into one streamlined platform.

## Overview

Mangrove forests are natural barriers against storms, biodiversity hotspots, and vital carbon sinks. However, they face threats like illegal cutting, land reclamation, oil spills, and plastic pollution.

BCW tackles this problem by enabling communities to report incidents in real-time with photos and metadata, while providing authorities with a dashboard for decision-making. Users earn Blue Carbon Ecosystem (BCE) credits for their contributions, redeemable in eco-friendly ways.

## Features (Frontend MVP)

### Interactive Map Dashboard

- Displays mangrove zones (from provided geospatial datasets).

- Zones can be segmented into regions (based on area thresholds).

- Regions are visually highlighted for easy monitoring.

### Report Incidents

- Users can submit reports via website form or through our integrated Telegram bot.

- Uploads include photo evidence, optional description, and location metadata.

### Dashboard

- View active reports, urgent alerts, and categorized cases (cutting, pollution, dumping).

- Track BCE credits earned by reporters.

- Premium dashboard includes detailed logs & severity analysis.

### User Accounts

- Login & profile system for contributors.

- Free tier → report & earn credits.

- Premium tier → advanced severity scoring (AI models, IoT sensors, drone data).

## Tech Stack

- Frontend: Next.js + React + Tailwind CSS

- Map Integration: Leaflet / Mapbox

- UI Frameworks: shadcn/ui for components, Recharts for visualization

- Backend (planned): FastAPI + PostgreSQL (separate repo / service)

- Integration: Telegram Bot API (for external reporting)

## Getting Started

1. Clone the Repo
```bash
https://github.com/prakash279/BlueCarbonWatch.git
cd bluecarbonwatch
```
2. Install Dependencies
```bash
npm install
```
3. Run the Dev server
```bash
npm run dev
```
