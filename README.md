# 🛡️ Insurance Sales Dashboard with Power BI

Projekt przedstawia dashboard sprzedażowy przygotowany w Power BI dla fikcyjnej agencji ubezpieczeniowej **Polisfera** działającej na terenie Polski.

Raport pokazuje analizę sprzedaży polis ubezpieczeniowych oraz powiązanych KPI na dwóch poziomach:

- **strategicznym** — strona `Executive Summary`,
- **menedżerskim / operacyjnym** — strona `Sales - Management`.

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
└── docs/
    ├── data_model.md
    ├── dax_measures.md
    └── report_pages.md

---

## ⚙️ Użyte technologie

W projekcie wykorzystano:

- **Power BI Desktop** — budowa modelu danych, miar DAX oraz raportu,
- **Power Query** — przygotowanie i transformacja danych źródłowych,
- **DAX** — tworzenie miar analitycznych, KPI, obliczeń YTD, LY i YoY,
- **CSV** — format danych źródłowych,
- **GitHub** — publikacja projektu portfolio i dokumentacji,
- **AI-generated synthetic dataset** — wygenerowanie fikcyjnych danych źródłowych na potrzeby projektu.

---

## 📈 Przyszłe usprawnienia

Możliwe kierunki dalszego rozwoju projektu:

- opublikowanie interaktywnej wersji raportu w Power BI Service,
- dodanie osobnej strony do analizy szkód i szkodowości,
- rozbudowanie raportu o analizę retencji i odnowień polis,
- dodanie bardziej rozbudowanych tooltipów dla agentów, produktów i regionów,
- przygotowanie wersji anglojęzycznej raportu,
- dodanie dokumentacji procesu Power Query,
- rozbudowanie modelu o dodatkowe wskaźniki efektywności sprzedaży,
- przygotowanie krótkiego demo wideo pokazującego działanie raportu.

---

## ✨ Dziękuję!

Dziękuję za odwiedzenie repozytorium.

Projekt jest częścią mojego portfolio Data Analyst / Power BI Developer i został przygotowany w celu pokazania umiejętności z zakresu:

- modelowania danych,
- tworzenia raportów Power BI,
- pisania miar DAX,
- projektowania dashboardów,
- interpretacji danych sprzedażowych,
- budowania dokumentacji projektu analitycznego.

Chętnie przyjmę feedback oraz sugestie dotyczące dalszego rozwoju projektu.
