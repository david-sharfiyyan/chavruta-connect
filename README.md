# ChavrutaConnect 📖

פלטפורמה למציאת חברותא ללימוד תורה — Tinder for Torah study partners.

## 🌐 אתר חי

**👉 https://david-sharfiyyan.github.io/chavruta-connect/**

## תכונות

- 🟢 **כפתור "מחפש חברותא עכשיו"** — הופעת פרופיל בזמן אמת לפי בקשה
- 📍 **חיפוש גאוגרפי** — מפה אינטראקטיבית עם רדיוס מותאם
- 🏛️ **חיפוש מוסדי** — בתוך 124+ ישיבות, מכינות, מדרשות וכוללים
- 🎯 **התאמה חכמה** — לפי נושא, רמה, פורמט, זמינות
- 💬 **צ'אט פנימי** — תקשורת ישירה בין חברותות
- 🔥 **Firestore Backend** — סנכרון בזמן אמת בין מכשירים
- 📱 **PWA-ready** — ניתן להוסיף למסך הבית בטלפון

## ארכיטקטורה

| שכבה | שירות |
|------|-------|
| Frontend Hosting | GitHub Pages |
| Code Repository | GitHub |
| Database | Firebase Firestore (project: `chavrutinder`) |
| Maps | Leaflet.js + OpenStreetMap |

## עדכון האתר

```bash
cd C:\Users\rolan\Desktop\chavruta-deploy
# ערוך את index.html
git add -A
git commit -m "תיאור השינוי"
git push
```

GitHub Pages יעדכן את האתר אוטומטית תוך ~דקה-שתיים.

## מבנה הקוד

קובץ HTML יחיד (`index.html`) עם:
- Vanilla JavaScript (ללא frameworks)
- CSS inline
- Leaflet.js למפות
- Firebase Firestore SDK

## רישיון

© 2026 ChavrutaConnect — דוד יהאל
