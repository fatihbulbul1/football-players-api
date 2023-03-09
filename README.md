# Turkish Super League API

![](./screenshot.png)

# Overview

- This API contains personal informations for 491 players of **17\*** Turkish clubs'.
- API is current as of 25.02.2023.
- API info is in Turkish.

\*Due to the Kahramanmaraş earthquake that occurred, 2 football clubs (Hatayspor and Gaziantep FK) decided to withdraw from league and their **teamless** players are not included.

# API Structure

Example player structure:

```json
{
    "number": 17,
    "name": "Nicolò Zaniolo",
    "position": "On Numara",
    "team": "Galatasaray",
    "nations": ["İtalya"],
    "age": 23,
    "contract": "30 Haz 2027",
    "value": "30.00 mil. €"
}
```

---

# Premier League Players API

![](./screenshot-pl.png)

# Overview

- This API contains personal informations for 534 players of 20 Premier League clubs'.
- API is current as of 28.02.2023.
- API info is in English.

# API Structure

Example player structure:

```json
{
  "number": "9",
  "name": "Erling Haaland",
  "position": "Centre-Forward ",
  "team": " Manchester City",
  "nations": ["Norway", "England"],
  "age": "22",
  "contract": "Jun 30, 2027",
  "value": "€170.00m"
}
```

---

# Bundesliga Players API

![](./bundesliga.png)

# Overview

- This API contains personal informations for 519 players of 18 Bundesliga clubs'.
- API is current as of 02.03.2023.
- API info is in English.

# API Structure

Example player structure:

```json
{
    "number": 22,
    "name": "Jude Bellingham",
    "position": "Central Midfield",
    "team": "Borussia Dortmund",
    "nations": ["England"],
    "age": 19,
    "contract": "Jun 30, 2025",
    "value": "€110.00m"
}
```

---

# Ligue 1 Players API

![](./ligue1.png)

# Overview

- This API contains personal informations for 529 players of 20 Ligue 1 clubs'.
- API is current as of 02.03.2023.
- API info is in English.

# API Structure

Example player structure:

```json
{
    "number": 30,
    "name": "Lionel Messi",
    "position": "Right Winger",
    "team": "Paris Saint-Germain",
    "nations": ["Argentina", "Spain"],
    "age": 35,
    "contract": "Jun 30, 2023",
    "value": "€50.00m"
}
```

---

# La Liga Players API

![](./laliga.png)

# Overview

- This API contains personal informations for 493 players of 20 La Liga clubs'.
- API is current as of 02.03.2023.
- API info is in English.

# API Structure

Example player structure:

```json
{
    "number": 9,
    "name": "Karim Benzema",
    "position": "Centre-Forward",
    "team": "Real Madrid",
    "nations": ["France", "Algeria"],
    "age": 35,
    "contract": "Jun 30, 2023",
    "value": "€35.00m"
}
```

---

# Serie A Players API

![](./seriea.png)

# Overview

- This API contains personal informations for 560 players of 20 Serie A clubs'.
- API is current as of 02.03.2023.
- API info is in English.

# API Structure

Example player structure:

```json
{
    "number": 11,
    "name": "Zlatan Ibrahimović",
    "position": "Centre-Forward",
    "team": "AC Milan",
    "nations": ["Sweden", "Bosnia-Herzegovina"],
    "age": 41,
    "contract": "Jun 30, 2023",
    "value": "€2.00m"
}
```
---
# Changelog v1.1

- "Number" and "age" fields are now integer.
- ```U+00a0``` invisible characters removed.
- Unnecessary spaces at "position" and "team" fields are removed.
### Author

- LinkedIn - [Ömer Fatih Bülbül](https://www.linkedin.com/in/ömer-fatih-bülbül-74a890236/)
- Twitter - [fatihbulbul91](https://twitter.com/fatihbulbul91)
