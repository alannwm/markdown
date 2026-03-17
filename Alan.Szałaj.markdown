
📘 Dokumentacja Projektu – „AppleShop”🍏 AppleShop – Markdown Store🏗️ Architektura
Typ aplikacji:
SPA (Single Page Application)
Model architektoniczny:

* MVC (Model-View-Controller):
* Model: Dane produktów w .json i stan koszyka w localStorage.
   * View: Dynamiczny HTML generowany przez JavaScript (Template Literals).
   * Controller: Logika filtrowania, wyszukiwania i obsługi koszyka.

API:

* Symulowane REST API oparte na lokalnych plikach .json.

Renderowanie:

* CSR (Client Side Rendering) – dynamiczne budowanie widoku z danych Markdown/JSON.

------------------------------
💻 Stack technologicznyJęzyki

* JavaScript (ES6+) – logika i sterowanie.
* HTML5 – struktura semantyczna.
* CSS3 – layout (Flexbox/Grid).
* JSON – struktura bazy danych produktów.

Biblioteki i narzędzia

* Vite – bundler i serwer deweloperski.
* Node.js – środowisko uruchomieniowe.
* LocalStorage – przechowywanie zawartości koszyka.

------------------------------
⚙️ Logika biznesowa🔍 Wyszukiwanie i Filtrowanie

* Wyszukiwarka tekstowa: Dynamiczne filtrowanie listy produktów po nazwie w czasie rzeczywistym.
* Filtry kategorii: Szybki wybór sekcji (iPhone, MacBook, iPad, Akcesoria).
* Sortowanie: Możliwość sortowania według ceny (rosnąco/malejąco).

🛒 Koszyk i "Co chcę kupić"

* Zarządzanie produktami: Dodawanie, usuwanie i zmiana ilości sztuk.
* Persystencja: Dane koszyka nie znikają po odświeżeniu strony (localStorage).
* Podsumowanie: Wyraźna lista wybranych pozycji z miniaturami i cenami jednostkowymi.

🎫 System Kodów Rabatowych
Aplikacja obsługuje 3 konkretne kody weryfikowane przy podsumowaniu:

   1. APPLE10 – obniża wartość koszyka o 10%.
   2. STUDENT – stała zniżka -200 PLN (aktywna od kwoty 2000 PLN).
   3. FREE – zeruje koszty dostawy i nalicza rabat -50 PLN.

------------------------------
📋 Przykładowe funkcjonalnościFunkcje użytkownika

* Przeglądanie: Intuicyjna galeria z dużymi zdjęciami.
* Wyszukiwanie: Pasek input filtrujący widoczne karty produktów.
* Kalkulator sumy: Automatyczne przeliczanie kwoty do zapłaty po dodaniu produktu lub wpisaniu kodu.
* Walidacja: Komunikaty o błędnym kodzie rabatowym lub pustym koszyku.

UI / UX

* Design: Styl minimalistyczny (Apple-like).
* Kolory: Biały, jasnosary, akcenty systemowe (niebieski/czarny).
* Responsywność: Pełne wsparcie dla Mobile i Desktop.

------------------------------
📂 Struktura bazy danych (JSON)

{
  "id": 1,
  "name": "iPhone 15 Pro",
  "price": 5299,
  "category": "iphone",
  "img": "path/to/image.jpg",
  "description": "Opis z pliku markdown..."
}

------------------------------
⚖️ Wymagania prawne i standardy

* RODO: Informacja o ciasteczkach (cookies).
* Edukacja: Wyraźna informacja: "Projekt nie jest sklepem komercyjnym".
* WCAG 2.1: Wysoki kontrast tekstu i opisy alt dla zdjęć produktów.
* SEO: Semantyczne tagi header, main, footer oraz h1-h3.

------------------------------
🛠️ Instrukcja uruchomienia

   1. npm install – instalacja zależności.
   2. npm run dev – uruchomienie serwera deweloperskiego.
   3. npm run build – przygotowanie wersji produkcyjnej.

------------------------------

