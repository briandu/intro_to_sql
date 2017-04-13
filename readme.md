[See assignment in Alexa.](https://alexa.bitmaker.co/cohorts/72/assignments/2244/latest)

1. Marvin and Deep Thought

SELECT * FROM robot


2. C3P0

SELECT * FROM robot


3.

SELECT nut_free, name FROM recipes WHERE nut_free = true;

t        | Butternut Squash Bake
t        | Vegetarian Bibimbap
t        | French Veggie Loaf
t        | Quinoa and Black Beans
t        | Juicy Roasted Chicken
t        | Garlic Green Beans
t        | Stout Slow Cooker Corned Beef and Veggies


4. 5

SELECT COUNT(gluten_free) FROM recipes WHERE
gluten_free = true;

count
-------
    5
(1 row)


5. Octopus

SELECT name, number_of_legs FROM animals ORDE
R BY number_of_legs DESC;

name       | number_of_legs
------------------+----------------
octopus          |              8
sheep            |              4
cat              |              4
cow              |              4
bat              |              2
duck             |              2
owl              |              2
chicken          |              2
whale            |              0
hammerhead shark |              0

(10 rows)


6. Sushi Go

SELECT name, mins_to_play FROM board_games ORDER BY mins_to_play ASC;

name          | mins_to_play
------------------------+--------------
Sushi Go               |           15
Quixo                  |           15
Quarto                 |           20
Cards Against Humanity |           30
7 Wonders              |           30
7 Wonders              |           30
Dixit                  |           30
Bohnanza               |           45
Carcassonne            |           45
Game of Things         |           45
Agricola               |          120


7. Stout Slow Cooker Corned Beef and Veggies

intro_to_sql=# SELECT name, minutes_required FROM recipes ORDER BY minutes_required DESC

name                    | minutes_required
-------------------------------------------+------------------
Stout Slow Cooker Corned Beef and Veggies |              390
French Veggie Loaf                        |              105
Juicy Roasted Chicken                     |              100
Butternut Squash Bake                     |               55
Quinoa and Black Beans                    |               50
Vegetarian Bibimbap                       |               50
Couscous with Olives and Sun-Dried Tomato |               50
Garlic Green Beans                        |               25
Vietnamese Rice-Noodle Salad              |               15
(9 rows)


8. Marvin and Mr. Butlertron

intro_to_sql=# SELECT name FROM robots WHERE name LIKE 'M%';

      name
----------------
 Marvin
 Mr. Butlertron
(2 rows)


9. 3

SELECT COUNT(name) FROM board_games WHERE max_players >= 8;
 count
-------
     3
(1 row)
