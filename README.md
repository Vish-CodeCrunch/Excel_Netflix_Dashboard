# 🎬 Netflix Dashboard Analysis

![Netflix Logo](https://upload.wikimedia.org/wikipedia/commons/0/08/Netflix_2015_logo.svg)  
*Dive into Netflix Movies with an Interactive Excel Dashboard!*  

![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)  
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)  

Welcome to the **Netflix Dashboard Analysis**! This project offers an Excel dashboard (`NetflixOriginals.xlsx`) to explore Netflix original movies from 2014 to 2021. Packed with raw data, pivot tables, and insights, it’s perfect for data analysts, Netflix fans, or anyone curious about streaming trends—all within Excel! 🍿

---

## 📋 Table of Contents

- [Overview](#overview)
- [Dataset Description](#dataset-description)
- [Key Insights](#key-insights)
- [Prerequisites](#prerequisites)
- [File Structure](#file-structure)
- [Usage Instructions](#usage-instructions)
- [Contributing](#contributing)
- [Contact](#contact)

---

## 🌟 Overview

This project provides a deep dive into Netflix movies through an Excel dashboard (`NetflixOriginals.xlsx`). It includes:  
- 📊 Raw data on movie titles, genres, premiere dates, runtimes, IMDB scores, and languages.  
- 📈 Pivot tables summarizing trends by genre, language, year, and more.  
- 🔍 Key insights into Netflix’s content production from 2014 to 2021.  

Explore and analyze Netflix trends entirely within Excel—perfect for movie lovers and data enthusiasts alike! 🚀

---

## 📊 Dataset Description

The dataset in `NetflixOriginals.xlsx` covers Netflix original movies with the following structure:

| **Column Name**    | **Type**    | **Description**          |
|--------------------|-------------|--------------------------|
| `Title`            | VARCHAR     | Movie title (e.g., "The Irishman") |
| `Genre`            | VARCHAR     | Movie genre (e.g., Documentary) |
| `Premiere`         | DATE        | Release date (e.g., November 27, 2019) |
| `Runtime`          | INT         | Duration in minutes (e.g., 209) |
| `IMDB Score`       | FLOAT       | IMDB rating (e.g., 7.8) |
| `Language`         | VARCHAR     | Primary language (e.g., English) |

**Additional Fields**: Includes derived columns like `DAY`, `YEAR`, `MONTH`, `DUB_LANGUAGE`, `GENRE_SP`, and `RANGE_SCORE`.  

**Pivot Tables**:  
- 🧩 **Genre Breakdown**: Stats by genre (e.g., Documentary: 159 movies, avg IMDB 6.94).  
- 🌍 **Language Distribution**: Language stats (e.g., English: 401 movies).  
- 📅 **Yearly Trends**: Movies per year (e.g., 2020: 183 movies).  
- 🕒 **Runtime Distribution**: Runtime ranges (e.g., 90-99 minutes: 154 movies).  

---

## 🔍 Key Insights

Here are some exciting findings from the dashboard:  
- 🌐 **Most Common Language**: English leads with 401 movies, followed by Hindi (33) and Spanish (31).  
- 📅 **Peak Production Year**: 2020 saw 183 movies, likely due to pandemic-driven demand.  
- ⭐ **Highest Rated Movie**: "David Attenborough: A Life on Our Planet" (IMDB 9.0, Documentary).  
- ⏳ **Runtime Extremes**:  
  - Longest: "The Irishman" (209 minutes, Crime drama, IMDB 7.8).  
  - Shortest: "Sol Levante" (4 minutes, Anime/Short, IMDB 4.7).  
- 🎭 **Genre Popularity**: Documentaries dominate (159 movies), followed by Drama (77) and Comedy (49).  
- 💡 **Interesting Fact**: Documentaries have a higher average IMDB rating (6.94) than genres like Comedy (5.51), showing Netflix’s documentary strength!  
- 🗓️ **Monthly Distribution**: October has the most releases (77 movies), while June has the fewest (35).  

---

## 🛠️ Prerequisites

Before diving in, ensure you have:  
- 📊 **Software**:  
  - Microsoft Excel, Google Sheets, or any compatible spreadsheet tool to open `NetflixOriginals.xlsx`.  
- 💻 **System Requirements**:  
  - Any OS (Windows, macOS, Linux).  
  - At least 1GB of free storage.  
- 🖥️ **GitHub Account**: To clone the repo and contribute.  

---

## 📂 File Structure

- `NetflixOriginals.xlsx`: The Excel dashboard with raw data and pivot tables.  
- `README.md`: This documentation file.  

---

## 🚀 Usage Instructions

Get started in a few simple steps:  

1. **Clone the Repository** 📥:  
   ```bash
   git clone https://github.com/Vish-CodeCrunch/Excel_Netflix_Dashboard.git
   cd netflix-originals-dashboard
   ```

2. **Open the Dashboard** 📊:  
   - Open `NetflixOriginals.xlsx` in Excel or Google Sheets.  
   - Explore the raw data and pivot tables.  

3. **Analyze Trends** 🔍:  
   - Use pivot tables to explore genres, languages, and yearly trends—all within Excel.  

4. **Visualize Insights** 📈:  
   - Create charts directly in Excel to visualize trends like movies per year or genre popularity.  

5. **Share Feedback** 💬:  
   - Found a cool insight? Share it by opening an issue or submitting a pull request!  

---

## 🤝 Contributing

We’d love your contributions! To get started:  
1. Fork this repository 🍴.  
2. Create a new branch (`git checkout -b feature/your-feature`).  
3. Make your changes and commit (`git commit -m "Add your feature"`).  
4. Push to your branch (`git push origin feature/your-feature`).  
5. Create a pull request 📬.  

Please follow the [Code of Conduct](CODE_OF_CONDUCT.md) and align with the project’s goals.  

---

## 📬 Contact

Have questions or ideas? Reach out!  
- **GitHub**: [your-username](https://github.com/Vish-CodeCrunch)  
- **Email**: [vishal.ds7428@gmail.com](mailto:vishal.ds7428@gmail.com)  
- **LinkedIn**: [Your LinkedIn Profile](https://www.linkedin.com/in/vishaldstech/)  
- **X**: [@your-username](https://x.com/Vishal_Datavibe)  

I’d love to hear your feedback or chat about Netflix trends! 🎥

---

⭐ If you find this project helpful, give it a star on GitHub! ⭐
