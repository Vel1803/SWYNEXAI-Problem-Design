# SWYNEX Internship - Task 1
## AI Problem Design

### 1. Project Title

AI Student Doubt Classifier

### 2. Problem Statement

Students ask questions from different subjects such as Programming, Data Structures, Database, Mathematics, and Artificial Intelligence.

When there are many student questions, manually sorting them into different categories takes time.

The proposed AI system will automatically classify a student's question into the appropriate subject category.

### 3. Target Users

The main users of this system are:

- College students
- Teachers
- Online learning platforms
- Academic support teams

### 4. AI Use Case

This project is an AI-based text classification problem.

The system receives a student's question as text and predicts the category of the question.

### 5. Example

Input:

"How does a binary search tree work?"

Expected output:

"Data Structures"

Another example:

"What is supervised learning in machine learning?"

Expected output:

"AI/ML"

### 6. Categories

The system will classify questions into the following categories:

1. Programming
2. Data Structures
3. Database
4. Mathematics
5. AI/ML
6. Other

### 7. Data Source

A small dataset of example student questions will be created for this project.

Each question will contain:

- Question text
- Correct category

Example:

| Question | Category |
|---|---|
| What is a Python list? | Programming |
| What is a binary tree? | Data Structures |
| What is SQL? | Database |
| What is a derivative? | Mathematics |
| What is supervised learning? | AI/ML |

### 8. Input

The system will accept a student's question as text.

Example:

"What is a primary key in SQL?"

### 9. Output

The system will return the predicted category.

Example:

"Database"

### 10. Constraints

The initial version of the system will have the following limitations:

- The dataset will be small.
- Questions must mainly be related to the predefined categories.
- Very unclear questions may be classified as "Other".
- The system may make mistakes when a question belongs to multiple subjects.
- The initial prototype will focus on English questions.

### 11. Success Criteria

The main success criterion will be classification accuracy.

The initial target is:

**At least 80% accuracy on a test dataset.**

For example, if the system correctly classifies 80 out of 100 test questions, its accuracy is 80%.

### 12. Evaluation Approach

The dataset will be divided into training and testing data.

The model will be tested using questions that it has not seen during training.

Accuracy will be calculated using:

**Accuracy = Correct Predictions / Total Predictions × 100**

Example:

Correct predictions = 85

Total predictions = 100

Accuracy = 85%

### 13. Expected Result

The expected result is an AI system that can automatically identify the subject category of a student's question.

This can reduce manual sorting and help organize student questions more efficiently.

### 14. Future Improvements

Future versions could include:

- More categories
- Support for multiple languages
- Better handling of unclear questions
- Confidence scores
- Automatic answers to questions
- Integration with a student chatbot

### 15. Conclusion

The AI Student Doubt Classifier is a beginner-friendly AI problem that demonstrates text classification.

The project defines a practical problem, identifies the users and data requirements, establishes constraints, and provides measurable success criteria for evaluating the AI system.
