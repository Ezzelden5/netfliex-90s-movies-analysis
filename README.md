# netfliex-90s-movies-analysis
An exploratory data analysis (EDA) of the Netflix dataset, with a special focus on movies released in the 1990s. This project delves into trends, genres and characteristics of nostalgic cinema to uncover insights from that iconic decade

# netfliex-90s-movies-analysis
An exploratory data analysis (EDA) of the Netflix dataset, with a special focus on movies released in the 1990s. This project delves into trends, genres and characteristics of nostalgic cinema to unco[...]

# Analysis of 1990s Movies on Netflix

<p align="center">
  <img src="redpopcorn.jpg" alt="A bag of popcorn" width="300"/>
</p>

## 🎬 Project Overview

This project performs an exploratory data analysis (EDA) on a dataset of shows and movies available on Netflix. The primary goal is to uncover trends and insights specifically related to **movies rele[...]

Working from the perspective of a production company specializing in nostalgic styles, this analysis helps to better understand the landscape of 90s cinema, including popular genres, movie durations, [...]

## 📊 Dataset

The analysis uses the `netflix_data.csv` file, which contains information about various titles on Netflix.

The dataset includes the following columns:
| Column       | Description                       |
|--------------|-----------------------------------|
| `show_id`    | The ID of the show                |
| `type`       | Type of show (Movie or TV Show)   |
| `title`      | Title of the show                 |
| `director`   | Director of the show              |
| `cast`       | Cast of the show                  |
| `country`    | Country of origin                 |
| `date_added` | Date added to Netflix             |
| `release_year` | Year the show was released      |
| `duration`   | Duration in minutes or seasons    |
| `description`| A brief summary of the show       |
| `genre`      | The genre of the show             |

## 🛠️ Tools and Libraries

This project is built using Python and the following core data science libraries:
* **Pandas:** For data manipulation and analysis.
* **Jupyter Notebook:** For interactive code development and visualization.
* _(You might also use Matplotlib or Seaborn for plotting)_

## 🚀 How to Use

To run this analysis on your own machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Ezzelden5/netfliex-90s-movies-analysis.git
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd netfliex-90s-movies-analysis
    ```

3.  **Install the necessary libraries.** It's recommended to create a `requirements.txt` file with the following content:
    ```
    pandas
    jupyter
    matplotlib
    seaborn
    ```
    Then, install them using pip:
    ```bash
    pip install -r requirements.txt
    ```

4.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

5.  Open the `notebook.ipynb` file to view and run the analysis.

## 📁 File Structure

```
