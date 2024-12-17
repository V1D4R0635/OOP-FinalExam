# WorkoutScheduler

## Overview
**WorkoutScheduler** is a Java-based GUI application that helps users calculate their BMI (Body Mass Index) and provides customized workout suggestions based on their BMI category. The app also features a to-do list manager for workouts, task timers, a history tracker, and the ability to add, edit, finish, and restore workout tasks.

The application is built using Java Swing for its graphical user interface, making it simple and interactive.

---

## Features
1. **BMI Calculator**
   - Allows users to input their height (in cm) and weight (in kg) to calculate their BMI.
   - Displays the BMI value along with the corresponding BMI category (Underweight, Normal, Overweight, or Obese).
   - Provides workout suggestions based on the calculated BMI.

2. **Workout Suggestions**
   - Dynamically displays a list of workout suggestions based on the user's BMI category.
   - Users can select workouts from the suggestions to add to their workout to-do list.

3. **Workout To-Do List**
   - View, manage, and track selected workout tasks.
   - Add custom tasks with details like task name, description, category, sets, reps, and timer duration.
   - Edit or finish tasks and move them to the history list.

4. **Workout Timer**
   - Start a countdown timer for selected tasks based on their specified duration.
   - Alerts users when the workout timer completes.

5. **History Tracker**
   - Keeps a history of finished workout tasks.
   - Users can restore tasks from the history back to their to-do list.

---

## Prerequisites
To run this application, ensure you have:
- **Java Development Kit (JDK) 8 or above** installed.
- An IDE like IntelliJ IDEA, Eclipse, or NetBeans (optional but recommended).

---

## How to Run
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-repo/WorkoutScheduler.git
   ```

2. **Compile the Code**
   Navigate to the directory containing `WorkoutScheduler.java` and compile it:
   ```bash
   javac WorkoutScheduler.java
   ```

3. **Run the Program**
   Execute the compiled program using:
   ```bash
   java WorkoutScheduler
   ```

4. **Using the Application**
   - Input your height and weight to calculate BMI.
   - Select suggested workouts or add your custom workout tasks.
   - Manage tasks in the to-do list, view timers, and restore tasks from history.

---

## Application Walkthrough

1. **BMI Calculation**
   - On launch, the app opens the BMI Calculator screen.
   - Enter your height (in cm) and weight (in kg), then click **"Calculate BMI"**.
   - The app displays your BMI value and category, and prompts you to view workout suggestions.

2. **Workout Suggestions**
   - Based on your BMI category, workouts such as **Strength Training**, **Cardio**, or **HIIT** are suggested.
   - Select one or more workouts and click **"Add Selected Workouts"**.

3. **Main Task Manager**
   - Tasks appear under the **"To-do Workouts"** section.
   - Options available:
     - **Add Task**: Add a custom workout with task details.
     - **Edit Task**: Modify a selected task.
     - **Finish Task**: Mark a task as complete and move it to history.
     - **View Task**: View task details and optionally start a timer.

4. **Workout Timer**
   - Selecting "View Task" allows users to start a timer for the task duration.
   - A countdown displays the remaining time, and an alert is shown when the timer completes.

5. **Task History**
   - Completed tasks appear in the **History** panel.
   - Use the **"Restore Selected"** button to move tasks back to the to-do list.

---

## Code Structure
- **`WorkoutScheduler`**: Main class containing all the components and logic.
  - **BMI Calculator**: Handles BMI calculation and displays categories.
  - **Workout Suggestions**: Dynamically generates workouts based on BMI.
  - **Task Manager**: Manages to-do tasks, history, and workout timers.
  - **Timers**: Implements a countdown timer for workout tasks using `javax.swing.Timer`.

---

## Technologies Used
- **Java Swing**: For building the graphical user interface (GUI).
- **AWT**: For layout management and event handling.
- **JOptionPane**: For dialogs and user prompts.

---

## Future Improvements
- Integration with a database to persist user data and workout history.
- Adding graphical progress charts for BMI trends and completed workouts.
- Allowing user-defined workout plans and customization.

---


