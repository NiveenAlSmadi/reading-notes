# DB Normalization
A process used to organize a database into tables and columns. 
- Limit a table to one purpose helps reduces the number of duplicate data. 
- Helps minimize issues.
- Minimizes modification issues.
- Simplifies queries.
- Tables should have one purpose. Many purposes decreases performance and are difficult to maintain. 
- Use multiple related tables to minimize redundancy.
- We need to reduce repetition of similar data to avoid insertion, deletion, and update issues.
#
Redundancy increases the amount of storage we are using. We can avoid this by avoided the storage of similar data in one table database.
In simpler words, we need to avoid repeating data. Normalization is a way of organizing things.
#
An example of this is having one table for student names and another table for branch. Student table will save student data and the branch will hold the branch data for the student. It's a bit more organized as well and also easier to read. We can connect both tables by adding the branch name into the student table. When the student data is updated the branch will also be updated because it is linked to the student table. This reminds me of smaccs in css.
## Reasons for Database Normalization
There are three main reasons to normalize a database.  The first is to minimize duplicate data, the second is to minimize or avoid data modification issues, and the third is to simplify queries. 
### Reasons for Database Normalization
* to minimize duplicate data
* to minimize or avoid data modification issues
* to simplify queries. 

***Having the table serve many purposes introduces many of the challenges; namely, data duplication, data update issues, and 
increased effort to query data.***

### Data Duplication and Modification Anomalies

* Duplicated information presents two problems:

  * It increases storage and decrease performance.
  * It becomes more difficult to maintain data changes.
  
* There are three modification anomalies that can occur:

  * ` Insert Anomaly` : There are facts we cannot record until we know information for the entire row. in order to create the
  record, we need provide a primary key.
  * `Update Anomaly` : if we have the same information in several rows, and If we don’t update all rows, then inconsistencies appear.
  * `Deletion Anomaly` : Deletion of a row causes removal of more than one set of facts.