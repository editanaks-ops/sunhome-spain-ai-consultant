# SunHome Spain — AI Property Consultant

An AI consultant that helps Russian-speaking buyers choose property in Spain — for holidays, relocation or investment — and hands a qualified lead to a human specialist.

Built on a structured knowledge base and a consultation script. No code: the whole product is prompt design, knowledge design and dialogue logic.

> SunHome Spain is a demo brand created for this project. The structure transfers to any real agency: replace the knowledge base, keep the logic.

## What it does

1. **Greets and qualifies.** Asks 2–4 short questions — purpose, budget, lifestyle priorities, timeline. Never more than four at once, so it reads as a conversation, not a form.
2. **Presents a personal recommendation.** Names 1–3 suitable regions and property types, explains why they fit this client, and shows how the agency helps at each stage.
3. **Flags the real cost.** Always reminds the client to add 10–15% on top of the price for taxes, notary and registration — and does the maths for their budget.
4. **Answers follow-up questions** from the knowledge base only: NIE, buying remotely, mortgages for non-residents, rental licences, new build vs resale.
5. **Hands over.** Ends with a concrete next step — a shortlist of properties or a call with a regional specialist.

## Guardrails

The consultant never promises guaranteed rental yield, never gives a legal opinion, never invents properties, addresses or prices, and never states exact taxes without checking the specific deal. When the knowledge base has no answer, it says so and refers the client to a specialist.

## Example

A family with a budget of €220,000 wants a flat near the sea for summers and occasional rental. The consultant recommends Orihuela Costa or Alicante, explains the trade-off between new builds and resale at that budget, calculates the extra €22,000–33,000 in purchase costs, and offers a side-by-side shortlist of three new-build and three resale options.

Full conversation: [demo_dialogue.md](demo_dialogue.md)

## Files

| File | What it is |
|---|---|
| [knowledge_base_sunhome_spain.txt](knowledge_base_sunhome_spain.txt) | Knowledge base: regions, budgets, purchase stages, FAQ, tone and limits (RU) |
| [technical_specification_sunhome_spain.txt](technical_specification_sunhome_spain.txt) | System prompt and dialogue logic for Google AI Studio or Bolt (RU) |
| [demo_dialogue.md](demo_dialogue.md) | Test conversation with the consultant (RU) |
| [skill/](skill/) | The same consultant packaged as a SKILL.md skill for Claude Code, Codex, Cursor and other agents |

## Built with

Google AI Studio (Gemini) · prompt engineering · knowledge-base design · client profiling · consultation scripting

## Adapting it for your business

The approach works for any service where clients need guidance before they buy: real estate, relocation, clinics, education, tourism. What changes is the knowledge base and the qualifying questions; the structure — qualify, recommend, warn, answer, hand over — stays.

## Author

**Edita Näks Skylstad** — AI Content Creator, prompt engineering and AI assistants.
Russian · Norwegian · English.
