# Data Folder

## Folders

### raw
Original, unmodified data after downloading, scraping, etc.

### final
Data after all cleaning, processing, and analyzing.

---

## Data dictionary

| Field                | Type     | Source            | Description                                                                                     |
|----------------------|----------|-------------------|-------------------------------------------------------------------------------------------------|
| `rank_2021`          | Integer  | Kaggle dataset    | This is the ranking of each movie in 2021 (based on IMDB user rating)                          |
| `rank_2024`          | Integer  | IMDB.com          | This is the ranking of each movie in 2024 (based on IMDB user rating)                          |
| `title`              | Object   | Both              | Title of the movie                                                                             |
| `year`               | Integer  | Both              | Year the movie was released                                                                    |
| `run_time`           | Integer  | Both              | The duration of the movie in minutes                                                          |
| `IMDB_rating_2021`   | Float    | Kaggle dataset    | User rating of the movie on IMDB scale (1-10)                                                 |
| `IMDB_rating_2024`   | Float    | IMDB.com          | User rating of the movie on IMDB scale (1-10)                                                 |
| `average_rating`     | Float    | Both              | Average of the user rating on the IMDB scale (1-10) between 2021 and 2024                     |
| `genre`              | Object   | Kaggle dataset    | Genres of the movie                                                                           |
| `box_office`         | Float    | Kaggle dataset    | Total box office revenue collection across the world (in $ USD)                               |
| `budget`             | Float    | Kaggle dataset    | The total cost of producing the movie (in $ USD)                                              |
| `certificate`        | Object   | Kaggle dataset    | Movie Certificate (PG-13, R, PG, etc.)                                                        |
| `tag_line`           | Object   | Kaggle dataset    | A slogan/catchphrase used to promote the movie                                                |
| `cast`               | Object   | Kaggle dataset    | List of main actors and actresses or anyone that appeared as part of the cast in the movie    |
| `directors`          | Object   | Kaggle dataset    | The person responsible for overseeing the creative aspects of the film                        |
| `writers`            | Object   | Kaggle dataset    | List of writers that created and wrote the script/story of the movie                          |
| `popularity_score`   | Integer  | IMDB.com          | Additional ranking encompassing present user interaction with the movies                      |
| `metascore`          | Integer  | IMDB.com          | Numeric score that combines user and critic ratings and reviews (1-100)                       |
| `oscars`             | Object   | IMDB.com          | Number of Oscars won by the movie                                                             |
| `url`                | Object   | IMDB.com          | Link to each movie’s page pulled from the list                                                |

