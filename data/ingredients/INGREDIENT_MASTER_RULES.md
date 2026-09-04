# Calyra Ingredient Master — Rules

This is the single global Ingredient Master for all Calyra meal categories.

## Source
Approved review decisions from:
- Śniadania I
- Śniadania II
- Obiad
- Podwieczorek
- Kolacja

## Rules
1. One shared global Ingredient Master.
2. No second ingredient database.
3. Never invent or silently rename canonical ingredients.
4. Source typos/variants belong in aliases.
5. Components are separate from simple ingredients and later belong to recipe/BOM logic.
6. LF = lactose-free variant attribute.
7. GF is separate only where explicitly approved.
8. WEGE substitutions are recipe-level logic.
9. No quantities, units, nutrition, allergens or IDs at identity-master stage.
10. `koncentrat pomidorowy` is canonical for earlier `przecier pomidorowy`.
11. Ambiguous generic strings are not forced into a master without context.
12. Audit existing Calyra ingredient data before migration.
13. Do not modify Calyra/Supabase/Lovable during the Master-only stage.
