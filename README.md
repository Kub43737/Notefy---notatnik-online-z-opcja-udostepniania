## 🏗️ Architektura aplikacji

- **Typ aplikacji:** SPA  
- **Model realizacji:** Monolit 
- **Komunikacja z danymi:** localStorage  
- **Renderowanie:** Client Side Rendering 


---

## 🛠️ Stos technologiczny

| Kategoria          | Technologie / narzędzia                              
|--------------------|-------------------------------------------------------|
| Język podstawowy   | JavaScript (vanilla)                                  |
| Struktura strony   | HTML5                                                 | 
| Wygląd             | CSS3 (flexbox, grid, custom properties)               | 
| Logika aplikacji   | JavaScript                                            | 
| Przechowywanie     | localStorage                                          | 
| Narzędzia dev      | Vite (opcjonalnie), Live Server, VS Code              |                             
| Dokumentacja       | Markdown                                              | 
| Inne               | marked.js (jeśli chcesz renderować markdown w apce)   | 

---

## 🎯 Logika biznesowa – główne funkcjonalności

1. Rejestracja użytkownika  
2. Logowanie / weryfikacja poświadczeń  
3. Tworzenie notatki / zadania  
4. Wyświetlanie listy notatek użytkownika  
5. Usuwanie notatki  
6. (opcjonalnie) Edycja notatki  
7. Wylogowanie  
8. Zachowanie danych po zamknięciu przeglądarki

**Przepływ użytkownika (najprostszy happy path):**

Zaloguj się → zobacz listę → dodaj notatkę → usuń niepotrzebną → wyloguj się → zaloguj się ponownie → dane nadal są

---

## 👥 Grupa docelowa

**Kto będzie używał aplikacji?**

- uczniowie / studenci (notatki z lekcji, listy zadań)
- osoby początkujące w organizacji czasu
- użytkownicy, którzy chcą prostej aplikacji offline bez zakładania konta w chmurze

**Główne potrzeby:**

- szybkie dodawanie krótkich notatek
- prywatność (każdy widzi tylko swoje dane)
- działanie bez internetu
- prosty i intuicyjny interfejs

---

## ⚖️ Wymagania techniczne i formalne

### Wymagania prawne / zgodność

- Brak przetwarzania danych osobowych poza loginem/hasłem w localStorage → **RODO nie dotyczy**
- Brak cookies → nie trzeba komunikatu o cookies
- Licencje: kod własny + biblioteki open-source (MIT / Apache 2.0)

### Dostępność i standardy (opcjonalnie na wyższą ocenę)

- WCAG 2.1 poziom A / AA (kontrast, focus, etykiety pól)
- podstawowe SEO (meta title, description, semantyczne tagi HTML)
- responsywność (działa na telefonie i komputerze)

---

## 📋 Standardowe elementy oddawanego projektu

- [ ] działająca aplikacja (można przetestować w przeglądarce)
- [ ] plik README.md z opisem projektu
- [ ] zrzuty ekranu / krótki filmik demonstracyjny (1–2 min)
- [ ] czytelny kod + komentarze
- [ ] dokumentacja w Markdown (ten plik + ewentualnie osobny folder /docs)
- [ ] (opcjonalnie) JSDoc przy ważniejszych funkcjach

---

Powodzenia!  

Jeśli chcesz – mogę pomóc dopisać konkretne funkcjonalności, przepływy albo gotowe fragmenty kodu startowego.
