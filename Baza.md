# Baza danych

Baza danych jest zarządzana przez MySQL.

Główne tabele to: auth_user(prywatne informacje użytkownika), stat_map_game(wyniki gry), stat_player_game(wyniki gracza), top_map(popularne karty), top_players(najlepsi gracze).

Aby uprościć pracę z bazą danych, stworzono funkcje logowania i dodawania statystyk.

Baza znajduje się w Google Cloud. Połączenie z bazą danych odbywa się za pomocą certyfikatów SSL. Baza danych jest bezpośrednio połączona ze stroną, znajdują się w jednym projekcie w Google Cloud. Połączenie z backendem jest nawiązywane za pomocą jdbc: mysql, w tym celu podano wszystkie szczegóły połączenia: Host, Port, User, Pass.
