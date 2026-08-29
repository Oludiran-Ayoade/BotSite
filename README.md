# dassistant — Screen Assessment Tool

A floating screen assistant that analyzes what's on your screen in real-time.

## Download

Download the latest release for your platform:
- **macOS**: [dassistant.dmg](#) (coming soon)
- **Windows**: [dassistant.exe](#) (coming soon)

Or build from source (see below).

## Build from source

### Prerequisites
- Python 3.11+
- macOS or Windows

### Install dependencies
```bash
cd gemini-desktop-assistant
python -m venv .venv
source .venv/bin/activate    # Mac/Linux
# .venv\Scripts\activate     # Windows
pip install -r requirements.txt
pip install pyinstaller
```

### Build the executable
```bash
# macOS
pyinstaller --onefile --windowed --name "dassistant" main.py

# Windows
pyinstaller --onefile --windowed --name "dassistant" main.py
```

The built app will be in `dist/`.

## Payment

Payments are processed securely via Flutterwave (card, bank transfer, USSD).
Visit the website to choose a plan or credit pack and pay.

## Pricing

| Plan | Price | Credits |
|------|-------|---------|
| Free Trial | $0 | 4 analyses |
| Basic | $5/mo | 150 analyses |
| Plus | $15/mo | 600 analyses |
| Pro | $39/mo | 2,500 analyses |
| Starter Pack | $2 | 50 analyses |
| Standard Pack | $5 | 200 analyses |
| Big Pack | $10 | 500 analyses |
