Path: Backend Engineering (Ruby on Rails) - January 2017  Unit: Week 3 - Persistence
Let's use Ruby and ActiveRecord to make the SQL go down a bit easier. Lesson.where(skill: 'High')

Description

Use ActiveRecord to query an existing SQLite3 database

Objectives

Learning Objectives
After completing this assignment, you should understand:

How to interact with a SQL database through ActiveRecord
Performance Objectives
After completing this assignment, you be able to effectively use

ActiveRecord#where to find data
ActiveRecord#save to modify data
ActiveRecord#sum and aggregation methods
Details

Fork this repo to get started: https://github.com/tiy-indy-bee-ror-jan17/storefront_cli

Create models as needed to use ActiveRecord to answer the following questions. (This means you'll need to create a ruby class file in /models for each table in the database. They should all inherit from ActiveRecord::Base)

** You won't need to write any migrations for this project **

Deliverables
A Pull Request to the original project repo with a completed set of scripts that outputs the answers to the following to the command line.

Explorer Mode

Before starting: Make sure you read the ActiveRecord Guides. Specifically Basics and Querying
How many users are there?
What are the 5 most expensive items?
What's the cheapest book?
Who lives at "6439 Zetta Hills, Willmouth, WY"? Do they have another address?
Correct Virginie Mitchell's address to "New York, NY, 10108".
How much would it cost to buy one of each tool?
How many total items did we sell?
How much was spent on books?

Adventurer Mode

Simulate buying an item by inserting a User from command line input (ask the user for their information) and an Order for that User (have them pick what they'd like to order and other needed order information).
What item was ordered most often? Grossed the most money?
What user spent the most?
What were the top 3 highest grossing categories?

Epic Mode

Create a new table and model to store reviews of items in the sqlite3 console.
The reviews table should contain an item_id, a user_id, an integer value from 1-5 that gives the star rating, and text that contains the review.
Create a command line interface that allows a user to find themselves by email address, pick an item they've ordered and leave a review on it.

Legendary Mode

Write tests for each of your models and each of the methods that answer the above questions.
Resources

Active Record Quering
APIDock Creating Tables
Active Record Migrations
Try SQL
