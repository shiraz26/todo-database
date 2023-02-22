# todo-database
firebase-todo

link for todo app https://todo-firebaseapp-shiraz.web.app/
After downloading zip file , you can change your web app  firebase configuration as per your project. 
changes will start from web app  firebase configuration in index.html file inside script tag . var firebaseConfig this line remain same changes from .
 var firebaseConfig { } in this  curly braces  you write your own configuration data and replace my data.
  Initialize Firebase firebase.initializeApp(firebaseConfig); this will remain same don't change this .
 In firebase application , real time database you can change in rules part <br>
<br>{
 <br> "rules": {
   <br> ".read": true,
  <br>  ".write": true
<br>  }
<br>}
copy and paste this code in rules of real time database in firebase
