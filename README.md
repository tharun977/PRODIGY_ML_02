# K-Means Clustering on Retail Customer Data

This project implements a K-means clustering algorithm to group customers of a retail store based on their purchase history. The dataset used contains information about customers' age, annual income, and spending score.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Dataset](#dataset)
- [Results](#results)
- [License](#license)

## Installation

To set up this project, you need to have Python installed on your machine. Follow the steps below:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/tharun977/PRODIGY_ML_02.git
   cd PRODIGY_ML_02
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv venv  # Windows
   python3 -m venv venv  # macOS/Linux
   ```

3. **Activate the virtual environment:**
   - **Windows:**
     ```bash
     venv\Scripts\activate
     ```
   - **macOS/Linux:**
     ```bash
     source venv/bin/activate
     ```

4. **Install required packages:**
   ```bash
   pip install pandas seaborn matplotlib scikit-learn
   ```

## Usage

1. **Run the script:**
   Execute the Python script to perform K-means clustering:
   ```bash
   python ProdigyTask2.py
   ```

2. **View the results:**
   The script will generate a plot showing the elbow method for optimal K and the K-means clustering results visualized based on annual income and spending score.

## Dependencies

This project requires the following Python packages:
- `pandas`
- `seaborn`
- `matplotlib`
- `scikit-learn`

You can install all dependencies using:
```bash
pip install -r requirements.txt
```

*(If desired, create a `requirements.txt` file with all the dependencies.)*

## Dataset

The dataset used for this project is `Mall_Customers.csv`, which contains the following columns:
- **CustomerID**: Unique identifier for each customer
- **Gender**: Gender of the customer
- **Age**: Age of the customer
- **Annual Income (k$)**: Annual income of the customer in thousands
- **Spending Score (1-100)**: Score assigned to the customer based on behavior and spending nature

## Results

The K-means clustering results are visualized, showing the groups formed based on the selected features (Annual Income and Spending Score). The elbow method helps in determining the optimal number of clusters.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

- **Tharun Raman**
- [GitHub Profile](https://github.com/tharun977)
- [LinkedIn Profile](https://www.linkedin.com/in/tharunraman?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BmOLf8ms%2FT1CLZliM7nBFiQ%3D%3D)
```

### Instructions for Adding the README to Your Repository:
1. Create a file named `README.md` in the root directory of your project.
2. Copy and paste the above content into the file.
3. Save the file.
4. Commit and push your changes to the GitHub repository:

```bash
git add README.md
git commit -m "Add complete README file"
git push origin main
```
