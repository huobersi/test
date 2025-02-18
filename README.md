| **Query-String** | **Beschreibung** | **Erwartete Antwort** |
|------------------|-----------------|------------------------|
| `?category=men's clothing&price<50&rating.rate>3` | Günstige Herrenbekleidung unter **50€** mit Bewertung **über 3 Sterne** | 2 Produkte (T-Shirts - 22.3€, Jacke - 55.99€ ❌ wegen Preis) |
| `?category=jewelery&rating.count>300&price>500` | Hochpreisiger Schmuck mit **vielen Bewertungen (>300)** | 1 Produkt (John Hardy Armband - 695€, 400 Bewertungen) |
| `?rating.rate>4&price<60&category=men's clothing` | Gut bewertete Herrenbekleidung unter **60€** | 2 Produkte (Jacke - 55.99€, T-Shirts - 22.3€) |
| `?price>100&rating.rate<4` | Teure Produkte **über 100€**, aber schlecht bewertet **(<4 Sterne)** | 1 Produkt (Rucksack - 109.95€, 3.9 Sterne ❌ knapp daneben) |
