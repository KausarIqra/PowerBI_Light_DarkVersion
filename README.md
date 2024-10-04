Power BI Project: Customer Performance Dashboard with Theme Toggle

Overview

This Power BI project showcases a Customer Performance Dashboard that provides insights into key metrics such as customer demographics, 
revenue segmentation, and gender-based earnings. The dashboard features an interactive Theme Toggle allowing users to switch between a Light Theme and a Dark Theme for a personalized viewing experience.

Features

Customer Insights:
Displays average customer age and total customer count.
Segments customers with and without children across various regions.
Highlights revenue segmented by different age brackets.
Earnings comparison based on gender.
Theme Toggle (Light/Dark Mode):
The dashboard allows users to switch between Light and Dark themes through an interactive toggle button.
The color schemes of the dashboard automatically change based on the selected theme for a more comfortable user experience.
Interactive Data Exploration:
Filter by country or customer demographics to gain specific insights.
Interactive visualizations, such as bar charts and donut charts, that respond to user input.
Dynamic KPI cards for earnings and customer profiling.
How the Theme Toggle Works

The theme toggle is implemented in Power BI using Bookmarks and Buttons to navigate between light and dark theme views of the same dashboard.

Steps for Theme Switching:
Bookmarks:
Two views of the dashboard are created: one with a Light Theme and another with a Dark Theme.
Bookmarks are used to capture each view with its respective formatting and visual elements.
Toggle Button:
A button is added to both the Light and Dark themed dashboards.
The button is linked to a bookmark action to switch between the themes when clicked.
Action Setup:
In the Light Theme dashboard, the button is labeled "Switch to Dark Theme" and vice versa.
The button action is tied to the bookmark that navigates to the corresponding theme.
How to Add a Theme Toggle Button:
Create two versions of your dashboard: one in Light Theme and the other in Dark Theme.
Use the Bookmark feature in Power BI to capture each dashboard layout.
Insert a button in both versions of the dashboard.
Assign an action to the button to toggle between the light and dark bookmarks.
Requirements

Power BI Desktop: Version October 2020 or later (for full functionality of bookmarks and buttons).
Data Source: The project is built using [describe the data source, e.g., SQL database, Excel files, etc.].
Files Included

Customer_Performance_Light.pbix: Power BI dashboard with the light theme applied.
Customer_Performance_Dark.pbix: Power BI dashboard with the dark theme applied.
How to Use the Dashboard

Open Power BI Desktop and load either the Light or Dark theme dashboard files.
Click the Theme Toggle Button located in the top section to switch between light and dark themes.
Explore the data by applying filters for customer segments, revenue, or other criteria.
Hover over visualizations for additional tooltips and insights.
Filter Usage:
Country Filter: Choose from the drop-down menu to view data specific to individual countries.
Customer Segmentation: Explore data based on customer categories, such as those with or without children.
Customization

Adjusting Themes: You can customize the color schemes used in the light and dark themes by adjusting the formatting options for visual elements in Power BI.
Data Refresh: If you have new data, you can refresh the data source in Power BI, and the visualizations will update automatically.
Future Enhancements

Automating Theme Switch: Potential improvement includes implementing DAX measures for more dynamic theme switching based on user selection.
Mobile-Friendly Layout: A future version could focus on optimizing the dashboard for mobile devices.
