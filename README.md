# 🎮 Video Game Sales Analysis

## 📌 Project Overview

This project analyzes historical video game sales data to identify market trends across genres, platforms, publishers, and geographic regions.

The analysis was performed using **Python**, **Pandas**, and **Matplotlib**, following a complete data analysis workflow: data cleaning, exploratory data analysis (EDA), business-driven insights, and data visualization.

---

## 📂 Dataset

The dataset contains information about more than **16,000 video games**, including:

* Game title
* Platform
* Release year
* Genre
* Publisher
* Sales in North America, Europe, Japan, and Other regions
* Global sales

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

---

## 🎯 Business Questions

The project aims to answer the following business questions:

1. Which video games generated the highest global sales?
2. Which genres are the most successful?
3. Which gaming platforms generated the highest sales?
4. How have video game sales evolved over time?

---

## 🧹 Data Cleaning

The following preprocessing steps were performed before the analysis:

* Removed duplicate records.
* Handled missing values.
* Corrected data types.
* Standardized column names.
* Removed unnecessary columns.
* Filled missing publisher values whenever the same game title was associated with a known publisher.

---

## 📊 Exploratory Data Analysis

The notebook includes several analyses and visualizations, including:

* Top 10 best-selling games
* Global sales by genre
* Sales distribution by platform
* Publisher performance
* Sales trends over time
* Genre evolution through the years
* Regional sales comparison
* Platform sales by geographic region

---

## 🔍 Key Insights

After selecting the top ten video games by global sales, I displayed them in a bar chart, using regional sales to add an additional layer of information. This analysis shows that the best-selling title, Wii Sports, generated almost twice the sales of the second-ranked game, Super Mario Bros., with nearly half of its sales coming from the North American market.

This observation led me to calculate the total sales across the entire dataset and compare the contribution of each geographic market. The analysis shows that North America alone accounts for nearly half of total global sales. An interesting example is Duck Hunt, which appears in the top ten best-selling games despite being sold almost exclusively in the North American market.

To analyze genre performance, I grouped all records by genre and aggregated total sales for each category. The resulting pie chart shows that Action and Sports games together account for approximately one-third of the entire market.

I then analyzed the console market by grouping the data by platform and aggregating total sales. The results were displayed in a bar chart. The PlayStation 2 is the highest-selling platform overall, although it is not the best-selling console in the North American market, where the Xbox 360 performs better. This difference is largely explained by the Japanese market, where Microsoft's console achieved very limited sales. To better interpret these results, I also displayed the first year in which each platform appears in the dataset.

Finally, I investigated how the video game market evolved over time. I first grouped the data by release year and aggregated total global sales, then visualized the results with a line chart. The graph highlights the market's steady growth throughout the 1990s, followed by a rapid increase in sales until the late 2000s, and then a sharp decline beginning around 2010.

The release of the PlayStation 2 and Xbox 360, two of the highest-selling consoles in the dataset, likely contributed to the rapid growth observed during this period.

By focusing on the five years with the highest total sales, it is possible to observe that the Japanese market reached its peak earlier, in 2006. Looking at the regional sales trends over time, the Japanese market, although considerably smaller than North America and Europe, appears to have anticipated the overall growth trend and experienced a more gradual decline.

This brief analysis raises several interesting questions that go beyond the information available in the dataset. Is the decline in sales related to the rise of subscription-based gaming services? Are newer console generations destined to sell less than their predecessors? How have smartphones and social media influenced the evolution of the video game industry?
