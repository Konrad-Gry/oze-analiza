Markdown
# Transformacja OZE w Polsce (2018–2024)

Prosty, interaktywny dashboard pokazujący, jak rozwijała się fotowoltaika i wiatr w Polsce oraz z jakimi problemami mierzy się teraz sieć (ujemne ceny prądu, wyłączanie OZE, kanibalizacja cenowa).

🔗 **Zobacz dashboard na żywo:** [konrad-gry.github.io/oze-analiza](https://konrad-gry.github.io/oze-analiza/)

---

### Co jest w środku?

* **Moduł A:** Wzrost mocy i produkcji energii z PV i wiatru na tle całego systemu.
* **Moduł B:** Problemy rynkowe: ujemne ceny na giełdzie, zjawisko capture rate i przymusowe odłączanie OZE przez PSE.
* **Moduł C:** Jakość danych: porównanie raportów PSE, URE i GUS oraz pokazanie różnic w ich liczeniu.

---

### Skąd są dane?

* **PSE** – bilanse mocy, generacja i redukcje OZE
* **URE i GUS** – moce zainstalowane
* **TGE** – ceny energii z rynku dnia następnego

---

### Jak to powstało?

Projekt zrealizowałem przy wsparciu **Claude (Anthropic)**:
* Zebrałem oficjalne raporty i dane źródłowe (PSE, URE, TGE).
* Claude pomógł mi ułożyć strukturę arkusza w Excelu, dobrać formuły i zweryfikować spójność liczb.
* Cały kod strony (HTML, CSS, JavaScript i wykresy SVG) wygenerowałem we współpracy z Claude, testując i dopasowując go tak, aby dashboard działał płynnie w przeglądarce bez żadnych zewnętrznych bibliotek.

---

**Konrad Grycner**  
Uniwersytet Ekonomiczny we Wrocławiu
