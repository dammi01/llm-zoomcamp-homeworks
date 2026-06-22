# LLM Zoomcamp Homeworks

This repository contains my practical implementations and homework solutions for the **DataTalksClub LLM Zoomcamp 2026**.

## Tech Stack & Environment
* **Language:** Python 3.14
* **Package Manager:** `uv`
* **LLM Ecosystem:** Google GenAI SDK (`gemini-2.5-flash`)
* **Search Engine:** `minsearch`

## Key Technical Solutions
* **IPv4 Network Binding:** Configured `httpx.HTTPTransport` with explicit `local_address="0.0.0.0"` to bypass local IPv6 routing constraints.
* **Token Tracking:** Leveraged native `response.usage_metadata.prompt_token_count` to audit exact prompt payload costs.
