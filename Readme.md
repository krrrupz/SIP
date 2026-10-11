<div align="center">

# ➕ SIP Round — Class 3 Maths Practice

### Addition & Subtraction Question Generator

Practise arithmetic with randomly generated questions, check answers instantly, review solutions, and print a worksheet or save it as a PDF.

<p>
  <a href="#-features"><img src="https://img.shields.io/badge/✨_Features-Explore-0b63d5?style=for-the-badge" alt="Features"></a>
  <a href="#-how-to-use"><img src="https://img.shields.io/badge/🚀_How_to_Use-Start-2ea44f?style=for-the-badge" alt="How to use"></a>
  <a href="#-printing-and-pdf"><img src="https://img.shields.io/badge/🖨️_Print_or_PDF-Export-7b61ff?style=for-the-badge" alt="Print or PDF"></a>
</p>

<p>
  <img src="https://img.shields.io/badge/HTML5-Worksheet-e34f26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-Responsive_Layout-1572b6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-No_Dependencies-f7df1e?style=for-the-badge&logo=javascript&logoColor=222" alt="JavaScript">
  <img src="https://img.shields.io/badge/Setup-Open_in_Browser-2ea44f?style=for-the-badge" alt="No installation">
</p>

</div>

---

## 📚 Overview

**SIP Round — Class 3 Questions** is a lightweight, browser-based maths worksheet for practising addition and subtraction. It generates a fresh set of arithmetic questions and lets learners enter answers, check their score, view correct solutions, or print the worksheet.

The project uses plain **HTML, CSS, and JavaScript**. It requires no Python, server, package manager, or external JavaScript libraries.

## ✨ Features

<table>
<tr>
<td width="50%">

### 🧮 Random Questions
- Generates addition and subtraction questions.
- Choose **100, 200, or 300** questions per set.
- Uses a mix of two- and three-digit numbers.
- Creates a new set on demand.

</td>
<td width="50%">

### ✅ Answer Checking
- Enter numeric answers for each question.
- Check answers in one click.
- See the score out of the total question count.
- Review incorrect and unanswered questions with their correct answers.

</td>
</tr>
<tr>
<td width="50%">

### 💡 Solutions
- Reveal the answer to every question.
- View each question alongside its correct result.
- Use solutions for self-checking and revision.

</td>
<td width="50%">

### 🖨️ Print-Friendly Worksheet
- Print the questions from the browser.
- Use the browser's **Save as PDF** option.
- Uses a print stylesheet to hide controls and results.
- Keeps the two-column layout on paper where possible.

</td>
</tr>
</table>

## 🚀 How to Use

### 1. Get the file

Save the HTML code as:

```text
index.html
```

Example project layout:

```text
sip-class-3/
└── index.html
```

### 2. Open it

Double-click `index.html` to open it in a modern browser, such as Chrome, Edge, or Firefox.

No installation or internet connection is required after you have saved the file.

### 3. Choose the question count

Use the **Questions** dropdown to select:

- `100` questions
- `200` questions
- `300` questions (default)

Changing the selection generates a new set.

### 4. Answer and check

1. Enter an answer in the box below each arithmetic question.
2. Select **Check Answers**.
3. Review the score and the result list. Correct answers are highlighted green; incorrect or unanswered questions are highlighted red.

### 5. Generate another set

Click **New Set** to generate new questions. If you have entered answers, the page asks you to confirm before replacing the current set.

### 6. View all answers

Click **Show Solutions** to display every question with its correct answer.

## 🖨️ Printing and PDF

1. Click **Print / Save PDF**.
2. In the browser print dialog, choose a printer or select **Save as PDF**.
3. Adjust paper size, margins, and scale if needed.
4. Save or print the worksheet.

The print stylesheet hides the controls, score, results panel, and footer so the printed page focuses on the questions. Input boxes are styled as blank answer spaces.

## ➗ Question Generation

The generator randomly selects addition or subtraction and varies the operand sizes.

| Operation | Number patterns used |
|---|---|
| Addition | Two-digit + two-digit; three-digit + two-digit; three-digit + three-digit |
| Subtraction | Three-digit − two-digit; three-digit − three-digit, arranged so the result is non-negative |

The generated set is random, so the exact questions and answers vary whenever a new set is created.

## 🧱 Technologies

| Technology | Purpose |
|---|---|
| HTML | Page structure, controls, answer fields, and results |
| CSS | Colors, cards, responsive layout, and print styling |
| JavaScript | Random question generation, rendering, answer checking, scoring, and solutions |

## 📱 Responsive Design

On wider screens, questions are arranged in two columns. At viewport widths of **900 px or less**, the layout changes to one column for easier reading on smaller screens.

## ⚠️ Current Behaviour and Limitations

- Question counts are limited to **100, 200, or 300** through the dropdown.
- The page checks answers locally in the browser; it does not save results to a server or database.
- Refreshing or closing the page loses the current question set and answers.
- Questions are randomly generated and are not guaranteed to be unique within a set.
- The answer fields accept numeric input. The page does not provide a teacher dashboard, student accounts, or persistent score history.
- The **New Set** button confirms before replacing entered answers. Changing the question-count dropdown generates a new set immediately.
- The print stylesheet hides the results panel, so check or review answers on screen before printing if you need to retain the result feedback.

## 🗂️ Project Structure

For the single-file version provided:

```text
sip-class-3/
└── index.html    # HTML, CSS, and JavaScript in one file
```

All styles and scripts are embedded in the HTML, making the project easy to copy, share, and run.

## 🤝 Customization Ideas

Possible future additions include:

- Multiplication and division.
- Difficulty levels.
- Timed practice rounds.
- A downloadable answer key.
- Student name and date fields on the printed worksheet.
- Saving scores locally.
- Separate teacher and student modes.

These are ideas for future development and are **not included** in the current code.

---

<div align="center">

### Made for simple, accessible maths practice

**HTML · CSS · JavaScript**

[⬆ Back to top](#-sip-round--class-3-maths-practice)

</div>
