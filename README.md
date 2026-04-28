# generator-nahodnych-priserek

### 🧾 Popis programu: Generátor ASCII příšerek

Tento program slouží k vytváření náhodných ASCII příšerek, tedy jednoduchých obrázků složených ze znaků. Cílem bylo procvičit práci s knihovnami `random` a `time`, konkrétně funkce pro generování náhodných hodnot a vytváření časových prodlev.

Program nejprve uživatele přivítá a poté postupně generuje několik příšerek. Každá příšerka je složena ze tří částí – hlavy, těla a nohou. Tyto části jsou uloženy v seznamech, ze kterých se náhodně vybírá pomocí funkce `random.choice()`. Díky tomu je každá vygenerovaná příšerka unikátní.

Pro zpestření běhu programu jsou mezi jednotlivými kroky použity pauzy (`time.sleep()`), které vytvářejí dojem napětí, jako by se příšerka právě „tvořila“. Program využívá cyklus `for` pro opakované generování příšerek a podmínku `if` pro ošetření speciální situace na konci běhu.

Kód je rozdělen do přehledných částí a obsahuje komentáře, které vysvětlují jeho fungování. Program je jednoduchý, ale ukazuje základní principy práce s náhodou, časem a strukturou programu v Pythonu.


