# CoopAI — Smart Cooperative & Employment System

A responsive front-end prototype for an AI-enabled cooperative capacity-building, ERP, and employment ecosystem.

## Problem statement
Cooperative societies face challenges in managing daily operations, member records, skill development, and employment opportunities. Manual processes can cause delays and inefficiency. CoopAI demonstrates a centralized platform to organize member information, show training programmes, and suggest jobs based on skills.

## Features
- Cooperative member directory with sample records
- Skill-development programme cards and progress bars
- Job listings with simple keyword-based skill matching
- Summary dashboard
- Responsive desktop/mobile layout
- Sample data only; no server or real AI model is connected

## Run locally
1. Extract the ZIP file.
2. Open `index.html` in a modern browser.
3. No installation or environment variables are required.

Optional: use VS Code Live Server to run it locally.

## Project structure
- `index.html` — page structure
- `style.css` — responsive styling
- `app.js` — sample data and interactive dashboard
- `docs/ARCHITECTURE.md` — architecture notes
- `data/sample-data.json` — sample dataset
- `tests/TEST_CASES.md` — manual test cases
- `LICENSE` — MIT License

## Architecture
This version is a browser-only prototype. The UI reads in-memory sample data from `app.js`, renders dashboard cards and tables, and calculates simple skill keyword matches. For a production version, add a secure backend, database, authentication, consent controls, and a validated AI/job-matching service.

## Sustainable Development Goals
- SDG 4: Quality Education — skill-development programmes
- SDG 8: Decent Work and Economic Growth — employment opportunities
- SDG 9: Industry, Innovation and Infrastructure — digital workflow support

## Limitations and privacy
The prototype does not persist changes, connect to real job providers, or use a trained AI model. All displayed people and organisations are fictional sample entries. Do not enter sensitive personal information.

## License
Released under the MIT License; see `LICENSE`.
