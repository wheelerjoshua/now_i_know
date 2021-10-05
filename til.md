##Today I learned...

-- 09-20-21: 
I learned how to use MySQL clauses WHERE, ORDER BY, LIMIT, and OFFSET.

-- 09-21-21: 
I learned that I can return things that start and end with a specification by using "..%.." eg. "E%e" will return strings that start and end with "e". Use option and click to add multiple cursors in VS Code. 
Knowing when to refine your while using GROUP BY by WHERE and HAVING clauses can be confusing. If your specifications are dependent on the GROUP BY being there, it must be coded after the GROUPY BY using the HAVING clause. If you're refining your SELECT before being grouped, it can be coded in the WHERE clause.

eg. Last names that start and end with an 'e' would be included in the WHERE clause, while querying the number of unique last names where the count is greater than a number would be included in the HAVING clause.

-- 09-22-21:
I learned that when a question may be subjected to interpretation to leave a note on my personal judgement calls. If that judgement call is above my head or pay grade, ask questions. Alternate viewpoints on code may reveal these scenarios.

-- 09-23-21:
I learned how powerful aliases can be. When joining tables and there's a lot of information being passed around, lengthy names can create clutter and confusion when analyzing code. Using aliases on tables reduces the clutter and confusion. I also learned about self joins.

-- 09-27-21:
I learned about subqueries and how quickly they can become complicated. I also learned how to create temporary tables using queries and how to add and remove things from them, along with how critical it is to make sure you're working from a personal database so you don't ruin the main database.

-- 09-28-21:
I learned about case statements and how they can be used to create pivot tables.

-- 09-29-21:
I learned that the solution I come up with might not always be the most efficient or simple and to always pay attention to your table for undesired duplicates.

-- 09-30-21:
I learned how complicated environment setup could potentially become. A simple misinterpretation of where something is installing can interrupt the entire process. Being able to identify where homebrew is installing may enable a more streamlined effort in future environment setups. I also learned broadly about how powerful jupyter notebook is and what can be done with it.

-- 10-01-21:
I learned that converting for loops into list comprehensions is both complicated and simple. I also learned that googling the answer sometimes makes things a lot more difficult than working through a solution on your own.

-- 10-04-21:
I was able to practice with dictionaries a little more and I learned that the more you use them, the less intimidating they become.

-- 10-05-21:
Today I learned of a better method to break while loops than using a user choice variable, setting while True, then breaking if the user decides not to continue.
