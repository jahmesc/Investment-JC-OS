# Investing OS Overlay

Investing OS Overlay is a TradingView package designed to standardize how you analyze charts, manage alerts, and run weekly reviews. The repository is organized so you can drop the Pine Script into TradingView and follow the documented routines to keep your workflow consistent.

## What is in v0.1
- Daily, weekly, and monthly moving averages plus optional RSI, OBV/CMF, and Fibonacci framework with manual override.
- Setup Score table that blends higher-timeframe regime, momentum, daily execution, and accumulation proxies with alert hooks.
- Alert scaffolding for score inflections, reload zones, weekly structure breaks, and monthly regime cautions.

## What is intentionally not included yet
- Auto trendlines, regression channels, or other discretionary drawing tools.
- Proprietary “whale” or dark-pool panels—everything is built on standard Pine indicators.

## Repository structure
- `pine/`: Pine Script overlays for TradingView.
- `docs/`: Setup, usage, and operating procedures for the overlay.
- `examples/`: Sample settings, alert presets, and screenshot placeholders.

## Getting started
1. Import the Pine Script from `pine/investing_os_overlay_v0_1.pine` into TradingView.
2. Follow the installation steps in `docs/01_install_on_tradingview.md` to add the script to your charts.
3. Review `docs/02_how_to_use.md` for daily operations and panel layouts.
4. Use the additional guides for manual Fibonacci work, alert packs, and weekly routines to keep your process aligned.

## Contributing and customization
- Copy the baseline Pine Script and adjust inputs for your personal risk model.
- Capture screenshots of preferred layouts and save them in `examples/` for future reference.
- Update the documentation whenever you refine the workflow so the playbook stays accurate.
