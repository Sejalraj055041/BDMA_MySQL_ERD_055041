# Fitness Tracking App Database

## About This Project
Managing fitness data efficiently can be challenging. This project simplifies it with a **Fitness Tracking App Database**, built using SQL. It includes well-structured tables for handling users, workouts, progress tracking, nutrition logs, instructors, and activity logs, ensuring seamless fitness management.

## Database Structure
### Database Name: **fitness_tracking_app**

### Tables & What They Do

1. **Person**  
   Stores general details about individuals, including name, age, gender, and contact information.

2. **User**  
   Contains specific user details such as fitness goals, membership status, and linked person ID.

3. **ProgressLog**  
   Maintains user progress records, tracking weight, body measurements, and fitness metrics over time.

4. **ActivityTracking**  
   Logs user activities, including type of activity, duration, calories burned, and timestamps.

5. **Workout**  
   Stores details of workout sessions, including workout type, duration, and intensity level.

6. **Workout_Exercise**  
   Links workouts to exercises, managing sets, reps, and workout specifics.

7. **Exercise**  
   Contains details about exercises, including muscle group targeted, difficulty level, and required equipment.

8. **Course**  
   Stores information about fitness courses, including title, description, and difficulty level.

9. **User_Course**  
   Manages the many-to-many relationship between users and courses.

10. **NutritionLog**  
    Tracks dietary intake, including meal type, calories, and macronutrients.

11. **User_Follows_Instructor**  
    Stores user-instructor follow relationships.

12. **Instructor**  
    Stores instructor details, including specialization and certifications.

## How to Use
1. **Set up the database:**  
   ```sql
   CREATE DATABASE fitness_tracking_app;
   USE fitness_tracking_app;
   ```
2. **Create the tables by running the provided SQL script.**
3. **Insert sample data to start testing.**
4. **Run queries to fetch and manipulate fitness data.**

## Installation Requirements
- Install **MySQL Server** (or a compatible database system).
- Use a SQL client like **MySQL Workbench, DBeaver, or phpMyAdmin**.
- Load the provided SQL schema to set up the database.

## Authors
**Sejal Raj (055041)**  
**Vidushi Rawat (055056)**

