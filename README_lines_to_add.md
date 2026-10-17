שורות להוספה לטבלה "הקבצים" ב-README של anatshapir/datasets:

| `happiness_2024.csv` | דוח האושר העולמי 2024: שורה לכל מדינה | 143 |
| `happiness_by_year.csv` | דוח האושר העולמי: מדינה בכל שנה, 2005-2023 (קידוד latin-1, בכוונה) | 2,363 |

שורה להוספה ל"הערות לשימוש":

- הקובץ `happiness_by_year.csv` שמור בקידוד latin-1 כמו שהגיע מ-Kaggle, ולא ב-UTF-8. זה בכוונה: שיעור 2 מלמד לטעון אותו עם `encoding="latin-1"`. לא להמיר.
- בקובץ `happiness_2024.csv` העמודות מ-`Log GDP per capita` ועד `Dystopia + residual` הן חלקים של ציון האושר, לא הערכים עצמם.

שורה להוספה ל"מקורות":

World Happiness Report, דרך Kaggle (jainaru/world-happiness-report-2024-yearly-updated).
