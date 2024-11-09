
==A key== consists of one or more attributes that determine other attributes. For example, an invoice number identifies all of the invoice 
attributes, such as the invoice date and the customer name.

==Determination== is the state in which knowing the value of one attribute makes it possible to determine the value of another. 

If you consider what the attributes of the STUDENT table actually 
represent, you will see a relationship among the attributes. If you are given a value for STU_NUM, then you can determine the value for STU_LNAME because one and only one value of STU_LNAME is associated with any given value of STU_NUM. A specific 
terminology and notation is used to describe relationships based on determination. 
The relationship is called ==functional dependence==, which means that the value of one or more attributes determines the value of one or more other attributes. The standard 
notation for representing the relationship between STU_NUM and STU_LNAME is 
as follows:

In this functional dependency, the attribute whose value determines another is called the ==determinant== or the key. The attribute whose value is determined by the other attribute is called the ==dependent==. Using this terminology, it would be correct to say that STU_NUM is the determinant and STU_LNAME is the dependent. STU_NUM functionally 
determines STU_LNAME, and STU_LNAME is functionally dependent on STU_NUM. 


## Types of keys

A ==composite key== is a key that is composed of more than one attribute. An attribute that is a part of a key is called a ==key attribute== 
A ==superkey== is a key that can uniquely identify any row in the table. In other words, a superkey functionally determines every attribute in the row



==Entity integrity== is the condition in which each row (entity instance) in the table has its own unique identity. To ensure entity integrity, the primary key has two requirements: 

   ~ all of the values in the primary key must be unique, and (2) no key attribute in the primary key can contain a null.

A null is the absence of any data value, and it is never allowed in any part of the primary key