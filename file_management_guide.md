---

## title: ניהול קבצים nav\_order: 2 has\_children: false

# 📁 ניהול קבצים ב-Linux וב-Windows

ניהול קבצים הוא חלק בסיסי וחשוב בכל מערכת הפעלה. כאן נסקור פקודות נפוצות, טיפים שימושיים ונציג דוגמאות קוד לניהול קבצים במערכות שונות.

---

## 🐧 פקודות בסיסיות ב-Linux

### יצירת תיקייה:

```bash
mkdir my_folder
```

### מעבר לתיקייה:

```bash
cd my_folder
```

### הצגת קבצים בתיקייה:

```bash
ls -la
```

### העתקת קובץ:

```bash
cp source.txt destination.txt
```

### מחיקת קובץ:

```bash
rm unwanted.txt
```

---

## 🪟 פקודות מקבילות ב-Windows (CMD)

### יצירת תיקייה:

```cmd
mkdir my_folder
```

### מעבר לתיקייה:

```cmd
cd my_folder
```

### הצגת קבצים:

```cmd
dir
```

### העתקת קובץ:

```cmd
copy source.txt destination.txt
```

### מחיקת קובץ:

```cmd
del unwanted.txt
```

---

## 💡 טיפים שימושיים

- הוסף את הסימן `-r` למחיקה רקורסיבית של תיקייה ב-Linux:

  ```bash
  rm -r my_folder
  ```

- השתמש ב-`Tab` להשלמה אוטומטית של שמות קבצים בטרמינל.

- שמור על שמות קבצים ברורים ותמציתיים.

---

## 📊 טבלת השוואה

| פעולה        | Linux    | Windows |
| ------------ | -------- | ------- |
| יצירת תיקייה | `mkdir`  | `mkdir` |
| מעבר תיקייה  | `cd`     | `cd`    |
| רשימת קבצים  | `ls -la` | `dir`   |
| העתקה        | `cp`     | `copy`  |
| מחיקה        | `rm`     | `del`   |

---

## 📝 סיכום

היכרות עם פקודות ניהול קבצים בסיסיות מאפשרת לך לעבוד ביעילות מול המערכת, בין אם אתה משתמש ב-Windows ובין אם ב-Linux. מומלץ לתרגל את הפקודות בסביבת עבודה בטוחה.

