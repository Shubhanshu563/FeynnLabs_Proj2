
---

# Electric Vehicle Market Analysis in India

## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Datasets](#datasets)
- [Methodology](#methodology)
  - [Data Preprocessing](#data-preprocessing)
  - [Segment Extraction](#segment-extraction)
  - [Profiling and Describing Potential Segments](#profiling-and-describing-potential-segments)
  - [Selection of Target Segment](#selection-of-target-segment)
  - [Customizing the Marketing Mix](#customizing-the-marketing-mix)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Project Overview
This project aims to analyze the Electric Vehicle (EV) market in India, focusing on identifying optimal market segments for launching a luxury EV model. Through data analysis, segmentation, and predictive modeling, we aim to inform strategic marketing and product development decisions.

## Objectives
- Analyze the current state of the EV market in India.
- Identify key segments of potential EV customers based on demographics and preferences.
- Develop a marketing strategy tailored to the selected target segments.
- Estimate the potential customer base and profitability of the luxury EV model.

## Datasets
Two primary datasets were used in this analysis:
1. **Cars Dataset**: Contains features related to various vehicle types, including specifications, pricing, and customer preferences.
2. **Census Dataset**: Provides demographic information, housing conditions, and regional infrastructure details relevant to EV adoption.

## Methodology

### Data Preprocessing
1. **Data Cleaning**: Removed duplicates, handled missing values, and corrected inconsistencies in both datasets.
2. **Feature Engineering**: Created new features where necessary to enhance the analysis (e.g., converting categorical variables).
3. **Normalization**: Scaled numerical features for better performance in clustering and modeling algorithms.

### Segment Extraction
1. **Clustering Techniques**:
   - **K-Means Clustering**: Grouped customers based on behaviors and preferences.
   - **Hierarchical Clustering**: Identified nested clusters for more granular insights.
   - **DBSCAN**: Discovered clusters of varying densities to highlight unique segments.

2. **Predictive Modeling**:
   - **Logistic Regression**: Predicted the likelihood of EV adoption among customer segments.
   - **Decision Tree Classifier**: Analyzed key decision-making factors influencing customer preferences.

### Profiling and Describing Potential Segments
- Developed detailed profiles for each identified segment, highlighting demographics, psychographics, and behavioral characteristics.
- Incorporated insights from predictive models to understand customer readiness and preferences better.

### Selection of Target Segment
- Selected segments based on market size potential, alignment with company goals, and readiness for EV adoption.
- Target segments include the **Luxury SUV Cluster** and the **Excellent Infrastructure Cluster**, identified through clustering and predictive analysis.

### Customizing the Marketing Mix
- Developed a tailored marketing strategy for the target segments based on the 4 Ps:
  - **Product**: Premium features based on customer preferences.
  - **Price**: Competitive pricing strategy aligned with perceived value.
  - **Promotion**: Targeted marketing campaigns designed to reach specific consumer groups.
  - **Place**: Optimal distribution channels for reaching target customers.

## Installation
To run this project locally, you need to have Python installed along with the following libraries:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

You can install the required packages using pip:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage
1. Clone the repository:
   ```bash
   git clone [repository-url]
   cd [repository-directory]
   ```
2. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Execute the notebooks sequentially to follow the analysis from data preprocessing to marketing strategy development.

## Contributors
- Shubhanshu (Project Lead)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

