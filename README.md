## Παραδοτέο 4 - ΤΕΛΙΚΗ ΑΝΑΦΟΡΑ
**Ονοματεπώνυμο: Μιχαήλ- Χρυσοβαλάντης Παγκρακιώτης**

**Αριθμός Μητρώου: Π2014035**

**Links:**
* Link προσωπικού Αποθετηρίου: https://github.com/Mikepag/pacman
* Link Εκτελέσιμου: https://mikepag.github.io/pacman/pacman.html

### Tίτλος Εργασίας: *Δημιουργία Pacman*

### Εισαγωγή
Σκοπός της εργασίας ήταν η επέκταση υπάρχουσας έκδοσης του παιχνιδιού Pacman με τη χρήση της γλώσσας HTML5 και τη βοήθεια της βιβλιοθήκης Phaser, παράλληλα με τον στόχο του μαθήματος που ήταν η εξάσκηση στην σχεδίαση και την ανάπτυξη λογισμικού.

### Επιλογή Εργαλείων 
**Τα εργαλεία που χρησιμοποιήθηκαν ήταν τα εξής:**
* **Tiled**, για την δημιουργία νέας πίστας η οποία είναι βασισμένη στην προϋπάρχουσα (pacman-map.json).
* **Microsoft Paint**, για την επεξεργασία των εικόνων pacman.png, pacman-tiles.png. 
* **Adobe Photoshop CS6 Portable**, για την επεξεργασία των εικόνων pacman.png, pacman-tiles.png, dots.png.
* **Sublime Text 3**, για την επεξεργασία του HTML5 κώδικα.
* **XAMPP**, για την εκτέλεση του κώδικα τοπικά στον προσωπικό μου υπολογιστή.

### Διαδικασία Ανάπτυξης
**Προκειμένου να φτάσει στη τελική της μορφή η εργασία έγιναν οι παρακάτω ενέργειες:**
* Αρχικά έγινε fork στο κεντρικό αποθετήριο του project όπου υπήρχε έτοιμο σε πρώιμο στάδιο το παιχνίδι.
* Αντικατάσταση της εικόνας [pacman.png](https://github.com/Mikepag/pacman/blob/master/assets/pacman.png) από νέα. Η καινούρια εικόνα επεξεργάστηκε στο paint ώστε να χωριστεί σε 3 στιγμιότυπα (για το animation) και μέσω του photoshop έγινε το resize στις επιθυμητές διαστάσεις και αποθηκεύτηκε σε format PNG.
* Αντικατάσταση της εικόνας [dot.png](https://github.com/Mikepag/pacman/blob/master/assets/dot.png). Στη νέα εικόνα έγινε resize στις επιθυμητές διαστάσεις καθώς και αποθήκευση σε format PNG μέσω του Photoshop.
* Δημιουργία νέας πίστας με το Tiled, κάνοντας χρήση της υπάρχουσας πίστας [pacman-map.json](https://github.com/Mikepag/pacman/blob/master/assets/pacman-map.json) καθώς και των πλακιδίων [pacman-tiles.png](https://github.com/Mikepag/pacman/blob/master/assets/pacman-tiles.png), στα οποία όμως πρώτα έγινε αλλαγή του χρώματος.
*Προσθήκη [κώδικα](https://github.com/Mikepag/pacman/blob/master/pacman.html) για την προβολή Score. Το score αρχικά είναι μηδέν (0) και κάθε φορά που ο Pacman "τρώει" ένα dot το score αυξάνεται κατά πέντε (5) μονάδες.
* Προσθήκη [κώδικα](https://github.com/Mikepag/pacman/blob/master/pacman.html) για την προβολή Lives. Αρχικά οι ζωές είναι τρείς (3). (Δεν αναπτύχθηκε λειτουργία που να αυξάνει ή να μειώνει αυτή τη μεταβλητή).
* Προσθήκη Bonus:
	1. Τροποποίηση εικόνας [pacman-tiles.png](https://github.com/Mikepag/pacman/blob/master/assets/pacman-tiles.png) για να προστεθεί καινούριο πλακίδιο (Burger).
	2. Προσθήκη του καινούριου πλακιδίου στον χάρτη [pacman-map.json](https://github.com/Mikepag/pacman/blob/master/assets/pacman-map.json).
	3. Προσθήκη μικρού τμήματος κώδικα στο [pacman.html](https://github.com/Mikepag/pacman/blob/master/pacman.html) ώστε να γίνεται ψευδοτυχαία εμφάνιση/απόκρυψη των bonus πλακιδίων.
	4. Τροποποίηση [κώδικα](https://github.com/Mikepag/pacman/blob/master/pacman.html) ώστε κάθε φορά που ο Pacman τρώει ένα burger το Score να αυξάνεται κατά πενήντα (50) μονάδες, αντί για πέντε (5) που αυξάνεται όταν τρώει ένα απλό dot.
*Προσθήκη ήχων:
	1. [Ήχος background](https://github.com/Mikepag/pacman/blob/master/assets/TheChainsmokersAllWeKnow8Bit.mp3).
	2. [Ηχητικό εφέ](https://github.com/Mikepag/pacman/blob/master/assets/SuperMarioFireFlowerSoundFX.mp3) κάθε φορά που ο Pacman τρώει ένα dot.
	3. [Ηχητικό εφέ](https://github.com/Mikepag/pacman/blob/master/assets/SuperMarioPipeTravelSoundFX.mp3) κάθε φορά που ο Pacman τρώει ένα burger.
 
### Ενδεικτικές Εικόνες
* Πριν την εμφάνιση των Bonus:
![s1](https://cloud.githubusercontent.com/assets/15000701/26785919/5f5ceb18-4a0d-11e7-891a-315c3455cfc2.JPG) 

* Μετά την εμφάνιση των Bonus:
![s2](https://cloud.githubusercontent.com/assets/15000701/26785918/5f5aa3ee-4a0d-11e7-9e59-264422423fe8.JPG)

### Βιβλιογραφία
* Κεντρικό αποθετήριο project : https://github.com/ioniodi/pacman
* Η τελική εικόνα [pacman.png](https://github.com/Mikepag/pacman/blob/master/assets/pacman.png) προέκυψε από επεξεργασία της εικόνας: https://goo.gl/HH3fTi
* [Dot.png](https://github.com/Mikepag/pacman/blob/master/assets/dot.png) : https://goo.gl/O048qq
* [Brgr.png](https://github.com/Mikepag/pacman/blob/master/assets/brgr.png) : https://goo.gl/RbVHBC
* [SuperMarioFireFlowerSoundFX.mp3](https://github.com/Mikepag/pacman/blob/master/assets/SuperMarioFireFlowerSoundFX.mp3) : https://goo.gl/z9tmnP
* [SuperMarioPipeTravelSoundFX.mp3](https://github.com/Mikepag/pacman/blob/master/assets/SuperMarioPipeTravelSoundFX.mp3) : https://goo.gl/PPpNPE
* [TheChainsmokersAllWeKnow8Bit.mp3](https://github.com/Mikepag/pacman/blob/master/assets/TheChainsmokersAllWeKnow8Bit.mp3) : https://goo.gl/ceqL9Y
  
### Συμπεράσματα
Η εργασία αυτή αποτέλεσε έναν δημιουργικό και πολύ ενδιαφέρων τρόπο ενασχόλησης με τη γλώσσα HTML5, τη βιβλιοθήκη Phaser και τo Github για την ανάπτυξη μιας ψυχαγωγικής εφαρμογής. Η τελική μορφή του παιχνιδιού μπορεί να μην είναι η βέλτιστη δυνατή αλλά δεν παύει να είναι αρκετά λειτουργική και φυσικά αφήνει πολλά περιθώρια μελλοντικής βελτίωσης.
