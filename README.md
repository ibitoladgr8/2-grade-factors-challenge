# Grade Factors? - Mini Data Challenge #2

Brought to you by the Data Community UNILAG

## Challenge Overview

Analyze the students' performance dataset to identify factors that influence their grades. You will explore various attributes to determine their impact on students' grades.

### Tasks

#### Part 1: ML Model

- Build a machine learning model to predict students' average scores based on the available features. (neural networks are not allowed 😅)

- At the end of your submission, write a function named `predict_scores` that takes in new student data and returns their predicted scores. (Jupyter notebooks are also accepted).

#### Part 2: Analysis

From your analysis, answer the following questions:

- How does each feature correlate with the students' average scores?
- What are the most important factors that influence students' grades?

## Submission Guidelines

### Timeline

- **Challenge Release:** Friday, 20th December, 2024
- **Submission Deadline:** Tuesday, 24th December, 2024 (11:59 PM)
- **Winner Announcement:** Someday between January 2nd and January 5th depending on the number of submissions.

### Evaluation Criteria

Your submission will be evaluated based on:

- **Accuracy:** Evaluation of your model's predictions (50%).
- **Analysis:** Depth of analysis and insights (30%).
- **Clarity:** Clear presentation of findings and visualizations (20%).

For accuracy, aim for less than the baseline which is a root mean squared error (RMSE) of around 22.2. This is gotten from a model that predicts 50 for all students.

### Get Started

1. **Fork this repository.**
2. **Clone the repository** to your local machine.
3. _(optional)_ Create a virtual environment and install the required packages using `pip install -r requirements.txt`.
4. Complete the challenge and include:
   - Your code (only Python will be accepted, that is, either `submission.ipynb` or `submission.py`).
   - A summary of your findings (`summary.md`).
   - (Optional) Any visualizations (e.g., `.png`, `.pdf`) in the `visualizations` folder.
   - (Optional) `requirements.txt`
5. **Submit your work** by creating a branch named `submission-[your-name]` and opening a pull request.

## Dataset Details

<details>
<summary>Click to expand</summary>

Find all relevant datasets in the `/data` folder

- **Name:** Students Performance in Exams
- **Source:** [Kaggle](https://www.kaggle.com/spscientist/students-performance-in-exams)
- **Columns:**
  - `gender`: Male or female
  - `race/ethnicity`: grouped into A, B, C, D, E
  - `parental level of education`: High school, some college, associate's degree, bachelor's degree, master's degree
  - `lunch`: Indicates whether the student's lunch is standard or free/reduced in terms of cost
  - `test preparation course`: Indicates whether the student completed a test preparation course (None or completed)
  - `average_score`: The average of the student's math, reading, and writing scores.

These are the individual scores from the original dataset which were combined to create the `average_score` column:

- `math score`: The student's math score (0-100)
- `reading score`: The student's reading score (0-100)
- `writing score`: The student's writing score (0-100)
</details>

## Prizes and Recognition

- 🌟 The top submission will be featured on our [Twitter page](https://twitter.com/DataComUnilag) and the community Whatsapp group.
- 🏆 Leaderboard points will be awarded to all participants based on performance.

## Questions or Feedback?

For any inquiries, open an issue on this repo (not on your fork) or reach out to us on the community Whatsapp group.

Happy analyzing! 🚀
