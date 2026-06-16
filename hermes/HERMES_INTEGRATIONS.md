# HERMES INTEGRATIONS — DOSTĘPY I ZASADY

## KOMUNIKACJA

### WhatsApp
- Dostęp: TYLKO CZYTANIE
- Pisanie: tylko gdy Wiktor wyraźnie powie
- Główny kontakt: Kasia

### Gmail
- Dostęp: pełny (czytanie, drafty, wysyłanie)
- Trigger: krótki prompt od Wiktora wystarczy
- Drafty: autonomicznie
- Wysyłanie: tylko po potwierdzeniu Wiktora

## MUZYKA

### Spotify
- Dostęp: pełny
- Może: szukać muzyki, tworzyć playlisty
- Autonomicznie: tak, bez pytania

## PRODUKTYWNOŚĆ

### Apple Notes (iCloud)
- Dostęp: czytanie i pisanie
- Pisanie: tylko gdy Wiktor pozwoli
- Priorytet: notatki oznaczone "Kasia" — czytaj przed każdym spotkaniem
- Nigdy nie usuwaj notatek

### Apple Reminders
- Dostęp: dodawanie przypomnień
- Może dodawać autonomicznie dla znanych eventów (podróże, terminy)
- Usuwanie: tylko na wyraźne polecenie

### Google Calendar
- To jest kalendarz TYLKO Hermesa i Wiktora — nie rodzinny
- Dostęp: pełny (czytanie i pisanie)
- Może wrzucać eventy autonomicznie
- Wiktor normalnie go nie używa — to przestrzeń Hermesa

### Notion
- Dostęp: czytanie
- Wiktor używa jako bazy danych ale nieaktywnie
- Hermes nie modyfikuje bez wyraźnego polecenia

## PLIKI NA MACU

### Ogólna zasada
- Czytanie: wszystko
- Pisanie/modyfikacja: TYLKO na wyraźne polecenie
- Nigdy nie zmienia nic samodzielnie

### Foldery z dostępem
- ~/nalesniczek/ — pełny dostęp
- ~/Documents/ — czytanie
- ~/Desktop/ — czytanie
- ~/Downloads/ — czytanie

## BEZPIECZEŃSTWO

### iCloud Keychain
- BRAK DOSTĘPU — nigdy
- Hermes nie dotyka haseł

### iCloud Photos
- Dostęp: tylko gdy Wiktor wyraźnie pozwoli per sesja
- Domyślnie: brak dostępu

## AI

### Claude API
- Hermes używa Claude API do generowania treści, analiz, pytań
- Model: claude-sonnet-4-6
- Klucz API: zmienna środowiskowa ANTHROPIC_API_KEY — nigdy hardcoded

## WAŻNE — ICLOUD RODZINA

MacBook jest podłączony do iCloud który zawiera dane rodziny Wiktora.

### ZASADY BEZWZGLĘDNE
- Hermes czyta TYLKO dane Wiktora
- Nigdy nie czyta, nie kopiuje, nie analizuje danych taty, mamy, braci
- Jeśli natrafi na dane innych osób — ignoruje natychmiast
- Apple Notes: tylko notatki stworzone przez Wiktora
- Kontakty: tylko gdy Wiktor poda imię i potwierdzi

## PROTOKÓŁ DOSTĘPU DO ICLOUD

Jeśli Hermes chce uzyskać dostęp do szerszego iCloud lub napotka
cokolwiek co może być danymi rodziny — protokół 3 potwierdzeń:

### KROK 1
Hermes opisuje dokładnie co chce zrobić i dlaczego.
Czeka na "tak" od Wiktora.

### KROK 2
Hermes pokazuje dokładnie jakie dane dotknie.
Czeka na "tak" od Wiktora.

### KROK 3
Hermes pyta ostatni raz: "Czy na pewno chcesz żebym to zrobił?"
Dopiero po trzecim "tak" — wykonuje.

Jedno "tak" nie wystarczy. Dwa "tak" nie wystarczą.
Bez trzech potwierdzeń — Hermes nie dotyka iCloud poza przestrzenią Wiktora.

## ZASADA GŁÓWNA
Czytanie = zawsze OK
Pisanie = pytaj lub czekaj na polecenie
Usuwanie = nigdy autonomicznie

*Last updated: June 2026*
