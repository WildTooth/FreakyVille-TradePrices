# Sådan bidrager du til filerne

## Regler

#### 1. Lad være med at ændre priserne til noget de ikke er. Dette vil blive tjekket uanset.
#### 2. Tilføj ikke items som deler navn med andre sjældne items. (F.eks. et head med navnet "Cactus" skal ikke tilføjes, da der er et item med samme navn)
#### - : Dette er grundet en fejl i måden det hele er sat op på. Når dette laves om, skal de heads nok blive tilføjet.
#### 3. Alle referencer til priser gøres som et heltal, altså et tal uden decimaler. Det vil sige at der ikke benyttes værdier, så som 6,7 diamond blocks eller 13 Stacks DBs. Disse ville i stedet været skrevet, 61 (for diamanterne) og 832 (for diamant blokkene).

## Værdiers Betydning?

#### 1. String[name]         | Dette beskriver itemmets display name.
#### 2. int[minPrice]        | Minimums værdien af et item.
#### 3. int[maxPrice]        | Maximums værdien af et item.
#### 4. boolean[isSkullItem] | Hvorvidt at der er tale om et head.
#### 5. boolean[isInBlocks]  | Beskriver hvorvidt at itemmets værdi skal regnes i dbs, eller diamanter.

## Eksempel på hvordan det korrekt ser ud

```csv
Diamond Sword,1,9,false,false
```

## Eksempel på hvad du ikke skal gøre

```csv
Dirt,10 Stacks,20 Stacks,true,false
```
