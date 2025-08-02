"""
  Task: Hundred Student Records - Filtering with Loops and Conditionals
  
 Scenario:
 The Federal University of Jos wants to analyze the performance of its students 
 after conducting a nationwide online assessment. 
 They have exactly 100 student records in the system.
 
 Each student record includes:
 - student_id (integer)
 - name (string)
 - score (0 - 100)
 
 A sample of the dataset looks like this:
 
 students = [
     {"id": 1, "name": "Alice", "score": 78},
     {"id": 2, "name": "Bob", "score": 45},
     {"id": 3, "name": "Charlie", "score": 92},
     ...
 ]
 
 The academic board wants to classify the students into 3 separate groups 
 based on their scores:
 
 1. High Performers: score >= 70
 2. Average Performers: 50 <= score < 70
 3. Low Performers: score < 50
 
 Requirements:
 1. Use a loop to iterate through all student records.
 2. Use conditionals to filter and classify students into 3 separate groups.
 3. Each group should be identified by its name (Group Name).
 4. Each group should use `student_id` as the key and a tuple `(name, score)` as the value.
 5. Print the number of students in each category as a summary report.
 6. print each category(3)
 
 Example Output:
 High Performers: 300,245
 Average Performers: 400,512
 Low Performers: 299,243
 
 
 e.g. 
 All High Performers: [{1: ("student1", 100)}, {32: ("student32", 90)}, ..... continously]
 All Average Performers: [{1: ("student1", 100)}, {32: ("student32", 90)}, ..... continously]
 All Low Performers: [{1: ("student1", 100)}, {32: ("student32", 90)}, ..... continously]
 """
 

