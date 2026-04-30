# ChavrutaConnect 📖

פלטפורמה למציאת חברותא ללימוד תורה — Tinder for Torah study partners.

## תכונות

- 🟢 **כפתור "מחפש חברותא עכשיו"** — הופעת פרופיל בזמן אמת לפי בקשה
- 📍 **חיפוש גאוגרפי** — מפה אינטראקטיבית עם רדיוס מותאם
- 🏛️ **חיפוש מוסדי** — בתוך 124+ ישיבות, מכינות, מדרשות וכוללים
- 🎯 **התאמה חכמה** — לפי נושא, רמה, פורמט, זמינות
- 💬 **צ'אט פנימי** — תקשורת ישירה בין חברותות
- 🔥 **Firestore Backend** — סנכרון בזמן אמת בין מכשירים
- 📱 **PWA-ready** — ניתן להוסיף למסך הבית בטלפון

## הפעלה

1. צור פרויקט Firebase ב-https://console.firebase.google.com/
2. הפעל Firestore (Test mode)
3. העתק את ה-Firebase config והדבק בקובץ `index.html` (חפש `YOUR_API_KEY_HERE`)
4. העלה ל-Netlify Drop / Cloudflare Pages / GitHub Pages

## מבנה

קובץ HTML יחיד עם:
- Vanilla JavaScript (ללא frameworks)
- Tailwind-style CSS
- Leaflet.js למפות
- Firebase Firestore SDK

## רישיון

© 2026 ChavrutaConnect — דוד יהאל
