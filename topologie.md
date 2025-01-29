### Topologie Sieci

#### a. Topologie sieci fizycznych

1. **Magistrala (Bus)**  
   - Opis:
   - Wszystkie urządzenia są połączone jednym przewodem, którym przesyłane są dane. 
   - **Zalety**:  
     - Łatwość w implementacji i niskie koszty.
     - Prosta w budowie i instalacji.
   - **Wady**:  
     - Jeśli przewód ulegnie uszkodzeniu, cała sieć przestaje działać.
     - Wydajność spada przy większej liczbie urządzeń.
   - **Zastosowanie**: Zwykle w małych i średnich sieciach, np. w biurach czy starszych instalacjach.

2. **Pierścień (Ring)**  
   - Opis: 
   - Urządzenia są połączone w pętli, a dane przesyłane są w jednym kierunku do momentu, aż dotrą do odbiorcy.
   - **Zalety**:  
     - Łatwość w synchronizacji urządzeń w sieci.
     - Mniejsze opóźnienia w przesyłaniu danych w porównaniu do magistrali.
   - **Wady**:  
     - Uszkodzenie pojedynczego urządzenia lub przewodu powoduje przerwanie całej sieci.
     - Trudniejsza diagnostyka problemów.
   - **Zastosowanie**: Stosowana w sieciach LAN, zwłaszcza w starszych technologiach, np. Token Ring.

3. **Gwiazda (Star)**  
   - Opis:
   - Wszystkie urządzenia są podłączone do centralnego węzła (np. switcha), który zarządza ruchem danych.
   - **Zalety**:  
     - Łatwość rozbudowy i konserwacji.
     - Awaria pojedynczego urządzenia nie wpływa na resztę sieci.
   - **Wady**:  
     - Awaria centralnego węzła powoduje całkowite załamanie sieci.
     - Wymaga więcej kabli, co może zwiększyć koszty.
   - **Zastosowanie**: W nowoczesnych sieciach, np. w biurach, domowych sieciach Wi-Fi, w sieciach Ethernet.

---

#### b. Topologie sieci logicznych

1. **Punkt-punkt (Point-to-Point)**  
   **Opis**
   - Łącze bezpośrednie między dwoma urządzeniami.
   
   **Zastosowanie**
   - Wykorzystywana w łączach WAN, np. pomiędzy dwoma oddziałami firmy.

2. **Przekazywanie żetonu (Token Passing)**  
   **Opis**
   - Token (specjalny pakiet) krąży po sieci, a urządzenie może wysłać dane tylko wtedy, gdy posiada token.
   
   **Zastosowanie**
   - Typowe w sieciach Token Ring, ale także w niektórych protokołach Ethernet.

3. **Wielodostępowa (Multiple Access)**  
   **Opis**
   - Więcej niż jedno urządzenie może jednocześnie wysyłać dane, przy czym sieć rozwiązuje konflikty dotyczące dostępu do medium.
    
    **Zastosowanie** 
   - Stosowana w sieciach Ethernet i Wi-Fi, gdzie urządzenia muszą radzić sobie z dostępem do wspólnego medium transmisyjnego.
