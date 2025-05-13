# dataset
# Students' Academic Performance Dataset

This dataset contains academic and behavioral information about students and is intended to help analyze factors that affect students' performance in an educational setting.

##  Dataset Overview

The dataset includes **480 records** and **17 columns**, covering both demographic and activity-based features of students.

---

##  Features Description

| Column Name                | Type    | Description |
|---------------------------|---------|-------------|
| `gender`                  | object  | Student's gender (e.g., Male, Female) |
| `NationalITy`             | object  | Nationality of the student |
| `PlaceofBirth`            | object  | City or place where the student was born |
| `StageID`                 | object  | Educational level (e.g., Lower, Middle, Upper) |
| `GradeID`                 | object  | Grade/year level of the student |
| `SectionID`               | object  | Classroom section ID |
| `Topic`                   | object  | Course subject (e.g., Math, Science) |
| `Semester`                | object  | Semester of the academic year (e.g., First, Second) |
| `Relation`                | object  | Relationship of the student’s parent who is responsible for their education |
| `raisedhands`             | int     | Number of times the student raised their hand in class |
| `VisITedResources`        | int     | Number of times the student visited course resources |
| `AnnouncementsView`       | int     | Number of times the student viewed course announcements |
| `Discussion`              | int     | Number of times the student participated in class discussion |
| `ParentAnsweringSurvey`   | object  | Whether the student's parent answered the school survey (Yes/No) |
| `ParentschoolSatisfaction`| object  | Parent's satisfaction level with the school (Good/Bad) |
| `StudentAbsenceDays`      | object  | Student's absence record (Under-7 or Above-7 days) |
| `Class`                   | object  | Final performance classification (L = Low, M = Middle, H = High) |

---

##  Potential Use Cases

- **Educational data mining**
- **Performance prediction models**
- **Student behavior analysis**
- **Parental involvement studies**
- **Visualization and dashboarding practice**

---

##  Sample Analyses

Here are some examples of insights you could extract:

- Relationship between `raisedhands` and performance (`Class`)
- Comparison of performance across `gender`, `StageID`, or `Topic`
- Effect of parental involvement (`ParentAnsweringSurvey`, `ParentschoolSatisfaction`) on student outcomes
- Absenteeism (`StudentAbsenceDays`) and its impact on grades

---

##  Tools You Can Use

- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebooks
- Machine Learning Libraries (Scikit-learn)
- Data Visualization Tools (Tableau, Power BI)

---

##  License

This dataset is provided for educational and research purposes only.

---

##  Maintainer

Project by: *[Hedi Madih Mohammed Qadir]*  


