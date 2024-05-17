1. SELECT DISTINCT replacement_cost FROM film;

   ![](./images//1.png)

2. SELECT COUNT(DISTINCT replacement_cost) FROM film;

   ![](./images//2.png)

3. SELECT COUNT(*) FROM film
   WHERE (title LIKE 'T%') AND (rating IN ('G'));

   ![](./images//3.png)

4. SELECT COUNT(*) FROM country
   WHERE country LIKE '_ _ _ _ _';

   ![](./images//4.png)

5. SELECT COUNT(*) FROM city
   WHERE city ILIKE '%R';

   ![](./images//5.png)
