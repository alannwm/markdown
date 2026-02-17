# 📘 Dokumentacja Projektu – „AppleShop”


## Apple 
**AppleShop – Markdown Store**



## Architektura

**Typ aplikacji:**  
SPA 
**Model architektoniczny:**  
- SSR (Server Side Rendering)

**API:**  
- REST API (symulowane plikami `.json` lub lokalnymi danymi)

**Renderowanie:**  
- SSR (Server Side Rendering) – generowanie HTML z Markdown po stronie serwera lub builda

**Wzorzec projektowy:**  
- Html 
 - Controller – JavaScript)

---

## Stack technologiczny

### Języki
- JavaScript (JS)
- HTML5
- CSS3
- JSON

### Biblioteki i narzędzia
- `Node.js` – środowisko uruchomieniowe
- `Vite` – bundler i dev-server
- Git / GitHub – repozytorium projektu

---

## Tokeny / Klucze API
- GitHub API – do pobierania danych repozytorium
- (Opcjonalnie) API kursów walut / płatności testowych

---

## Logika biznesowa

- Wyświetlanie produktów Apple na podstawie plików `.md`
- Kategorie produktów: iPhone, MacBook, iPad, Akcesoria
- Koszyk zapisany w `localStorage`
- Sumowanie cen produktów
- Promocje procentowe
- Symulacja zamówienia (bez prawdziwych płatności)
- „Baza danych” w plikach `.json` lub tabelach Markdown

---

## Przykładowe funkcjonalności

### Funkcje użytkownika
- Przeglądanie kategorii
- Podgląd produktu
- Dodanie do koszyka
- Usuwanie z koszyka
- Liczenie sumy zamówienia
- Strona kontaktowa
- Strona promocji

### Przepływ UX
1. Wejście na stronę główną  
2. Wybór kategorii  
3. Kliknięcie produktu  
4. Dodanie do koszyka  
5. Podsumowanie zamówienia  
6. Powrót do sklepu  

### UI
- Minimalistyczny styl
- Jasne kolory
- Duże zdjęcia produktów
- Prosta nawigacja

---

## Grupa docelowa

**Odbiorcy:**
- Młodzież 15–25 lat  
- Studenci IT  
- Osoby zainteresowane technologią

**Potrzeby i oczekiwania:**
- Szybkość działania
- Przejrzystość
- Prostota interfejsu
- Czytelne ceny i opisy

---

## Wymagania techniczne

- Przeglądarka: Chrome / Firefox / Edge
- Obsługa JavaScript
- Rozdzielczość min. 1366×768
- Hosting statyczny (np. GitHub Pages)
- Pliki JSON

---

## Wymagania prawne

- Informacja o cookies (RODO)
- Projekt edukacyjny – brak prawdziwej sprzedaży
- Informacja o znakach towarowych Apple
- Licencja MIT / Creative Commons dla kodu

---

## Standaryzacja

### WCAG 2.1
- Kontrast tekstu
- Atrybuty `alt` do obrazów
- Czytelne fonty
- Nawigacja klawiaturą

### SEO
- Meta tagi
- Opisy stron
- Nagłówki H1–H3
- Przyjazne URL

---

## Standardowe wymagania końcowe projektu

- Strona główna
- Minimum 3 kategorie produktów
- Koszyk
- Baza danych produktów
- Strona kontaktowa
- Dokumentacja techniczna
- Repozytorium Git

---

## Dokumentacja kodu

### Komentarze techniczne
- JSDoc w plikach `.js`
- Opis architektury
- Logika biznesowa
- Struktura folderów
- Instrukcja uruchomienia projektu

---

