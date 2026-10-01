<div dir="rtl">

# נתוני הקורס - מבוא לבינה מלאכותית

קובצי הנתונים לקורס "מבוא לבינה מלאכותית, חלופה ליחידה 3", הכפר הירוק.
כל הקבצים בקידוד UTF-8 with BOM, ונפתחים נכון גם באקסל.

## טעינה מ-Colab

```python
import pandas as pd
DATA_BASE = "https://raw.githubusercontent.com/anatshapir/datasets/main/"
df = pd.read_csv(DATA_BASE + "ballots50.csv", encoding="utf-8-sig")
```

## הקבצים

| קובץ | תוכן | שורות |
| --- | --- | --- |
| `ballots50.csv` | 50 קלפיות לדוגמה, כנסת 25 | 50 |
| `ballots_k25.csv` | כל הקלפיות, כנסת 25, עם אחוז הצבעה | 12,545 |
| `towns_turnout_19_25.csv` | יישובים: אחוז הצבעה בכנסות 19 עד 25 | 1,177 |
| `knn_turnout_change.csv` | קובץ KNN: האם ההצבעה עלתה בין 24 ל-25 | 1,177 |
| `accidents_2025.csv` | תאונות דרכים 2025 | 7,717 |
| `personal_security_2020_2025.csv` | סקר ביטחון אישי 2020-2025 | 30,289 |
| `social_survey_2022_2025.csv` | הסקר החברתי 2022-2025 | 26,334 |
| `household_expenses_2023.csv` | הוצאות משק בית 2023 | 4,005 |
| `covid_survey_2020.csv` | סקר קורונה 2020, ארבעה גלים | 5,340 |
| `excess_mortality_israel.csv` | תמותה עודפת וחיסונים, ישראל | 261 |
| `covid_israel_daily.csv` | קורונה בישראל: תחלואה ותמותה | 1,674 |
| `oecd_mortality_by_cause.csv` | תמותה לפי סיבה, OECD | 17,639 |
| `simpson_vaccines_israel.csv` | פרדוקס סימפסון: חיסונים בישראל | 11 |
| `pisa_over_time.csv` | PISA: ציונים לאורך זמן | 1,310 |
| `pisa_change_2018_2022.csv` | PISA: שינוי 2018-2022 | 86 |
| `pisa_2025.csv` | PISA 2025: תוספת | 168 |

## הערות לשימוש

- בקובץ `ballots_k25.csv` יש 838 שורות של מעטפות חיצוניות, שבהן מספר בעלי זכות הבחירה הוא 0. אלה נתונים לגיטימיים, ואי אפשר לחשב עליהם אחוז הצבעה.
- בקובץ `knn_turnout_change.csv` אין להשתמש בבחירות 24 ו-25 כמאפיינים: זו דליפת נתונים.
- נתון על קלפי או על יישוב אינו נתון על אדם.

## מקורות

ועדת הבחירות המרכזית, הלמ"ס (קובצי PUF), OECD Health Statistics, OECD PISA, Our World in Data.

</div>
