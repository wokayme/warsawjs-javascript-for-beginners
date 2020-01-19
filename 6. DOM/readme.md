## Zadania DOM

### Pobieranie elementów
1. Pobierz element o id `mojnaglowek` i zmień jego treść na "Javascript jest super"
2. Pobierz input o id `coTutajJestNapisane` i zwró jego zawartość w konsoli, a następnie podmień jego treść na nowy tekst
3. Przepisz zawartość inputa z zadania 2go to treści nagłówka z zadania 1go



### Tworzenie nowych elementów
1. Stwórz nowy akapit, uzupełnij go dowolną treścią i wstaw go na końcu body
2. Stwórz komentarz i dodaj go do sekcji o id `comments`, poniżej masz jego strukturę:
```
    <div class="comment">
        <h2>Autor: Krzysztof Łokaj</h2>
        <span>Wysłane 20.03.2019</span>
        <p>
            Ten warsztat jest po prostu świetny
        </p>
    </div>
```
3. Zedytuj kod z zadania 2go i podmień jego zawartość z obiektu poniżej:
```
    let comment = {
        author: "Andrzej Molek",
        date: "20.03.2019",
        msg: "Ale super ten warsztat robimy już czary mary"
    }
```
4. Rzadko kiedy dostajemy od serwera pojedyńczą tablicę, tym razem dostaliśmy listę z wieloma komentarzami i warto było by ją wyświetlić...
Podejmiesz wyzwanie? Tutaj lista:

```
    let comments = [
        {
            author: "Wojtek Trek",
            date: "20.03.2019",
            msg: "Już taki jestem..."
        },
        {
            author: "Strach na wróble",
            date: "21.03.2019",
            msg: "Zimny drań"
        },
        {
            author: "Wokay",
            date: "24.03.2019",
            msg: "I dobrze mi z tym"
        },
        {
            author: "Zenek Martyniuk",
            date: "26.03.2019",
            msg: "Miłość miłość w zakopanym"
        },
        {
            author: "Sławomir",
            date: "30.03.2019",
            msg: "Ej Zenek, ukradłeś mi tekst..."
        }
    ]
```