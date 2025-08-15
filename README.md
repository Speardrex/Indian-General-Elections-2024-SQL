# ![Logo](https://github.com/Speardrex/Indian-General-Elections-2024-SQL/blob/main/Screenshot%202025-08-12%20224046.png)  **Indian General Elections 2024 SQL Project**
## Project Overview
The Indian General Election, conducted by the Election Commission of India (ECI), is the world’s largest democratic exercise, spanning 543 parliamentary constituencies to elect members of the Lok Sabha (House of the People). This project aims to design and implement a SQL-based database system to store, manage, and analyze data from the Indian General Elections. The system will enable structured querying of election results, voter demographics, and political party performance
## Entity Relationship Diagram (ERD)
![ERD](https://github.com/Speardrex/Indian-General-Elections-2024-SQL/blob/main/Model%20databases.png)


## Database Schema

The project uses five main tables:

1. **Constituencywise Results**: Contains information about constituencywise results.
   - `Parliament Constituency`: name and the number together of each constituency.
   - `Constituency Name`: Name of the Constituency.
   - `Winning Candidate`: Person who got elected.
   - `Total Votes`: Number of votes gained.
   - `Margin`: Won by the number of votes.
   - `Constituency ID`: Unique identifier for each constituency.
   - `Party ID`: Unique identifier for each party.

2. **Constituencywise Details**: Detail information on candidate, votes, percentage of votes.
   - `Candidate`: A candidate is ultimately an applicant for a position.
   - `Party`: Name of the party.
   - `EVM Votes`:Electronic Voting Machine votes.
   - `Postal Votes`: Votes by physically attending.
   - `Total Votes`: Sum of EVM & Postal votes.
   - `% of Votes`: Percentage of votes
   - `Constituency ID`: Unique identifier for each constituency.

3. **Statewise Results**: Details about state results.
   - `Constituency`: Name of the Constituency.
   - `Const. No.`: Number for each constituency.
   - `Parliament Constituency`: name and the number together of each constituency.
   - `Leading Candidate`: A leading candidate is the person who is ahead in votes.
   - `Trailing Candidate`: A trailing candidate is a person who is behind in votes.
   - `Margin`: Indicates how much one candidate is ahead or behind another.
   - `Status`: Whether votes are still being counted, certified, or contested.
   - `State ID`: Unique identifier for each state.
   - `State`: Name of the state.

4. **Partywise Results**: Stores result depending on parties.
   - `Party`: Name of the party.
   - `Won`: Number of seats won.
   - `Party ID`: Unique identifier for each party.

5. **States**: Contains information about state.
   - `State ID`: Unique identifier for each state.
   - `State`: Name of the state.

## Objectives
The project is split into two tiers of questions to test SQL skills of increasing complexity:
### Intermediate
1.Total Seats
2.What are the total number of seats available for election in each state?
3.Total seats won BY NDA Alliance
4.Seats Won by NDA Alliance Parties
5.Total Seats Won by I.N.D.I.A. Allianz
6.Seats Won by I.N.D.I.A Alliance Parties
7.Adding a new column field in the table partywise_results to get the party allianz as NDA or I.N.D.I.A
8.Add party alliance as NDA Allianz
9.Add party alliance as I.N.D.I.A Allianz
10.Add other party alliance as Other.
