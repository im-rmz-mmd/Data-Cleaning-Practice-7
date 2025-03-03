📊 First Data Analysis Experience with SQLite and Seaborn

After learning new concepts for a while, I decided to take on a test project, and the result was an exciting data analysis on an SQLite database!

😎 But this time, there was a major difference:
✅ Instead of CSV files, I used SQLite for data storage.
✅ Along with Matplotlib, I leveraged Seaborn for better data visualization.

Let’s dive into the process! 🚀


🛠 Step 1: Data Loading and Cleaning

The first step was to connect to the SQLite database and clean up the data.

📌 Connecting to the Database and Reading Data
Using sqlite3 and pandas, I connected to the database and loaded the data.
This method is far more efficient than CSV files in terms of speed and data management.

📌 Removing Unnecessary and Incomplete Data

Dropped redundant columns (such as employee numbers and commission data).

Removed duplicate and missing records.

Clean data ensures more accurate analysis!


📌 Renaming Columns
To improve readability, I renamed some columns. For instance:

ENAME → Name

HIREDATE → Hire_Date


📊 Step 2: Data Analysis and Visualization

Once the data was cleaned, I extracted meaningful insights from it!

🔹 Average Salary by Job Title

One key question was: Which job titles have the highest salaries?

Grouped salaries by job title and calculated the average.

Used Seaborn’s barplot to visualize the results.


📌 Seaborn provides better aesthetics and color schemes than Matplotlib, making visualizations more engaging!

🔹 Salary Trends Based on Hire Date 📅

I wanted to analyze whether salaries changed over time.

Converted hire dates to DateTime format and sorted them chronologically.

Used a line plot to track salary changes over time.


🔹 Salary Distribution Across Job Titles 💰

To see salary variations within each job title, I used a box plot.

This visualization highlights minimum, maximum, and average salaries per job.

It also reveals if there's a significant salary gap within a specific job role.

---

This was my first hands-on experience with SQLite and Seaborn for data analysis.
Next, I plan to explore more advanced statistical techniques and improve my data storytelling skills.
