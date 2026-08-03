# Advanced RPAS Exam Simulator — Canada

A mobile-compatible, unofficial study simulator for the Canadian **Advanced Operations RPAS pilot examination**.

## Features

- 270 original practice questions across all eight TP 15263 knowledge areas
- Direct official source link on every question
- Exact CAR section links for regulatory questions
- Original visual/diagram questions
- Study mode with immediate explanations
- 50-question, 60-minute simulated exam with an 80% benchmark
- Flagging, question navigator, category results, and retry-incorrect mode
- No framework, build process, login, analytics, or external JavaScript dependency

## Official source policy

Questions and explanations are original paraphrases. They are grounded in current official sources, including:

- Canadian Aviation Regulations, particularly Part IX
- Transport Canada TP 15263, Fourth Edition (March 2025)
- CAR Standards 921, 922, and 923
- Transport Canada Aeronautical Information Manual
- NAV CANADA VFR Phraseology Guide and aeronautical publications
- ISED RIC-21

The simulator is not an official Transport Canada examination and does not reproduce confidential examination questions. Regulations and publications can change; always verify the linked official source before an operation.

## Run locally

Open `index.html` in a browser. For full mobile functionality, serve it over HTTP/HTTPS rather than using an attachment preview:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages

In repository **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
