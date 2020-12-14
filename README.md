https://loizenai.com/angular-11-upload-file-to-firebase-storage/

# @angular/fire/storage Angular 11 Upload files to Firebase

## Technologies – Angular 11 Upload File to Firebase Storage
– Angular 11
– RxJs 6
– @angular/fire 5.1.3
– firebase 5.11.1

## Overview Angular 11 Upload file to Firebase Storage

![Overview Angular 11 Upload file to Firebase Storage](https://loizenai.com/wp-content/uploads/2020/12/Angular-11-Upload-Files-to-Firebase-Storage-Demo.png)

We will build an Angular 11 Firebase App that can:
– helps user choose file from local and upload it to Firebase Storage
– show progress with percentage
– save file metadata to Firebase Realtime Database
(Functions above from the posts: Upload File to Storage)
– get list Files and display

## How to upload file from Angular to Firebase storage using @angular/fire/storage?

![How to upload file from Angular to Firebase storage using @angular/fire/storage?](https://loizenai.com/wp-content/uploads/2020/12/Angular-11-Upload-Files-to-Firebase-Storage-Overview.png)

– Upload file:
+ save file to Firebase Cloud Storage
+ retrieve {name, url} of the file from Firebase Cloud Storage
+ save {name, url} to Firebase Realtime Database

– Get/delete files: use file {name, url} stored in Database as reference to Firebase Cloud Storage.

So, after upload process, the results will be like:

-> Firebase Storage:

![Firebase Storage](https://loizenai.com/wp-content/uploads/2020/12/Angular-11-Firebase-Storage-Results.png)

-> Firebase Realtime Database:

![Firebase Realtime Database](https://loizenai.com/wp-content/uploads/2020/12/Angular-11-Firebase-Storage-Database-Results.png)

## Related post

- [Reactjs CRUD Firebase Realtime Database Example](https://loizenai.com/reactjs-crud-firebase-realtime-database/)
- [Angular 10 CRUD Firebase Realtime Database – use @angular/fire](https://loizenai.com/angular-10-crud-firebase-realtime-database-angular-fire/)
