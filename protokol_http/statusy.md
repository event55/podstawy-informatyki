# Grupy kodów statusu HTTP

## 1XX - Informacyjne
Kody z tej grupy informują o tym, że zapytanie zostało odebrane i jest przetwarzane.  
**Przykłady:**  
- **100 Continue** – Serwer otrzymał początkową część żądania i klient może kontynuować.

## 2XX - Sukces
Kody te oznaczają, że żądanie zakończyło się sukcesem.  
**Przykłady:**  
- **200 OK** – Żądanie zostało poprawnie przetworzone.  
- **201 Created** – Zasób został utworzony.  

## 3XX - Przekierowania
Wskazują, że klient musi podjąć dodatkową akcję, aby zakończyć żądanie.  
**Przykłady:**  
- **301 Moved Permanently** – Adres URL został trwale zmieniony.  
- **302 Found** – Tymczasowe przekierowanie.  

## 4XX - Błędy klienta
Wskazują, że wystąpił błąd po stronie klienta.  
**Przykłady:**  
- **400 Bad Request** – Błędne zapytanie.  
- **401 Unauthorized** – Brak uwierzytelnienia.  
- **404 Not Found** – Zasób nie istnieje.  

## 5XX - Błędy serwera
Oznaczają, że wystąpił błąd po stronie serwera.  
**Przykłady:**  
- **500 Internal Server Error** – Ogólny błąd serwera.  
- **503 Service Unavailable** – Serwer jest tymczasowo niedostępny.  
