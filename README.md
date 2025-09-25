# **Formula 1 Dashboard (1950–2025)**

## **📌 Overview**

This Power BI project provides a comprehensive analysis of Formula 1 racing history from 1950 to 2025. Using interactive dashboards, the report highlights driver and team performance, race distributions, and circuit statistics. The objective is to present both a macro-level view of F1 evolution and micro-level insights into circuits and winners.

The dashboard is divided into three structured pages:

### **Overview Dashboard** – a high-level snapshot of races and global trends.
### **Drivers & Teams Dashboard** – in-depth analysis of drivers’ and constructors’ dominance.
### **Circuit Stats Dashboard** – insights into circuit usage, diversity of winners, and race distribution.

Each page contains carefully selected KPIs and visuals, designed for intuitive exploration through slicers and filters.

## **Dashboard Pages & Visual Explanations**

## **1️ Overview Dashboard**

<img width="1359" height="763" alt="image" src="https://github.com/user-attachments/assets/96ad4d0b-1efb-4929-9717-dcad8ee4cf88" />

The Overview Dashboard provides a high-level summary of Formula 1’s history. It contains key performance indicators (KPIs) and global visuals to understand the scale and distribution of races.

### **Visuals Included:**

Total Wins (Card) → Total number of races won in the dataset.

Total Races (Card) → Aggregate count of all races between 1950–2025.

Average Laps per Race (Card) → Displays the typical race length.

Fastest & Longest Race Duration (Cards) → Highlights the shortest and longest races (in minutes).

Minimum & Maximum Race Duration (Cards) → Range of race times across the dataset.

Unique Winning Drivers (Card) → Number of distinct race winners.

Unique Winning Teams (Card) → Number of distinct constructors with victories.

Map of Wins by Continent (Map Visual) → Shows the geographical distribution of wins across continents.

### **Interpretation:** This page answers “how big is F1?” by showing the scale of races, the spread across continents, and how race dynamics (laps, durations) vary globally.

## **2️ Drivers & Teams Dashboard**

<img width="1358" height="763" alt="image" src="https://github.com/user-attachments/assets/2ccf9ac9-3c58-49fa-aa42-e16eb1df8a37" />

This dashboard shifts focus from global metrics to individual and team dominance. It captures both the historical success of drivers and teams and the growth of F1’s race calendar.

### **Visuals Included:**

Wins by Driver (Bar Chart) → Ranks drivers by total victories. Highlights career dominance.

Wins by Team (Bar Chart) → Displays constructors’ historical success. Useful for comparing eras (e.g., Ferrari, Mercedes, Red Bull).

Races by Year (Line Chart) → Shows how the number of races per season has expanded from the 1950s to the present.

Races by Year & Continent (Line Chart) → Illustrates globalization of the sport, showing how races expanded beyond Europe into Asia, Americas, Middle East, etc.

### **Interpretation:** This page explains “who dominates F1?” and “how has the race calendar evolved?”

## **3️ Circuit Stats Dashboard**

<img width="1359" height="763" alt="image" src="https://github.com/user-attachments/assets/d9d8ec83-3d35-4b37-947a-79e2cd55584e" />

The Circuit Stats Dashboard dives into track-level performance and diversity. It identifies the most historic circuits, which drivers dominate certain venues, and where competition is most diverse.

### **Visuals Included:**

Top Driver per Circuit (Table) → For each circuit, shows the driver with the highest number of wins.
Circuit with Most Races (Card) → Identifies the circuit most frequently used in F1 history.
Circuit with Most Unique Winners (Card) → Highlights circuits with the greatest variety of winning drivers.
Races Count by Circuit (Bar Chart) → Ranks circuits by frequency of races hosted.
Unique Winners per Circuit (Treemap/Bar Chart) → Displays how competitive each circuit is (some dominated by a few, others widely shared).

### **Interpretation:** This page answers “which circuits are most iconic?” and “where do many different drivers succeed vs. where do legends dominate?”

## **Purpose**

The dashboard is designed for data storytelling in sports analytics:

Provide historical context of Formula 1’s growth.

Compare dominance across drivers, teams, and circuits.

Enable interactive exploration through slicers (Year, Driver, Team, Circuit, Continent).

## **Tools & Technologies**

Power BI Desktop → Data modeling, DAX calculations, interactive dashboards.

PostgreSQL → Initial data exploration and transformation.

GitHub → Version control and project documentation.
