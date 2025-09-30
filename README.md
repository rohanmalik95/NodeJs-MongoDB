# NodeJs-MongoDB
This is a command-line application built with Node.js that connects to a local MongoDB server using the mongodb library. The application allows users to perform CRUD (Create, Read, Update, Delete) operations on a collection of records via a simple and interactive CLI interface.

Each record stored in the MongoDB collection represents a person and contains the following fields:
name – the person’s name
age – the person’s age

Features:
1. Add new records: Users can insert a new person with a name and age.
2. View all records: Users can display all stored records in the collection.
3. Update records: Users can update the name and age of a selected record.
4. Delete records: Users can delete a specific record safely using its unique _id.

Learning Objectives:
1. Establish a connection with MongoDB from Node.js.
2. Perform asynchronous operations using async/await.
3. Implement basic error handling for robust operation.
4. Gain hands-on experience with CRUD operations in MongoDB.
5. Work with CLI-based user input using the prompt-sync library.
