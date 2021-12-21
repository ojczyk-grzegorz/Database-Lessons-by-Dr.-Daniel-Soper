#### Components of Database System
- users <->
- database application <->
- [database management system](#database-management-system) (dbms) <->
- database

#### Database Contents
- user data
- metadata
- indexes and other overhead data
- application metadata

#### Database Management System
- intermediary between database app and database
- manages and controls db activities
- creates, processes and administers db it controls
- functions
    - creates dbs
    - creates tables
    - creates supporting structures
    - reads database data
    - modifies db data (inserts, updates, deletes)
    - maintains db structures
    - enforces rules/ constraints
        -e.g. Referential integrity constraints
            - ensures that values of a column in one table are valid based on values in another table
    - controls concurrency
    - provides security
    - performs data backup and recovery

#### Personal Database Systems
- contents
    - user <->
    - [database application <-> dbms] <->
    - database
- examples
    - Ms Access

#### Enterprise-Level Databases Systems
- support several users simultaneously
- support more than 1 app
- involve multiple computers
- are complex in design
- have many tables
- have many databases