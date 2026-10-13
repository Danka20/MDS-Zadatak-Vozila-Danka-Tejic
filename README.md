# MDS-Zadatak-Vozila-Danka-Tejic
* **Okruženje za testiranje:** macOS Sonoma 14.4.1 / Chrome (arm64)
* **Link aplikacije:** https://qa-test-manual.vercel.app
# MDS Vozila – QA Test Dokumentacija i Summary Report

## O Projektu

Ovaj projekat predstavlja kompletnu QA dokumentaciju i analizu testiranja za **MDS Vozila** aplikaciju (sistem za upravljanje voznim parkom).

Cilj testiranja je bio verifikovati funkcionalnost ključnih modula, identifikovati UI/UX i funkcionalne defekte, sagledati aplikaciju iz korisničke perspektive, te predložiti poboljšanja poslovne logike kako bi se aplikacija uskladila sa savremenim standardima u industriji.

Ukupan cilj bio je utvrđivanje **stabilnosti aplikacije**, **verifikacija tačnosti unosa podataka**, kao i **identifikacija funkcionalnih i logičkih nedostataka**.

---

## Obim Testiranja (Test Scope)

Testiranje je obuhvatilo sledeće funkcionalne celine:

* **Evidencija:** Upravljanje vozilima i korisnicima
* **Operacije:** Kreiranje zapisa o vožnji
* **Praćenje:** Kreiranje zapisa o kilometraži i sipanju goriva
* **Korisnički profil i UI/UX analiza**

---

## Struktura Dokumentacije i Repozitorijuma

Dokumentacija se sastoji iz **3 Excel fajla** i pratećeg medijskog sadržaja:

* **Bug Report:** Pregled identifikovanih grešaka sa dodeljenim prioritetima (Visok, Srednji, Nizak), opisima i koracima za reprodukciju.
* **Sugestije:** Lista predloga za poboljšanje funkcionalnosti sistema sa fokusom na poslovnu logiku i korisničko iskustvo.
* **Test Cases:** Obuhvata  test slučajeve pisane tokom testiranja.
Modul **Evidencija (Vozila i Korisnici)** odrađen je detaljno pomoću **Low-Level** tehnike pisanja test slučajeva, dok su ostale celine obrađene **High-Level** tehnikom.
* **Dokazni materijali:** Šest foldera sa screenshot-ovima i video zapisima sa dokazima o uočenim bug-ovima.

---

## Test Summary Report

### 1. Pregled Test Slučajeva po Prioritetu

Pregled svih **197 test slučajeva** razvrstanih po nivou prioriteta:

- **Visok (High):** 98 test slučajeva (49.7%)
- **Srednji (Medium):** 72 test slučaja (36.5%)
- **Nizak (Low):** 27 test slučajeva (13.7%)

### 2. Pregled Identifikovanih Bug-ova

Tokom testiranja otvoreno je ukupno **39 bug-ova** (koji odgovaraju palim test slučajevima). Njihova struktura po ozbiljnosti i prioritetu rešavanja je sledeća:

- **Visok Prioritet:** 22 bug-a (56.4%)
- **Srednji Prioritet:** 16 bug-ova (41.0%)
- **Nizak Prioritet:** 1 bug (2.6%)

---

## Zaključak i Ocena Stanja Aplikacije

Aplikacija pokazuje dobar potencijal i jasnu strukturu, međutim, prisustvo **22 bug-a visokog prioriteta** ukazuje na to da ključni moduli još uvijek pate od funkcionalnih grešaka koje narušavaju pouzdanost podataka.

Pored kritičnih defekata, identifikovan je i značajan broj **UI/UX nedostataka** koji direktno narušavaju korisničko iskustvo. Takođe, nedostaju adekvatne **poslovne validacije na unosnim poljima**, što ostavlja prostor za unos nelogičnih i nevalidnih podataka.

Neophodna je **sanacija identifikovanih defekata** i **potencijalna implementacija predloženih logičkih unapređenja** kako bi aplikacija dostigla visok nivo pouzdanosti, ispoštovala integritet podataka i pružila stabilno korisničko iskustvo.
