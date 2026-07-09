# App Mafia Course Transcripts

Text transcripts of the **[App Mafia — 0 to $100k Course](https://whop.com/joined/appmafia/courses-EvnQidFnfcQ9K7/app/courses/cors_HU0XWmy7QlYiv/)** on Whop, extracted from each video's English captions.

This is **not** a set of personal notes. It's the course recordings as searchable text so you (or an AI agent) can look up a lesson, answer a targeted question, or RAG over the material without scrubbing through video.

**Course:** [whop.com/joined/appmafia/…](https://whop.com/joined/appmafia/courses-EvnQidFnfcQ9K7/app/courses/cors_HU0XWmy7QlYiv/)

**59 video transcripts** across **5 modules**. Lesson numbers jump in a few places (`06`, `11`, `14`, `23`) because those course items were non-video (docs/text) and have no captions.

---

## Quick start (for humans & agents)

| Goal                                                           | Open this                                                                                  |
| -------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| Learn a **specific** topic (e.g. Meta/Instagram ads dashboard) | The matching lesson `.md` from the index below — **not** the combined doc                  |
| Find which lesson covers a topic                               | Course map + full index below, or `[transcripts/manifest.json](transcripts/manifest.json)` |
| Grep / RAG across the **entire** course                        | `[transcripts/ALL_TRANSCRIPTS.md](transcripts/ALL_TRANSCRIPTS.md)`                         |
| Plain text only (no markdown chrome)                           | matching `transcripts/*.txt`                                                               |
| Timestamped lines (`[mm:ss] text`)                             | matching `transcripts/*.timestamped.txt`                                                   |
| Raw subtitle cues                                              | matching `captions/*.vtt`                                                                  |

**Default:** open the single lesson `.md` for the topic.  
**Only use `ALL_TRANSCRIPTS.md`** when you truly need the whole course in one pass (broad search, full-course RAG). For targeted questions — Meta ads setup, Superwall, ASO, influencer outreach, etc. — the specific lesson is better: less noise, clearer context, faster answers.

---

## Repo layout

```
captions/                 # Raw WebVTT subtitle files (one per video)
transcripts/              # Human-readable exports
  ALL_TRANSCRIPTS.md      # Every lesson transcript concatenated
  manifest.json           # Machine-readable index (ids, titles, paths, durations)
  NN-Title-lesn_….md      # Markdown transcript (best for reading)
  NN-Title-lesn_….txt     # Plain text transcript
  NN-Title-lesn_….timestamped.txt
README.md
```

Filename pattern:

```
{index:02d}-{slug}-{lessonId}.{ext}
```

Example: `03-1-0-0-Case-Studies-lesn_13nQVvbwh1DWP4aLppSyrh.md`

---

## Course map (what each section is for)

| Module               | Theme                    | What these transcripts cover                                                                                                            |
| -------------------- | ------------------------ | --------------------------------------------------------------------------------------------------------------------------------------- |
| **0 — Introduction** | Orientation              | Who App Mafia is, course intent, recommended tech stack                                                                                 |
| **1 — Ideation**     | Finding the app idea     | Case studies, idea vs execution, psychology, problem discovery via social, competitive analysis, locking the idea                       |
| **2 — Design**       | Turning the idea into UI | Figma, wireframes, hiring designers, primary/secondary actions, onboarding + paywalls, brand, viral design                              |
| **3 — Development**  | Building the iOS app     | Learn vs hire, SwiftUI stack, Apple/Xcode setup, AI prompting, rebuild walkthrough (Cal AI), paywalls (Superwall), attribution (Adjust) |
| **4 — Distribution** | Getting users & revenue  | Channel trade-offs, virality, influencer marketing, organic growth, paid ads (Meta etc.), creatives, attribution, ASO, X, Reddit        |

### Module 4 subunits (distribution is large)

| Unit    | Focus                                                                  |
| ------- | ---------------------------------------------------------------------- |
| `4.0.x` | Channel overview + social virality                                     |
| `4.1.x` | Influencer marketing end-to-end                                        |
| `4.2.x` | Organic / content accounts                                             |
| `4.3.x` | Paid acquisition (campaigns, creatives, attribution, Apple Search Ads) |
| `4.4.x` | ASO + X + Reddit                                                       |

---

## Full lesson index

Paths below are relative to the repo root. Open the `.md` link to read that lesson.

### Module 0 — Introduction

| #   | Lesson         | Duration | Transcript                                                                                                                     |
| --- | -------------- | -------- | ------------------------------------------------------------------------------------------------------------------------------ |
| 01  | Intro          | 5m33s    | `[transcripts/01-Intro-lesn_1wJkWdHiRKYWtk3dBH0Vdr.md](transcripts/01-Intro-lesn_1wJkWdHiRKYWtk3dBH0Vdr.md)`                   |
| 02  | Our Tech Stack | 4m53s    | `[transcripts/02-Our-Tech-Stack-lesn_68627CjjxtSWTVBspVQ4ZL.md](transcripts/02-Our-Tech-Stack-lesn_68627CjjxtSWTVBspVQ4ZL.md)` |

### Module 1 — Ideation

| #   | Lesson                                | Duration | Transcript                                                                                                                                                           |
| --- | ------------------------------------- | -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 03  | 1.0.0 — Case Studies                  | 20m43s   | `[transcripts/03-1-0-0-Case-Studies-lesn_13nQVvbwh1DWP4aLppSyrh.md](transcripts/03-1-0-0-Case-Studies-lesn_13nQVvbwh1DWP4aLppSyrh.md)`                               |
| 04  | 1.0.1 — Idea vs Execution             | 19m01s   | `[transcripts/04-1-0-1-Idea-vs-Execution-lesn_3HTSgX6ZwnaRntU4qAQeSi.md](transcripts/04-1-0-1-Idea-vs-Execution-lesn_3HTSgX6ZwnaRntU4qAQeSi.md)`                     |
| 05  | 1.0.2 — Human Psychology              | 14m21s   | `[transcripts/05-1-0-2-Human-Psychology-lesn_6OuPvkCpyJfU9MRLe93a2r.md](transcripts/05-1-0-2-Human-Psychology-lesn_6OuPvkCpyJfU9MRLe93a2r.md)`                       |
| 07  | 1.1.0 — Solve Your Problems           | 18m28s   | `[transcripts/07-1-1-0-Solve-Your-Problems-lesn_4cVbw2vGvf84JywUtuwUcN.md](transcripts/07-1-1-0-Solve-Your-Problems-lesn_4cVbw2vGvf84JywUtuwUcN.md)`                 |
| 08  | 1.1.1 — Instagram and TikTok — Part 1 | 6m55s    | `[transcripts/08-1-1-1-Instagram-and-TikTok-Part-1-lesn_1NsMzXlj6e0KiKtxBPDJ6N.md](transcripts/08-1-1-1-Instagram-and-TikTok-Part-1-lesn_1NsMzXlj6e0KiKtxBPDJ6N.md)` |
| 09  | 1.1.1 — Instagram and TikTok — Part 2 | 26m46s   | `[transcripts/09-1-1-1-Instagram-and-TikTok-Part-2-lesn_5g7DOLTE9UD8BvksDxgTqt.md](transcripts/09-1-1-1-Instagram-and-TikTok-Part-2-lesn_5g7DOLTE9UD8BvksDxgTqt.md)` |
| 10  | 1.1.2 — Reddit and X                  | 15m29s   | `[transcripts/10-1-1-2-Reddit-and-X-lesn_4AUs1porzdesNtKdS7CFlp.md](transcripts/10-1-1-2-Reddit-and-X-lesn_4AUs1porzdesNtKdS7CFlp.md)`                               |
| 12  | 1.2.0 — Competitive Analysis          | 15m48s   | `[transcripts/12-1-2-0-Competitive-Analysis-lesn_3IKajcgsR8zdhTQaAIAwau.md](transcripts/12-1-2-0-Competitive-Analysis-lesn_3IKajcgsR8zdhTQaAIAwau.md)`               |
| 13  | 1.2.1 — Finalizing Your Idea          | 15m10s   | `[transcripts/13-1-2-1-Finalizing-Your-Idea-lesn_4ViLMRQQF7jR1lL7NQfcVm.md](transcripts/13-1-2-1-Finalizing-Your-Idea-lesn_4ViLMRQQF7jR1lL7NQfcVm.md)`               |

### Module 2 — Design

| #   | Lesson                              | Duration | Transcript                                                                                                                                                       |
| --- | ----------------------------------- | -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 15  | 2.0.0 — Figma Inspiration           | 13m46s   | `[transcripts/15-2-0-0-Figma-Inspiration-lesn_lH7PBZdxL4yTMVZac01ja.md](transcripts/15-2-0-0-Figma-Inspiration-lesn_lH7PBZdxL4yTMVZac01ja.md)`                   |
| 16  | 2.0.1 — Wireframing                 | 22m22s   | `[transcripts/16-2-0-1-Wireframing-lesn_3YT85MbLlM5fypbvBtLKxz.md](transcripts/16-2-0-1-Wireframing-lesn_3YT85MbLlM5fypbvBtLKxz.md)`                             |
| 17  | 2.0.2 — Hiring a Designer           | 9m46s    | `[transcripts/17-2-0-2-Hiring-a-Designer-lesn_4oM2DTo1pVf5fCvVgb9zqc.md](transcripts/17-2-0-2-Hiring-a-Designer-lesn_4oM2DTo1pVf5fCvVgb9zqc.md)`                 |
| 18  | 2.1.0 — Primary & Secondary Actions | 23m16s   | `[transcripts/18-2-1-0-Primary-Secondary-Actions-lesn_6IDO7cEm84yUAFdNUzb5FS.md](transcripts/18-2-1-0-Primary-Secondary-Actions-lesn_6IDO7cEm84yUAFdNUzb5FS.md)` |
| 19  | 2.1.1 — Onboarding and Paywalls     | 20m45s   | `[transcripts/19-2-1-1-Onboarding-and-Paywalls-lesn_kH6lvtlkIKTRlPjhnp1y9.md](transcripts/19-2-1-1-Onboarding-and-Paywalls-lesn_kH6lvtlkIKTRlPjhnp1y9.md)`       |
| 20  | 2.2.0 — Brand Aesthetics            | 21m42s   | `[transcripts/20-2-2-0-Brand-Aeshetics-lesn_2CuQxkFAacnsD6VRxeFxUe.md](transcripts/20-2-2-0-Brand-Aeshetics-lesn_2CuQxkFAacnsD6VRxeFxUe.md)`                     |
| 21  | 2.2.1 — Viral Design                | 6m10s    | `[transcripts/21-2-2-1-Viral-Design-lesn_41qLwvkZ3vJaQEHJ4XFdU6.md](transcripts/21-2-2-1-Viral-Design-lesn_41qLwvkZ3vJaQEHJ4XFdU6.md)`                           |
| 22  | 2.X — Viral App Design              | 63m06s   | `[transcripts/22-2-X-Viral-App-Design-lesn_6bBiEDcobz7UiCOCWiLEaF.md](transcripts/22-2-X-Viral-App-Design-lesn_6bBiEDcobz7UiCOCWiLEaF.md)`                       |

### Module 3 — Development

| #   | Lesson                                 | Duration | Transcript                                                                                                                                                             |
| --- | -------------------------------------- | -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 24  | 3.0.0 — Intro to Development           | 1m16s    | `[transcripts/24-3-0-0-Intro-to-Development-lesn_6CGCEGtPGpRkb8Av4HmA4a.md](transcripts/24-3-0-0-Intro-to-Development-lesn_6CGCEGtPGpRkb8Av4HmA4a.md)`                 |
| 25  | 3.0.1 — Should you learn to code?      | 2m16s    | `[transcripts/25-3-0-1-Should-you-learn-to-code-lesn_6YBxgeFSGuHhiIpcDY2A1Q.md](transcripts/25-3-0-1-Should-you-learn-to-code-lesn_6YBxgeFSGuHhiIpcDY2A1Q.md)`         |
| 26  | 3.0.2 — Hiring a developer             | 7m05s    | `[transcripts/26-3-0-2-Hiring-a-developer-lesn_4JK5d1cLRVyJXaLIVlJdOk.md](transcripts/26-3-0-2-Hiring-a-developer-lesn_4JK5d1cLRVyJXaLIVlJdOk.md)`                     |
| 27  | 3.1.1 — Languages and Frameworks       | 2m08s    | `[transcripts/27-3-1-1-Languages-and-Frameworks-lesn_5fRSXGm1ihFN6HmFyHFOUO.md](transcripts/27-3-1-1-Languages-and-Frameworks-lesn_5fRSXGm1ihFN6HmFyHFOUO.md)`         |
| 28  | 3.2.0 — Setting up Apple Developer     | 1m00s    | `[transcripts/28-3-2-0-Setting-up-Apple-Developer-lesn_1G2OPYNCEphjqsRqPrQhC5.md](transcripts/28-3-2-0-Setting-up-Apple-Developer-lesn_1G2OPYNCEphjqsRqPrQhC5.md)`     |
| 29  | 3.2.1 — Setting up Xcode               | 3m13s    | `[transcripts/29-3-2-1-Setting-up-Xcode-lesn_5C9Qdxn35X8U7xksDQAMha.md](transcripts/29-3-2-1-Setting-up-Xcode-lesn_5C9Qdxn35X8U7xksDQAMha.md)`                         |
| 30  | 3.2.2 — Core Tech Stack and Setup      | 1m56s    | `[transcripts/30-3-2-2-Core-Tech-Stack-and-Setup-lesn_75VUi63KGLXrVtVjXyMuwX.md](transcripts/30-3-2-2-Core-Tech-Stack-and-Setup-lesn_75VUi63KGLXrVtVjXyMuwX.md)`       |
| 31  | 3.3.0 — App architecture               | 1m00s    | `[transcripts/31-3-3-0-App-architecture-lesn_34mbFTxdn0SVe6BwtCtLBc.md](transcripts/31-3-3-0-App-architecture-lesn_34mbFTxdn0SVe6BwtCtLBc.md)`                         |
| 32  | 3.3.1 — Prompting AI                   | 3m19s    | `[transcripts/32-3-3-1-Prompting-AI-lesn_6amGsYQrNFH4vbbvmCiqOE.md](transcripts/32-3-3-1-Prompting-AI-lesn_6amGsYQrNFH4vbbvmCiqOE.md)`                                 |
| 33  | 3.3.2 — Core Features                  | 5m38s    | `[transcripts/33-3-3-2-Core-Features-lesn_5sGCDWZPHvDCUY6ap7M3bz.md](transcripts/33-3-3-2-Core-Features-lesn_5sGCDWZPHvDCUY6ap7M3bz.md)`                               |
| 34  | 3.3.3 — Rebuilding Cal AI              | 19m17s   | `[transcripts/34-3-3-3-Rebuilding-Cal-AI-lesn_bSMkqkpZ6J8cGJcTtLkXC.md](transcripts/34-3-3-3-Rebuilding-Cal-AI-lesn_bSMkqkpZ6J8cGJcTtLkXC.md)`                         |
| 35  | 3.3.4 — Onboarding and Questions       | 8m12s    | `[transcripts/35-3-3-4-Onboarding-and-Questions-lesn_6qzpPAzLJE101FD8AJtdJW.md](transcripts/35-3-3-4-Onboarding-and-Questions-lesn_6qzpPAzLJE101FD8AJtdJW.md)`         |
| 36  | 3.3.5 — Paywall and Access             | 19m28s   | `[transcripts/36-3-3-5-Paywall-and-Access-lesn_30r8aIhPG6XxaSiS06EAAR.md](transcripts/36-3-3-5-Paywall-and-Access-lesn_30r8aIhPG6XxaSiS06EAAR.md)`                     |
| 37  | 3.3.6 — Optimizations + Revenue Levers | 22m16s   | `[transcripts/37-3-3-6-Optimizations-Revenue-Levers-lesn_7BBMAKJUyVgjYSVVFcuqNO.md](transcripts/37-3-3-6-Optimizations-Revenue-Levers-lesn_7BBMAKJUyVgjYSVVFcuqNO.md)` |
| 38  | 3.4.0 — Mastering Superwall            | 23m16s   | `[transcripts/38-3-4-0-Mastering-Superwall-lesn_463y4d1ZBBthloUM7D4jV2.md](transcripts/38-3-4-0-Mastering-Superwall-lesn_463y4d1ZBBthloUM7D4jV2.md)`                   |
| 39  | 3.4.1 — Mastering Adjust               | 8m17s    | `[transcripts/39-3-4-1-Mastering-Adjust-lesn_EryAIFDRSks4xsNBZsepV.md](transcripts/39-3-4-1-Mastering-Adjust-lesn_EryAIFDRSks4xsNBZsepV.md)`                           |

### Module 4 — Distribution

| #   | Lesson                                             | Duration | Transcript                                                                                                                                                                                         |
| --- | -------------------------------------------------- | -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 40  | 4.0.0 — Distribution channels and their trade-offs | 8m40s    | `[transcripts/40-4-0-0-Distribution-channels-and-their-trade-offs-lesn_1GEaah6M1s2MbDKvED3382.md](transcripts/40-4-0-0-Distribution-channels-and-their-trade-offs-lesn_1GEaah6M1s2MbDKvED3382.md)` |
| 41  | 4.0.1 — Understanding social media virality        | 9m33s    | `[transcripts/41-4-0-1-Understanding-social-media-virality-lesn_IjVZiQFcwafLuVMpDusNG.md](transcripts/41-4-0-1-Understanding-social-media-virality-lesn_IjVZiQFcwafLuVMpDusNG.md)`                 |
| 42  | 4.1.0 — Influencer Marketing Case Studies          | 10m36s   | `[transcripts/42-4-1-0-Influencer-Marketing-Case-Studies-lesn_6tfAeXTa1DawcOZ72Nm9xT.md](transcripts/42-4-1-0-Influencer-Marketing-Case-Studies-lesn_6tfAeXTa1DawcOZ72Nm9xT.md)`                   |
| 43  | 4.1.1 — What is Influencer Marketing?              | 2m36s    | `[transcripts/43-4-1-1-What-is-Influencer-Marketing-lesn_3rcxialsMs0Ccqy904dBjr.md](transcripts/43-4-1-1-What-is-Influencer-Marketing-lesn_3rcxialsMs0Ccqy904dBjr.md)`                             |
| 44  | 4.1.2 — How to Source Influencers                  | 8m37s    | `[transcripts/44-4-1-2-How-to-Source-Influencers-lesn_FalepqckBKY0Gdg9NiezZ.md](transcripts/44-4-1-2-How-to-Source-Influencers-lesn_FalepqckBKY0Gdg9NiezZ.md)`                                     |
| 45  | 4.1.3 — Outreach & Messaging                       | 10m58s   | `[transcripts/45-4-1-3-Outreach-Messaging-lesn_ZtgrzHW4ww2RHvmiogLay.md](transcripts/45-4-1-3-Outreach-Messaging-lesn_ZtgrzHW4ww2RHvmiogLay.md)`                                                   |
| 46  | 4.1.4 — Negotiations                               | 16m34s   | `[transcripts/46-4-1-4-Negotiations-lesn_2MRaEbC1Aa578NCwXb0yiu.md](transcripts/46-4-1-4-Negotiations-lesn_2MRaEbC1Aa578NCwXb0yiu.md)`                                                             |
| 47  | 4.1.5 — Management + Tracking Influencers          | 4m37s    | `[transcripts/47-4-1-5-Management-Tracking-Influencers-lesn_6vZupEgyy3lW97VwNoxW6I.md](transcripts/47-4-1-5-Management-Tracking-Influencers-lesn_6vZupEgyy3lW97VwNoxW6I.md)`                       |
| 48  | 4.1.6 — Theme Pages                                | 3m39s    | `[transcripts/48-4-1-6-Theme-Pages-lesn_1hJ6qbY5xLKTwuJ8sbkAmc.md](transcripts/48-4-1-6-Theme-Pages-lesn_1hJ6qbY5xLKTwuJ8sbkAmc.md)`                                                               |
| 49  | 4.2.0 — Organic Case Studies                       | 9m46s    | `[transcripts/49-4-2-0-Organic-Case-Studies-lesn_1YK9Btpm0cY6oyhkltV5Ra.md](transcripts/49-4-2-0-Organic-Case-Studies-lesn_1YK9Btpm0cY6oyhkltV5Ra.md)`                                             |
| 50  | 4.2.1 — Types of Organic                           | 17m15s   | `[transcripts/50-4-2-1-Types-of-Organic-lesn_3sDvpunmmg1BDwcUALYvFo.md](transcripts/50-4-2-1-Types-of-Organic-lesn_3sDvpunmmg1BDwcUALYvFo.md)`                                                     |
| 51  | 4.2.2 — Account Creation                           | 1m17s    | `[transcripts/51-4-2-2-Account-Creation-lesn_n9FcELeAKiAOfe4qOz586.md](transcripts/51-4-2-2-Account-Creation-lesn_n9FcELeAKiAOfe4qOz586.md)`                                                       |
| 52  | 4.2.3 — Warming up Accounts                        | 5m33s    | `[transcripts/52-4-2-3-Warming-up-Accounts-lesn_2oaFGeST0BE8pZv2c6B3R5.md](transcripts/52-4-2-3-Warming-up-Accounts-lesn_2oaFGeST0BE8pZv2c6B3R5.md)`                                               |
| 53  | 4.3.0 — Case Studies (paid)                        | 6m18s    | `[transcripts/53-4-3-0-Case-Studies-lesn_I7V0YSXayiiXUelboZgor.md](transcripts/53-4-3-0-Case-Studies-lesn_I7V0YSXayiiXUelboZgor.md)`                                                               |
| 54  | 4.3.1 — Different Channels                         | 7m07s    | `[transcripts/54-4-3-1-Different-Channels-lesn_2gNmGezE6wrzHTRfdIcUQj.md](transcripts/54-4-3-1-Different-Channels-lesn_2gNmGezE6wrzHTRfdIcUQj.md)`                                                 |
| 55  | 4.3.2 — High Level Heuristics                      | 9m08s    | `[transcripts/55-4-3-2-High-Level-Heuristics-lesn_1zfbBWpHHnEYlK8zldeWwy.md](transcripts/55-4-3-2-High-Level-Heuristics-lesn_1zfbBWpHHnEYlK8zldeWwy.md)`                                           |
| 56  | 4.3.3 — Campaign structure                         | 38m33s   | `[transcripts/56-4-3-3-Campaign-structure-lesn_3N07IgiLQPYESwUiHNJUdj.md](transcripts/56-4-3-3-Campaign-structure-lesn_3N07IgiLQPYESwUiHNJUdj.md)`                                                 |
| 57  | 4.3.4 — Creative Fatigue                           | 2m29s    | `[transcripts/57-4-3-4-Creative-Fatigue-lesn_1gkVISr6qCWrak6JmxLZMh.md](transcripts/57-4-3-4-Creative-Fatigue-lesn_1gkVISr6qCWrak6JmxLZMh.md)`                                                     |
| 58  | 4.3.5 — Creatives                                  | 25m04s   | `[transcripts/58-4-3-5-Creatives-lesn_6AFkTmVMp0z7SROc3QdQRt.md](transcripts/58-4-3-5-Creatives-lesn_6AFkTmVMp0z7SROc3QdQRt.md)`                                                                   |
| 59  | 4.3.6 — Attribution                                | 15m34s   | `[transcripts/59-4-3-6-Attribution-lesn_2wLuVmEFqazubVb49SpY3w.md](transcripts/59-4-3-6-Attribution-lesn_2wLuVmEFqazubVb49SpY3w.md)`                                                               |
| 60  | 4.3.7 — Apple Search Ads                           | 6m49s    | `[transcripts/60-4-3-7-Apple-Search-Ads-lesn_3VkyR2ao48WCtyYskjs2MP.md](transcripts/60-4-3-7-Apple-Search-Ads-lesn_3VkyR2ao48WCtyYskjs2MP.md)`                                                     |
| 61  | 4.4.0 — ASO                                        | 16m44s   | `[transcripts/61-4-4-0-ASO-lesn_4fUQAuH2OC7fviLJQ7YW3Y.md](transcripts/61-4-4-0-ASO-lesn_4fUQAuH2OC7fviLJQ7YW3Y.md)`                                                                               |
| 62  | 4.4.1 — x.com marketing                            | 9m56s    | `[transcripts/62-4-4-1-x-com-marketing-lesn_28bqH1KqUWQeuziWXuvFz.md](transcripts/62-4-4-1-x-com-marketing-lesn_28bqH1KqUWQeuziWXuvFz.md)`                                                         |
| 63  | 4.4.2 — Reddit Marketing                           | 11m06s   | `[transcripts/63-4-4-2-Reddit-Marketing-lesn_12zFdK1AZ5UDI5zDqVuLiE.md](transcripts/63-4-4-2-Reddit-Marketing-lesn_12zFdK1AZ5UDI5zDqVuLiE.md)`                                                     |

---

## Agent notes

- Start with this README + `manifest.json` to route to the right lesson; don't scrape Whop unless asked.
- For a targeted ask (e.g. “how do I set up the Meta/Instagram ads dashboard?”), open the specific lesson (here: `56` Campaign structure, plus nearby `4.3.x` paid lessons) — do **not** dump `ALL_TRANSCRIPTS.md` into context.
- Use `ALL_TRANSCRIPTS.md` only for broad cross-course search or full-course RAG.
- Content is caption-derived speech-to-text — expect occasional ASR typos.
- These are transcripts of the course recordings for agent/human lookup — not personal notes, and not a redistribution of the paid videos.
- Official course (membership required): [App Mafia on Whop](https://whop.com/joined/appmafia/courses-EvnQidFnfcQ9K7/app/courses/cors_HU0XWmy7QlYiv/).
