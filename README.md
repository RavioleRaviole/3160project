# Campus Eats - ITCS 3160 Project

TEAM:

Thomas Bilbao,
Nanayaw Boakye,
Daniel Camacho,
Benson Huynh,
Isabella Ochsner

OVERVIEW:

1)  Given an existing database, review the Entity Relationship Diagram and Database to understand the database structure.  This can be done locally by each team member using the SQL script that is provided for the database.
2)  Review the “BACKGROUND” information below – carefully.
3)  Either work locally with the database (this is a good place to start) or load the database to cloud services (GCP or Azure may be available). Set up admin access privileges for all members of your project group (team).
4)  Following proper guidelines for fully normalized relational databases, the use case requires the addition of a rating system for both drivers and restaurants.  The rating files must show supertypes and subtypes. Load the tables with sufficient test data (http://www.generatedata.com can be used – 20 or more rating records per table in most cases).
5)  Create stored procedures that provide the highest and lowest ratings for drivers and restaurants, and the average rating for drivers and restaurants.  Test the stored procedures and show the output.
6)  Also demonstrate:a. Two views which employ joins, nested selects or subqueries, conditions, and where/sorting (requiring indexing)b. Query optimization (Use of Explain, slow query log, discuss use of indexes for 

BACKGROUND: 

With the threat of the Corona virus, food delivery services are more important than ever.  Local restaurants are eager to find easy ways to have food delivered to customers without having to hire delivery employees. Even when things return to normal, many experts feel that food delivery will be something that we all will have become accustomed to as a part of our regular activites (even more than before).  Students love food delivery services on campus.  Campuses do not like the steady stream of visitors that may or  may not have a formal connection with the university.  Companies such as UberEats and GrubHub are happy to deliver on campus, but many schools are wondering if they should take control of the delivery and ensure that students and 
authorized university employees are the only ones delivering food on campus for safety and health reasons.One startup that has tried to tackle this problem  is http://www.craveoncampus.com The company is a startup and  the site shows evidence of the system design.  Your assignment is to understand a test database for a campus controlled food delivery service similar to craveoncampus.com.  You will be enhancing the database with a rating system for both restaurants and delivery drivers.  You can also look at grubhub and ubereats for ideas.  Please remember this is extending a prototype for the database not a fully implemented working model.   

