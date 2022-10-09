# Movies

## Název

movies.XML

## Specifikace

Kódováno v UTF-8

## Příklad

[demo příklad](movies.xml)

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
