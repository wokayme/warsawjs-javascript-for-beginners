## Zadania Obiekty
1. Zdefiniuj człowieka, warto by miał pola takie jak `'wiek'`, a także `'imie'`
2. Skorzystaj z obiektu

```
let myClass = {
    title:  'JavaScript jest świetny',
    room: {
        number: 112,
        numberOfSits: 30,
        owner: {
            name: 'Maciej Wij',
            teachFrom: 'Chemist'
        }
    }
}

```
Wypisz:
- tutył klasy
- ile osób może zmieścić się w pokoju
- czego uczy właściciel klasy

3. Skorzystaj z obiektu
```
let myGroup = {
    menthor: 'Wojtek',
    members: [
        {
            name: 'Janek',
            age: 22
        },
        {
            name: 'Asia',
            age: 12
        },
        {
            name: 'Marek',
            age: 33
        },
        {
            name: 'Andrzej',
            age: 44
        },
        {
            name: 'Jaś',
            age: 24
        },
        {
            name: 'Wokay JSON',
            age: 19
        }
    ]
}
```

Wypisz:
- mentora grupy
- ilość osób w klasie
- sume wieku wszystkich osób w klasie
- średnia wieku w klasie

4. Skorzystaj z obiektu powyżej i znajdź możliwe klasy, w których grupa mogła by mieć zajęcia, listę klas znajdziesz niżej,
Uwaga ze względu, że szkolenie odbywa się w szkole samochodowej to mechanicy zostawili pewne plakaty, które nie powinny zobaczyć osoby nieletnie.
Każda sala posiada atrybut `minAge` który definiuje od jakiego wieku można tam wejść ;>
```
let classAvaiable = [
    {
        name: 'A',
        number: 1,
        slots: 5,
        minAge: 10
    },
    {
        name: 'B',
        number: 2,
        slots: 10,
        minAge: 15
    },
    {
        name: 'C',
        number: 3,
        slots: 10,
        minAge: 0
    },
    {
        name: 'D',
        number: 4,
        slots: 15,
        minAge: 30
    },
    {
        name: 'E',
        number: 5,
        slots: 2,
        minAge: 5
    },
    {
        name: 'F',
        number: 6,
        slots: 12,
        minAge: 10
    },
    {
        name: 'G',
        number: 7,
        slots: 3,
        minAge: 40
    },
    {
        name: 'H',
        number: 8,
        slots: 30,
        minAge: 20
    }
]

```

