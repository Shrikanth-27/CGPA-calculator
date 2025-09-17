# CGPA Calculator

A simple CGPA calculator built using **JavaScript**, **HTML**, and **CSS**. This platform allows users to calculate their GPA for each semester and overall CGPA efficiently.

## 🚀 Features

- 📊 **GPA & CGPA Calculation**: Automatically calculates GPA for the current semester and cumulative CGPA.
- 📅 **Multiple Semester Support**: Calculate CGPA over multiple semesters.
- 📱 **Responsive Design**: Works seamlessly on both mobile and desktop.

## 🛠️ Technologies Used

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)


## 📋 How CGPA is Calculated

The CGPA (Cumulative Grade Point Average) is calculated based on the grades you achieve in each subject and their corresponding credits. Here’s how it works:

### Formula:
- **CGPA** = (Total Grade Points in all Semesters) / (Total Credits in all Semesters)

- **GPA** for each semester is calculated using:
  - GPA = (Sum of [Grade Points × Credits]) / (Sum of Credits)

### Grade Points Table

| Grade | Grade Points | Credits                                         |
|-------|--------------|-------------------------------------------------|
| O     | 10           | Depends on the subject (typically 3 or 4 credits) |
| A+    | 9            | Depends on the subject                          |
| A     | 8            | Depends on the subject                          |
| B+    | 7            | Depends on the subject                          |
| B     | 6            | Depends on the subject                          |
| RA    | 0            | -                                               |

- The grades are assigned based on the marks obtained in each subject.
- Multiply the grade point by the corresponding credit hours to get the grade point for each subject.
- Sum the grade points for all subjects and divide by the total credits to get the GPA for the semester.
- The **CGPA** is the average of all semester GPAs, weighted by credits.




