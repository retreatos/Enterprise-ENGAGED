# RetreatsOS — חבילת העלאה ללייב (פשוטה)

מטרה: לקחת את הקוד המאוחד שלך ולהעלות אותו ללייב בלי ידע תכנותי.

## מה זה עושה
- פרונטאנד (Next.js) → Vercel
- בקאנד (Node/Express/Nest/Next API) + Postgres → Render
- מייצר קובץ ENV לדוגמה שתוכל להעתיק ולהדביק לערכי הסוד שלך.

## איך להשתמש (ב-10 דקות)
1) פותחים חשבון חינמי ב-Vercel וב-Render (וגם Postgres ב-Render).
2) מעלים את התיקייה `.github/` והרשימות שבחבילה הזו לרפו שלך בגיטהאב (Commit & Push).
3) ב-Vercel: Create New Project → בחר את הרפו → תן משתני סביבה לפי `env.example` → Deploy.
4) ב-Render: New → PostgreSQL (תעתיק את ה-connection string למשתנה DB_URL) → New → Web Service → חבר את הרפו → בחר Docker → Deploy.
5) ב-GitHub → Actions: תראה את ה-build/deploy רצים. בסוף תקבל לינקים ל-LIVE.

> לא חייבים להבין הכל; פשוט לעקוב אחרי ה-README והמסכים יכוונו אותך.
