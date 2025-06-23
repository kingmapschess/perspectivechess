# KAMPS-DASH: Structured Chess Evaluation & Reflective Training Engine

**KAMPS-DASH** is a dynamic, schema-driven chess analysis system designed to provide players and coaches with layered, interpretive insights beyond raw engine scores. Built around structured YAML frameworks—**KAMPS**, **SOAP**, **SCOPE**, and the evolving **DEEP** model—this tool transforms live gameplay and post-match review into a rich environment for strategic and cognitive growth.

---

## ✨ Project Vision

Traditional engine evaluations are precise but shallow. KAMPS-DASH interprets **why** a position matters, **how** decisions unfold across time and tempo, and **what** players can learn from their own styles—especially against human opponents. 

The system aims to offer:
- Sector-based live commentary
- Schema-aligned decision feedback
- Post-game performance KPIs
- Modular YAML architecture for customisation

---

## 🧠 Core Schema Layers

- **KAMPS** – Evaluates King Safety, Activity, Material, Pawn Structure, and Space, with real-time tempo adjustments
- **SOAP** – Tracks Subjective assessments, Objective features, Assessments, and Plans per move
- **SCOPE** – Reflects on Successes, Challenges, Opportunities, Patterns, and Evolution after games
- **DEEP** *(in development)* – Targets decision psychology, emotional tracking, and adaptability scoring

All schemas are maintained as modular `.yaml` files and can be queried/updated using [`yq`](https://github.com/mikefarah/yq).

---

## 📊 Human-Centred KPIs

KAMPS-DASH tracks human-vs-human performance using quantitative, strategy-aligned metrics such as:

- **KAMPS Sector Shift Rate**
- **Pace–Tempo Correlation**
- **SOAP Plan Frequency**
- **Initiative Acquisition Ratio**
- **Decision Quality Under Time Pressure**
- **Evaluation Drift vs Opponent Strength**
- **Subjective–Objective Alignment Score**

These KPIs are designed to favour *learning performance*, not perfection.

---

## 🛠️ System Components

- Live move capture via [Lichess API](https://lichess.org/api)
- Engine analysis (Stockfish or equivalent)
- Real-time `yq`-powered schema evaluation
- Visual dashboard with sector commentary
- Post-game journaling with SOAP & SCOPE reports

---

## 📦 Getting Started

> Setup instructions coming soon. This README will grow alongside the MVP!

---

## 💬 Philosophy

KAMPS-DASH is about awareness, not just evaluation. It’s a tutor that doesn't just score your moves—it understands your thinking patterns, highlights your blind spots, and helps you grow through structured reflection.

---

## 📁 Journal

See [`/docs/kamps-dash-journal.md`](./docs/kamps-dash-journal.md) for a full breakdown of the concept, use cases, KPIs, and architectural notes.

---

## 📌 Roadmap Highlights

- [ ] Define DEEP schema structure
- [ ] Build YAML query engine for KPIs
- [ ] Design dashboard visual mockups
- [ ] Implement SOAP/SCOPE logging module
- [ ] Pilot integration with Lichess live games

---

## 👤 Author

Designed by **Gary**, co-dreamed with **Copilot**.

---

## 📜 Licence

To be confirmed. Possibly open-source with attribution required for schema logic reuse.