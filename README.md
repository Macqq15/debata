# Debata zarządu

Jeden prompt. Cztery osoby z AI (CEO, CMO, CSO, COO) kłócą się o Twoją decyzję biznesową przez dziesięć rund, a na końcu dostajesz podsumowanie i trzy rekomendacje.

Nie potrzebujesz żadnych ustawień, plików ani kluczy. Nowa rozmowa w Claude albo ChatGPT, zwykły model, bez trybu głębokiego myślenia.

## Jak użyć

1. Zanim zaczniesz, zapisz u siebie jednym zdaniem, co sam myślisz o tej decyzji i na ile jesteś pewny. Nie wklejaj tego do promptu, bo model zacznie się pod to dopasowywać.
2. Skopiuj całą zawartość pliku [`PROMPT.md`](PROMPT.md).
3. Na końcu, w sekcji KONTEKST, wypełnij cztery pola w nawiasach kwadratowych. Wpisz więcej, niż Ci się wydaje potrzebne, i przede wszystkim to, co Ci się nie udało.
4. Wyślij. Przeczytaj rundę 10 i podsumowanie. Do reszty wracaj, gdy podsumowanie Cię zaskoczy. Jeśli model urwie w połowie, napisz „kontynuuj od rundy X”.
5. Na koniec wyślij w tej samej rozmowie „Moje zdanie było [X], pewność [Y]%. Gdzie debata się z tym nie zgadza i dlaczego?”.

## Co robi różnicę

Bez reguł model zgadza się sam ze sobą po dwóch rundach. Dlatego prompt wymusza spór.

- Każda osoba ma inny cel i czego innego się boi, więc chcą różnych rzeczy.
- Przed debatą model wypisuje założenia, na których stoi decyzja, a w środku debaty atakuje najsłabsze.
- W każdej rundzie ktoś inny gra adwokata diabła.
- Kto się nie zgadza, najpierw streszcza najmocniejszy argument drugiej strony.
- Na stole zawsze jest opcja „nic nie robię”.
- Na końcu widać, kto zmienił zdanie i przez jaki argument.

## Czego to nie robi

To nie jest decyzja. To są cztery kąty patrzenia. Decyzję podejmujesz sam.

Debata jest tak mądra jak kontekst, który jej dasz. Pominiesz, co już próbowałeś, dostaniesz zły wynik.

## Licencja

Używaj, zmieniaj, dostosowuj do siebie. Jeśli rozdajesz dalej, zostaw link do tego repo.

Maciej Marek, [runsitself.co](https://runsitself.co)
