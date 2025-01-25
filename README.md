# Genetic Algorithm for University Exam Schedule Generation
This project demonstrates the use of a Genetic Algorithm (GA) to efficiently generate university exam schedules. 
The algorithm is designed to handle constraints such as avoiding exam overlaps for students, distributing exams evenly, and optimizing the scheduling process for practical use.

## Features
Constraint Satisfaction: Ensures no two exams for the same student are scheduled at the same time.
Optimization: Distributes exams efficiently across available time slots and venues.
Flexibility: Adapts to different numbers of students, courses, and time constraints.
Visualization: Provides insights into the scheduling process and results.

## Prerequisites
##### Python 3.x
##### Jupyter Notebook

### Required Python libraries:
##### numpy
##### pandas
##### matplotlib

### Clone the repository:
git clone [https://github.com/yourusername/GENETIC-ALGORITHM-FOR-UNIVERSITY-EXAM-SCHEDULE-GENERATION.git](https://github.com/AbdullahButt-00/GENETIC-ALGORITHM-FOR-UNIVERSITY-EXAM-SCHEDULE-GENERATION.git)
##### jupyter notebook main.ipynb

### How It Works
#### The Genetic Algorithm operates as follows:
Initialization: Creates a population of random schedules.
Fitness Function: Evaluates each schedule based on constraints like avoiding conflicts and optimizing time slot usage.
Selection: Selects the best-performing schedules.
Crossover and Mutation: Combines and mutates schedules to produce a new generation.
Iteration: Repeats the process until an optimal or near-optimal schedule is generated.

### Usage
Open main.ipynb in Jupyter Notebook.
Adjust parameters such as the population size, number of generations, and constraints as needed.
Run the notebook to generate a schedule.

### Acknowledgments
Inspiration for this project came from real-world challenges in university exam scheduling.
Special thanks to the developers and researchers behind Genetic Algorithms.
