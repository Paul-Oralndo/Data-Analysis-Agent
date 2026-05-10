# Data Analysis Agent (ChatGPT Custom GPT)
### Compact Instruction Set — v7

A professional-grade data analysis agent built as a 
ChatGPT Custom GPT. Designed for automated EDA, hybrid 
AutoML modeling, PII detection, leakage detection, and 
governance — with dynamic adaptation to Beginner, Expert, 
and Executive users.

---

## Key Capabilities

- Dynamic user expertise adaptation (Beginner / Expert / Executive)
- Two-mode automated EDA (Light and Full)
- Mandatory preprocessing pipeline before modeling
- Hybrid AutoML with self-correction fallback loop
- PII and sensitive field auto-detection
- Data leakage detection and categorization
- Uncertainty and confidence reporting on every model
- Multi-file handling (join, append, or separate analysis)
- Session context management
- Text intelligence via TF-IDF or embeddings
- Hardened confidentiality and security protection

---

## Tech Stack

- ChatGPT Custom GPT (GPT-4)
- Python (Pandas, Scikit-learn, TF-IDF)
- Logistic Regression, RandomForest, Ridge, Linear Regression
- One-hot, frequency, and target encoding strategies

---

## Example Output — Black Hole Effects Research

The agent was queried about black hole physics and produced
a full research presentation including data visualizations.

**Query used:**
> "What causes black holes? What are the effects near one?"

**Output includes:**
- Key concepts: gravity, tidal forces, orbital velocity
- Time dilation curve near event horizon
- Orbital instability growth simulation
- Evidence-based key takeaways

📄 [Research Presentation (PDF)](examples/black_hole_research_presentation.pdf)
📊 [Research Presentation (PowerPoint)](examples/black_hole_presentation.pptx)

> Grounding Score: High — all content retrieved from
> knowledge base, no hallucination detected

---

## Instruction Set

The agent is powered by a versioned, compact instruction 
set. See the full specification:

📄 [instructions/agent-instructions-v7.md](instructions/agent-instructions-v7.md)

---

## Version History

See [changelog.md](changelog.md) for full version history 
from v6C through v7.

---

## Design Highlights

**Self-Correction Loop** — automatically detects model 
failure and attempts a single structured fallback before 
stopping and explaining why.

**Executive Output Structure** — leads with conclusion, 
follows with evidence, ends with action. Never methodology first.

**Leakage Detection** — scans for post-event indicators 
and categorizes features as Safe, Suspicious, or High-risk 
before any modeling begins.

**Multi-File Handling** — detects shared keys, matching 
schemas, or structural differences and routes accordingly 
with row count validation.

---

## Author

Paul Orlando
Creative Technologist | AI Agent Developer | Data Analytics
🌐 [paulforlando.com](https://www.paulforlando.com)
