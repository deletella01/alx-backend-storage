## MySQL advanced

Indexing is a powerful structure in MySQL which can be leveraged to get the fastest response times from common queries. MySQL queries achieve efficiency by generating a smaller table, called an index, from a specified column or set of columns. These columns, called a key, can be used to enforce uniqueness.
Queries utilize indexes to identify and retrieve the targeted data, even if they are a combination of keys. Without an index, running that same query results in an inspection of every row for the needed data. Indexing produces a shortcut, with much faster query times on expansive tables.

Indexing is only advantageous for huge tables with regularly accessed information. For instance, to continue with our textbook analogy, it makes little sense to index a childrens storybook with only a dozen pages. It's more efficient to simply read the book to find each occurrence of the word turtle than it would be to set up and maintain indexes, query for those indexes, and then review each page provided. In the computing world, those extra tasks surrounding indexing represent wasted resources which would be better purposed by not indexing.

Without indexes, when tables grow to enormous proportions, response times suffer from queries targeting those obtuse tables. Inefficient queries manifest into latency within application or website performance. We commonly identify this latency by using the MySQL slow query log feature.
Once a colossal table hits its tipping point, it reaches the potential for downtime for applications and websites. Conducting routine evaluations for growing database establishes optimal database performance and sidesteps long queries' inherent interruptions.
