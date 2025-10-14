# Team Webring

Ένα **webring** που εμφανίζει τα βιογραφικά των μελών της ομάδας μέσα σε iframe viewer.

**Δείτε το Webring online:**  
-> [https://hci-iv-2025.github.io/webring/](https://hci-iv-2025.github.io/webring/)

---

## Για τα μέλη της ομάδας

Ακολουθήστε **τα παρακάτω βήματα** για να προσθέσετε το δικό σας βιογραφικό στη λίστα.

---

### Βήμα 1: Κάντε "Fork" το αποθετήριο

1. Συνδεθείτε στο GitHub με τον λογαριασμό σας.
2. Μεταβείτε στη σελίδα του project (π.χ. `https://github.com/όνομα_ομάδας/webring`).
3. Πατήστε πάνω δεξιά το κουμπί **"Fork"** για να δημιουργήσετε ένα **αντίγραφο** του αποθετηρίου στο δικό σας προφίλ.

---

### Βήμα 2: Κάντε "Clone" το fork σας στον υπολογιστή σας

Ανοίξτε το **GitHub Desktop** ή ένα **terminal** και εκτελέστε:

```bash
git clone https://github.com/<το-username-σας>/webring.git
```

### Βήμα 3: Κάντε "Clone" το fork σας στον υπολογιστή σας

1. Ανοίξτε το φάκελο **webring** σε οποιονδήποτε editor
2. Βρείτε το αρχείο **js/index.js**
3. Μέσα σε αυτό υπάρχει ένας πίνακας με τα μέλη

```javascript
const members = [
  {
    id: 'marios',
    url: 'https://mstephanidhs.github.io/',
    name: 'Marios Stefanidis',
    icon: 'M',
  },
  // Προσθέστε νέα μέλη εδώ:
  // { id: 'maria', url: 'https://maria.github.io/cv', name: 'Μαρία Κ.', icon: 'Μ' }
];
```

4. Προσθέστε τη δική σας εγγραφή στο τέλος του πίνακα, ακολουθώντας το ίδιο πρότυπο

```javascript
{
  id: 'onoma',
  url: 'CV Website Link',
  name: 'Το Ονοματεπώνυμό σας',
  icon: 'Αρχικό Γράμμα',
},

```

### Βήμα 4: Ανεβάστε τις αλλαγές στο Github

Αν χρησιμοποιείτε Github Desktop:

- Επιλέξτε **"Commit to main"** & **"Push origin"**

Διαφορετικά, μέσω terminal

```bash
git add .
git commit -m "Προσθήκη μέλους: Το Όνομά σας"
git push origin main
```

### Βήμα 5: Δημιουργήστε ένα **"Pull Request"**

1. Μεταβείτε στο fork σας στο GitHub
2. Επιλέξτε **"Compare & Pull Request"**
3. Πατήστε **"Create Pull Request"**
