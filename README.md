# SWYNEX AI Student Doubt Classifier

## SWYNEX Technologies - Artificial Intelligence Internship

### Task 1: AI Problem Design

This project is part of my Artificial Intelligence Internship at SWYNEX Technologies.

## 1. Project Overview

The AI Student Doubt Classifier is a proposed AI system that automatically identifies the category of a student's question.

Students may have questions related to programming, data structures, databases, mathematics, or artificial intelligence. Manually organizing a large number of questions can take time.

The proposed system uses AI-based text classification to automatically categorize these questions.

## 2. Problem Statement

Students ask questions from different technical and academic subjects.

The problem is:

> How can we automatically classify a student's question into the correct subject category?

An AI-based classification system can help organize these questions automatically.

## 3. Proposed AI Solution

The system receives a student's question as text and predicts the most appropriate category.

### Example 1

**Input:**

"What is a binary search tree?"

**Predicted Category:**

Data Structures

### Example 2

**Input:**

"What is supervised learning in machine learning?"

**Predicted Category:**

AI/ML

### Example 3

**Input:**

"What is a primary key in SQL?"

**Predicted Category:**

Database

## 4. AI Use Case

This project is a **text classification** problem.

The AI system analyzes the text of a student's question and assigns it to one of the predefined categories.

## 5. Categories

The initial system will use these categories:

1. Programming
2. Data Structures
3. Database
4. Mathematics
5. AI/ML
6. Other

## 6. Target Users

The main users of this system are:

- College students
- Teachers
- Academic support teams
- Online learning platforms

## 7. Data Source

A small dataset of example student questions will be created for the initial prototype.

Each record will contain:

- Question text
- Correct category

### Sample Dataset

| Question | Category |
|---|---|
| What is a Python list? | Programming |
| What is a binary tree? | Data Structures |
| What is SQL? | Database |
| What is a derivative? | Mathematics |
| What is supervised learning? | AI/ML |
| How do I install an application? | Other |

## 8. Input

The system will accept a student's question as text.

Example:

```text
What is a primary key in SQL?
