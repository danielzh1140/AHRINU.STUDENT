# איך למזג את העדכון / How to merge

1. הורד את הקובץ `AHRINU.STUDENT.tar.gz` או את תוכן ה-gist
2. חלץ לתיקייה
3. העתק לריפו שלך:

```bash
git clone https://github.com/sh0548430599-beep/AHRINU.STUDENT.git
cd AHRINU.STUDENT
# העתק את הקבצים מהחבילה לכאן (החלף את הקיימים)
# then:
git checkout -b AHRINU.STUDENT
git add -A
git commit -m "Sync full student LMS update"
git push -u origin AHRINU.STUDENT
# ואז ב-GitHub: Open Pull Request -> Merge
```
