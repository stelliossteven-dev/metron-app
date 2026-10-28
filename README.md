# Μέτρον — εφαρμογή για Android

Το εργαλείο του διατροφολόγου: πελάτες, ραντεβού, μετρήσεις, εβδομαδιαία διατροφή με έλεγχο θρεπτικών, PDF για τον πελάτη.

**Τελευταία έκδοση: 0.68** — [κατέβασε το αρχείο](https://raw.githubusercontent.com/stelliossteven-dev/metron-app/main/metron-v0.68.apk)

Για υπολογιστή Windows: [Metron Diet - Desktop](https://github.com/stelliossteven-dev/metron-desktop-app).

Δοκιμαστική έκδοση: οι τιμές των τροφίμων (αμερικανική βάση USDA) και οι υπολογισμοί θέλουν έλεγχο από διαιτολόγο πριν από πραγματική χρήση.

## Εγκατάσταση

1. Άνοιξε τον σύνδεσμο από το κινητό ή το tablet (Android 10 ή νεότερο) και κατέβασε το αρχείο.
2. Άνοιξε το αρχείο που κατέβηκε. Την πρώτη φορά το κινητό ζητά να επιτρέψεις την εγκατάσταση από τον browser.
3. Αν έχεις ήδη την εφαρμογή, η νέα έκδοση μπαίνει πάνω στην παλιά και τα δεδομένα σου μένουν.

Η εφαρμογή ελέγχει μόνη της για νέα έκδοση κάθε φορά που ανοίγει και σε ειδοποιεί: πατάς «Ενημέρωση τώρα» και η εφαρμογή κατεβάζει τη νέα έκδοση και ανοίγει την εγκατάσταση, χωρίς browser.

Τα δεδομένα σου μένουν μόνο στη συσκευή σου. Κάνε τακτικά αντίγραφο από τις Ρυθμίσεις.
Η εφαρμογή παρέχεται ως έχει, χωρίς εγγύηση.

---

## Privacy policy

*Last updated: 26 October 2026 (version 0.64). Ελληνικά παρακάτω.*

**Metron (Μέτρον)** is an Android app for dietitians: clients, appointments, measurements, weekly diets and PDFs for the client.

- **Your data stays on your device.** The app has no server of its own and does not collect, sell or share your data. It has no advertising and no analytics.
- **Health data.** What you enter about your clients (for example weight, body composition, test results, diets) can be health data. It is stored only on your device. You, the dietitian, are responsible for your clients' data (for example their consent and how long you keep it). The developer of the app receives none of it and has no access to it.
- **Network connections the app makes:** (1) it checks for a new version by reading a small file from this page (`latest.json`); (2) when you scan a food barcode, the barcode number is sent to Open Food Facts (openfoodfacts.org) to look up the product. No client data is sent in either case.
- **Optional permissions, used only when you use the feature:** contacts (only the single contact you choose, to fill in a new client), calendar (only if you turn on calendar sync), biometrics (to unlock the app with your fingerprint), notifications, and installing updates.
- **Optional device sync (Google Drive), experimental and off by default (version 0.61 and later).** If you turn it on, you sign in with your Google account and the app stores your data in the hidden *application data folder* of **your own** Google Drive (permission `drive.appdata`). It cannot see or change any other file in your Drive. The data is **encrypted on your device before it is uploaded** (AES-256) and the key stays on your devices, so the developer and Google cannot read it. Photos and exam files are synced too, encrypted the same way, and the screen-lock code stays on each device. The same sync is used by the Windows version (Metron Diet - Desktop), where the key is protected by Windows data protection. If you lose all your devices and the recovery key, the data in Drive cannot be recovered by anyone.
- **What we receive:** nothing. The developer has no access to your Google account, your Drive or your clients' data.
- **Deleting your data:** uninstalling the app removes the data on that device. If you turned on sync, you can turn it off in the app and delete the app's data from your Google account (Google Account › Data & privacy › Third-party apps and services › Metron › *Delete app data*, or Drive › Settings › *Manage apps*).
- **Contact:** stellios.steven@gmail.com

The app is provided as is, without warranty.

## Πολιτική απορρήτου

*Τελευταία ενημέρωση: 26 Οκτωβρίου 2026 (έκδοση 0.64).*

Το **Μέτρον (Metron)** είναι εφαρμογή Android για διατροφολόγους: πελάτες, ραντεβού, μετρήσεις, εβδομαδιαίες διατροφές και PDF για τον πελάτη.

- **Τα δεδομένα σου μένουν στη συσκευή σου.** Η εφαρμογή δεν έχει δικό της server και δεν συλλέγει, δεν πουλά και δεν μοιράζεται τα δεδομένα σου. Δεν έχει διαφημίσεις ούτε αναλυτικά στοιχεία χρήσης.
- **Δεδομένα υγείας.** Όσα καταχωρείς για τους πελάτες σου (π.χ. βάρος, σύσταση σώματος, αποτελέσματα εξετάσεων, διατροφές) μπορεί να είναι δεδομένα υγείας. Αποθηκεύονται μόνο στη συσκευή σου. Υπεύθυνος για τα δεδομένα των πελατών είσαι εσύ, ο διατροφολόγος (π.χ. για τη συγκατάθεσή τους και για το πόσο καιρό τα κρατάς). Ο δημιουργός της εφαρμογής δεν λαμβάνει τίποτα από αυτά και δεν έχει πρόσβαση σε αυτά.
- **Δικτυακές συνδέσεις της εφαρμογής:** (1) ελέγχει για νέα έκδοση διαβάζοντας ένα μικρό αρχείο από αυτή τη σελίδα (`latest.json`)· (2) όταν σκανάρεις barcode τροφίμου, ο αριθμός του barcode στέλνεται στο Open Food Facts (openfoodfacts.org) για να βρεθεί το προϊόν. Σε καμία από τις δύο δεν στέλνονται στοιχεία πελατών.
- **Προαιρετικές άδειες, που χρησιμοποιούνται μόνο όταν χρησιμοποιείς τη λειτουργία:** επαφές (μόνο η μία επαφή που διαλέγεις, για να συμπληρωθεί νέος πελάτης), ημερολόγιο (μόνο αν ενεργοποιήσεις τον συγχρονισμό ημερολογίου), βιομετρικά (για ξεκλείδωμα με αποτύπωμα), ειδοποιήσεις και εγκατάσταση ενημερώσεων.
- **Προαιρετικός συγχρονισμός συσκευών (Google Drive), δοκιμαστικός και κλειστός από προεπιλογή (από την έκδοση 0.61).** Αν τον ενεργοποιήσεις, συνδέεσαι με τον λογαριασμό σου Google και η εφαρμογή αποθηκεύει τα δεδομένα στον κρυφό *φάκελο δεδομένων εφαρμογής* του **δικού σου** Google Drive (άδεια `drive.appdata`). Δεν μπορεί να δει ή να αλλάξει κανένα άλλο αρχείο του Drive σου. Τα δεδομένα **κρυπτογραφούνται στη συσκευή σου πριν ανέβουν** (AES-256) και το κλειδί μένει στις συσκευές σου, οπότε ούτε ο δημιουργός ούτε η Google μπορούν να τα διαβάσουν. Οι φωτογραφίες και τα αρχεία εξετάσεων συγχρονίζονται επίσης, κρυπτογραφημένα με τον ίδιο τρόπο, και ο κωδικός κλειδώματος οθόνης μένει σε κάθε συσκευή. Τον ίδιο συγχρονισμό χρησιμοποιεί και η έκδοση για Windows (Metron Diet - Desktop), όπου το κλειδί προστατεύεται με την προστασία δεδομένων των Windows. Αν χάσεις όλες τις συσκευές σου και το κλειδί ανάκτησης, τα δεδομένα στο Drive δεν ανακτώνται από κανέναν.
- **Τι λαμβάνουμε:** τίποτα. Ο δημιουργός δεν έχει πρόσβαση στον λογαριασμό Google, στο Drive ή στα δεδομένα των πελατών σου.
- **Διαγραφή δεδομένων:** η απεγκατάσταση της εφαρμογής σβήνει τα δεδομένα της συσκευής. Αν έχεις ενεργοποιήσει τον συγχρονισμό, μπορείς να τον απενεργοποιήσεις στην εφαρμογή και να διαγράψεις τα δεδομένα της εφαρμογής από τον λογαριασμό σου Google (Λογαριασμός Google › Δεδομένα και απόρρητο › Εφαρμογές και υπηρεσίες τρίτων › Metron › *Διαγραφή δεδομένων εφαρμογής*, ή Drive › Ρυθμίσεις › *Διαχείριση εφαρμογών*).
- **Επικοινωνία:** stellios.steven@gmail.com

Η εφαρμογή παρέχεται ως έχει, χωρίς εγγύηση.

---

Εδώ υπάρχουν μόνο τα έτοιμα αρχεία της εφαρμογής. Το `latest.json` το διαβάζει η εφαρμογή για να δει ποια είναι η τελευταία έκδοση.
