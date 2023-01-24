# Πρώτα η ασφάλεια

**Όταν αποφασίζετε να δημιουργήσετε το δικό σας τεχνητό πάγκρεας, είναι πάντα σημαντικό να σκεφτείτε την ασφάλεια, και να κατανοήσετε τον αντίκτυπο όλων των ενεργειών σας**

## Γενικά

- Το AndroidAPS είναι απλά ένα εργαλείο για να σας βοηθήσει να διαχειριστείτε το διαβήτη, δεν είναι ένα πλήρως αυτοματοποιημένο σύστημα που μπορείτε να εγκαταστήσετε και να το ξεχάσετε!
- Μην υποθέσετε ότι το AndroidAPS ποτέ δεν θα κάνει λάθη. Αυτή η συσκευή αναλαμβάνει τον έλεγχο της χορήγησης ινσουλίνης: Παρακολουθήστε τη συνεχώς, κατανοήστε πώς λειτουργεί και μάθετε πώς να ερμηνεύετε τις ενέργειές της.
- Να θυμάστε ότι, μόλις συνδεθεί, το τηλέφωνο μπορεί να δώσει εντολή στην αντλία να κάνει οτιδήποτε. Χρησιμοποιήστε μόνο αυτό το τηλέφωνο για το AndroidAPS και, εάν χρησιμοποιείται από ένα παιδί, να του μιλήσετε ώστε να προσέχει το κινητό. Μην εγκαταστήσετε περιττές εφαρμογές ή παιχνίδια (!!!) που θα μπορούσαν να εισάγουν κακόβουλο λογισμικό, όπως trojans, ιούς ή bots που θα μπορούσαν να παρεμβληθούν στο σύστημά σας.
- Εγκαταστήστε όλες τις ενημερώσεις ασφαλείας που παρέχονται από τον κατασκευαστή του τηλεφώνου σας και το Google.
- Μπορεί επίσης να χρειαστεί να αλλάξετε τις συνήθειες του διαβήτη καθώς αλλάζετε τη θεραπεία σας χρησιμοποιώντας ένα σύστημα κλειστού κυκλώματος. Π.χ. μερικοί άνθρωποι αναφέρουν ότι χρειάζονται λιγότερες θεραπείες υπογλυκαιμίας, καθώς το AndroidAPS έχει ήδη μειώσει την ινσουλίνη.

## Επικοινωνία με SMS

- Το AndroidAPS σας επιτρέπει να ελέγχετε τηλεφωνικά ένα παιδικό τηλέφωνο μέσω μηνύματος κειμένου. Αν ενεργοποιήσετε αυτό την επικοινωνία με SMS, θυμηθείτε πάντα ότι το τηλέφωνο που έχει ρυθμιστεί για να δώσει απομακρυσμένες εντολές μπορεί να κλαπεί. Συνεπώς, πάντα να το προστατεύετε τουλάχιστον από ένα κωδικό PIN.
- Το AndroidAPS θα σας ενημερώσει επίσης με μήνυμα κειμένου εάν έχουν πραγματοποιηθεί οι απομακρυσμένες εντολές σας, όπως μια αλλαγή bolus ή προφίλ. Συνιστάται να το ρυθμίσετε έτσι ώστε τα κείμενα επιβεβαίωσης να αποστέλλονται σε τουλάχιστον δύο διαφορετικούς αριθμούς τηλεφώνου σε περίπτωση κλοπής ενός από τα τηλέφωνα λήψης.

## AndroidAPS can also be used by blind people

On Android devices TalkBack is part of the operating system. It is a program for screen orientation via voice output. With TalkBack you can operate your smartphone as well as AndroidAPS blind.

We users create the AndroidAPS app ourselves with Android Studio. Many use Microsoft Windows for this purpose, where there is the Screenreader analogous to TalkBack. Since Android Studio is a Java application, the "Java Access Bridge" component must be enabled in the Control Panel. Otherwise, the screen reader of the PC will not speak in Android Studio.

To do this, please proceed as follows:

- Press WINDOWSTASTE and enter "Control Panel" in the search field, open with Enter. It opens: "All Control Panel Items".
- Press the letter C to get to "Center for Ease of Use", open with Enter.
- Then open "Use computer without a screen" with Enter.
- There, at the bottom, you will find the checkbox "Enable Java Access Bridge", select it.
- Done, just close the window! The screen reader should work now.

```{eval-rst}
.. σημείωση::
   ** ΣΗΜΑΝΤΙΚΗ ΑΝΑΚΟΙΝΩΣΗ ΑΣΦΑΛΕΙΑΣ **

   Η ίδρυση των χαρακτηριστικών ασφάλειας του AndroidAPS που αναφέρονται σε αυτήν την τεκμηρίωση βασίζεται στα χαρακτηριστικά ασφαλείας του υλικού που χρησιμοποιείται για την κατασκευή του συστήματός σας. Είναι πολύ σημαντικό να χρησιμοποιείτε μόνο μια δοκιμασμένη, πλήρως λειτουργική FDA ή CE εγκεκριμένη αντλία ινσουλίνης και CGM για το κλείσιμο ενός αυτοματοποιημένου κυκλώματος δοσολογίας ινσουλίνης. Οι τροποποιήσεις υλικού ή λογισμικού σε αυτά τα εξαρτήματα μπορεί να προκαλέσουν απροσδόκητη δόση ινσουλίνης, προκαλώντας σημαντικό κίνδυνο για τον χρήστη. Αν βρείτε σπασμένες, τροποποιημένες ή αυτο-κατασκευαζόμενες αντλίες ινσουλίνης ή δέκτες CGM, * μην τις χρησιμοποιήσετε * για τη δημιουργία ενός συστήματος AndroidAPS.

   Επιπλέον, είναι εξίσου σημαντικό να χρησιμοποιείτε μόνο αυθεντικά προϊόντα όπως εισαγωγείς, κάνουλα και δοχεία ινσουλίνης εγκεκριμένα από τον κατασκευαστή για χρήση με την αντλία ή το CGM. Η χρήση μη δοκιμασμένων ή τροποποιημένων αναλωσίμων μπορεί να προκαλέσει ανακρίβεια CGM και σφάλματα δοσολογίας ινσουλίνης. Η ινσουλίνη είναι εξαιρετικά επικίνδυνη όταν δίνετε σε λάθος δοσολογία - παρακαλώ μην παίζετε με τη ζωή σας με μη εγκεκριμένες προμήθειες.

   Last not least, you must not take SGLT-2 inhibitors (gliflozins) as they incalculably lower blood sugar levels.  The combination with a system that lowers basal rates in order to increase BG is especially dangerous as due to the gliflozin this rise in BG might not happen and a dangerous state of lack of insulin can happen.
```