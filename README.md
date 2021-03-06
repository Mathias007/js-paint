# JS Paint

Przygotowany z wykorzystaniem m. in. Javascript i HTML `Canvas` projekt aplikacji inspirowanej programem MS Paint.

## Opis

Projekt wykorzystuje `context` elementu canvas do tworzenia prostych rysunków z poziomu przeglądarki. Aktualnie aplikacja umożliwia wybór koloru (dzięki zewnętrznemu skryptowi pickera - `jscolor`) i grubości pędzla, koloru tła oraz gumki. Istnieje także możliwość wyczyszczenia widoku. Projekt może zostać zapisany, wczytany bądź usunięty z `localStorage`. Wreszcie, aplikacja umożliwia pobranie obrazu w postaci pliku `.jpeg` przez użytkownika.

## Zastosowanie i plany rozwoju

Aplikacja może i powinno zostać rozwijana poprzez dodawanie nowych opcji rysowania, takich jak dodawanie kształtów czy elementów tekstowych. Nadto warto rozważyć poszerzenie możliwości jej pamięci wewnętrznej, poprzez zapisywanie do localStorage większej liczby projektów. Wreszcie, zasadnym wydaje się udostępnienie również innych formatów zapisu oraz umożliwienie użytkownikowi wybrania nazwy pliku już na etapie zapisywania.

W pełni funkcjonalna aplikacja mogłaby stanowić element szerszego środkowiska pracy biurowej dostępnego z poziomu przeglądarki, obok chociażby edytora tekstu czy oprogramowania do tworzenia prezentacji.

Preview dostępne [na serwerze własnym (eGildia Graczy)](https://egildia.pl/projects/js-paint/)
