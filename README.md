# NeuroScan

Production-grade medical image analysis for **early brain tumor detection** using **ResNet50**, with:
- **Backend**: FastAPI + SQLModel + PostgreSQL + JWT auth
- **Frontend**: Next.js + Tailwind + protected routes
- **Reports**: Professional PDF with logo + MRI + Grad-CAM heatmap
- **Features**: Doctor auth, patient management, MRI upload & inference, report download, reports list & delete

## Monorepo Layout

## Quick Start

### Backend
```bash
cd backend
python -m venv venv
venv\Scripts\activate    
pip install -r requirements.txt

# copy env and edit
copy .env.example .env

# run
uvicorn app.main:app --reload --port 8000
```
### Frontend
```bash
cd frontend
npm install
# copy env
copy .env.local.example .env.local
npm run dev
```
