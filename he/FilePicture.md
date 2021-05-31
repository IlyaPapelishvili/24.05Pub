כותרת ראשונה | כותרת שנייה
--- | ---
תא תוכן | תא תוכן
תא תוכן | תא תוכן

כותרת ראשונה | כותרת שנייה
--- | ---
תא תוכן | תא תוכן
תא תוכן | תא תוכן

![מְצוּדָה](https://vignette.wikia.nocookie.net/masseffect/images/d/d7/MassEffect2Citadel.jpg/revision/latest?cb=20100721191415)

מיושר משמאל | מרכז מיושר | מיושר מימין
:-- | :-: | --:
קול 3 הוא | טקסט מילולי כלשהו | **1600 דולר**
קול 2 הוא | מְרוּכָּז | 12 דולר
פסי זברה | מסודרים | ~~ $ 1 ~~

Dillinger is a cloud-enabled, mobile-ready, offline-storage, AngularJS powered HTML5 Markdown editor.

- הקלד קצת Markdown בצד שמאל
- ראה HTML בצד ימין
- קֶסֶם

# נָכוֹן

- ייבא קובץ HTML וצפה בו הופך בצורה קסומה ל- Markdown
- גרור ושחרר תמונות (מחייב את קישור חשבון Dropbox שלך)

אתה יכול גם:

- ייבא ושמור קבצים מ- GitHub, Dropbox, Google Drive ו- One Drive
- גרור ושחרר קבצי סימון ו HTML לתוך דילינג'ר
- ייצא מסמכים כ- Markdown, HTML ו- PDF

Markdown היא שפת סימונים קלת משקל המבוססת על מוסכמות העיצוב שאנשים משתמשים בהן באופן טבעי בדוא"ל. כפי שכותב [ג'ון גרובר] באתר [Markdown] [df1]

> מטרת התכנון העיקרית לתחביר העיצוב של Markdown היא להפוך אותו לקריא ככל האפשר. הרעיון הוא שמסמך בפורמט Markdown צריך להיות פרסום כפי שהוא, כטקסט רגיל, מבלי להיראות כאילו סומן בתגים או הוראות עיצוב.

הטקסט הזה שאתה רואה כאן *כתוב למעשה* ב- Markdown! כדי להרגיש את התחביר של Markdown, הקלד טקסט כלשהו בחלון השמאלי וצפה בתוצאות בצד ימין.

### שֶׁקֶר

דילינגר משתמש במספר פרויקטים של קוד פתוח כדי לעבוד כראוי:

- [AngularJS] - HTML משופר לאפליקציות אינטרנט!
- [עורך אס] - עורך טקסטים מבוסס אינטרנט מדהים
- [markdown-it] - מנתח Markdown נעשה נכון. מהיר וקל להארכה.
- [טוויטר Bootstrap] - boilerplate נהדר עבור יישומי אינטרנט מודרניים
- [node.js] - אירע קלט / פלט עבור ה- backend
- [Express] - מסגרת יישומי רשת node.js מהירה [@tjholowaychuk]
- [Gulp] - מערכת הזרמת הבניין
- [Breakdance](https://breakdance.github.io/breakdance/) - ממיר HTML ל- Markdown
- [jQuery] - דו

וכמובן דילינגר עצמו הוא קוד פתוח עם [מאגר ציבורי] [שמיר] ב- GitHub.

### הַתקָנָה

![אילוס](https://lh3.googleusercontent.com/proxy/DDV8a7sLIWurhJtW8Ego9bq-JlwpfFFoR0tkLJQKKYXEXoWHB6ZUP5jGKD2VcYt3z1QVsgcn6L3GoU1ns8m9fvi3U51GzddA70ZUMHgzHvjl4-i7YOJY9cShBPrfjUhMQhxaJ97WFBp612XmjMXVGypfGkiBarN4PWxhiHkiYYNW7HGbtTpOcyt9GQ4Q23C2noxLTWFXZMcQZhRpQA_qzu2n6_H6CPViBnhSHpEl4JZAPaGCSJqgZg)

דילינגר דורש [את הפעלת Node.js](https://nodejs.org/) v4 +.

התקן את התלות והתלות התלות והפעל את השרת.

```sh
$ cd dillinger
$ npm install -d
$ node app
```

לסביבות ייצור ...

```sh
$ npm install --production
$ NODE_ENV=production node app
```

### תוספים

דילינגר מורחבת כעת עם התוספים הבאים. הוראות כיצד להשתמש בהן ביישום שלך מקושרות למטה.

חיבור | תקרא אותי
--- | ---
דרופבוקס | [תוספים / dropbox / README.md] [PlDb]
GitHub | [תוספים / github / README.md] [PlGh]
גוגל דרייב | [תוספים / googledrive / README.md] [PlGd]
OneDrive | [תוספים / onedrive / README.md] [PlOd]
בינוני | [תוספים / מדיום / README.md] [PlMe]
גוגל ניתוח נתונים | [תוספים / googleanalytics / README.md] [PlGa]

### התפתחות

רוצים לתרום? גדול!

דילינגר משתמש ב- Gulp + Webpack לפיתוח מהיר. בצע שינוי בקובץ שלך וראה מיד את העדכונים שלך!

פתח את הטרמינל המועדף עליך והפעל פקודות אלה.

כרטיסייה ראשונה:

```sh
$ node app
```

כרטיסייה שנייה:

```sh
$ gulp watch
```

(אופציונלי) שלישי:

```sh
$ karma test
```

#### בניין למקור

לשחרור הפקה:

```sh
$ gulp build --prod
```

יצירת ארכיוני zip שנבנו מראש להפצה:

```sh
$ gulp build dist --prod
```

### דוקר

דילינגר קל מאוד להתקנה ולפריסה במיכל דוקר.

כברירת מחדל, ה- Docker יחשוף את יציאת 8080, לכן שנה זאת בתוך Dockerfile במידת הצורך. כשתהיה מוכן, פשוט השתמש ב- Dockerfile לבניית התמונה.

```sh
cd dillinger
docker build -t joemccann/dillinger:${package.json.version} .
```

זה ייצור את תמונת הדילינגר וימשוך את התלות הדרושה. הקפד להחליף את `${package.json.version}` עם הגרסה האמיתית של דילינג'ר.

לאחר שתסיים, הפעל את תמונת ה- Docker ומפה את היציאה לכל מה שתרצה למארח שלך. בדוגמה זו, אנו פשוט ממפים את יציאת 8000 של המארח ליציאה 8080 של ה- Docker (או כל יציאה שנחשפה ב- Dockerfile):

```sh
docker run -d -p 8000:8080 --restart="always" <youruser>/dillinger:${package.json.version}
```

אמת את הפריסה על ידי ניווט לכתובת השרת שלך בדפדפן המועדף עליך.

```sh
127.0.0.1:8000
```

#### Kubernetes + Google Cloud

ראה [KUBERNETES.md](https://github.com/joemccann/dillinger/blob/master/KUBERNETES.md)

### לעשות
