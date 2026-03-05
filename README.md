# Library-Management-System

Στόχος της άσκησης είναι να δημιουργήσεις μια απλή console εφαρμογή σε Java για τη διαχείριση βιβλίων σε μια βιβλιοθήκη και να μάθεις να αποθηκεύεις τον κώδικά σου σε repository χρησιμοποιώντας Git και GitHub.

1)
Εγκατάσταση IDE
Κατέβασε το:
IntelliJ IDEA
Εγκατέστησέ το και άνοιξέ το.

2)
Clone το repository

Το clone σημαίνει ότι κατεβάζεις ένα repository από το GitHub στον υπολογιστή σου.

Αντέγραψε το URL του repository
Και μεσα στο intellij δημιουργησε project μεσω version control

3)
Δημιούργησε Java classes
Δημιούργησε τις παρακάτω κλάσεις:

Book.java

Library.java

Main.java

4)
Κλάση Book
Η κλάση πρέπει να έχει τα πεδία:

id

title

author

isBorrowed

και:

constructor

getters / setters

toString()

6)
Κλάση Library

Η κλάση πρέπει να έχει μια λίστα βιβλίων:
ArrayList<Book>
και μεθόδους:

addBook

removeBook

borrowBook

returnBook

listBooks

6)
η εφαρμογή πρέπει να μπορεί:

να προσθέτει βιβλία

να αφαιρεί βιβλία

να δανείζει βιβλία

να επιστρέφει βιβλία

να εμφανίζει τη λίστα βιβλίων

7) απο το git μενου του intellij κανε commit τα αρχεια και push στο remote


Bonus Άσκηση — Κληρονομικότητα (Inheritance)

Για να εξασκηθείς στην κληρονομικότητα στην Java, πρόσθεσε χρήστες που μπορούν να δανείζονται βιβλία.

Δημιουργία κλάσης User

Δημιούργησε:

User.java

Πεδία:

id
name
Step 18 — Δημιουργία subclasses

Δημιούργησε δύο κατηγορίες χρηστών:

Student
Teacher

και οι δύο να κληρονομούν από User.

Student

Πρόσθεσε:

maxBooks = 3
Teacher

Πρόσθεσε:

maxBooks = 5
Step 19 — Δανεισμός βιβλίων με όριο

Τροποποίησε τη μέθοδο borrowBook ώστε:

Student να μπορεί να δανειστεί μέχρι 3 βιβλία

Teacher μέχρι 5 βιβλία

Αν ξεπεραστεί το όριο:

Borrow limit reached
