# Calyra Ingredient Master Package

## Files
- `data/ingredients/ingredient_master.csv` — tabular master
- `data/ingredients/ingredient_master.json` — application-friendly master
- `data/ingredients/INGREDIENT_MASTER_RULES.md` — implementation rules

## Workflow
Master → audit existing Calyra data → explicit mapping → migration/import → validation.

Do not import blindly into Calyra/Lovable/Supabase.
