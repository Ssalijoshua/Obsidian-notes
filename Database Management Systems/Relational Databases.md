#### 3-1 A Logical View of Data
The relational data model allows the designer to focus on the logical represen-
tation of the data and its relationships, rather than on the physical storage details. To use an automotive analogy, the relational database uses an automatic transmission to relieve you of the need to manipulate clutch pedals and gearshifts. In short, the relational model
enables you to view data logically rather than physically.

##### 3-1a Tables and Their Characteristics
A table is also called a ==relation== because the relational model’s creator, E. F. Codd, used the two terms as synonyms.

==Domain== refers to an attributes range of possible values
==Attribute== refers to a column in the table in a table [[Entity Relationship Modelling]]

###### Characteristics of a table or relation
- A table is perceived as a two-dimensional structure composed of rows and columns.
- Each table row (tuple) represents a single entity occurrence within the entity set.
- Each table column represents an attribute, and each column has a distinct name.
- Each intersection of a row and column represents a single data value.
- All values in a column must conform to the same data format.
- Each column has a specific range of values known as the attribute domain.
- The order of the rows and columns is immaterial to the DBMS.
- Each table must have an attribute or combination of attributes that uniquely identifies each row.

#### 3-2 Keys
