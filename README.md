# alien_invasion

Simple side-scrolling shooter built with `pygame`.

## Setup (recommended: virtual environment)

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

## Run locally

```bash
python alien_invasion.py
```

## Headless smoke test (non-interactive)

This mode auto-starts gameplay, simulates basic movement/firing, and exits after a fixed number of frames.

```bash
ALIEN_INVASION_AUTOPLAY_FRAMES=180 SDL_VIDEODRIVER=dummy python alien_invasion.py
```
