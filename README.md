# 🇮🇱 Hebrew Language Education Skills
### מערכת סקילים לעברית וחינוך לשוני — כיתות ד–ו

קובצי סקיל לסביבת Claude, המיועדים לתמוך במורים לעברית וחינוך לשוני בבית הספר היסודי הממלכתי בישראל.

---

## 📦 תוכן המאגר

| קובץ | תיאור |
|------|--------|
| `hebrew-project-knowledge.skill` | בסיס הידע המרכזי — תוכנית הלימודים, ממדי הבנת הנקרא, נושאי ד–ו |
| `hebrew-teacher-guide.skill` | מדריך למורה לנושא ספציפי או מפת שנה |
| `hebrew-lesson-planner.skill` | תכנון מערך שיעור — שלבי או מלא |
| `hebrew-worksheet-creator.skill` | יצירת דפי משימות (הבנת הנקרא / תרגול דקדוק) |
| `hebrew-assessment.skill` | כלי הערכה: מבחן, רובריקה, Exit Ticket, Checklist |
| `hebrew-text-generator.skill` | מחולל טקסטים מקוריים: סיפור, הבנת הנקרא, דיאלוג |
| `project-instructions.md` | הוראות פרויקט להדבקה ב-Claude Project Instructions |

---

## 🚀 התחלה מהירה

### 1. התקנת הסקילים
- עבור להגדרות Claude → **Skills**
- העלה כל קובץ `.skill` בנפרד

### 2. הגדרת הפרויקט
- צור פרויקט חדש ב-Claude
- העתק את תוכן `project-instructions.md` לתוך **Project Instructions**

### 3. העלאת קבצי ידע לפרויקט
העלה לתוך **Project Knowledge** את הקבצים הבאים:
- `תוכנית_הלימודים_המלאה_כל_הפרקים.pdf`
- `הבנת_הנקרא_פירוט_ממדי_ההבנה.pdf`
- `יצירת_דף_משימות.docx`

---

## 🛠️ שימוש

### שרשראות עבודה מומלצות

**שיעור מלא:**
```
hebrew-text-generator → hebrew-worksheet-creator → hebrew-lesson-planner → hebrew-assessment
```

**הכנת נושא:**
```
hebrew-teacher-guide → hebrew-lesson-planner
```

**הערכה:**
```
hebrew-worksheet-creator (תרגול) → hebrew-assessment (מבחן + רובריקה)
```

### דוגמאות לפקודות

```
"בנה מערך שיעור על מילות קישור לכיתה ד', 45 דקות, טקסט על כלבים"

"צור דף משימות הבנת הנקרא לכיתה ה' — סיפור"

"מדריך למורה על בניין פיעל, כיתה ה'"

"מבחן על שמות המספר לכיתה ד'"
```

---

## 📚 בסיס הידע (references)

הסקיל `hebrew-project-knowledge` כולל 9 קבצי reference הנטענים לפי צורך:

| קובץ | תוכן |
|------|-------|
| `topics-d.md` | תוכנית כיתה ד' — פירוט מלא |
| `topics-h.md` | תוכנית כיתה ה' — כולל סימון "חדש" |
| `topics-v.md` | תוכנית כיתה ו' + רשימת יצירות ה'–ו' |
| `topics-hv.md` | Scope & Sequence — טבלת השוואה בין כיתות |
| `grammar-scope.md` | נושאי דקדוק לפי חובה/העשרה |
| `worksheet-template.md` | תבנית דף המשימות ב-7 חלקים |
| `yesod.md` | 8 הישגי יסוד לפי כיתה ד' וה'–ו' |
| `hots.md` | חשיבה מסדר גבוה — 7 אסטרטגיות |
| `critical-thinking.md` | חשיבה ביקורתית — מסגרת פדגוגית |

---

## ⚙️ עקרונות עיצוב

- **ממלכתי בלבד** — מבוסס על תוכנית הלימודים הממלכתית (תשס"ג)
- **חשיבה ביקורתית ו-HOTS** — מוטמעים בכל פלט כברירת מחדל
- **בדיקת תקינות לשונית** — כל פלט עובר `hebrew-grammar-checker` לפני מסירה
- **Progressive disclosure** — SKILL.md תמיד בהקשר, references נטענים לפי צורך

---

## 📋 דרישות

- חשבון Claude עם גישה לסקילים
- סקיל `hebrew-grammar-checker` מותקן בנפרד

---

## 📄 רישיון

לשימוש חינוכי חופשי.
