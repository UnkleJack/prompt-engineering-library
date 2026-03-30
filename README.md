# Prompt Engineering Library
### by UnkleJack — Verified. Annotated. Sourced.

> *"Prompts decay. Models update. Nobody tracks this. We do."*

This repository is a curated collection of prompt engineering 
patterns, adversarial test cases, and composable templates 
across diverse domains. It exists to establish a public record 
of prior art — timestamped contributions that document the 
evolution of effective AI interaction patterns before they are 
absorbed, redacted, or co-opted. Provenance matters: every 
technique here carries a date and a lineage, asserting that 
thoughtful prompt design is both an emerging craft and a form 
of public knowledge worth preserving. The library is 
intentionally open and ungated; it grows through use, 
refinement, and the recognition that building reliable AI 
systems demands sharing what works without waiting for 
permission.

---

## Why provenance matters

Anyone can scrape prompts. That takes an afternoon.

You cannot scrape *verified annotation history.* You cannot 
clone the fact that a human ran it, on a specific model, on 
a specific date, and documented what actually came out vs 
what the prompt claimed it would do.

That's not a database. That's a body of work.

---

## Schema

Every entry follows this standard:

| Field | Description |
|---|---|
| `prompt_id` | Unique ID — e.g. PE-0001 |
| `title` | Descriptive name |
| `prompt_text` | The actual prompt |
| `technique` | Zero-shot / Few-shot / CoT / Chain / Meta / Role |
| `source_url` | Where it came from |
| `author_handle` | Attributed if known |
| `model_tested` | GPT-4o / Claude / Gemini etc |
| `date_captured` | When retrieved |
| `verified_output` | Human-run? Y/N + result note |

---

## Contributing

Found a high-signal prompt worth preserving?  
Fill the schema. Open a PR. That's it.

No slop. No "Top 10 ChatGPT prompts to make money" garbage.  
Signal only.

---

## The bigger picture

This library feeds a podcast, a newsletter, and a growing 
community studying how humans and AI actually communicate — 
and what happens when you get it right.

More at: [UnkleJack on GitHub](https://github.com/UnkleJack)

---

*Prior art established: March 2026*
