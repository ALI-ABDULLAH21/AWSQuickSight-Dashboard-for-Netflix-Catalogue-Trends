

# Netflix Catalogue Analysis Dashboard using Amazon QuickSight

This project involves analyzing the trends and patterns in Netflix's catalogue using AWS services, particularly Amazon QuickSight, to create an interactive dashboard. The aim is to visualize various metrics, including genre distribution, release year trends, and content type proportions to understand Netflix's catalogue better.

## Table of Contents

- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Dataset](#dataset)
- [Project Setup](#project-setup)
- [Visualizations](#visualizations)
- [AWS Services Used](#aws-services-used)
- [Conclusion](#conclusion)
- [Contact](#contact)

## Overview

In this project, I explored Netflix's catalogue data by building a comprehensive dashboard in Amazon QuickSight. By leveraging AWS S3 to store data and QuickSight for visualization, I was able to answer key data questions, including trends in genre popularity, content type distribution, and the release year of Netflix titles. The resulting dashboard presents all these insights interactively in one place.

## Tech Stack

- **Amazon S3**: Data storage
- **Amazon QuickSight**: Data visualization and dashboard creation
- **AWS IAM**: User permissions for secure access


## Features

- 📊 **Donut charts**: Visualize content type distribution (TV shows vs. Movies)
- 📈 **Bar graphs**: Analyze yearly trends in Netflix content releases
- 📋 **Tables**: Present detailed data on Netflix’s titles (genres, release years, etc.)
- 📊 **Custom dashboards**: Combine multiple visualizations into a comprehensive dashboard
- 🔍 **Filters and drill-down options**: Enable interactive exploration of the dataset

## Dataset

The dataset for this project was sourced from Kaggle: [Netflix Movies and TV Shows Dataset](https://www.kaggle.com/shivamb/netflix-shows).

**Key Columns:**
- `title`: Title of the movie/show
- `type`: TV Show or Movie
- `release_year`: Year of release
- `genre`: Genre of the content
- `country`: Country of production
- `date_added`: Date when the title was added to Netflix
- `duration`: Duration of the content (minutes or seasons)

## Project Setup

### Step 1: Upload the Dataset to S3

1. Go to the **Amazon S3 Console**.
2. Create a new bucket and upload the Netflix dataset CSV file.
3. Ensure that your S3 bucket has the correct permissions for Amazon QuickSight to access it.

### Step 2: Connect QuickSight to the Dataset

1. Open **Amazon QuickSight** and navigate to **Datasets**.
2. Connect to the dataset stored in the S3 bucket.
3. Perform any necessary data transformation (optional).

### Step 3: Create Visualizations

1. Use QuickSight’s drag-and-drop interface to create donut charts, bar graphs, and tables.
2. Customize the visuals with filters, legends, and formatting.
3. Combine these visuals into one cohesive dashboard.

## Visualizations

1. **Donut Chart**: Content Type Distribution (Movies vs. TV Shows).
2. **Bar Graph**: Number of Titles Released per Year.
3. **Table**: List of Netflix titles with genre, country, and release year.
4. **Heatmap**: Popular Genres by Year.

Each visualization provides valuable insights into Netflix’s catalogue, enabling data-driven decisions.

## AWS Services Used

1. **Amazon S3**: Used for storing the dataset securely in the cloud.
2. **Amazon QuickSight**: For creating visualizations and interactive dashboards.
3. **AWS IAM**: Managed user permissions for accessing S3 and QuickSight.

## Conclusion

This project was a great way to enhance my understanding of data visualization and cloud services. Amazon QuickSight allowed me to quickly build interactive visualizations and dashboards, enabling in-depth analysis of Netflix's content trends. This hands-on experience also solidified my skills in working with AWS services.

