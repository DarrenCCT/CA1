# CA1 – Analysis of Footfall in Capel Street (2015)

This project was completed as part of a MSc programme in Data Analytics. It involves applying **Data Analysis & Visualisations**, **Statistics**,  and **Machine Learning** techniques. The scope of the assignment was to apply these techniques to a publically available dataset from a pre-selected set of choices. I chose the footfall of Capel Street for the year 2015. The dataset contains footfall measured for each day of the week throughout the entire year. 

**Note:** It was the first CA. It will look amateur-ish.

## Project Structure

- **CA1 Notebook.ipynb** - The entire project is in this one notebook. It is split into three sections for each of the modules. **Data Analysis & Visualisations** shows how the data was acquired, how exploratory data analysis was performed, and choosing appropiate visualisations throughout. **Statistics** includes measurements of central tendendancy and both poisson and normal distributions. **Machine Learning** features using Supervised Machine Learning models to evaluate if footfall can be used to predict what day of the week it is. Models tested were SVM and Decision Tree Classifiers. 

## Dataset

The dataset used in this project was sourced from data.gov.ie:
👉 [Capel St 2015 Dataset (data.gov.ie)](https://data.gov.ie/dataset/pedestrian_footfall/resource/3df44fb9-900a-46cb-b6c1-35889c8d2d60)

Only footfall measurements from **2015** were used.

## Technologies Used

- **Python** — Core programming language
- **pandas** — Data manipulation and analysis
- **NumPy** — Numerical computing
- **Seaborn** — Statistical data visualization
- **Matplotlib** — Plotting and visualization
- **SciPy** — Scientific computing and statistics
- **scikit-learn** — Machine learning and data preprocessing

## How to Run

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/CA1.git
    cd CA1
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run Notebooks**:
    - Open Jupyter Lab or Jupyter Notebook:
      ```bash
      jupyter lab
      ```
    - Run `CA1 Notebook.ipynb`


---

## 📉 Disclaimer

> **Interpretation of visualisations and charts is intentionally limited in the notebook.**  
> This is due to a course requirement mandating that analytical conclusions and detailed explanations be presented separately in the accompanying report.

---

## License

This project is licensed under the **MIT License**. See `LICENSE` for details.

## Author

- Darren Smith
