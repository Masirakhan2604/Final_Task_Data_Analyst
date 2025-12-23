# Final_Task_Data_Analyst

🏥 Healthcare Appointment No-Show Prediction
📌 Objective
Predict whether patients will miss their healthcare appointments and provide insights to optimize scheduling and reduce no-shows.

🛠 Tools & Technologies
Decision Tree Classifier
Power BI (for dashboard design)
GitHub
📊 Dataset
Appointment data containing:

Appointment Date & Time
Reason for Visit
Status (No-show, Scheduled, Cancelled)
🧹 Data Cleaning
Normalized column names
Created target variable no_show from status
Extracted weekday and hour features
Handled missing values
Cleaned files available in data/.

🤖 Model
Algorithm: Decision Tree Classifier
Features: weekday, hour, reason for visit
Output: predicted_no_show (1 = likely no-show)
📈 Dashboard
A Power BI–style dashboard showing:

KPIs: Total Appointments, Predicted No-Shows, No-Show Rate
No-Shows by Weekday
No-Shows by Reason for Visit
No-Shows by Hour
Actual vs Predicted Comparison
Dashboard file:
dashboard/No_Show_Dashboard.pptx

💡 Key Insights
Higher no-shows on Sundays, Wednesdays, and Saturdays
Therapy visits have the highest no-show risk
Midday hours (12–4 PM) show more missed appointments
🚀 Optimization Recommendations
Overbook high-risk days
Send reminders for Therapy appointments
Shift risky bookings to morning slots
Use predictions to manage waitlists

✅ Outcome
This project demonstrates how machine learning and dashboards can help healthcare providers reduce appointment no-shows and improve operational efficiency.
