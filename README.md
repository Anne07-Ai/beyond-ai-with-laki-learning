<div align="center">

# ✦ Beyond AI with Laki

### AI made simple. One day at a time.

**A free learning library for curious minds — no technical background required.**

[Explore Day 1 Notes](./day/1/) · [Instagram](https://www.instagram.com/beyondaiwithlaki/) · [Report an issue](https://github.com/Anne07-Ai/beyond-ai-with-laki-learning/issues)

</div>

---

## 💜 Why we're building this

Artificial intelligence is changing everyday life, but learning about it shouldn't feel like reading a technical manual.

**Beyond AI with Laki** makes AI, language models and digital safety approachable through clear explanations, thoughtful visual examples and practical takeaways. The goal is **useful public education**, not jargon-heavy tutorials.

Our first series, **30 Days of LLMs**, introduces one concept at a time. Each lesson is written for complete beginners without sacrificing factual accuracy.

## ✨ What you'll find

| Learning experience | What it means |
| --- | --- |
| 📖 **Plain-English notes** | Simple definitions and real-world examples |
| 🧩 **Visual explanations** | Concepts such as tokens and next-token prediction, explained step by step |
| ✅ **Mini quizzes** | A quick way to check what you've learned |
| 🔎 **Further reading** | Links to references for deeper learning |
| 📱 **Mobile-first pages** | Comfortable reading on phones, tablets and desktops |
| 🖨️ **Save as PDF** | Browser-based Print / Save as PDF for offline reading |

## 🎓 30 Days of LLMs

| Day | Topic | Availability |
| :---: | --- | --- |
| **01** | [What is an LLM — and how does ChatGPT work?](./day/1/) | Notes available in this repository |
| **02** | [What exactly is a token?](./day/2/) | Notes available in this repository |
| **03** | [What are embeddings?](./day/3/) | Proposed in the Day 3 feature branch; release pending review |
| **04–30** | More beginner-friendly AI lessons | Planned; released after editorial review |

**Day 1 covers:** language patterns, a simplified “Twinkle, twinkle…” analogy, tokenisation, next-token generation and why confident AI answers can still be incorrect.

> **Creator's note:** Learn at your own pace. The aim is understanding, not memorising technical words.

## 🎨 Our design language

- **Palette:** elegant blush pink, lavender, pearl white and muted violet.
- **Tone:** friendly, inclusive and professional — never childish or condescending.
- **Visuals:** purposeful diagrams and examples, not decoration for its own sake.
- **Accessibility:** readable typography, semantic page structure, mobile-friendly layout and printable notes.

## 🗂️ Project structure

```text
beyond-ai-with-laki-learning/
├── index.html           # Learning Library homepage
├── day/
│   ├── 1/
│   │   └── index.html   # Day 1 lesson and quiz
│   ├── 2/
│   │   └── index.html   # Day 2 lesson and quiz
│   └── 3/
│       ├── index.html   # Embeddings guide, diagrams, quiz and interview Q&A
│       └── lesson.css   # Scoped Day 3 screen/print styling
├── styles.css           # Responsive design system
├── _headers             # Security-related response headers
└── README.md
```

This is intentionally a **static website**. No database, sign-in, API keys or paid backend is needed for the initial library.

## 🚀 Run locally

Clone this public repository:

```bash
git clone https://github.com/Anne07-Ai/beyond-ai-with-laki-learning.git
cd beyond-ai-with-laki-learning
python3 -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser.

## ☁️ Cloudflare Workers deployment

The existing site uses **Cloudflare Workers with static assets**, connected to this GitHub repository. Do not create a Cloudflare Pages project or another repository.

Existing site: https://beyond-ai-with-laki-learning.lakshmianne07.workers.dev

Release workflow:
1. Prepare lesson changes on a feature branch and open a pull request.
2. Review factual accuracy, links, responsive layout and browser printing.
3. Obtain creator approval before merging into `main`.
4. The existing Cloudflare integration automatically builds/deploys the merge.
5. Check the deployment result and verify the lesson in a browser. A merged PR alone does not prove successful deployment.

Feature branches may trigger Cloudflare builds too. Inspect check results; a preview build failure must not be described as a successful production deployment. No Cloudflare configuration is changed by the Day 3 lesson PR. Deployment settings are managed by the existing integration, not inferred from a new local configuration file.

The intended Day 3 route is `/day/3/`; it is **not a verified live release until deployment and browser checks succeed**. Days 1 and 2 are existing published lessons according to the project handover.

## 📄 Notes and Instagram delivery

Lessons include browser-based **Print / Save as PDF**. This does not require a separately hosted PDF, an account or an email address.

The selected delivery provider is **Repli**. The intended Day 3 journey after website release is:

**Instagram Reel → comment `DAY3` → Repli DM → verified Day 3 learning page**

Configure and test delivery separately after the website is live. This repository change does not publish a Reel, send DMs or activate automation. Do not claim delivery works without an end-to-end test.

## 🔐 Content quality and privacy

- Human review of factual claims and learning materials before public release.
- No sensitive credentials, private voice recordings or unpublished production files in this public repository.
- No analytics scripts, contact forms or collection of personal data in the current static pages.
- Original writing and visuals only, with appropriate licences and attributions for external assets.
- AI-generated responses can be mistaken; important information should be independently checked.

## 🧭 Project status

**Days 1 and 2:** existing lesson pages preserved.  
**Day 3:** comprehensive embeddings guide prepared on a feature branch for review.  
**Release:** creator approval required before merge; deployment verification follows the merge.  
**Day 3 coverage:** vectors and embeddings, token versus sentence representations, illustrative semantic maps, search, worked cosine similarity, engineering considerations, glossary, six quiz questions and fourteen interview answers.

This repository is independent of the private/local AI video-production studio and the creator's personal portfolio.

---

<div align="center">

**Made with care for curious minds. 💗**

Follow **[@beyondaiwithlaki](https://www.instagram.com/beyondaiwithlaki/)** for simple, practical AI education.

</div>

