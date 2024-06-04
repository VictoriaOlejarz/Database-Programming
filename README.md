# Database Programming (PostreSQL, SQLalchemy/Python)

## Creating a database based on the cosmetic/beauty store Sephora.
## Database Programming Project includes:
- Project description
- Entity Relationship Diagram
- Relational Schema
- Relational Table Details
- DDL + DML + SQL Script
- SQL and ORM Queries


## 1. Introduction
We are looking at the entity relationships within Sephora. Sephora is a retail store that sells products from various cosmetic brands. Their inventory includes items such as makeup, hair care, and skincare. Sephora has various locations across the United States. The entity relationship diagram visualizes the relationship between sephora locations, brands, employees, categories, and products. 
 
## 2. Description of the Organization
The SEPHORA Database (SEPHORA) stores relevant information regarding a company’s employees within categories and different products and brands sold within those categories. The SEPHORA Database contains data about the various locations of the store, the employees within those locations, which employees work in which category in the location, the brands and products available at a specific location, the products that belong to a certain brand, the brands that belong to certain products, and the categories that contain certain brands and products. 

Sephora has many store locations. Each location contains a unique address, unique phone number, and a unique store identification number. Each location carries many brands.  Brands make many products.
Many employees work in specific locations. Each employee has a unique employee identification number as well as their name, salary,and job title. Each employee works in one store location. Each location has one manager.
Sephora’s categories are distinguished by classifying similar shared characteristics. For example: haircare, skincare, makeup, etc. Categories contain many products, and categories specialize in many brands. 
Sephora’s products are attributed to one product type such as: moisturizers, blush, serums, etc. A specific product belongs to only one category, one product type, and only one brand. 
Brands make many products. Each brand has a unique brand identification number, a reliable contact, and a unique name. Brands specialize in one category.

## 3. ER Diagram
The figure below shows the ER diagram of the SEPHORA Database (SEPHORA).



## 4. ER Diagram Uncaptured Constraints
The following is a list of constraints that are not captured by the ER diagram of SEPHORA:

An employee’s salary must be a positive integer.
Product price must be a positive integer.
A brand’s contact must be an active phone number.
A category’s name must be less than 15 characters.
A variation will be a description of the product.

## 5. Relational Schema
This section provides the relational schema with referential integrity and the relational table details.



5.2 Relational Table Details 

The relational schema given in Section 5.1 was mapped into the following tables in the SEPHORA database. Primary keys have been underlined. Tables that have multiple attributes underlined represent composite keys.





## DDL + DML + SQL Script
https://github.com/VictoriaOlejarz/Database-Programming/blob/main/docs/sql_script.txt

## ORM Implementation
https://github.com/VictoriaOlejarz/Database-Programming/blob/main/docs/ORM_script.txt

## Queries

https://github.com/VictoriaOlejarz/Database-Programming/tree/main/queries


