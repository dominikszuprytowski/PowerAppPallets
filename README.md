# SPID - System sprzedaży i dostaw palet

Projekt SPID (System sprzedaży i dostaw palet) jest skierowany do małych firm, które potrzebują efektywnego i niedrogiego oprogramowania do zarządzania sprzedażą i dostawą palet. System obejmuje obsługę zleceń od momentu ich pozyskania aż do ich zrealizowania przez łańcuch dostaw. Dodatkowo, projekt zawiera interaktywny dashboard, który pozwala na podsumowanie wyników przedsiębiorstwa.

## Informacje o projekcie

- **Nazwa skrócona:** SPID
- **Nazwa pełna:** System sprzedaży i dostaw palet
- **Opis:** System sprzedaży i dostaw palet, wykorzystujący PowerPlatform od Microsoft, umożliwiający zarządzanie zleceniami i analizę wyników.

## Autorzy

- Dominik Szuprytowski
- Agata Herrmann
- Zuzanna Łuszczyk

## Specyfikacja wymagań

| Identyfikator | Nazwa                                   | Opis                                                                         | Priorytet | Kategoria    |
|---------------|-----------------------------------------|------------------------------------------------------------------------------|-----------|--------------|
| BD1           | Baza Danych                             | Przygotowanie testowej bazy danych                                           | 1         | Funkcjonalne |
| DSD1          | Diagram sekwencji działań                | Przygotowanie diagramu działań od przyjęcia zlecenia do analizy wyników       | 2         | Funkcjonalne |
| U1            | Utworzenie testowych kont użytkowników  | Utworzenie kont użytkowników w systemie                                      | 1         | Funkcjonalne |
| U2            | Logowanie do systemu                    | Umożliwia użytkownikom zalogowanie się do systemu                            | 1         | Funkcjonalne |
| Z1.1          | Dodawanie nowych zamówień               | Umożliwia użytkownikom dodawanie nowych zamówień                              | 1         | Funkcjonalne |
| Z1.2          | Przepływ zamówienia przez etapy         | Umożliwia przekazywanie zamówienia do realizacji po sprawdzeniu wykonalności   | 1         | Funkcjonalne |
| Z1.3          | Sprawdzenie stanu magazynowego          | Umożliwia sprawdzenie stanu magazynowego i decyzję o realizacji zamówienia    | 1         | Funkcjonalne |
| Z1.4          | Rejestracja kontrahentów                | Umożliwia rejestrację nowych kontrahentów                                     | 1         | Funkcjonalne |
| Z1.5          | Powiadomienia mailowe o nowych zleceniach| Wysyła powiadomienia o nowych zleceniach do działu transportu i magazynu     | 2         | Funkcjonalne |
| P1            | Dostępność                              | Aplikacja jest dostępna 24/7/365 przez około 99,9% czasu                    | 1         | Niefunkcjonalne |
| P2            | Wydajność                               | Nie ma ograniczeń co do ilości użytkowników korzystających z systemu         | 2         | Niefunkcjonalne |
| P3            | Wsparcie                                | Użytkownicy mają dostęp do wsparcia technicznego oferowanego przez Microsoft | 3         | Niefunkcjonalne |
| P4            | Bezpieczeństwo                          | Aplikacja jest zabezpieczona zgodnie z zasadami Microsoft                     | 3         | Niefunkcjonalne |
| P5            | Kompatybilność                          | Aplikacja jest kompatybilna z różnymi systemami operacyjnymi i przeglądarkami | 2         | Niefunkcjonalne |

## Architektura systemu/oprogramowania

### Architektura rozwoju

- **PowerApps - PowerFX**
- **Baza danych:** SQL
- **Raport PowerBI:** DAX

### Architektura uruchomieniowa

- **System operacyjny:** Windows 10
- **Przeglądarka internetowa**

## Testy

Wykonamy testy funkcjonalności, testy integracyjne i testy wydajnościowe.

## Sprawozdanie z wykonania scenariuszy

Po zbudowaniu aplikacji...

