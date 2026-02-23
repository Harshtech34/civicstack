# CivicStack 🚀

![Build Status](https://img.shields.io/badge/build-in_progress-yellow) ![License](https://img.shields.io/badge/license-MIT-green) ![Backend](https://img.shields.io/badge/backend-FastAPI-blue) ![Frontend](https://img.shields.io/badge/frontend-React-blue) ![Database](https://img.shields.io/badge/database-PostgreSQL-blue) ![Open Source](https://img.shields.io/badge/open_source-yes-brightgreen)

**Team:** Harshal Chavan & Team  
**Demo Video (unlisted):** https://youtu.be/YOUR_DEMO_LINK *(replace with your unlisted YouTube link)*  
**Live (staging):** https://staging.civicstack.example.com *(replace when ready)*  
**Repo:** https://github.com/Harshtech34/CivicStack

Built for :contentReference[oaicite:0]{index=0} in partnership with :contentReference[oaicite:1]{index=1}.

---

## TL;DR
CivicStack is an open-source civic issue reporting and transparency platform that enables citizens to submit geo-tagged reports (potholes, drainage, streetlights, sanitation), empowers municipal triage, and publishes open, machine-readable data exports. Designed to be reproducible, privacy-aware, and pilot-ready for real cities.

---

## Why CivicStack?
- **Impact-first:** Closes the loop from citizen report → municipal triage → public accountability.  
- **Reproducible & production-ready:** Docker-based local demo and cloud-ready deployment options.  
- **Open & extensible:** MIT licensed; contributions welcome; export-friendly (CSV/JSON/CKAN).

---

## MVP Feature Set (March deliverables)
1. Map-based report submission (title, category, photo, location)  
2. Public dashboard (map + list + filters)  
3. Admin triage panel (status, notes, assign agency)  
4. Export endpoints (CSV / JSON) + unique tracking IDs for provenance  
5. Reproducible `docker-compose` demo + staging deploy

---

## Tech stack
- Frontend: React, Tailwind CSS, Leaflet using :contentReference[oaicite:2]{index=2} tiles  
- Backend: FastAPI, SQLAlchemy  
- Database: :contentReference[oaicite:3]{index=3}  
- Storage: Supabase Storage / Cloud Storage (optional)  
- Dev / Deploy: Docker & Docker Compose; cloud options: Cloud Run / Render / GCP  
- Repo & CI: :contentReference[oaicite:4]{index=4} and GitHub Actions  
- Container tooling: :contentReference[oaicite:5]{index=5}

---

## Quickstart (local, demo-ready)

1. Clone:
```bash
git clone https://github.com/Harshtech34/CivicStack.git
cd CivicStack