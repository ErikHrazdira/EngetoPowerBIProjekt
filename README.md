# Analýza dat ze silového trojboje – Power BI Dashboard

Tento repozitář obsahuje interaktivní dashboard v Microsoft Power BI (.pbix), zaměřený na vizualizaci a analýzu výkonů v silovém trojboji s důrazem na datové modelování a pokročilé DAX výpočty.

## Co je to silový trojboj (Powerlifting)?
Základní kontext pro pochopení metrik v dashboardu:
* **Disciplíny:** Dřep, Benčpres a Mrtvý tah. Závodník má na každou 3 pokusy.
* **Total:** Součet nejlepších platných pokusů ze všech tří disciplín.
* **GL body:** Koeficient pro objektivní porovnání výkonnosti různě těžkých závodníků a napříč pohlavími.
* **Raw vs. Equip:** Dvě oddělené divize. V Raw divizi se zvedá s minimálním vybavením (opasek, nákoleníky), v Equip s podpůrnými kompresními dresy, které výrazně zvyšují výkon.

## Zdroj dat
Otevřená databáze [OpenPowerlifting.org](https://www.openpowerlifting.org). Dataset byl upraven a filtrován pouze na závodníky ČSST - Českého svazu silového trojboje.

## Struktura Dashboardu
Report je rozdělen do 3 částí s vlastní interaktivní navigací:
1. **Přehled:** Makro-data – vývoj počtu startů a závodníků, rozložení pohlaví a popularita váhových kategorií.
2. **Analýza:** Detailní pohled na výkony. Bodový graf (Total vs. tělesná váha) a sloupcový graf s průměrnými výkony v jednotlivých disciplínách vypočítaný pouze z nejvydařenějších závodů.
3. **Žebříček:** Tabulka pro vyhledávání nejlepších závodníků historie podle GL bodů.
