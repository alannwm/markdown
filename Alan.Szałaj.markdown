
# 📘 Dokumentacja Projektu – „Mini AppleShop” 🍏

---

## 🏗️ Architektura

**Typ aplikacji:**

* Strona statyczna (bez backendu)

**Model działania:**

* Prosta struktura (bez MVC)

**Dane:**

* Produkty zapisane w pliku `script.js` (tablica)

**Renderowanie:**

* HTML + JavaScript (proste dodawanie elementów do strony)

---

## 💻 Stack technologiczny

### Języki:

* HTML5 – struktura strony
* CSS – wygląd (kolory, układ)
* JavaScript – logika aplikacji

### Narzędzia:

* Przeglądarka (Chrome / Edge)
* Edytor kodu (np. VS Code)

---

## ⚙️ Logika biznesowa

### 🛍️ Produkty

* Lista kilku produktów (np. iPhone, MacBook, iPad)
* Każdy produkt ma:

  * nazwę
  * cenę
  * zdjęcie
 
---

### 🛒 Koszyk

* Dodawanie produktów do koszyka
* Wyświetlanie listy produktów
* Obliczanie sumy ceny
* Przycisk „Wyczyść koszyk”
* Prosta wyszukiwarka (po nazwie)
* Filtrowanie (np. tylko iPhone)
* Kody rabatowe
* Zapamiętywanie koszyka

---

## 📋 Przykładowe funkcjonalności

### Funkcje użytkownika:

* Przeglądanie produktów
* Dodawanie do koszyka
* Wyświetlanie sumy
* Usuwanie wszystkich produktów

---

### UI / UX

* Styl prosty (Apple-like)
* Kolory:

  * biały
  * szary
  * czarny
* Układ:

  * produkty w siatce (grid/flex)
  * koszyk z boku lub na dole

---

## 📂 Struktura projektu

```
/MiniAppleShop
 ├── index.html
 ├── style.css
 └── script.js
```

---

## 📂 Struktura danych (JavaScript)

```js
const products = [
  {
    id: 1,
    name: "iPhone 15",
    price: 5000,
    img: "iphone.jpg"
  },
  {
    id: 2,
    name: "MacBook Air",
    price: 7000,
    img: "macbook.jpg"
  }
];
```

---

