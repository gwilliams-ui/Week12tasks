1. Create an Entity-Relationship Diagram (ERD) showing entities, attributes, and relationships.

You may:
Hand-draw the ERD, and take a clear photo of the drawing.
OR use a digital tool (e.g., Figma, Canva, draw.io), and take a screenshot.

2. Save the image and place it in a “Task2” folder.

3. SQL Schema

Write CREATE TABLE statements for at least three entities, including:
- Primary keys (PK)
- Foreign keys (FK)
- Appropriate data types and NOT NULL constraints.

Please add your SQL query below AND add an explanation: 

(copy and paste SQL Query here)
Create Table Author(
AuthorID INT PRIMARY KEY, 
[Name] VARCHAR (25) Not Null, 
Nationality VARCHAR (25) Not Null,
); 

Create Table Book(
BookID INT PRIMARY KEY,
Title VARCHAR (50) Not null, 
Genre VARCHAR (25) Not Null, 
Pubilcation VARCHAR (25) Not Null,
); 

Create Table Member(
MemberID INT PRIMARY KEY,
[Name] Varchar (25) Not Null,
Email Varchar (25), 
Phone Varchar (25), 
); 

(add an explanation of your query here)

Each table organizes a different type of data for a bookstore. 
4. Save this file in a "Task2" folder along with your ERD diagram

5. For submission, commit and push your "Task2" folder with the two files to your GitHub.
