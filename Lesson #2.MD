#### Entity
- something of importance to user or organization that needs to be represented in db
- represents one theme, topic or business concept
- entity-relationship model, resticted to things that can be represented using a single table 

#### Characteristics of a Relation
- rows contain data about instances of an entity
- columns contain data about attributes of the entity
- cells hold a single value
- all values in a column are of the same kind (data type)
- each column has a unique name
- the order of the columns is unimportant
- the order of rows is unimportant
- no two rows can be identical
- each cell has ONLY 1 value

#### Synonyms
- table, file, relation
- row, record, tuple
- column, field, attribute

#### Keys
- is one or more columns of a relation whose values are used to identify a row
- type of keys
    - unique - data value is unique for each row- it will identify only 1 row
    - non-unique - data value may be shared among several rows- it will identify a set of rows

#### Dan's Typology of Databse Keys
- unique
    - candidate key
        - has potential to become primary key
    - composite key
        - composed of two or more attributes 
    - primary key
        - main identifier for relation 
    - surrogate key
        - numeric value that is added to a relation to serve as the primary key
    - have no meaning, usually hidden on forms, queries and reports
    - used in place of composite key
- non-unique
    - foreign key
        - to establish relationships, we need to implement a foreign key
        - it is primary key from one table, put to another

#### Referential Integrity
- every value of foreign key must match a value of xisting primary key 