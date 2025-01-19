# testline

# NEET Testline Quiz Analysis

## Description
This Python-based project analyzes quiz performance data and provides personalized recommendations to help students improve their preparation. It processes current quiz data and historical quiz data to identify trends, highlight weak areas, and generate actionable suggestions for improvement.

---

## Features
1. **Current Quiz Analysis:**
   - Calculates overall accuracy.
   - Analyzes accuracy by topic.
   - Identifies weak topics based on performance.

2. **Historical Quiz Analysis:**
   - Tracks performance trends over time.
   - Calculates average scores and accuracy by topic.
   - Highlights weak topics with low historical scores.

3. **Recommendations:**
   - Generates a list of weak topics from both current and historical quizzes.
   - Suggests practice difficulty and additional questions to focus on.

4. **Student Persona:**
   - Classifies students based on performance as "Strategic Learner," "Accuracy-Focused," "Speed-Focused," or "Balanced Learner."

---

## Requirements
- Python 3.7+
- Required Libraries:
  - `requests`
  - `pandas`
  - `matplotlib`

Install the dependencies using pip:
```bash
pip install requests pandas matplotlib
```

---

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook assignment.ipynb
   ```

3. Run all cells in the notebook.

---

## Approach
1. **Data Fetching:**
   - Fetches data from three endpoints:
     - Current quiz data.
     - Quiz submission data.
     - Historical quiz data.

2. **Current Quiz Analysis:**
   - Analyzes the latest quiz for weak areas and accuracy trends.

3. **Historical Quiz Analysis:**
   - Tracks long-term performance trends and identifies weak topics.

4. **Recommendations:**
   - Combines insights from current and historical data to generate actionable recommendations.

5. **Visualizations:**
   - Displays bar plots for accuracy by topic and score trends over time.

---

## Outputs
- **Insights:**
  - Weak topics and improvement trends.
  - Performance gaps by topic.
- **Recommendations:**
  - Suggested topics to focus on.
  - Suggested difficulty levels and practice questions.
- **Visualizations:**
  - Accuracy by topic.
  - Score trends over time.

---

## Example Output
### Weak Topics:
```
Current Weak Topics:
['Topic 1', 'Topic 3']

Historical Weak Topics:
['Topic 4', 'Topic 5']
```
### Recommendations:
```json
{
  "current_weak_topics": ["Topic 1", "Topic 3"],
  "historical_weak_topics": ["Topic 4", "Topic 5"],
  "practice_difficulty": "medium",
  "suggested_questions": 10
}
```

---



