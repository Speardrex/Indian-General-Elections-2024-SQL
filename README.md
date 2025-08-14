# ![Logo](https://github.com/Speardrex/Indian-General-Elections-2024-SQL/blob/main/Screenshot%202025-08-12%20224046.png)  **Indian General Elections 2024 SQL Project**
## Project Overview
## Database Schema

The project uses five main tables:

1. **Constituencywise Results**: Contains information about constituencywise results.
   - `Parliament Constituency`: Unique identifier for each constituency.
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
   - `Constituency`: Unique identifier for each product.
   - `Const. No.`: Name of the product.
   - `Parliament Constituency`: References the category table.
   - `Leading Candidate`: Date when the product was launched.
   - `Trailing Candidate`: Price of the product.
   - `Margin`:
   - `Status`:
   - `State ID`:
   - `State`:

4. **Partywise Results**: Stores sales transactions.
   - `Party`: Unique identifier for each sale.
   - `Won`: Date of the sale.
   - `Party ID`: References the store table.

5. **States**: Contains information about warranty claims.
   - `State ID`: Unique identifier for each warranty claim.
   - `State`: Date the claim was made.

