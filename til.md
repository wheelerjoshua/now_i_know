##Today I learned...

-- 09-20-21: 
I learned how to use MySQL clauses WHERE, ORDER BY, LIMIT, and OFFSET.

-- 09-21-21: 
I learned that I can return things that start and end with a specification by using "..%.." eg. "E%e" will return strings that start and end with "e". Use option and click to add multiple cursors in VS Code. 
Knowing when to refine your while using GROUP BY by WHERE and HAVING clauses can be confusing. If your specifications are dependent on the GROUP BY being there, it must be coded after the GROUPY BY using the HAVING clause. If you're refining your SELECT before being grouped, it can be coded in the WHERE clause.

eg. Last names that start and end with an 'e' would be included in the WHERE clause, while querying the number of unique last names where the count is greater than a number would be included in the HAVING clause.

-- 09-22-21:
I learned that when a question may be subjected to interpretation to leave a note on my personal judgement calls. If that judgement call is above my head or pay grade, ask questions. Alternate viewpoints on code may reveal these scenarios.