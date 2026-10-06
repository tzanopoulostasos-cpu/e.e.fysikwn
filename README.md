# Διαγώνισμα Προσομοίωσης Πανελλαδικών 2026 — Φυσική

Διαδραστική έκδοση του διαγωνίσματος προσομοίωσης Πανελλαδικών Εξετάσεων 2026
στη Φυσική Γ' Λυκείου, με αναλυτικές λύσεις, αυτοαξιολόγηση, επιλογέα γλώσσας
και υποστήριξη σκούρου/φωτεινού θέματος.

🔗 **Ζωντανή έκδοση:** <https://tzanopoulostasos-cpu.github.io/e.e.fysikwn/>

📝 **Κύρια ανάρτηση (blog):** <https://httpmyphysics.blogspot.com/>

---

![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-live-brightgreen)
![License](https://img.shields.io/badge/license-CC%20BY--NC%204.0-blue)
![Language](https://img.shields.io/badge/language-Ελληνικά%20%7C%20English-orange)
![MathJax](https://img.shields.io/badge/MathJax-3-blueviolet)
![Tailwind](https://img.shields.io/badge/Tailwind-CDN-38bdf8)

---

## 📖 Περιγραφή

Το project είναι μια **διαδραστική, αυτόνομη HTML σελίδα** που παρουσιάζει ένα
πλήρες διαγώνισμα Φυσικής Γ' Λυκείου (Προσομοίωση Πανελλαδικών 2026), βασισμένο
σε θέματα προτεινόμενα από την **Ένωση Ελλήνων Φυσικών**.

Περιλαμβάνει:

- **Θέμα Α** — Ερωτήσεις θεωρίας & κρίσης (5 × 5 μονάδες)
- **Θέμα Β** — Ασκήσεις εφαρμογής (8 + 8 + 9 μονάδες)
- **Θέμα Γ** — Μηχανική Στερεού Σώματος (6 + 11 + 8 μονάδες)
- **Θέμα Δ** — Κρούσεις & Ηλεκτρομαγνητισμός (8 + 9 + 8 μονάδες)
- **Αναλυτικές λύσεις** για κάθε ερώτηση, με πλήρη μαθηματική τεκμηρίωση
- **Τελικό πίνακα απαντήσεων** με σύντομες αιτιολογήσεις
- **Διαδραστική αυτοαξιολόγηση** (score 0–100)

---

## ✨ Χαρακτηριστικά

| Χαρακτηριστικό | Περιγραφή |
|---|---|
| ✅ Θέματα Α, Β, Γ, Δ | 25 μονάδες το καθένα, σύνολο 100 |
| ✅ Αναλυτικές λύσεις | Με MathJax — μαθηματικά υψηλής ποιότητας |
| ✅ Διαδραστική αυτοαξιολόγηση | Score 0–100, με bars ανά θέμα, τελικό βαθμό |
| ✅ Επιλογέας γλώσσας | Ελληνικά / English (αποθηκεύεται στο localStorage) |
| ✅ Σκούρο / φωτεινό θέμα | Εναλλαγή με ένα κλικ, αποθηκεύεται |
| ✅ Τυπολόγιο (drawer) | Γρήγορη αναφορά σε τύπους |
| ✅ Υπολογιστής Φυσικής (modal) | Υπολογισμός ω, T, υ_max |
| ✅ Λήψη Word / PDF | Links σε Google Drive |
| ✅ Print-friendly | Καθαρή εκτύπωση χωρίς UI |
| ✅ Προσβάσιμο | sr-only, ARIA, keyboard navigation, focus states |
| ✅ Κινητά | Πλήρως responsive (Tailwind) |
| ✅ Χωρίς build | Ένα αρχείο HTML — ανοίγει παντού |

---

## 🗂️ Δομή αρχείων
e.e.fysikwn/
├── index.html # Η κύρια σελίδα (single-file, self-contained)
├── README.md # Αυτό το αρχείο
└── LICENSE # Άδεια χρήσης (προαιρετικό)

text

Όλο το project είναι **ένα αρχείο HTML** — δεν χρειάζεται build, npm, ή framework.
Ανοίγει απευθείας σε οποιονδήποτε σύγχρονο browser.

---

## 🚀 Τοπική εκτέλεση

### Μέθοδος 1 — Απλή
1. Κατέβασε το `index.html`
2. Άνοιξέ το με διπλό κλικ σε Chrome, Firefox, Safari ή Edge
3. Έτοιμο — δεν χρειάζεται server

### Μέθοδος 2 — Με τοπικό server (προαιρετικό)

Αν θέλεις να δοκιμάσεις συμπεριφορά «σαν να είναι online»:

```bash
# Python 3
python3 -m http.server 8000

# ή Node.js
npx serve .
Μετά άνοιξε: http://localhost:8000

🌐 Δημοσίευση στο GitHub Pages
Ανέβασε το index.html (και το README.md) στο branch main

Πήγαινε στο αποθετήριο → Settings → Pages

Source: Deploy from a branch

Branch: main / folder: /(root)

Αποθήκευσε — η σελίδα θα είναι διαθέσιμη σε 1–2 λεπτά στο:
https://<username>.github.io/<repo>/

🛠️ Τεχνολογίες
HTML5 — σημασιολογική δομή

Tailwind CSS (CDN) — styling, responsive design

MathJax 3 — μαθηματικά (LaTeX)

Font Awesome 6 — εικονίδια

Vanilla JavaScript — i18n, score, theme, calculator, progress bar

localStorage — αποθήκευση γλώσσας & θέματος

Schema.org JSON-LD — δομημένα δεδομένα για SEO

Δεν χρησιμοποιείται:

❌ Κανένα framework (React, Vue, κ.λπ.)

❌ Κανένα build step (Webpack, Vite, κ.λπ.)

❌ Καμία βάση δεδομένων

❌ Κανένα backend

🌍 Προσαρμογή & Επέκταση
Αλλαγή κειμένων
Τα κείμενα είναι σε data-el / data-en attributes:

html
<p data-el="Ελληνικό κείμενο" data-en="English text">
  Ελληνικό κείμενο
</p>
Η συνάρτηση applyLanguage(lang) εναλλάσσει αυτόματα τα περιεχόμενα.

Αλλαγή χρωμάτων ανά θέμα
Στο <style>:

css
#tema-a { --theme: #0891b2; }  /* Θέμα Α — cyan */
#tema-b { --theme: #2563eb; }  /* Θέμα Β — blue */
#tema-g { --theme: #4f46e5; }  /* Θέμα Γ — indigo */
#tema-d { --theme: #059669; }  /* Θέμα Δ — emerald */
Προσθήκη νέας γλώσσας (π.χ. Γαλλικά)
Πρόσθεσε <option value="fr"> στον επιλογέα γλώσσας

Πρόσθεσε data-fr σε κάθε στοιχείο:

html
<p data-el="Ελληνικά" data-en="English" data-fr="Français">Ελληνικά</p>
Επέκτεινε τη συνάρτηση applyLanguage():

javascript
document.querySelectorAll('[data-el][data-en][data-fr]').forEach(el => {
  const text = el.getAttribute('data-' + lang);
  // ...
});
Προσθήκη νέας ερώτησης
Αντέγραψε ένα <article class="problem-card ..."> και άλλαξε:

data-question (π.χ. A6)

data-theme (A, B, G, D)

data-points

data-correct (για MC)

Τα κείμενα (και data-el / data-en)

📊 Δομή δεδομένων (score)
javascript
const scoreState = {
  A: { earned: 0, total: 25, answered: new Set() },
  B: { earned: 0, total: 25, answered: new Set() },
  G: { earned: 0, total: 25, answered: new Set() },
  D: { earned: 0, total: 25, answered: new Set() }
};
answered αποτρέπει διπλή μέτρηση της ίδιας ερώτησης

earned είναι το άθροισμα των σωστών απαντήσεων

refreshScoreUI() ενημερώνει τις μπάρες και το τελικό σκορ

♿ Προσβασιμότητα
sr-only headings για screen readers

aria-label σε κουμπιά

role="dialog" + aria-modal στο modal υπολογιστή

focus-visible outlines

prefers-reduced-motion support

Πλήρης πλοήγηση με πληκτρολόγιο (Tab, Enter, Escape)

📱 Print
Η σελίδα είναι 최적ized για εκτύπωση:

Κρύβονται header, nav, κουμπιά, modals, progress bar

Τα details ανοίγουν αυτόματα

Ο πίνακας απαντήσεων αποκτά borders

Καθαρή τυπογραφία σε μαύρο/άσπρο

Δοκίμασε: Ctrl+P (ή Cmd+P σε Mac).

🔍 SEO
application/ld+json (Schema.org LearningResource)

<title> και <meta name="description"> στα ελληνικά

Σημασιολογικό HTML (<main>, <section>, <article>, <header>)

Προαιρετικό: <meta name="robots" content="noindex, follow"> αν θέλεις
να μην ανταγωνίζεται το blogspot το GitHub Pages

📄 Άδεια
Περιεχόμενο (θέματα, λύσεις, κείμενα)
Creative Commons BY-NC 4.0 — ελεύθερη χρήση για μη εμπορικούς σκοπούς,
με αναφορά πηγής.

Επιτρέπεται: διαμοιρασμός, προσαρμογή, μη εμπορική χρήση

Απαιτείται: αναφορά δημιουργού

Απαγορεύεται: εμπορική χρήση

Πλήρες κείμενο: https://creativecommons.org/licenses/by-nc/4.0/

Κώδικας (HTML/CSS/JS)
MIT License — ελεύθερη χρήση, τροποποίηση, διανομή, με διατήρηση
του copyright notice.

Πλήρες κείμενο: https://opensource.org/licenses/MIT

🙏 Ευχαριστίες
Ένωση Ελλήνων Φυσικών — για τα προτεινόμενα θέματα

Daniil Danin — έμπνευση από το Probabilities of the Quantum World
(MIR Publishers, 1983)

Oleg Glebov & Vitaly Kisin — για την αγγλική μετάφραση του βιβλίου

MathJax, Tailwind, Font Awesome — για τα εργαλεία ανοιχτού κώδικα

📬 Επικοινωνία
📧 Email: tasos_tzanopoulos@yahoo.com

🌐 Blog: https://httpmyphysics.blogspot.com/

💻 GitHub: @tzanopoulostasos-cpu

🔗 Live: https://tzanopoulostasos-cpu.github.io/e.e.fysikwn/

📝 Σημειώσεις
Το project είναι single-file — όλα σε ένα index.html

Λειτουργεί offline μετά την πρώτη φόρτωση (εκτός από CDN)

Τα CDN (Tailwind, MathJax, Font Awesome) φορτώνουν online

Για πλήρη offline λειτουργία, κατέβασε τα CDN τοπικά

© 2026 Τάσος Τζανόπουλος — Φυσικός, συγγραφέας
