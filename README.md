# MyFirstAPP

This is my first application developing with Android Studio

For reference we use this guide to create this App
Android Room with a View - Java
https://developer.android.com/codelabs/android-room-with-a-view#0

this is the final result of the application:

The purpose of Architecture Components is to provide guidance on app architecture, with libraries for common tasks like lifecycle management and data persistence. Architecture components help you structure your app in a way that is robust, testable, and maintainable with less boilerplate code. The Architecture Component libraries are part of Android Jetpack.

This is the Java programming language version of the codelab. The version in the Kotlin language can be found here.

If you run into any issues (code bugs, grammatical errors, unclear wording, etc.) as you work through this codelab, please report the issue via the Report a mistake link in the lower left corner of the codelab.

Prerequisites
You need to be familiar with Java, object-oriented design concepts, and Android Development Fundamentals. In particular:

RecyclerView and adapters
SQLite database and the SQLite query language
Threading and ExecutorService
It helps to be familiar with software architectural patterns that separate data from the user interface, such as MVP or MVC. This codelab implements the architecture defined in the Guide to App Architecture.
This codelab is focused on Android Architecture Components. Off-topic concepts and code are provided for you to simply copy and paste.

This codelab provides all the code you need to build the complete app.

What you'll do
In this codelab, you'll learn how to design and construct an app using the Architecture Components Room, ViewModel, and LiveData, and build an app that does the following:

Implements our recommended architecture using the Android Architecture Components.
Works with a database to get and save the data, and pre-populates the database with some words.
Displays all the words in a RecyclerView in MainActivity.
Opens a second activity when the user taps the + button. When the user enters a word, adds the word to the database and the list.
The app is no-frills, but sufficiently complex that you can use it as a template to build upon. Here's a preview:


![image](https://user-images.githubusercontent.com/68777214/198829038-dfa0fb9a-607e-4f1f-81c9-382feeda1585.png)
