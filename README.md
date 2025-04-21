# e-commerce.io

E-Commerce Database Project.

Project Summary
This project involves designing and implementing a relational database schema for a real-world E-Commerce platform. It handles product listings, categories, inventory management, product variations (e.g. size and color), and custom attributes. The schema includes tables for managing brands, categories, images, and attributes that are essential for an e-commerce system.

Key Features
-12 relational tables with defined keys and constraints
-Support for brands, categories, sizes, colors, and images
-Product-item relationships supporting multiple variations
-for products using typed values (e.g., material, weight)
-Indexes for optimized querying (e.g., for product and category)

Tables Created.
1.brand - Stores information about product brands.
2.product_category - Organizes products into categories (e.g., electronics, clothing).
3.product- Stores general product details (name, brand, base price).
4.color - Manages available color options.
5.size_category - Groups sizes into categories (e.g., clothing sizes, shoe sizes).
6.size_option - Lists specific size options (e.g., S, M, L, 42).
7.product_item - Represents purchasable items with variations (color, size).
8.product_image - Stores image URLs or file references for product items.
9.product_variation - Links products to their variations (e.g., color, size).
10.attribute_category** - Groups product attributes into categories (e.g., physical, technical).
11.attribute_type - Defines types of attributes (e.g., text, number, boolean).
12.product_attribute - Stores custom attributes for products (e.g., material, weight).

Relationships
A product belongs to one brand and one category.
A product can have multiple items (variations).
Each item has a size and color.
Product images are associated with product items.
Custom attributes are linked to products and categorized.

How to Use
1.Create a new database;
--sql
   CREATE DATABASE ecommerce_db;
   USE ecommerce_db;
2.Run the `ecommerce.sql` file in your SQL environment to create the schema.
3. The file contains the schema definition, including the tables and relationships.

Learning Outcomes
Data modeling and normalization of a real-world e-commerce system.
Relational schema design with primary and foreign key constraints.
Index creation for optimizing database queries.
Collaboration using GitHub and version control.

Project Deliverables
-ecommerce.sql
-ERD diagram (PNG or SVG format)
-GitHub README (this file)

Contributors
This project was designed and implemented by the team for the E-Commerce Database Coursework Project.
