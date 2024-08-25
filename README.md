# MGH-Executive-Dashboard

![MGH Dashboard](https://github.com/user-attachments/assets/a159fef0-77df-4a26-8ab8-a7b1a9e51b78)


This project was created as a part of the Maven Analytics Hospital Challenge, which included data on over 1,000 patients from Massachusetts General Hospital spanning 2011-2022.
The challenge was to create a dashboard for the hospital’s executives, designed to answer specific questions and provide additional insights from the data. Since this dashboard was intended for executives, I focused on making it simple, direct, and focused on delivering key findings clearly.

### Approach:

- **Defining Key Questions**: I started by identifying both fundamental and additional questions that were essential for the analysis.
- **Calculating Metrics**: Using DAX & Power Query, I calculated key measures, created necessary columns, and built tables to answer these questions.
- **Establishing Relationships**: I carefully set up relationships between tables to ensure accurate data representation.
- **Dashboard Design**: I sketched the dashboard layout on paper first, which helped me visualize the final design.
- **Creating the Dashboard**: I used Line & Bar charts, Donut charts, Cards, and Tables to build the dashboard.

### Challenges:

- **Handling Outliers**: I encountered patients with unusually high ages, which, upon inspection, were linked to death dates. I decided to filter these out to maintain the integrity of the analysis.
- **DAX Calculations**: Calculating metrics like average visit length, age, and re-admittance rates was challenging due to the complexity of DAX expressions. As I learned by doing, debugging required extensive research and documentation.
- **Table Relationships**: Establishing accurate relationships between tables was crucial, as any misalignment caused issues with filtering or aggregating data.

### Tools Used:

- **DAX & Power Query**: For Data Cleaning & Manipulation
- **Power BI**: For Data Visualization

### Key Questions Answered:
* How many patients were admitted vs. re-admitted?
* What's the average staying period for patients?
* How much is the average cost per visit?
* What's the total insurance coverage?
* What's the gender & age group distribution per encounters?
* What's the total revenue per year?
