# HongKongEmergency

HongKongEmergency is a compact Cantonese phrasebook for Chinese-speaking newcomers living and working in Hong Kong. It focuses on phrases that are useful at the MTR, restaurants, rental flats, clinics, banks, government counters, offices, and everyday conversations.

## What It Includes

- Hong Kong spoken Cantonese in traditional characters
- Jyutping romanization with tone numbers
- Mandarin explanations for quick reference
- Living scenarios: commuting, food, shopping, renting, repairs, banking, telecoms, healthcare, and typhoon arrangements
- Workplace scenarios: introductions, meetings, tasks, messages, feedback, leave, pay, MPF, and interviews
- Browser/operating-system TTS controls for every Cantonese entry in the web version
- A Markdown source that stays free of audio links and embedded controls

## Read Online

GitHub Pages: [https://sutfuturecoder.github.io/HongKongEmergency/](https://sutfuturecoder.github.io/HongKongEmergency/)

After GitHub Pages is enabled, publish directly from the `docs/` directory.

Recommended GitHub Pages settings:

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/docs`

The local web entry point is:

- [docs/index.html](docs/index.html)

The full Markdown source is:

- [docs/hong-kong-cantonese.md](docs/hong-kong-cantonese.md)

## Notes on Pronunciation

The page uses the browser `SpeechSynthesis` API with `yue-HK` as the preferred language. Voice availability depends on the browser and the Cantonese voice packages installed on the operating system. The Jyutping here is a practical reference, not a substitute for listening to native speakers.

## Project Structure

```text
HongKongEmergency/
├─ docs/
│  ├─ index.html
│  └─ hong-kong-cantonese.md
├─ .gitignore
└─ README.md
```
