# Pagination in Flutter using Firebase Cloud Firestore

- In this article we are going to learn about pagination in flutter using firebase cloud firestore database. As we know that accessing data in small pieces rather than whole bunch is better approach in terms of application performance and bandwidth cost. I would like to also include that firebase firestore bills you according to the number of read, write and delete operations so, this article will be very crucial to those developers who wants to use firebase firestore as backend for their app. 
- We are going to implement scroll to load feature for loading more data in the below example. Initially we will load 15 records and then after when user reaches the end of the list or bottom of the list we load another 15 records and so on. So let’s begin our step by step example tutorial for pagination in flutter using firebase cloud firestore.

## Prerequisite:
- Created New Project named as ``“flutter_firebase_pagination”``
- I am assuming that you are familiar with how to create firebase project and initialize firestore database in it. If you are a beginner and don’t have an idea about firestore you can check my article Firebase Firestore CRUD Operation In Flutter.
- After creating firebase database create collection as named “products” and add 25 documents manually in products collection. I have attached screenshot will make you easily understand how to structure our collection. There are two fields in document “name” and “short_desc”.

![Collection Screenshot](https://raw.githubusercontent.com/myvsparth/flutter_firebase_pagination/master/screenshots/1.png)

Check Step By Step Implementation Article: https://www.c-sharpcorner.com/article/pagination-in-flutter-using-firebase-cloud-firestore/

``Pull the repository and check main.dart file``

Related Tags: Flutter, Pagination, Firebase, Firestore, Google Cloud Database, Android, iOS, ListView Pagination

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
