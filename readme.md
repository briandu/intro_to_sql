[See assignment in Alexa.](https://alexa.bitmaker.co/cohorts/72/assignments/2244/latest)

1.

SELECT * FROM robot
Marvin and Deep Thought


2.

SELECT * FROM robot
C3PO


3.

SELECT nut_free, name FROM recipes WHERE nut_free = true;

t        | Butternut Squash Bake
t        | Vegetarian Bibimbap
t        | French Veggie Loaf
t        | Quinoa and Black Beans
t        | Juicy Roasted Chicken
t        | Garlic Green Beans
t        | Stout Slow Cooker Corned Beef and Veggies


4.

SELECT COUNT(gluten_free) FROM recipes WHERE
gluten_free = true;

count
-------
    5
(1 row)


5.

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
