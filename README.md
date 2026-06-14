# 🛡️ Insurance Sales Dashboard with Power BI

Projekt przedstawia dashboard sprzedażowy przygotowany w Power BI dla fikcyjnej agencji ubezpieczeniowej **Polisfera** działającej na terenie Polski.

Raport pokazuje analizę sprzedaży polis ubezpieczeniowych oraz powiązanych KPI na dwóch poziomach:

* **strategicznym** — strona `Executive Summary`,
* **menedżerskim / operacyjnym** — strona `Sales - Management`.

Dane obejmują lata **2021–2025** i zostały wygenerowane z wykorzystaniem AI na potrzeby projektu portfolio. Projekt nie korzysta z rzeczywistych danych biznesowych.

> Interaktywny link Power BI Service nie jest dostępny z powodu ograniczeń konta Power BI Service.
> Z tego względu repozytorium zawiera zrzuty ekranu raportu w formacie PNG, dane źródłowe, dokumentację modelu danych oraz opis zastosowanych miar DAX.

---

## 📂 Zawartość repozytorium

Struktura repozytorium:

```text
Insurance-Sales-Dashboard/
│
├── report/
│   ├── Dashboard - 1st page.png
│   ├── Dashboard - 2nd page.png
│   └── Dashboard - Tooltip page (hidden).png
│
├── data/
│   ├── Dim_Agents.csv
│   ├── Dim_Branches.csv
│   ├── Dim_Customers.csv
│   ├── Dim_Date.csv
│   ├── Dim_Products.csv
│   ├── Dim_Sales_Channels.csv
│   ├── Fact_Policies.zip
│   ├── Fact_Premium_Payments.zip
│   └── Fact_Claims.zip
│
└── documentation/
    └── 📊 Dokumentacja raportu.docx
```

### `report/`

Folder zawiera zrzuty ekranu kolejnych stron raportu Power BI w formacie PNG.

Ze względu na rozmiar pliku `.pbix`, który przekracza limit uploadu GitHub, plik Power BI nie został dodany do repozytorium. Zamiast tego w folderze znajdują się screeny pokazujące końcowy wygląd raportu:

* `Dashboard - 1st page.png` — strona Executive Summary,
* `Dashboard - 2nd page.png` — strona Sales - Management,
* `Dashboard - Tooltip page (hidden).png` — ukryta strona tooltipa produktowego.

### `data/`

Folder zawiera dane źródłowe użyte do budowy raportu.

Dane zostały wygenerowane z wykorzystaniem AI i przedstawiają fikcyjny scenariusz sprzedaży polis ubezpieczeniowych w Polsce w latach 2021–2025.

Tabele wymiarów zapisano jako pliki CSV, natomiast większe tabele faktów zostały skompresowane do formatu ZIP ze względu na limity rozmiaru plików na GitHub.

### `documentation/`

Folder zawiera plik z dokumentacją projektu, która zawiera:

* opis modelu danych,
* opis stron raportu,
* listę najważniejszych miar DAX,
* wyjaśnienie zastosowanych funkcji i mechanizmów Power BI.

---


## 📌 Najważniejsze wnioski biznesowe

Na podstawie raportu można zauważyć, że:

* największy udział w sprzedaży mają wybrane kanały sprzedaży, przede wszystkim kanał agencyjny i online,
* sprzedaż jest skoncentrowana w kilku głównych grupach produktów,
* wyniki sprzedaży różnią się między regionami i województwami,
* porównanie YoY pozwala szybko ocenić, które obszary poprawiają wynik względem poprzedniego roku,
* ranking agentów według prowizji pomaga wskazać osoby generujące najwyższy koszt / wartość sprzedażową,
* analiza wariantów produktu według regionu pozwala porównać strukturę sprzedaży między regionami,
* udział w regionie % pokazuje znaczenie poszczególnych województw i oddziałów w ramach regionu.

---

## ⚙️ Użyte technologie

W projekcie wykorzystano:

* **Power BI Desktop** — budowa modelu danych, miar DAX oraz raportu,
* **Power Query** — przygotowanie i transformacja danych źródłowych,
* **DAX** — tworzenie miar analitycznych, KPI, obliczeń YTD, LY i YoY,
* **CSV** — format danych źródłowych,
* **GitHub** — publikacja projektu portfolio i dokumentacji,
* **AI-generated synthetic dataset** — wygenerowanie fikcyjnych danych źródłowych na potrzeby projektu.

---

## 📈 Przyszłe usprawnienia

Możliwe kierunki dalszego rozwoju projektu:

* opublikowanie interaktywnej wersji raportu w Power BI Service,
* dodanie osobnej strony do analizy szkód i szkodowości,
* rozbudowanie raportu o analizę retencji i odnowień polis,
* dodanie bardziej rozbudowanych tooltipów dla agentów, produktów i regionów,
* przygotowanie wersji anglojęzycznej raportu,
* dodanie dokumentacji procesu Power Query,
* rozbudowanie modelu o dodatkowe wskaźniki efektywności sprzedaży,
* przygotowanie krótkiego demo wideo pokazującego działanie raportu.

---

> ✨ Dziękuję za odwiedzenie repozytorium! Ten projekt jest częścią mojej drogi do świata profesjonalnej analizy danych. Zachęcam do kontaktu przez LinkedIn:[https://www.linkedin.com/in/patryk-dziebowski/)].
