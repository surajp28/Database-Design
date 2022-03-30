# Database-Design
Database Design library Management
MU Library Management System
Suraj Punjabi – spunjab@iu.edu
Vighnesh Kolhatkar - vkolhatk@iu.edu 

MU Library Management System is used to keep a track of the students as well as faculty members that borrow books from the library. MU is an acronym for the Mumbai University which contains multiple colleges. The purpose of the database is to create a centralized library system to provide ease of convenience for the library staff and replace the current paper-based file system with the database system that would be used to retrieve information easily. The system will be highly useful to the library staff in order to access book as well as borrower information. Having entities such as the book author and the book publisher would further enhance the book search operation to help users work with specific publishers or authors. The following information will be captured as part of the Database –

1.	For each book, the system will keep a track of the unique book identifier along with the book title and the book publisher name.
2.	For each publisher, the system will keep a track of the unique publisher identifier with the publisher’s name, address and phone.
3.	For each author, the system will keep a track of the unique author identifier, along with the book identifier that was written by an author and the author’s name.
4.	Every book has more than one copy at the library. For every copy of a book, the system will keep a track of the unique copy identifier along with the original book, the branch where the copy is situated and the number of copies for the book.
5.	For each borrower, the system will keep track of the unique borrower card number along with borrower name, address and phone number.
6.	The University has multiple colleges and hence multiple library branches. For each library branch, the system will keep track of the unique branch identifier along with the branch name and branch address.

Relationships:
1.	Multiple books can be written by multiple authors. 
2.	Multiple books can be published by one publisher.
3.	A book has multiple copies.
4.	One borrower can borrow multiple copied of the book.
5.	Multiple branches may or may not have copies of the book.

These relations can be further understood with EERD and Relational diagrams shows below

EERD:

 

Relational Schema:

 

Data and Normalization:
The data source will be achieved by inserting values manually. 
1NF: To achieve this, the design is set in a way that a column would not have multiple values.
2NF: To achieve this, every element in a row would be dependent on the primary key. As shown in diagrams above, the attributes of an entity belong to the primary key.
3NF: The final normalization standard was achieved by ensuring that the columns are only dependent on one primary key.

Tools And Technologies.
MySQL as the Database Management System. Due to the interface and high efficiency it’s a good choice that is easy to access, understand and work with.
![image](https://user-images.githubusercontent.com/64825150/160893463-0e198fee-d729-4243-a051-05c7703b204b.png)
