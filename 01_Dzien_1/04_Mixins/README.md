![Coders-Lab-1920px-no-background](https://user-images.githubusercontent.com/30623667/104709394-2cabee80-571f-11eb-9518-ea6a794e558e.png)


> ### Przygotowanie
> Zmodyfikuj plik `gulpfile.js` tak, aby zmienna `entryPath` wskazywała na:
> -  `01_Dzien_1/04_Mixins/02_Zadanie_2`
>
> **Pamiętaj aby po każdej zmianie w pliku `gulpfile.js` przerwać działanie Gulpa (`CTRL+C`) a następnie włączyć go z powrotem (`gulp`).**

## Zadanie 2

Stwórz mixin, który na podstawie przekazanego do niego parametru - `$font` - ustawi wielkość tekstu dla elementu `header`. Dodatkowo ustawi również `border-radius` na `5px`.



> ### Przygotowanie
> Zmodyfikuj plik `gulpfile.js` tak, aby zmienna `entryPath` wskazywała na:
> -  `01_Dzien_1/04_Mixins/03_Zadanie_3`
>
> **Pamiętaj aby po każdej zmianie w pliku `gulpfile.js` przerwać działanie Gulpa (`CTRL+C`) a następnie włączyć go z powrotem (`gulp`).**


## Zadanie 3

Stwórz mixin, o nazwie `dialogBox`, który przyjmuje dwa argumenty - kolor ($backgroundColor) oraz szerokość boksa ($width). Jego zadaniem jest ustawienie styli dla elementu o klasie `dialog`.

```
  width: $width;
  padding: 10px;
  background: $backgroundColor;
  border: 1px solid black;
  margin: 40px auto;
```

Do mixinu dodaj pseudo element `:after`, który stworzy kwadrat o wymiarach 10x10px, dekorujący boks. Końcowy projekt powinien wyglądać następująco:

![Dialog](images/dialog.png)

Zadanie przetestuj dla tła `green` i `lightgray`, oraz dowolnymi szerokościami.

