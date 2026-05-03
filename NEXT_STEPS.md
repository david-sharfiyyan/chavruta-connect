# 🚀 השלבים הבאים — מה אתה צריך לעשות

הקובץ `index.html` מוכן לפריסה. עכשיו 2 פעולות בדפדפן:

---

## שלב A: Firebase (5 דק')

1. פתח: https://console.firebase.google.com/
2. **"Add project"** → שם: `chavruta-connect` → המשך → המשך → "Create"
3. המתן ~30 שניות → "Continue"
4. תפריט שמאל: **Build → Firestore Database**
5. **"Create database"** → **"Start in test mode"** → אזור: `eur3` → "Enable"
6. חזור לעמוד הראשי → לחץ אייקון **`</>`** (Web)
7. nickname: `ChavrutaConnect` → "Register app"
8. **תעתיק את הקוד שמופיע ותשלח לי בצ'אט**

הוא נראה ככה:
```javascript
const firebaseConfig = {
  apiKey: "AIzaSy...",
  authDomain: "chavruta-connect.firebaseapp.com",
  projectId: "chavruta-connect",
  storageBucket: "chavruta-connect.appspot.com",
  messagingSenderId: "1234567890",
  appId: "1:1234567890:web:abc..."
};
```

---

## שלב B: פריסה ל-Netlify (3 דק')

1. פתח: https://app.netlify.com/drop
2. הירשם עם Google
3. **גרור את התיקייה הזו** (`chavruta-deploy`) לחלון
4. תקבל URL כמו `https://amazing-chavruta-12345.netlify.app`
5. (אופציונלי) Domain settings → "Edit site name" → `chavrutaconnect`

---

## ✅ זהו!

שלח את הקישור ל-WhatsApp לחבר. שניכם תראו אחד את השני בזמן אמת.
