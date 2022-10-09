# Movies

## Název

movies.XML

## Specifikace

Kódováno v UTF-8

## Příklad

[demo příklad](https://github.com/Filsonprg/movies.xml/blob/5f444838ebea6771b40a1b22266eb59d990442d8/movies.xml)

### `<movies>`
- **Hlavní atribut**
- Atribut pro filmy

### `<movie>`
- Atribut pro film
- podkategorie `<movies>`
- Atributy:
    - `id`: identifikátor
    - `name`: název filmu
    - `year`: rok vydání

### `<genres>`
- **Hlavní atribut** 
- Atribut pro žánry
- podkategorie `<movie>`

### `<genre>`
- Atribut pro žánr
- podkategorie `<genres>`
- Atributy:
    - `id`: identifikátor
    - `name`: název žánru
