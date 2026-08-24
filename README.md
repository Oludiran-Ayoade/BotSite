# Assistant — Screen Assessment Tool

A floating screen assistant that analyzes what's on your screen in real-time.

## Download

Download the latest release for your platform:
- **macOS**: [Assistant.dmg](#) (coming soon)
- **Windows**: [Assistant.exe](#) (coming soon)

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
pyinstaller --onefile --windowed --name "Assistant" main.py

# Windows
pyinstaller --onefile --windowed --name "Assistant" main.py
```

The built app will be in `dist/`.

## Payment

Send USDT (TRC20) to the address shown on the website, then message us with your license key and transaction hash to activate your subscription.

## Pricing

| Plan | Price | Credits |
|------|-------|---------|
| Free Trial | $0 | 15 analyses |
| Monthly | $9/mo | 1,000 credits |
| Pro | $19/mo | 3,000 credits |
| Credit Packs | from $3 | 1,000–11,000 credits |
