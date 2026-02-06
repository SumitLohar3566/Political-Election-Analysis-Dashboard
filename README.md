### Political Election Analysis Dashboard

A complete and interactive Power BI dashboard designed to analyze political election data, including party-wise results, seat share, turnout percentage, constituency-level insights, winning margins, and vote share analytics.

# Project Preview:
<img width="1323" height="736" alt="Screenshot 2025-11-30 203507" src="https://github.com/user-attachments/assets/86ea064c-340f-4a3e-9e83-b98f2d456135" />
<img width="1327" height="748" alt="Screenshot 2025-11-30 203524" src="https://github.com/user-attachments/assets/b8a07425-8bd1-4589-8281-176a4ee45427" />

# Project Overview

- This dashboard provides a deep analytical overview of election trends and performance.

# It helps understand:

- Which party is leading?

- Winning margins per constituency

- Vote share distribution

- Seats gained/lost

- Year-wise comparison

- Voter turnout analysis

- The dashboard is ideal for data visualization, political research, and election insights.

# Dataset Information:

The dataset used in the dashboard includes:

- Constituency Name

- Leading Candidate

- Leading Party

- Winning Margin

- Year

- Total Votes

- Turnout %

- Party-wise seat distribution

# Key Features:
1. Party-wise Seat Share

Beautifully designed donut chart showing seats won by each political party.

2. Constituency-level Details

# Table showing:

- Leading candidate

- Party

- Winning margin

- Constituency comparison

 3. Winning Votes by Leading Party

- Line chart showing winning margins across different constituencies.

 4. Year-wise Filtering

- A dynamic filter allowing comparison of different election years:

- 2009

- 2014

- 2019

- 2024 

5. Constituency Count by Year & Leading Party

- Bar chart describing which party dominated across various years.

6. KPI Cards

- Total Seats

- Total Votes

- Turnout %

- Winning Votes

# Tools & Technologies Used:

- Power BI Desktop	Dashboard & Data Visualization
- Excel / CSV Files	Data Source Processing
- DAX	Calculated Columns & Measures
- Power Query	Data Cleaning & Shaping

# Important DAX Measures Used (Example):
- Total Seats = COUNTROWS(Seats)

Turnout Percentage = 
DIVIDE( SUM(Votes[Total Voters Attended]), SUM(Votes[Total Registered Voters]) ) * 100

Winning Margin = SUM(Constituency[Margin])

# How to Use:

- Download the .pbix file

- Open in Power BI Desktop

- Explore dashboard features

- Use slicers for:year, party, or candidate

# Future Enhancements:

- Interactive maps

- Prediction of winning chances using ML

- Sentiment analysis based on public comments

- License

This project is open-source. You may use it for learning or portfolio purposes.

- Contact Developer: Sumit Lohar
- Email:sumitlohar063@gmail.com
- GitHub: https://github.com/SumitLohar3566
- LinkedIn:(https://www.linkedin.com/in/sumit-lohar-498341317/)

