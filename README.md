# AI-102 · Microsoft Azure AI Engineer — Study Notes

> Personal study repository for **Microsoft Certified: Azure AI Engineer Associate** (Exam AI-102).
> **⚠️ Exam AI-102 was retired on 2026-06-30** — these notes are preserved for portfolio, Microsoft Foundry competency reference, and job-market currency.
> Source: [Microsoft Learn AI-102 Study Guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/ai-102)

---

## 📚 What's inside

| Type | Count | Purpose |
|---|---|---|
| **Main study guide** | 1 | 6 functional groups · weights · sub-skills · change log · Foundry architecture |
| **Index (MOC)** | 1 | Hub with note inventory + cross-vault connections |
| **Master mind map** | 1 | Mermaid mind map of the 6 functional groups |
| **Reference docs (crawled from Microsoft Learn)** | 10 | One note per official Microsoft Learn page — Foundry Tools, Foundry Models, Azure AI Search, etc. |
| **Total** | **13** | ~120 KB of focused study material |

All content is in **English** (per Microsoft Learn source). Mermaid diagrams render natively on GitHub. YAML frontmatter on every note.

---

## 🗂 Repository layout

```
AI102/
├── README.md                                          ← you are here
├── 00 - AI-102 Study Guide.md                          ← main hub (15 KB)
├── 00 - AI-102 Index.md                                ← MOC index
├── Module-Mind-Map.md                                  ← Mermaid master mind map
└── 01-Reference-Docs/                                  ← 10 Microsoft Learn pages
    ├── 01-Azure-AI-Services-Overview.md                (Microsoft Foundry umbrella)
    ├── 02-Azure-AI-Vision.md                           (Image analysis, OCR, custom vision)
    ├── 03-Azure-AI-Video-Indexer.md                    (Video insights, spatial analysis)
    ├── 04-Azure-AI-Language.md                         (Text Analytics, CLU, Q&A)
    ├── 05-Azure-AI-Speech.md                           (STT, TTS, translation, custom voice)
    ├── 06-Azure-AI-Search.md                           (Classic + agentic retrieval, knowledge store)
    ├── 07-Azure-OpenAI-Service.md                      (OpenAI models on Azure, Foundry Models pivot)
    ├── 08-Azure-AI-Document-Intelligence.md            (Form Recognizer → Document Intelligence)
    ├── 09-Plan-and-Prepare-Azure-AI-Development.md     (1-hour 9-unit training module)
    └── 10-Azure-AI-Engineer-Certification-Overview.md  (Cert page + retirement notice)
```

Each note follows a consistent shape:

```
YAML frontmatter (title / date / tags / exam / source / related)
↓
# Service Name + one-paragraph summary
↓
## Key Capabilities
## Common Use Cases
## Service Tiers / SKUs
## Key APIs / SDK Methods
## Connections to Other Services
## Exam-Relevant Notes          ← what an AI-102 candidate should know
## Visual (Mermaid)
## Source                        ← original + final URL (after redirects)
```

---

## 🎯 Exam at a glance

| Field | Value |
|---|---|
| **Exam code** | AI-102 |
| **Title** | Designing and Implementing a Microsoft Azure AI Solution |
| **Level** | Associate |
| **Product** | Microsoft Azure (Microsoft Foundry) |
| **Roles** | Azure AI Engineer · Data Engineer · AI Developer |
| **Status** | ⚠️ **Retired 2026-06-30** |
| **Pass score** | 700 / 1000 |
| **Renewal** | Annual (free online assessment) |
| **Last updated** | 2025-12-23 (final exam version) |

---

## 📊 Skills measured (6 functional groups)

| # | Functional group | Weight | Last updated |
|---|---|---|---|
| 1 | **Plan and manage an Azure AI solution** | **20–25%** | 2025-12-23 |
| 2 | **Implement generative AI solutions** | **15–20%** | 2025-12-23 |
| 3 | **Implement an agentic solution** | **5–10%** | 2025-12-23 (NEW) |
| 4 | **Implement computer vision solutions** | **10–15%** | 2025-12-23 |
| 5 | **Implement natural language processing solutions** | **15–20%** | 2025-12-23 |
| 6 | **Implement knowledge mining and information extraction** | **15–20%** | 2025-12-23 |

> Source: <https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/ai-102>

---

## ⚠️ Critical rebrand: "Cognitive Services" → "Foundry"

> All 10 reference doc URLs from the original study guide **redirect to new locations** as of 2026. The product family has been renamed **three times**:

```
Cognitive Services (2017)
       ↓
Azure AI Services (2023)
       ↓
Microsoft Foundry / Foundry Tools (2025)
       ↓
Foundry Models (separate brand for hosted LLMs, formerly Azure OpenAI Service)
```

| Old name | New name | Service |
|---|---|---|
| Cognitive Services → Computer Vision | **Azure AI Vision** in Foundry Tools | Image analysis, OCR |
| Cognitive Services → Language Understanding (LUIS) | **Azure AI Language** in Foundry Tools · **CLU** is the replacement (LUIS retired **2025-10-01**) | CLU, Q&A, Text Analytics |
| Cognitive Services → Speech | **Azure AI Speech** in Foundry Tools | STT, TTS, Translation |
| Cognitive Services → Form Recognizer | **Azure AI Document Intelligence** in Foundry Tools | Document extraction |
| Azure AI Video Indexer | **Azure AI Video Indexer** in Foundry Tools | Video insights |
| Azure AI Search | **Azure AI Search** in Foundry Tools | Cognitive Search |
| Azure AI Services (umbrella) | **Microsoft Foundry** (umbrella) | All of the above + Models + Agents + IQ |
| Azure OpenAI Service | **Foundry Models** (sold by Azure, with OpenAI pivot) | OpenAI GPT/DALL-E/embeddings |

> **★ Exam tip**: On the AI-102 exam, you will see all three brand names interchangeably. Know they refer to the same product family.

---

## 🛠 Exam-day reality (retired exam)

> **If you took AI-102 before 2026-06-30**: the certification is valid for **1 year from pass date**, then you must renew via free online assessment.
>
> **If you didn't take it**: the credential is no longer available. Microsoft's recommended successor is **Azure AI Foundry Engineer** (replacement cert not yet announced as of 2026-07-29 — watch the certification page).

For **portfolio + LinkedIn**, the AI-102 still demonstrates:
- Knowledge of the Microsoft Foundry ecosystem (the current production stack)
- Skills in 6 functional areas: Foundry planning, GenAI, Agentic, Vision, NLP, Knowledge Mining
- Familiarity with Azure-specific branding and SDK patterns

---

## 🚀 How to use

### Read on GitHub (fastest)
1. Start at [00 - AI-102 Study Guide.md](00%20-%20AI-102%20Study%20Guide.md) for the master index and skill map
2. Pick a reference doc → open the matching file in `01-Reference-Docs/`
3. Mermaid mind maps render inline. YAML frontmatter is preserved at the top of every note.

### Read in Obsidian (richest)
1. Clone or download as ZIP.
2. Open the folder as a vault in Obsidian (or copy the files into your existing vault).
3. Internal links become clickable cross-references; the graph view reveals the dependency structure.

### Use as exam prep
- For each functional group, read the [Study Guide section](00%20-%20AI-102%20Study%20Guide.md) → drill into each sub-skill → read the matching reference doc.
- Run the [official training module](01-Reference-Docs/09-Plan-and-Prepare-Azure-AI-Development.md) (1 hour, 9 units).
- Track your progress with the [Module-Mind-Map.md](Module-Mind-Map.md).

---

## 📎 Source references

- **Primary URL**: <https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/ai-102>
- **Microsoft Foundry umbrella**: <https://learn.microsoft.com/en-us/azure/foundry/>
- **Microsoft Q&A**: <https://learn.microsoft.com/en-us/answers/products/>
- **Tech Community (AI/ML)**: <https://techcommunity.microsoft.com/t5/ai-machine-learning/bd-p/MachineLearning>
- **The AI Show**: <https://learn.microsoft.com/en-us/shows/ai-show/>

---

<sub>Repository created 2026-07-29 · Crawled from Microsoft Learn official sources same day · All content adapted from a personal Obsidian vault snapshot · Microsoft Foundry / Foundry Tools branding reflects the current production stack (2026)</sub>
