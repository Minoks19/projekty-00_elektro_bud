# Projekt Elektro-Bud – analiza wymagań

## 1. Wymagania funkcjonalne

| ID | Nazwa | Opis |
|---|---|---|
| FR-01 | Logowanie użytkownika | System powinien umożliwiać użytkownikowi zalogowanie się przy użyciu danych dostępowych. |
| FR-02 | Wyszukiwanie produktu | System powinien umożliwiać wyszukiwanie produktu na podstawie nazwy lub kodu EAN. |
| FR-03 | Sprawdzanie lokalizacji produktu | System powinien umożliwiać sprawdzenie lokalizacji produktu w magazynie. |
| FR-04 | Rejestracja przyjęcia towaru | System powinien umożliwiać rejestrowanie przyjęcia towaru do magazynu. |
| FR-05 | Rejestracja wydania towaru | System powinien umożliwiać rejestrowanie wydania towaru z magazynu. |
| FR-06 | Kontrola stanu magazynowego | System powinien umożliwiać sprawdzanie aktualnego stanu magazynowego produktów. |
| FR-07 | Aktualizacja stanu magazynowego | System powinien aktualizować stan magazynowy po przyjęciu lub wydaniu towaru. |
| FR-08 | Przeglądanie historii operacji | System powinien umożliwiać przeglądanie historii operacji magazynowych. |
| FR-09 | Raportowanie | System powinien umożliwiać kierownikowi magazynu przeglądanie informacji i raportów dotyczących magazynu. |
| FR-10 | Zarządzanie użytkownikami | System powinien umożliwiać administratorowi zarządzanie kontami użytkowników. |
| FR-11 | Obsługa ról i uprawnień | System powinien umożliwiać przypisywanie użytkownikom odpowiednich ról i uprawnień. |
| FR-12 | Skanowanie kodu EAN | System powinien umożliwiać identyfikowanie produktu za pomocą kodu EAN. |

## 2. Wymagania niefunkcjonalne

| ID | Nazwa | Opis |
|---|---|---|
| NFR-01 | Wydajność | System powinien odpowiadać na operacje wyszukiwania produktu oraz obsługę kodu EAN w czasie nie dłuższym niż 1–2 sekundy w typowych warunkach pracy. |
| NFR-02 | Bezpieczeństwo | System powinien wymagać uwierzytelnienia użytkownika przed uzyskaniem dostępu do funkcji systemu. |
| NFR-03 | Kontrola dostępu | Użytkownik powinien mieć dostęp wyłącznie do funkcji wynikających z przypisanej mu roli. |
| NFR-04 | Dostępność | System powinien być dostępny dla uprawnionych użytkowników w godzinach pracy magazynu. |
| NFR-05 | Integralność danych | System powinien zapewniać poprawność i spójność danych dotyczących produktów oraz stanów magazynowych. |
| NFR-06 | Rejestrowanie operacji | System powinien zapisywać informacje o wykonanych operacjach magazynowych oraz użytkowniku, który je wykonał. |
| NFR-07 | Sposób korzystania | System powinien posiadać prosty i czytelny interfejs umożliwiający sprawną obsługę operacji magazynowych. |
| NFR-08 | Obsługa kodów EAN | System powinien umożliwiać szybkie identyfikowanie produktów za pomocą kodów EAN. |

## 3. Aktorzy

### Magazynier

**Rola:** pracownik odpowiedzialny za bieżącą obsługę magazynu.

**Podstawowe działania w systemie:**
- logowanie do systemu,
- wyszukiwanie produktów,
- skanowanie kodów EAN,
- sprawdzanie lokalizacji produktów,
- rejestrowanie przyjęcia towaru,
- rejestrowanie wydania towaru,
- sprawdzanie stanu magazynowego.

### Kierownik magazynu

**Rola:** osoba odpowiedzialna za nadzorowanie pracy magazynu.

**Podstawowe działania w systemie:**
- logowanie do systemu,
- wyszukiwanie produktów,
- sprawdzanie stanu magazynowego,
- przeglądanie historii operacji,
- przeglądanie raportów.

### Administrator

**Rola:** osoba odpowiedzialna za administrację systemem i użytkownikami.

**Podstawowe działania w systemie:**
- logowanie do systemu,
- zarządzanie użytkownikami,
- dodawanie i edytowanie kont użytkowników,
- usuwanie kont użytkowników,
- przypisywanie ról i uprawnień.
