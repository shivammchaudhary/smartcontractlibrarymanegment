# smartcontractlibrarymanegment


This Solidity smart contract, successfully deployed on Ethereum Remix, is designed to manage a decentralized library of books. It allows users to add, track, and update their book collection directly on the blockchain. Here’s an overview of the contract and its functionalities:

Key Features:
Book Structure:

Each book is defined by a unique id, name, year, author, and finished status (indicating whether the book is finished or not).
Book Storage:

The contract maintains an array bookList that stores all books, with a mapping bookToOwner to link each book's ID to the user (owner) who added it.
Events:

AddBook: Logs when a new book is added.
SetFinished: Logs when a book's "finished" status is updated.
Book Management:

addBook(): Allows a user to add a new book to the library with the necessary details like name, publication year, author, and its completion status.
getFinishedBooks() / getUnfinishedBooks(): Retrieves all finished or unfinished books owned by the caller, filtering based on their completion status.
markFinished(): Lets a user mark a book as finished or unfinished, ensuring that only the owner of the book can make this change.
Running on Ethereum Remix:
This smart contract was successfully deployed and tested on Ethereum's Remix IDE. All functionalities, including adding books, retrieving finished or unfinished books, and marking books as finished, worked smoothly, demonstrating the decentralized nature of book management using Ethereum blockchain technology.

This contract showcases how blockchain can be used for efficient and transparent book tracking, where users maintain full ownership and control over their own book entries.

