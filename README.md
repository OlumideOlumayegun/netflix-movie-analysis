# Beyond the Screen: Analysing Netflix Movie Data

![watching netflix](datasets/netflix.jpg)

## Project Overview
This project investigates trends in Netflix movie durations over time, focusing on whether the average length of movies has been declining. Using a dataset netflix movies, we explore how movie durations have evolved from 2011 to 2020, analyse the impact of different genres, and visualise the data to uncover insights. The analysis is conducted using Python, with a focus on data manipulation with **pandas** and data visualisation with **matplotlib**.

## Key Questions Explored
1. Has the average duration of Netflix movies declined over the past decade?
2. Which genres are most associated with shorter movie durations?
3. How do non-feature films (e.g., Children’s movies, Documentaries, Stand-Up comedy) influence the overall trend?

## Tools and Technologies
- **Python**: Primary programming language for analysis.
- **pandas**: Used for data manipulation and analysis.
- **matplotlib**: Used for creating visualizations.
- **Jupyter Notebook**: Environment for writing and executing code.

## Dataset
The dataset used in this project was provided by DataCamp and includes information about Netflix movies and TV shows, such as:
- Title
- Type (Movie or TV Show)
- Genre
- Release Year
- Duration
- Country of Production

## Analysis Steps
1. **Loading and Inspecting Data**: The dataset was loaded into a pandas DataFrame, and initial inspections were performed to understand its structure.
2. **Filtering for Movies**: The dataset was filtered to include only movies, excluding TV shows.
3. **Visualising Trends**: A scatter plot was created to visualise movie durations over time, with non-feature films highlighted in different colors.
4. **Exploring Genres**: Shorter movies (under 60 minutes) were analysed to identify which genres are most common.
5. **Drawing Insights**: The analysis revealed that genres like Children’s movies, Documentaries, and Stand-Up comedy are associated with shorter durations and may be influencing the overall trend.

## Key Findings
- The average duration of Netflix movies has declined over the past decade.
- Non-feature films, such as Children’s movies, Documentaries, and Stand-Up comedy, are significantly shorter and have become more prevalent in recent years.
- Traditional feature films (e.g., Dramas, Comedies, Action) have remained relatively consistent in duration.

## Repository Structure
```
netflix-movie-analysis/
├── dataset/
│   └── netflix_data.csv         # Dataset used for analysis
├── notebook.ipynb               # Jupyter Notebook containing the analysis
├── README.md                    # Project overview and documentation
└── requirements.txt             # List of Python dependencies
```

## How to Use This Repository
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/OlumideOlumayegun/netflix-movie-analysis.git
   cd netflix-movie-analysis
   ```
2. **Set Up the Environment**:
   - Install the required dependencies:
     ```bash
     pip install -r requirements.txt
     ```
3. **Run the Analysis**:
   - Open the Jupyter Notebook (`notebook.ipynb`) and execute the cells to reproduce the analysis.

## Dependencies
- Python 3.x
- pandas
- matplotlib
- Jupyter Notebook

## Acknowledgements
This project was conducted as part of the project portfolio for **DataCamp's Data Scientist with Python Career Track**. Special thanks to DataCamp for providing the dataset and resources that made this analysis possible.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---