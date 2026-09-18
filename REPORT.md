# ENSE 375 – Software Testing and Validation

## Budget Expense Tracker

**Team Members**

| Name | UofR ID |
| --- | --- |
| Thomas Persson | 200525550 |
| Aldan Henry | 200533636 |
| Wei Wen Darren Liow | 200569702 |

---

## Table of Contents

1. [Introduction](#1-introduction)
2. [Design Problem](#2-design-problem)
   - [2.1 Problem Definition](#21-problem-definition)
   - [2.2 Design Requirements](#22-design-requirements)
3. [Solution](#3-solution)
4. [Team Work](#4-team-work)
5. [Project Management](#5-project-management)
6. [Conclusion and Future Work](#6-conclusion-and-future-work)
7. [References](#7-references)
8. [Appendix](#8-appendix)

---

## 1 Introduction

Managing money is a skill that many students are forced to learn very quickly. Starting university is often the first time a person becomes responsible for their own rent, groceries, transportation and tuition, and this usually happens while living on a fixed amount of money drawn from student loans, savings and a job held during the term. Because that money arrives in a few large deposits but leaves in many small amounts, it is difficult to judge how much is actually left for a given kind of spending until the money is already gone.

The traditional answer to this problem is a budget, which divides the available money into categories, gives each category a spending limit, and records expenses against those limits. Budgeting on paper or in a spreadsheet does work, but it depends entirely on the discipline of the user and it gives no warning as a limit is approached. Commercial budgeting applications automate the arithmetic instead, yet many of them require an account, display advertisements, charge a subscription fee, or store personal financial data on servers that the user does not control.

This project therefore proposes a Budget Expense Tracker, which is a small application that allows a user to create spending categories with limits, record expenses against those categories, see the remaining funds at any time, and receive a warning as a limit is approached or passed. The application is developed with a method that writes the tests before the code, and it is organised using the Model View Controller architecture so that the logic can be tested apart from the interface. Its correctness is then established through a test suite that covers path, data flow, integration, boundary value, equivalence class, decision table, state transition and use case testing.

The remainder of this report is organised as follows. Section 2 defines the design problem, and it includes both the problem statement and the functions, objectives and constraints of the design. Section 3 then presents the solutions that the team considered, along with the final design that was chosen. After that, Section 4 documents the meetings of the team and the distribution of tasks, while Section 5 describes the schedule of the project. Finally, Section 6 concludes the report and outlines the work that could follow it.

---

## 2 Design Problem

### 2.1 Problem Definition

Students entering university typically manage their own money for the first time, and they must make a limited and largely fixed amount cover several separate kinds of spending, such as rent, groceries, transportation, tuition and personal expenses. Spending happens in many small transactions spread across a term, whereas income arrives in a small number of large deposits. As a result, a student can still have money in their account while having already overspent in one category that has to last until the next deposit arrives. Overspending in one category quietly takes money away from another, and the consequence is usually discovered at the end of the month, which is far too late to change the behaviour that caused it.

The tools that students have today do not solve this problem well. Recording expenses on paper or in a spreadsheet forces the user to build and maintain the categories and the arithmetic without help, and it gives no feedback at all until the user sits down and works the numbers out, so the habit is easily abandoned. Commercial budgeting applications do automate the tracking, yet they introduce costs of a different kind, because they commonly ask the user to create an account, connect a bank account, accept advertisements, or pay a subscription, and they place personal financial data on servers outside the control of the user. In addition, these applications are built for a general audience, so they carry far more features than a student with a handful of categories actually needs.

**Problem statement.**
No simple tool exists that is free to use, keeps financial data private, and allows a student to set spending limits for a small number of budget categories, record expenses against those categories with very little effort, see at any time how much money remains in each one, and receive a warning before a limit is passed rather than afterwards.

The design problem addressed by this project is therefore to design, build and thoroughly test a small desktop application that holds a set of budget categories and their spending limits, records expenses against those categories, keeps the remaining balance of each category up to date as expenses are added, and warns the user when a category is near its limit or beyond it. Because the purpose of the tool is to be trusted with financial decisions, the correctness of the balance and warning logic is not optional. The application must behave correctly for valid input, it must reject invalid input safely, and it must produce the right warning for every combination of conditions. Establishing that correctness through a systematically designed test suite is the main objective of this project, and for that reason the design is judged on how easily its parts can be isolated, controlled and observed by tests, just as much as on the features it offers.

The scope of the problem is deliberately limited so that the work fits within a design and development period of roughly two months. Consequently, the application serves one user, it stores its data on the local machine, and it does not connect to a bank, import transactions automatically, handle more than one currency, or offer forecasting or investment features.

### 2.2 Design Requirements

*To be completed for the September 24 deliverable.*

#### 2.2.1 Functions

*Functions are stated with verbs, because they describe what the design does.*

#### 2.2.2 Objectives

*Objectives are stated with adjectives, because they describe how well the design does it.*

#### 2.2.3 Constraints

*Constraints are binary, so each one is either satisfied or not. At least four are required, drawn from economic factors, regulatory compliance covering security and access, reliability, sustainability and environmental factors, ethics, and societal impacts.*

---

## 3 Solution

### 3.1 Solution 1

*To be completed for the October 8 deliverable.*

### 3.2 Solution 2

*To be completed for the October 8 deliverable.*

### 3.3 Final Solution

*To be completed for the December 3 deliverable.*

#### 3.3.1 Components

#### 3.3.2 Environmental, Societal, Safety, and Economic Considerations

#### 3.3.3 Test Cases and Results

#### 3.3.4 Limitations

---

## 4 Team Work

### 4.1 Meeting 1

| | |
| --- | --- |
| **Time** | *Month Date, 2026, from hh.mm am to hh.mm am* |
| **Agenda** | Project selection and distribution of the first tasks |

| Team Member | Previous Task | Completion State | Next Task |
| --- | --- | --- | --- |
| *Team member 1* | N/A | N/A | *Task* |
| *Team member 2* | N/A | N/A | *Task* |
| *Team member 3* | N/A | N/A | *Task* |

### 4.2 Meeting 2

*To be completed.*

### 4.3 Meeting 3

*To be completed.*

### 4.4 Meeting 4

*To be completed.*

---

## 5 Project Management

*A Gantt chart will be added here as the schedule develops, and it will show all tasks together with their predecessors, the slack time of each task, and the critical path.*

| Deliverable | Due Date | Status |
| --- | --- | --- |
| Problem Definition, Section 2.1 | Sept 17, 2026 | |
| Design Constraints and Requirements, Section 2.2 | Sept 24, 2026 | |
| Iterative Engineering Design Process, Sections 3.1 and 3.2 | Oct 8, 2026 | |
| Final Design, Implementation and Testing, Section 3.3 | Dec 3, 2026 | |
| Final Submission | Dec 7, 2026 | |

---

## 6 Conclusion and Future Work

*To be completed.*

---

## 7 References

*The IEEE reference style is used, and only the references cited in the text are listed.*

---

## 8 Appendix

*Additional information, if any is needed.*

