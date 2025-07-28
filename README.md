📘 SchedWiz – Your AI-Powered Study Wizard

SchedWiz is an AI-powered study scheduler that personalizes, adapts, and optimizes study plans to boost student productivity and academic performance. It reduces decision fatigue by transforming raw performance data into structured, intelligent learning schedules.
________________________________________________________________________________________________________________________________________________________________________________________
Overview :

Many students struggle with inconsistent study habits, rigid routines, and difficulty prioritizing tasks. Traditional schedules rarely adapt to changing needs or performance. SchedWiz solves this by using machine learning and user inputs (exam dates, difficulty levels, scores) to generate dynamic, personalized study plans—instantly.

Students enter key academic details via a user-friendly Streamlit interface, and the AI responds with a customized plan that prioritizes weaker areas, upcoming exams, and user-defined preferences.
<img width="1470" height="956" alt="Screenshot 2025-07-18 at 4 39 26 PM" src="https://github.com/user-attachments/assets/b385b58e-7225-4217-99b1-ff24e188aae2" />

________________________________________________________________________________________________________________________________________________________________________________________
Methodology : 

SchedWiz uses a combination of machine learning, PySpark processing, and interactive UI design to deliver adaptive study plans. The system:

- Ingests student data including past scores, exam dates, and subject difficulty via a Streamlit web interface.
- Performs EDA using Pandas and Seaborn to derive summary statistics and handle missing values.
- Predicts performance using a Multi-Layer Perceptron (MLP) trained on student datasets via PySpark, PyTorch, and TensorFlow, optimized for class imbalance.
- Implements an event-driven pipeline with multithreading, memory-safe task orchestration, and cache-aware scheduling logic to build efficient study timelines.
- Applies causal inference methods (Propensity Score Matching and Difference-in-Differences) to evaluate the impact of early engagement on outcomes.
<img width="1470" height="956" alt="Screenshot 2025-07-18 at 4 39 39 PM" src="https://github.com/user-attachments/assets/d9920a07-e76e-4ce5-aa5b-7c7219ba4053" />

________________________________________________________________________________________________________________________________________________________________________________________
Results :

- Achieved 73.3% test accuracy in academic performance prediction using the MLP model.
- Delivered personalized study plans to 32,000+ students, dynamically adjusting based on inputs.
- Observed a 12.6% causal lift in academic performance for students with high early engagement.
- Improved scheduler responsiveness with optimized multithreading and real-time schedule reshuffling.
- Interface designed with Streamlit to ensure easy access and real-time plan generation

<img width="1470" height="956" alt="Screenshot 2025-07-18 at 4 39 53 PM" src="https://github.com/user-attachments/assets/192a2755-e726-43a2-8600-4eac0849b8a9" />
