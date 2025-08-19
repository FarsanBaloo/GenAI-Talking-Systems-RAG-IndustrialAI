# GenAI-Talking-Systems-RAG-IndustrialAI

Här är en färdig, ren och professionell README som du kan använda rakt av för ditt projekt:

---

# GenAI-Talking-Systems-RAG-IndustrialAI

## Talking Systems – When AI Starts Understanding Industrial Machines

Proof-of-Concept AI agent built with **GenAI + Retrieval-Augmented Generation (RAG)** for industrial systems.
The agent connects directly to a **Siemens S7 PLC** via **OPC UA**, running fully on the edge to ensure data privacy and reliability.

---

## Project Overview

Industrial machines often communicate in cryptic error codes. Our goal was to make them “talk” in clear, natural language.
This system enables operators to troubleshoot issues without waiting for technical experts, reducing downtime and improving efficiency.

**Key features:**

* Root cause analysis from real-time PLC error messages
* Suggested fixes with step-by-step instructions
* Interactive Q\&A for maintenance and diagnostics
* Domain-grounded answers via RAG (no hallucinations)
* Runs locally on edge hardware, no data leaves the factory floor

---

## Tech Stack

* LangChain – orchestration of LLM + RAG pipeline
* Large Language Model – local, edge-deployed
* OPC UA – communication with Siemens S7 PLC
* FESTO CP-Factory – evaluation environment
* Python – glue logic and data handling

---

## Evaluation

We tested in a smart factory lab (FESTO CP-Factory) with real operators.
Results showed that even non-technical users could resolve machine issues with AI guidance – as if they had a virtual expert on-site.

---

## Applications

* Industrial Technical Support – automated troubleshooting
* Field Service – on-site, offline support with edge AI
* Sales & Product Selection – natural language guidance
* Smart Factories – reducing downtime, boosting resilience

---

## Team

Developed as part of the Mälardalen University (MDU) – Applied AI Programme, 2025.

Contributors:

* Rickard Sörlin
* Pea Andersson
* Fredrik Karlsson
* Azad Karimi

---

## License

MIT License (or whichever you prefer).

---

Vill du att jag gör en **kort README-mall** för dina labbar också (så att de blir enhetliga men enklare, typ titel + kort beskrivning + kursnamn)?
