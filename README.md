# Netflix Content Analysis

Exploratory Data Analysis of the Netflix Movies and TV Shows dataset to understand how the platform’s catalog is structured, how it has grown over time, and how content is distributed across countries, genres, and production contributors.

The project focuses on identifying patterns in Netflix’s content strategy using Python-based data analysis.

---

## Dataset

**Source:** [Netflix Movies and TV Shows — Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

The dataset contains metadata about titles available on Netflix, including information about production, release, and content characteristics.


**Core Characteristics:**
* Hybrid Content: Mix of Movies and TV Shows.
* Global Scope: Titles from 100+ countries.
* Library Type: Both original and licensed content.
* Data Status: Includes missing values in key metadata fields.


| Column       | Description                                   |
| ------------ | --------------------------------------------- |
| show_id      | Unique identifier for each title              |
| type         | Movie or TV Show                              |
| title        | Title name                                    |
| director     | Director(s) of the title                      |
| cast         | Main cast members                             |
| country      | Production country                            |
| date_added   | Date added to platform                        |
| release_year | Year of release                               |
| rating       | Content rating                                |
| duration     | Movie duration (minutes) or number of seasons |
| listed_in    | Genre categories                              |
| description  | Short content description                     |

---

## Analytical Questions

**Platform Identity**
— Is Netflix primarily movie-driven or series-driven, and what genres define its core?

**Growth & Strategic Shift**
— When did the catalog grow fastest, and has the Movie/TV Show balance shifted over time?

**Geographic Expansion**
— Which countries dominate production, is Netflix reducing U.S. reliance, and which markets are growing fastest?

**Content Structure**
— What are the runtime patterns for movies, and how deep are TV productions in terms of seasons?

**Production Architecture**
— Is Netflix's creative network concentrated or distributed across directors, cast, and co-productions?

---

## Project Structure

The analysis is organized into four main stages:

1. **Dataset Overview**
   Initial inspection of the dataset, loading libraries, and understanding data structure.

2. **Data Cleaning**
   Handling missing values, formatting dates, correcting inconsistent fields, and preparing data for analysis.

3. **Exploratory Data Analysis (EDA)**
   Investigation of Netflix catalog structure through five thematic analysis blocks.

4. **Conclusion**
   Summary of the key observations from the analysis.

---

## Technologies

The analysis was conducted using:

* Python
* Pandas
* NumPy
* Matplotlib
* Google Colab

---

## How to Run

1. Clone the repository

3. Install dependencies

```bash
pip install -r requirements.txt
```
3. Open the notebook

```bash
jupyter notebook Netflix_Content_Analysis.ipynb
```
