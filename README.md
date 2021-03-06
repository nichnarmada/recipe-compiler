# recipe-compiler

I'm currently developing a web app / mobile app to compile multiple recipes available online into 1 single grocery shopping list. 

## Features
Currently, the progress is up until sorting out patterns for 1 single webpage and splitting important data such as quantity and units. 

Dataset is also converted to a JSON file.

Sample of JSON file is available, file name is called sample.json (JSON file will be uploaded to Firebase)

Extracted all links from a website's xml file, and filter their recipes only (bettycrocker)

UPDATE: Tested an upload of 1 recipe to Firestore

## Next steps

### Data Mining
1. Code a loop for all recipe links in a website, and uploading them into Firebase.
2. Whitelist websites that can be generalised with current text pattern
3. Loop all whitelisted websites and upload them to Firebase

### Creating Web-app & Mobile-app
1. Use Javascript/Dart to make a simple website
2. Connect Firebase database with website
3. Design a proper UI/UX for ease of using website, and to show which websites are whitelisted

## Built with:
+ [Recipe Scrapers](https://github.com/hhursev/recipe-scrapers) library (made by [hhursev](https://github.com/hhursev), thank you!)
+ [Inflector](https://github.com/ixmatus/inflector) library (made by [ixmatus](https://github.com/ixmatus), thank you too!)
+ Python 
+ Javascript/Dart (Soon to be)