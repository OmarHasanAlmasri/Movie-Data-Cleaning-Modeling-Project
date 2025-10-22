🎬 Movie Data Cleaning & Modeling Project

Overview
This project focuses on cleaning and modeling a movie dataset to prepare it for analysis and visualization. The data was transformed and standardized using Power Query Editor in Power BI.

📁 Dataset Description  
- Movies dataset including details about movies, actors, languages, and financials.  
- Total records cleaned and prepared for analysis.  

🧹 Data Cleaning & Preparation  

Steps Taken:  
- Imported data as separate tables for easier management and relationship creation.  
- Enabled Power Query profiling features:  
  - Column Profile  
  - Column Quality  
  - Column Distribution  
  - Monospace View  
  - Show Whitespace  
- Separated movie-id from movie-title.  
- Renamed columns for clarity.  
- Applied appropriate data types (text, decimal-number, General..).  
- Used Trim and Clean functions to remove extra spaces and non-printable characters.  
- Removed duplicate records.  
- Handled missing or invalid IMDb ratings by calculating average or replacing with null.  
- Removed rows with null values in studio column.  
- Standardized financial columns (revenue, budget) into Millions (USD) using a Custom Column.  
- Added a performance indicator column (revenue vs. budget).  
- In movie_actor table, created a new sequential ID column.  
- Removed unnecessary columns (currency, unit, budget, revenue) from the Financial table after transformation.  

⚙️ Excel Functions & Tools Used  
- Power Query Editor (Power BI): Data cleaning, transformation, profiling  
- Excel Functions: Trim, Clean, Custom Columns, Conditional Columns  
- GitHub: Version control and project documentation  
- Draw.io: For creating the ER Diagram (.drawio file included) (https://app.diagrams.net/#G1Gd0KhILalGlAt2u8WxrdZFeWPcE2LF1a#%7B%22pageId%22%3A%22IqgdGY4Sww-5nYbZuyX6%22%7D)

🧩 Data Model (ER Diagram)  

Entities:  
- Movies  
- Actors  
- Languages  
- Financials  
- Movie_Actor (Bridge Table)  

Relationships:  
- Movie ↔ Language → Many-to-One  
- Movie ↔ Actor (via Movie_Actor) → Many-to-Many  
- Movie ↔ Financial → One-to-One  

Note: The ER Diagram was created using Draw.io, and the (Movies_Data_raw) file is included for reference or editing.  

🚀 Key Learnings  
- Importance of data cleaning and standardization before analysis.  
- Building a structured data model (ERD) to understand relationships between entities.  
- Preparing datasets for future visualization and insights in Power BI.  

👨‍💻 Created by  
Omar Hasan  
October 2025  
LinkedIn Profile(https://www.linkedin.com/in/omar-almasri375/)
