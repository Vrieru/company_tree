# company_tree

The company tree as the following DB table structure.
+-------+---------------+---------------------------+--------------------------------------+
|   id  |   parent_id   |           title           |               details                |
+-------+---------------+---------------------------+--------------------------------------+
|   1   |       0       |   Parent Page             |    Has no parent                     |
|   2   |       1       |   Sub Page                |    Has a parent and child            |
|   3   |       2       |   Sub Sub Page            |    Is the same as its parent         |
|   4   |       0       |   Another Parent Page     |    I am a parent with no children    |
+-------+---------------+---------------------------+--------------------------------------+

TODO
- Creature an easy SQL import for local use.
- Create a basic index that displays all records.
