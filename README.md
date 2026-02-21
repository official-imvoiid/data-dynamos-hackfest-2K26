# SentinelForge - Hackfest 2K26

SentinelForge is an autonomous AI-powered security platform built for **Hackfest 2K26** at M.Kumarasamy College of Engineering (Feb 20-21, 2026). It provides real-time detection and response for advanced cyber threats.

## Key Features
- **AI SOC Supervisor**: Local LLM for autonomous threat analysis.
- **Ransomware Canary**: Real-time I/O monitoring to stop mass encryption.
- **Anti-BadUSB**: Keystroke dynamics analysis to detect hardware-injected scripts.
- **Network Forensic Agents**: Packet inspection for DDoS and C2 traffic detection.
- **Memory Shield**: Scans for fileless malware and process injections.

## Tech Stack
- **Frontend**: Next.js 14, TypeScript, Tailwind CSS, Framer Motion.
- **Backend**: FastAPI, Python, Scapy, PyTorch, HuggingFace (SmolLM).
- **Security**: AES-GCM Encryption, JWT Authentication, Rate Limiting.

## Quick Setup

### 1. Backend
```bash
cd backend
python -m venv venv
# Windows: venv\Scripts\activate
# Linux/Mac: source venv/bin/activate
pip install -r requirements.txt
```

### 2. Frontend
```bash
cd frontend
npm install
```

### 3. Run
Use the root startup script:
```bash
./run.sh
```

- **Backend**: http://localhost:8000
- **Dashboard**: http://localhost:3000
