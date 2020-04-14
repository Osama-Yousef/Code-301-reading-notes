# Read: 14a Summary 
## DB Normalization
* Database normalization is a process used to organize a database into tables and columns.  The main idea with this is that a table 
should be about a specific topic and only supporting topics included. Take a spreadsheet containing the information as an example, where
the data contains salespeople and customers serving several purposes:
  * Identify salespeople in your organization
  * List all customers your company calls upon to sell a product
  * Identify which salespeople call on specific customers.
  
***By limiting a table to one purpose you reduce the number of duplicate data contained within your database. This eliminates some
issues stemming from database modifications.***

* To achieve these objectives, we’ll use some established rules. As you apply these rules, new tables are formed. The progression
from unruly to optimized passes through several normal forms.
* There are three normal forms most databases adhere to using.  As tables satisfy each successive database normalization form, they 
become less prone to database modification anomalies and more focused toward a sole purpose or topic.

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
### Search and Sort Issues

* We use normalization too to make it easier to search and sort your data.***by separating the data into different tables. This puts
the data into tables serving a single purpose.***

### Definition of Database Normalization
> There are three common forms of database normalization: 1st, 2nd, and 3rd normal form. They are also abbreviated as 1NF, 2NF, 
and 3NF respectively. 

***The forms are progressive, meaning that to qualify for 3rd normal form a table must first satisfy the rules for 2nd normal
form, and 2nd normal form must adhere to those for 1st normal form.***

* let’s summarize the various forms (three rules for database normalization that upon each other) :
  * `First Normal Form `– The information is stored in a relational table with each column containing atomic values. There are
  no repeating groups of columns.
  * `Second Normal Form `– The table is in first normal form and all the columns depend on the table’s primary key.
  * `Third Normal Form `– the table is in second normal form and all of its columns are not transitively dependent on the primary key.






