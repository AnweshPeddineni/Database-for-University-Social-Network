# DMDD-Project

Created 11 entities 
1. User 2. Group 3. Professor 4. Employer 5. Student
6. Post 7. General Post 8. Marketplace Post
9. Post Like 10. Comment 11. Comment Like

Used SQL DDL statements for Create and Insert, Used Encryption of password using Encryption Key before inserting, Made use of SQL triggers and Computed Functions and Stored Procedures, SQL views, Non-clustered indexes have also been used. Used Tableau for Data visualization.

The User entity is a generalized entity with subtypes such as Student, Professor, Employer, and Group. These subtypes inherit attributes and relationships from the User entity.
A Group can have its user account and can perform actions like posting, commenting, and liking related to specific topics.
Each Student will be under a Major and each professor will have a research interest which helps in personalizing the user’s feed.
Items that users want to sell should be posted as a part of the Marketplace Post which is separated from general post.


Team 20
Names :
Payal Nagaonkar – 002658318
Anwesh Peddineni – 002775775
Smrithi Jagithyala – 002658318
Aditya Ramesh Mysore – 002774017
Ritika Mangamuru - 002651513
