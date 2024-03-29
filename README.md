<div dir="rtl">

## תיאור הפרויקט 
עיצבנו אתר עבור לקוחה בעלת עסק של קרמיקה ותכשיטים ייחודיים ועל פי הצרכים שלה יצרנו את האתר. השתדלנו לעשות זאת ברמה גבוהה ובסטנדרטים הדומים לאלו של האתרים בארץ. ניתן לצפות ולהשתמש באתר עם כל סוגי המסכים (מחשב, אייפד ופלאפון)

## הנחות 
- הלקוחות שלנו מישראל ולכן יצרנו את האתר בעברית ואפשרנו הזנה רק של טלפון ישראלי.
- בשלב זה לא ראינו צורך להוסיף את האובייקטים מכיוון שאין עדיין חיבור לbackend ולכן אין צורך עדיין לשמור פרטים. יוצג בחלק ג'.

## הנחיות למשתמש 
בכל אחד מהעמודים קיים סרגל ניווט עליון 'nav' וסרגל ניווט תחתון 'footer' כך שבכל שלב נוכל לעבור לעמודים הרצויים בקלות.

## עמודים
### עמוד הבית
קיימת אפשרות בעמוד הבית לעבור לעמודים אחרים ע"י שימוש בסרגל העליון – בשימוש באייפד/אייפון הסרגל יהיה סרגל ניווט צידי. בכל שלב ישנה אפשרות לחזור לעמוד הבית על ידי לחיצה על 'בית' או על 'michal studio'. בעמוד ניתן לבחור אחת מבין 2 הקטגוריות – קרמיקה או תכשיטים. בנוסף, ישנה אפשרות להירשם לניוזלטר למטרות שיווק ומבצעים: נכניס את כתובת המייל שלנו בקלט ולאחר מכן נלחץ על כפתור 'הרשמה'.
### התחברות
כל משתמש יכול להיכנס לעמוד זה על מנת לבצע תהליך התחברות לחשבון משתמש, ניתן יהיה לאפס סיסמה עבור משתמש קיים. לאחר ההתחברות לחשבון נעבור אוטומטית לעמוד החשבון האישי שלנו 'purchase_history'.
- תהליך הכניסה באמצעות גוגל - יעבוד כאשר נרצה להשיק את האתר סופית, ונשיג את הclient id של גוגל.
### הרשמה
כל משתמש יכול להיכנס לעמוד זה כדי לבצע תהליך יצירת חשבון משתמש חדש.
נניח כי מתבצע אימות של כתובת המייל עבור חשבון משתמש קיים (ניישם בחלק ג') ואז תופיע בירוק הודעת השלמת פעולת האיפוס בהצלחה. 
- הגבלנו את גיל המינימום לגיל 12 (אנחנו מניחות שהלקוחות הנרשמים יהיו כנים לגבי תאריך הלידה שלהם).
### איפוס סיסמה
העמוד הזה מיועד למשתמשים בעלי חשבון קיים אשר מעוניינים לאפס את הסיסמה שלהם. נאפס את הסיסמה באמצעות כתובת המייל של החשבון הקיים במערכת.
### עגלת הקניות
כל סוג משתמש יכול להיכנס לעמוד זה כדי לצפות בפריטים שהוסיף לעגלת הקניות שלו בין אם מדובר במשתמש מחובר או אורח. ניתן להסיר מוצר מסל הקניות ולצפות במוצרים שהוספנו עד כה.
### היסטוריית רכישות (עמוד חשבון המשתמש)
מיועד עבור לקוח מחובר בלבד, מדובר בעמוד החשבון האישי של הלקוח ובתוכו קיימת היסטוריית הרכישות שלו. בעבור משתמש מחובר, אייקון החשבון בסרגל העליון יפנה ישירות להיסטוריית הזמנות של הלקוח.
### קניות (תכשיטים וקרמיקה)
כל סוג משתמש יכול להיכנס לעמוד זה במטרה לצפות בקטלוג מוצרי הקרמיקה המוצעים למכירה, להיכנס לעמוד של המוצר עצמו ולהוסיף לסל ישירות מהקטלוג.
ניתן להוסיף מוצר לסל קניות, לעבור לעמוד מורחב של כל מוצר- לטובת המחשה בלבד יצרנו עמוד למוצר הראשון משמאל בלבד, ויש אפשרות לסינון ומיון המוצרים בדף. 
- יישום של הסינון והמיון לא יתבצעו בחלק זה של הפרויקט.
### מוצר (תכשיט וקרמיקה)
ניתן לצפות בתמונות שונות של המוצר ולהוסיף מוצר זה לסל הקניות. חשוב לציין כי כל מוצר מקרמיקה הינו ייחודי במינו ולכן ישנה אופציה להוסיף אך ורק כמות של מוצר בודד לסל הקניות בניגוד לתכשיטים.
### צור קשר
ניתן ליצור קשר עם בעלת החנות ע"י מילוי פרטים שנמצאים בטופס ושליחת ההודעה. בנוסף, קיימת מפה עם מיקום הסטודיו עבור לקוחות שמעוניינים לבקר בחנות או בסטודיו.
### אודות
דף זה משמש לקבלת מידע אודות העסק. בדף קישורים לכל הרשתות החברתיות ולווטסאפ של בעלת העסק. הפעלת כל קישור מתבצעת על ידי לחיצה על האייקון המתאים. 
כמו כן, ניתן להיכנס לסרטונים שמציגים תהליך הכנת כלים מקרמיקה של בעלת העסק בסטודיו על ידי לחיצה על הסרטון עצמו.

</div>