# Script to Budget

Codex agent skill for reading a whole screenplay, identifying production cost drivers, and creating a preliminary film budget PDF with traceable assumptions.

## How to use

1. Clone this repository or add it to your Codex skills directory. Read [SKILL.md](SKILL.md) for the full method.
2. Provide a screenplay in PDF, DOCX, FDX, Fountain, or TXT format. State the filming region, currency, intended scale, and any producer rate card you have.
3. Ask: “Use Script to Budget to estimate this screenplay.” Identify the preferred revision when several exist.
4. Review the scene ledger, schedule assumptions, department line items, low/base/high totals, exclusions, and cost-saving options.
5. Check major rates against current local quotes before using the PDF for a production decision. The estimate is a planning document, not a vendor bid.

The skill delivers an editable budget input JSON, scene ledger, and PDF. See [budget-schema.md](references/budget-schema.md) for the data format.
