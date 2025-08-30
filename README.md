# ✈️ Flight Data Analysis

This project analyzes airline flight prices and trends using Python.  
It uses **Pandas, Matplotlib, and Seaborn** to answer important questions about airline pricing and provide visual insights.

---

##  Dataset
The dataset includes:
- **airline** – Airline name  
- **source_city** – City of departure  
- **destination_city** – Destination city  
- **class** – Economy or Business  
- **departure_time** – Departure time slot (Morning, Evening, etc.)  
- **arrival_time** – Arrival time slot  
- **days_left** – Days before departure when the ticket is booked  
- **price** – Ticket price  
- **stops** – Non-stop or number of stops  
- **duration** – Total flight duration  

---

##  Questions Answered in this Notebook
- Q1: Looking up flights based on user-entered Source, Destination, and Class  
- Q2: What are the airlines in the dataset (with their frequency)?  
- Q3: Are non-stop flights significantly more expensive than flights with 1+ stops?
- Q4: Does price vary with airlines?  
- Q6: How is the price affected when tickets are bought 1 or 2 days before departure?  
- Q7: How does the ticket price vary between Economy and Business class?  

---

## 📷 Visualizations
The notebook includes several charts created using **Matplotlib** and **Seaborn**:
- Airline frequency (horizontal bar chart)  
- Price variation by airlines (bar plot)  
- Non-stop vs stops price comparison across airlines (bar plot)  
- Economy vs Business class price comparison (bar plot with airline hue)  
- Price variation by days left before departure (point plot)  
- Average price by departure time and class (point plot)
---
