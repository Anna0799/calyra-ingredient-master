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
14. `tłuszcz kokosowy` maps to `olej kokosowy` and is not a separate canonical identity.
15. `serek kanapkowy z oliwkami` is a simple ready-made spread cheese. `serek z oliwkami` is an alias, not a component.
16. `polędwica sopocka` is its own ingredient. `polędwica kostka` maps to it.
17. `buraczki ćwikła` is the approved Polish canonical simple name. It is separate from the component `sałatka z buraczków`.
18. `omlet gotowy` is not a final ingredient. Homemade omelet remains a component.

## Unresolved / needs context
Do not force these into a canonical ingredient:
- owoce
- olej
- warzyw
- kasza
- tortilla (plain)
- orzechy mielone
- ciastka okrągłe
- z naleśnika
- 005 almonds (title-only; not a BOM ingredient)
- `baton` (generic prepared product; too ambiguous for a canonical identity)
- any generic source string whose identity cannot be safely determined

Approved component identities may have blank EN/DE until an approved translation exists. Do not invent translations.
