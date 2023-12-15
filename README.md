# LibraryManagementSystem

GROUP 15 



Description: Library Management System using .NET MAUI Blazor App. The app will allow the user to view the details of a book, including its "Serial Number," "Title," and a short "Description" about the book. It supports both ADDING and DELETING books from the database. The purpose of this project is to create an effective and user-friendly application for libraries to keep track of their resources.
Technologys used in the project: .NET MAUI to create GUI, C# Classes, C# Interface, SQLite Database


The core functionality involves managing a library of books through a MAUI application. The application allows users to add, update, delete, view details of books. CustomImageControl helps displaying images stored as base64 strings to the application. SQLite is a lightweight, self-contained database engine which is used for local data storage.


The classes ues are:
CustomImageControl which extends Microsoft.Maui.Controls.Image, it helps in setting the image source. BookService inplements an interface called IBookservice, it manages the SQLite database to store and retrieve data of Books. And this class has methods for adding, updating, deleting and viewing the details of the books. The class called Book has attributes Id, Title, Description, and Image. The Error class have attributes Property and Value. ServiceResponse have Flag, Message, and DatabaseResponseValue. AddBookBaseViewModel is a class using CommunityToolkit.Mvvm.ComponentModel. AddOrUpdateBookPageViewmodel, BookDetailsPageViewmodel class inherits from AddBookBaseViewModel and uses ObservableProperty for accessing books details, BooklistHomePageViewmodel. MainProgram is the starting point of the app. It builds the app using MauiApp.CreateBuilder().


MAUI GUI is used throughout the project to create a cross-platform application, pages for listing books: Home Page (`BooklistHomePage`) and adding or updating books (`AddOrUpdateBookPage`).

The Library Management System project is a .NET MAUI desktop application that helps users to manage books in a library. It demonstrates the use of classes, interfaces, MAUI GUI.It also makes use of the CommunityToolkit.Maui library for additional build in functionality of MAUI framework. The main goal of creating this application is to allow users to manage books, including adding, updating, deleting, and viewing book records. 
