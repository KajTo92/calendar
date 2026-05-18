# Kalendarz

Minimalistyczny kalendarz dla Janka i Moniki z automatycznym grafikiem pracy, wspólnymi wolnymi dniami oraz ręcznymi wyjątkami zapisywanymi w Supabase.

## Supabase

Aplikacja oczekuje dwóch tabel:

- `calendar_events`
- `calendar_deleted_events`

Potrzebne są polityki RLS dla roli `anon`: `select`, `insert`, `delete`.

## Obrazki

Aplikacja odwołuje się do plików:

- `mis.png`
- `myszka.png`

Trzeba je dograć do głównego katalogu repozytorium, jeśli nie zostały jeszcze przesłane.
