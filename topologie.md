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

   **Zalety**
   - Sieć point-to-point jest łatwa do skonfigurowania, ponieważ łączy tylko dwa urządzenia. Nie ma potrzeby tworzenia skomplikowanej infrastruktury sieciowej.
   - Ze względu na bezpośrednią łączność między urządzeniami, opóźnienia są minimalne.

   **Wady**
   - Sieć point-to-point wymaga stabilnych i niezawodnych połączeń między urządzeniami. Jeśli występują problemy z linią, komunikacja jest zakłócona.
   - W przypadku awarii jednego z urządzeń lub łącza, cała komunikacja między tymi punktami zostaje przerwana. Brak redundancji może prowadzić do problemów w dostępności.
   
   **Zastosowanie**
   - Wykorzystywana w łączach WAN, np. pomiędzy dwoma oddziałami firmy.

2. **Przekazywanie żetonu (Token Passing)**  
   **Opis**
   - Token (specjalny pakiet) krąży po sieci, a urządzenie może wysłać dane tylko wtedy, gdy posiada token.
   
   **Zalety**
   - Kolizje w sieci są znacznie ograniczone, ponieważ token jest przekazywany w określonym porządku, co zapewnia, że tylko jedno urządzenie w danym czasie korzysta z medium transmisyjnego.
   - Sieć może być łatwo rozszerzana o nowe urządzenia, a token jest przekazywany do nowych urządzeń w sposób uporządkowany, co nie wpływa na jakość komunikacji w sieci.

   **Wady**
   - W sieci z dużą liczbą urządzeń czas oczekiwania na dostęp do medium może stać się znacznie dłuższy, co wpływa na efektywność komunikacji
   - Jeśli jedno z urządzeń lub połączeń w sieci ulegnie awarii, może to zakłócić przepływ tokena, co prowadzi do spadku wydajności sieci.

   **Zastosowanie**
   - Typowe w sieciach Token Ring, ale także w niektórych protokołach Ethernet.

3. **Wielodostępowa (Multiple Access)**  
   **Opis**
   - Więcej niż jedno urządzenie może jednocześnie wysyłać dane, przy czym sieć rozwiązuje konflikty dotyczące dostępu do medium.
    
    **Zalety**
    - Umożliwia wielu użytkownikom jednoczesny dostęp do sieci, co jest podstawą dla rozwoju dużych sieci komórkowych, takich jak 4G, 5G czy sieci Wi-Fi.
    - W miarę rozwoju sieci, w systemach opartych na Multiple Access można łatwo dodawać nowych użytkowników bez konieczności dużych zmian w infrastrukturze. To sprawia, że sieci mogą rosnąć w miarę potrzeb.
   
    **Wady**
    - W zatłoczonych sieciach może wystąpić zmienna jakość transmisji, opóźnienia i utrata pakietów.
    - W systemach takich jak CSMA, gdzie urządzenia konkurują o dostęp do medium, mogą występować kolizje, co prowadzi do konieczności retransmisji i opóźnień w transmisji danych. Może to obniżyć wydajność w zatłoczonych sieciach.

**Zastosowanie** 
   - Stosowana w sieciach Ethernet i Wi-Fi, gdzie urządzenia muszą radzić sobie z dostępem do wspólnego medium transmisyjnego.
