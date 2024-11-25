Based on the provided details, here is a README.md file for your project:

```markdown
# OnShape Insights Dashboard

## Overview
The OnShape Insights Dashboard is a Python-Wedgit and HTML-powered application designed to manage and analyze OnShape projects efficiently. The platform provides detailed visualizations and statistics for projects, employees, and user activities, offering valuable insights through an interactive interface.

## Features
- **Main Page**: Overview of total projects, employees, and actions with visual graphs.
- **Projects Page**: Detailed statistics and visualizations for specific projects.
- **Employees Page**: Analysis of employee activity with heatmaps and bar charts.
- **ChatBot Page**: Interactive assistant to answer queries about project data.
- **Notifications Page**: Alerts for inactive projects, employee assistance needs, and project challenges.
- **Upload JSON Page**: Upload and manage JSON data for analysis.
- **Collaborations Page**: Visual representation of team contributions to documents.

## Technologies Used
- **Backend**: Python with Firebase integration for data retrieval and storage.
- **Frontend**: Widgets and HTML for an interactive user interface.
- **Visualization**: Matplotlib, Seaborn, and Chart.js for data representation.
- **Development Environment**: Google Colab for coding and collaboration.

## Key Functionalities
### 1. Main Page
- **Summary**: Total number of projects, employees, and actions.
- **Graphs**:
  - Monthly distribution of actions.
  - Top 5 projects by actions.
- **Employee Projects Table**: List of employees with their involvement metrics.

### 2. Projects Page
- Displays actions per tab, modeling time, and user contribution statistics.
- Graphical insights into project activity and progress.

### 3. Employees Page
- Detailed statistics for individual employees.
- Heatmaps showing activity patterns.
- Monthly activity trend analysis.

### 4. ChatBot Page
- Answers queries like "Most accessed document" or "Least used tab."
- Provides quick, insightful information.

### 5. Notifications Page
- Alerts for:
  - Inactive projects.
  - Employees needing support.
  - Projects with challenges.

### 6. Upload JSON Page
- Upload and manage JSON datasets.
- Integrate data directly into the dashboard.

### 7. Collaborations Page
- Visual representation of team contributions to documents.

## Design Patterns
- **Model-View-Controller (MVC)**: Separates data, UI, and control logic.
- **Factory Method**: Used in creating widgets and pages.

## Usage
1. Upload JSON files containing project data via the Upload JSON page.
2. Navigate through the dashboard using the navigation bar.
3. Analyze projects, employee activity, or collaboration data using the interactive widgets.
4. Use the chatbot for quick insights or ask predefined questions.
