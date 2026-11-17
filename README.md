# Hi, I'm Manny
**CS @ Northeastern University (Khoury) · Class of 2028 · 3.89 GPA**

I build things people can actually use, from full-stack web apps to machine learning projects. Right now I'm focused on **applied ML and backend engineering**, and I'm looking for a **January–June 2027 co-op**.

- Currently: Machine Learning and Human-Computer Interaction at Northeastern
- I like the math behind ML: linear algebra, probability, and stats
- Outside of code: bodybuilding, rock climbing, hiking, cooking (which is why my biggest project is a fitness tracker)
- Reach me: [LinkedIn](https://www.linkedin.com/in/emmanuel-canizales) · canizales.e@northeastern.edu

---

## Featured projects

### [Fitness Tracker](https://github.com/EC1819/Fitness-Tracker) · [Live demo](https://fitness-tracker-bvkm.onrender.com)
A full-stack, mobile-first app for logging workouts and body measurements. It calculates body fat % (U.S. Navy method) and FFMI.
- React frontend → Spring Boot REST API (9 endpoints) → PostgreSQL
- 4-table relational schema with Flyway migrations and CHECK constraints
- JUnit and Mockito tests, including a regression test for a bug from my original terminal version
- Deployed with Docker on Render, with the database on Neon

`React` `Java` `Spring Boot` `PostgreSQL` `Docker`

### [Radio Signal Classifier](https://github.com/EC1819/radio-signal-classifier)
Classifies 11 radio modulation types from 220,000 raw I/Q signals (DeepSig RadioML 2016.10A).
- Engineered 12 amplitude, phase, and frequency features from the raw samples
- Compared 5 models with stratified 5-fold cross-validation; the random forest hit **50% test accuracy (5.5× baseline)** and **~83% on high-SNR signals**
- Wrote logistic regression with gradient descent from scratch in NumPy; it matches scikit-learn on 99.8% of predictions
- Serves predictions through a FastAPI endpoint with input validation and pytest tests

`Python` `scikit-learn` `NumPy` `FastAPI` `pytest`

### [Tic-Tac-Toe with an unbeatable AI](https://github.com/EC1819/Web-Version-of-Tic-Tac-Toe)
A browser game where the computer opponent uses the minimax algorithm, so it never loses.

`JavaScript` `HTML` `CSS`

### [Ultimate Tic-Tac-Toe](https://github.com/EC1819/Ultimate-Tic-Tac-Toe)
A 9-board version of tic-tac-toe I built for my brother without AI tools. Refactoring cut it from about 1,000 lines to about 300.

`Java`

---

## Tech Stack

**Languages:** Java · Python · JavaScript · SQL · C · HTML/CSS

**Frameworks & libraries:** Spring Boot · React · scikit-learn · FastAPI · pandas · NumPy · Matplotlib

**Tools:** Git · Docker · PostgreSQL · Flyway · JUnit · Mockito · pytest · IntelliJ IDEA · PyCharm · Linux
