# 💕 Náš spoločný čas ♡

> Osobný partnerský kalendár vytvorený s láskou ❤️

**Náš spoločný čas ♡** je moderná, responzívna webová aplikácia vytvorená ako osobný partnerský kalendár. Zobrazuje, ako dlho sme spolu, významné dátumy, meniny, kalendár, aktuálny čas a ďalšie spoločné udalosti.

Projekt je vytvorený pomocou **HTML5, CSS3, JavaScriptu a Bootstrap 5** a obsahuje podporu pre **Progressive Web App (PWA)**.

---

## ❤️ O projekte

### Spolu od

**24. 11. 2024**

Aplikácia automaticky počíta:

- ❤️ počet dní spolu
- 💕 počet mesiacov spolu
- 💞 počet rokov spolu
- 🕐 aktuálny čas
- 📅 aktuálny dátum
- 💗 najbližšie významné udalosti
- 🌸 slovenské meniny
- 💞 výročie začiatku vzťahu
- 🎂 narodeniny
- 💋 osobné meniny

Všetky výpočty prebiehajú automaticky podľa aktuálneho dátumu.

---

# ✨ Funkcie

## ⏳ Počítadlo spoločného času

Hlavná časť aplikácie zobrazuje aktuálne trvanie nášho spoločného času od:

**24. novembra 2024**

Počet dní, mesiacov a rokov sa vypočítava automaticky.

Nie je potrebné nič manuálne nastavovať.

---

## 🕐 Aktuálny čas

Aplikácia zobrazuje aktuálny čas podľa zariadenia, na ktorom je otvorená.

Čas sa automaticky aktualizuje.

---

## 📅 Partnerský kalendár

Kalendár umožňuje prechádzať jednotlivé mesiace pomocou navigačných tlačidiel.

Používa slovenské názvy:

- január
- február
- marec
- apríl
- máj
- jún
- júl
- august
- september
- október
- november
- december

Dni v týždni:

**Po · Ut · St · Št · Pi · So · Ne**

Významné dátumy sú v kalendári vizuálne zvýraznené.

---

# 💞 Významné dátumy

## 💕 Naše narodeniny

**16. júl**

Aplikácia automaticky vypočítava odpočítavanie do najbližšieho dátumu.

---

## 💞 Výročie začiatku

**24. november**

Výročie sa počíta od:

**24. 11. 2024**

---

# 💗 Meniny

Aplikácia obsahuje slovenský kalendár menín.

Osobitne sú zvýraznené:

- 💋 **Peter – 29. jún**
- 💗 **Erika – 2. február**

Meniny sa automaticky zobrazujú aj priamo v kalendári.

---

# 🌸 Dizajn

Aplikácia používa moderný romantický dizajn založený na pastelových farbách a glassmorphism efektoch.

Použité prvky:

- 💕 pastelová ružová
- 💜 jemná fialová
- 🤍 sklenené karty
- ✨ jemné tiene
- 💗 animované srdiečka
- 🌸 dekoratívne prvky
- 📱 responzívny dizajn
- 🎨 SVG grafika
- 🔤 font Quicksand

Rozhranie je optimalizované pre:

- 📱 smartfóny
- 📲 tablety
- 💻 notebooky
- 🖥️ stolné počítače

---

# 📱 Progressive Web App

Projekt obsahuje podporu pre **PWA – Progressive Web App**.

Súčasťou projektu je:

```text
manifest.webmanifest

Manifest obsahuje názov aplikácie, krátky názov, farby, ikony a spôsob spustenia.

Použité nastavenie JSON
{
  "name": "Náš spoločný čas ♡",
  "short_name": "Náš čas ♡",
  "start_url": "./",
  "display": "standalone"
}
Na podporovaných zariadeniach je možné aplikáciu pridať na domovskú obrazovku a používať ju podobne ako klasickú aplikáciu.

🖼️ Ikony

Projekt používa PWA a Apple ikony.
apple-touch-icon.png 180 × 180 px
icon-512.png 512 × 512 px

📂 Štruktúra projektu
Náš spoločný čas/
│
├── index.html
├── README.md
├── manifest.webmanifest
│
├── apple-touch-icon.png
├── icon-512.png
└── favicon.ico

Ak projekt obsahuje ďalšie súbory, môžu byť pridané podľa potreby.

🛠️ Použité technológie
HTML5

Zabezpečuje základnú štruktúru aplikácie.

CSS3

Používa sa na:

vizuálny dizajn
animácie
responzivitu
glassmorphism
efekty
rozloženie prvkov
JavaScript

JavaScript zabezpečuje:

výpočet spoločného času
výpočet dní
výpočet mesiacov
výpočet rokov
aktuálny čas
kalendár
meniny
odpočítavanie udalostí
zvýrazňovanie významných dátumov
interakcie s kalendárom
toastové oznámenia
animované srdiečka
Bootstrap 5

Použitá verzia:

Bootstrap 5.3.3

Bootstrap zabezpečuje základné responzívne rozloženie a UI komponenty.

Google Fonts

Použitý font:

Quicksand

⚙️ Konfigurácia dátumov

Hlavný dátum začiatku vzťahu je uložený v JavaScripte:
const START_DATE = new Date(2024, 10, 24);

JavaScript používa číslovanie mesiacov od 0.
Preto:
0  = január
1  = február
2  = marec
3  = apríl
4  = máj
5  = jún
6  = júl
7  = august
8  = september
9  = október
10 = november
11 = december

Zápis:
new Date(2024, 10, 24) teda predstavuje: 24. november 2024

🎂 Narodeniny
const BIRTHDAY = {
  month: 6,
  day: 16
};

Výsledný dátum:

16. júl

💞 Výročie
const ANNIVERSARY = {
  month: 10,
  day: 24
};

Výsledný dátum:
24. november
___________________________________

🌐 Spustenie

Projekt nevyžaduje:

PHP
MySQL
databázu
Node.js
serverovú aplikáciu

Ide o statickú webovú aplikáciu.

Stačí otvoriť:
index.html

_____________________

📱 Inštalácia ako aplikácia

Ak je projekt publikovaný cez HTTPS a prehliadač podporuje PWA, môže byť aplikácia pridaná na zariadenie.

Android

V podporovanom prehliadači je možné použiť možnosť:

Pridať na plochu / Inštalovať aplikáciu

iPhone / iPad

V Safari:

Zdieľať → Pridať na plochu

Aplikácia následne môže byť spustená samostatne bez klasického rozhrania prehliadača.


________________________________________
🔐 Súkromie

Aplikácia nevyžaduje:

používateľský účet
registráciu
heslo
databázu
osobný účet
serverovú časť

Výpočty prebiehajú priamo v prehliadači.

Osobné dátumy sú súčasťou JavaScriptu aplikácie.

_________________________________________
❤️ Myšlienka projektu

Každý deň spolu je ďalším dňom nášho spoločného príbehu.

Tento projekt vznikol ako osobný digitálny kalendár na pripomínanie spoločných dní, výročí, menín a ďalších dôležitých okamihov.

________________________________________
👨‍💻 Autor

Mgr. Peter Galko

📄 Licencia

Projekt je vytvorený ako osobný projekt.

Bez súhlasu autora nie je povolené:

vydávať projekt za vlastný
odstraňovať informácie o autorovi
redistribuovať upravenú verziu ako pôvodný projekt
