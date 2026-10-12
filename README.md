# kolokotronis-static-site

Στατικό αντίγραφο (static snapshot) της ιστοσελίδας **Νικόλαος Κολοκοτρώνης**
(https://www.nikolaskolokotronis.gr).

## Τι είναι

- Πλήρες, αυτόνομο στατικό αντίγραφο: HTML + CSS + εικόνες.
- **Χωρίς JavaScript**, χωρίς βάση δεδομένων, χωρίς CMS. Δεν εξαρτάται από κανένα backend.
- Ίδια εμφάνιση (pixel-identical) με την τρέχουσα δημόσια ιστοσελίδα.

## Δομή

```
index.html                     Αρχική
about/index.html               Σχετικά
services/index.html            Υπηρεσίες
services/<slug>/index.html     Κάθε υπηρεσία
blog/index.html                Blog
blog/<slug>/index.html         Κάθε άρθρο/ανακοίνωση
books/index.html               Βιβλία
contact/index.html             Επικοινωνία
privacy/index.html             Πολιτική Απορρήτου
terms/index.html               Όροι Χρήσης
assets/styles-*.css            CSS
assets/media/                  Εικόνες
logo*.png                      Λογότυπα / favicon
```

## Σημειώσεις

- Οι σελίδες φέρουν `noindex, nofollow` (και header `X-Robots-Tag`) ώστε να μην
  ανταγωνίζονται την κανονική ιστοσελίδα στις μηχανές αναζήτησης.
- Η φόρμα επικοινωνίας και τα δυναμικά στοιχεία (mobile menu, accordion) δεν
  λειτουργούν σε στατική μορφή.
- Δεν περιλαμβάνονται κωδικοί ή τεχνικά στοιχεία.

## Deploy

Vercel (static). Δεν απαιτείται build.

AION WEB — www.aionweb.gr
