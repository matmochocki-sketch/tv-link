# tv-link

Strona przekierowania do TradingView dla prywatnej aplikacji „Skanery Claude”: podgląd claude.ai otwiera linki w karcie Chrome,
która nie przekazuje ich aplikacji TradingView; przekierowanie z tej strony na `intent://` otwiera aplikację.
Prowadzi wyłącznie do `www.tradingview.com/chart/?symbol=…` (parametr `s`, np. `?s=NASDAQ:FTAI`). Bez danych i śledzenia.

## skanery/

Skrót na pulpit Androida dla aplikacji „Skanery Claude”: otwiera artefakt w aplikacji Claude (intent z pakietem
`com.anthropic.claude`), awaryjnie w przeglądarce. Adres artefaktu przychodzi w parametrze `u` (UUID) i nie jest zapisany
w repozytorium. Konfiguracja: `skanery/?u=<UUID>&konfig=1`.
