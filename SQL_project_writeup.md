# **SQL Project Briefing**
## **Background**
In this scenario, we had been hired by a mobile game company to gain insights on player retention. In this game, players from across the globe can interact with one another by engaging in a head-to-head "match". Additionally, we were told that there exists a store in this game where players can purchase items of various kinds.

To start, building a table schema helped visualize where certain elements existed, where records could be connected, and how more elaborate questions could be answered in the deeper levels of analysis. 

~INSERT TABLE SCHEMA IMAGE HERE~

Beginning with a phase of exploratory data analysis (EDA), the “financial” side of the schema showed:
* distinct items
* range of prices
* number of transactions
* total sales

Similarly, on the "interaction" side of the schema revealed:
* number of players
* number of matches
* number of unmatched
* average matches per player

These numbers, to have on hand, served as quick references for quality assurance checks throughout the analysis. 

## **Constructing the Retention Table**

The task involved constructing a table that included columns for each of:
1. day (of game’s lifespan)
1. number of players joined (on given days)
1. number of retained players (i.e., players that joined on the given day and ended up being retained)
1. fractional retention




