# 💊 MedMate — Daily Wellness Companion

**Live app:** https://jjmoontravel-design.github.io/medmate/

MedMate is a free, privacy-first medication companion. Enter the medications you take (or scan the bottle label with your camera) and MedMate builds a clear daily plan: when to take each medicine, foods that help, foods and drinks to limit or keep apart, and healthy habits that support your treatment — all in plain language.

## Features

- **📋 My Medications** — searchable library of 62 common medications (generic + brand names), each with a plain-English "what is this for?" explanation, optional dose strength, and camera **bottle-label scanning** (AI-powered)
- **🌞 My Daily Plan** — timing, food, and lifestyle tips generated from your medication list, plus warnings for well-known risky combinations (e.g. blood thinners + NSAIDs, grapefruit + statins)
- **⏰ Reminders** — dose reminders with chime + browser notifications, one-tap **"with breakfast / lunch / dinner / bedtime"** scheduling that adjusts when your day shifts, 30-minute snooze, a daily taken/undo checklist, and an optional **caregiver backup** (one-tap text when a dose runs 2+ hours late)
- **📷 Photo Check** — snap a photo of a food or exercise machine and get an AI verdict (good choice / use caution / better to skip) with approximate calories and medication-specific notes *(requires your own Anthropic API key)*
- **📈 Report** — 30-day adherence score, 5-week heatmap, refill tracker with "call the pharmacy" alerts, printable **doctor visit report**, and backup/restore
- **♿ Senior-friendly** — three text sizes (Aa button), flat navigation, large touch targets, gentle ring-once alarms
- **📱 Installable PWA** — add it to your phone's home screen; works offline

## Privacy

All personal data — medications, reminders, dose history, caregiver contact — is stored **only in your browser** (localStorage). Nothing is sent to any server. The optional Photo Check and bottle-scan features send only the photo you choose to Anthropic's API using your own key.

## ⚠️ Disclaimer

MedMate provides **general wellness and educational information only**. It is not medical advice, does not replace your doctor or pharmacist, and does not catch every interaction. Always follow your prescription label and consult a healthcare professional before changing anything.

## Running locally

It's a single static page — no build step:

```
npx serve .
```

or just open `index.html` in a browser.

---

Built with [Claude Code](https://claude.com/claude-code).
