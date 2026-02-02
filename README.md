# StatAssist: Automated Hypothesis Tester

StatAssist is a Streamlit-based web application designed to streamline the statistical analysis workflow. Instead of manually checking assumptions and selecting tests, this tool automates the decision-making process for group comparisons.

It bridges the gap between raw data and statistical insights by automatically verifying assumptions (Normality, Homogeneity) and applying the correct statistical test (ANOVA or Kruskal-Wallis).

## 🚀 Features

* **Data Upload:** Supports CSV format.
* **Assumption Checking:**
    * Shapiro-Wilk Test for Normality.
    * Levene's Test for Homogeneity of Variance.
* **Decision Engine:** Automatically switches between parametric (ANOVA) and non-parametric (Kruskal-Wallis) tests based on assumption results.
* **Visualization:** Generates Boxplots combined with Stripplots to visualize data distribution and outliers.

## 🛠 Installation & Usage

1.  Clone the repository:
    ```bash
    git clone [https://github.com/YOUR_USERNAME/stat-assist.git](https://github.com/YOUR_USERNAME/stat-assist.git)
    cd stat-assist
    ```

2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3.  Run the application:
    ```bash
    streamlit run app.py
    ```

## 📂 Project Structure

* `app.py`: Main application logic and UI.
* `requirements.txt`: List of Python dependencies.

## 🔮 Future Improvements

* Integration of Post-hoc tests (Tukey HSD, Dunn's Test).
* Support for paired samples (T-test, Wilcoxon).
* Export results to PDF/Word format.

## 📝 License

This project is open-source and available under the MIT License.
