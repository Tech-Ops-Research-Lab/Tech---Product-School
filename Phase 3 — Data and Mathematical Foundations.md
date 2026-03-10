# Phase 3 — Data and Mathematical Foundations
## AI Engineering Product School Curriculum.

Phase 3 introduces the **mathematical and data science foundations required for artificial intelligence engineering**.

Artificial intelligence systems are not built only through programming.  
They rely on **mathematics, statistical reasoning, and structured data engineering**.

The purpose of this phase is to ensure engineers develop the ability to:

- understand how data represents real-world systems
- apply mathematical models to extract patterns
- design data pipelines that power intelligent systems
- prepare datasets for machine learning
- evaluate models through statistical analysis

This phase forms the **analytical backbone of AI engineering**.

The learning process builds gradually from:

```

Mathematics for computation
↓
Statistical reasoning
↓
Data representation
↓
Data processing pipelines
↓
Foundations for machine learning

```

Engineers completing this phase gain the ability to **treat data as a computational resource used to power intelligent systems**.

---

# Table of Contents

1. Phase Objectives  
2. Mathematical Thinking for Engineers  
3. Linear Algebra for AI Systems  
4. Calculus for Optimization  
5. Probability Theory  
6. Statistics for Data Analysis  
7. Data Representation and Encoding  
8. Data Engineering Foundations  
9. Data Cleaning and Preparation  
10. Exploratory Data Analysis  
11. Feature Engineering  
12. Data Pipelines and Processing Systems  
13. Data Storage Systems  
14. Data Quality and Validation  
15. Numerical Computing Tools  
16. Visualization and Analytical Reporting  
17. Engineering Labs  
18. Applied Data Projects  
19. Competencies After Phase 3

---

# 1. Phase Objectives

The objective of this phase is to develop **mathematical and data fluency for AI engineering**.

Engineers must learn how to:

- represent data mathematically
- analyze datasets statistically
- process large volumes of structured and unstructured data
- build pipelines that feed machine learning systems

By the end of Phase 3 engineers will understand:

- the mathematical structure behind machine learning algorithms
- how to manipulate data programmatically
- how to build reliable data infrastructure

---

# 2. Mathematical Thinking for Engineers

Mathematics provides the **formal language used to describe machine learning systems**.

AI models rely heavily on mathematical constructs such as:

- vectors
- matrices
- probability distributions
- optimization functions

Engineers must shift from informal reasoning to **structured mathematical thinking**.

Example reasoning structure:

```

Problem → Mathematical Model → Computational Implementation

```

Example:

Predicting housing prices.

Steps:

1. Represent housing features numerically  
2. Build mathematical relationship between variables  
3. Implement model computationally

---

# 3. Linear Algebra for AI Systems

Linear algebra forms the **core mathematical framework of machine learning**.

AI models operate primarily on **vectors and matrices**.

### Core Concepts

Vectors  
Matrices  
Matrix multiplication  
Linear transformations  
Eigenvectors and eigenvalues  

### Vectors

A vector represents a list of numbers.

Example:

```

[1200, 3, 2]

```

This vector could represent:

- house size
- number of bedrooms
- number of bathrooms

### Matrices

Matrices represent collections of vectors.

Example:

```

[
[1200,3,2]
[1500,4,2]
[900,2,1]
]

```

This represents a dataset containing multiple observations.

### Matrix Operations

Machine learning algorithms perform operations such as:

```

Matrix Multiplication
Matrix Transpose
Matrix Inversion

```

These operations enable:

- dimensional transformations
- data projections
- neural network computations

---

# 4. Calculus for Optimization

Calculus allows engineers to **optimize models by minimizing errors**.

Machine learning systems improve through optimization processes.

### Key Concepts

Derivatives  
Partial derivatives  
Gradients  
Gradient descent  

### Derivatives

Derivatives measure **how a function changes with respect to its inputs**.

Example:

```

f(x) = x²

```

Derivative:

```

f'(x) = 2x

```

### Gradient Descent

Machine learning models learn by minimizing error functions.

The algorithm repeatedly adjusts model parameters.

Simplified process:

```

1. Initialize model parameters
2. Calculate prediction error
3. Compute gradient
4. Update parameters
5. Repeat

```

This is the foundation of **neural network learning**.

---

# 5. Probability Theory

Probability theory describes **uncertainty in data**.

AI systems often make predictions under uncertain conditions.

### Core Concepts

Random variables  
Probability distributions  
Conditional probability  
Bayesian reasoning  

### Probability Distributions

Common distributions include:

Normal distribution  
Binomial distribution  
Poisson distribution  

Example:

The normal distribution describes many natural phenomena.

```

Mean (μ)
Standard deviation (σ)

```

Understanding distributions allows engineers to model **data variability**.

---

# 6. Statistics for Data Analysis

Statistics enables engineers to **analyze and interpret datasets**.

Key statistical concepts include:

Mean  
Median  
Variance  
Standard deviation  
Correlation  
Regression  

### Example

Dataset:

```

[5, 8, 10, 12, 15]

```

Mean:

```

(5 + 8 + 10 + 12 + 15) / 5 = 10

```

Statistics helps engineers understand:

- central tendencies
- variability
- relationships between variables

---

# 7. Data Representation and Encoding

Real-world information must be converted into **numerical representations**.

This process is called **data encoding**.

Examples:

Text data

```

"AI"

```

Encoded as:

```

[65, 73]

```

Categorical data

Example:

```

Color: Red, Blue, Green

```

Encoded using **one-hot encoding**:

```

Red → [1,0,0]
Blue → [0,1,0]
Green → [0,0,1]

```

Proper encoding ensures data can be **processed by machine learning models**.

---

# 8. Data Engineering Foundations

AI systems depend on **well-structured data pipelines**.

Data engineering involves:

- collecting data
- transforming data
- storing data
- delivering data for analysis

Pipeline structure:

```

Data Sources
↓
Data Ingestion
↓
Data Processing
↓
Data Storage
↓
Model Training

```

Engineers must design systems capable of **reliable data flow**.

---

# 9. Data Cleaning and Preparation

Real-world datasets often contain:

- missing values
- incorrect entries
- inconsistent formatting

Data cleaning ensures datasets are reliable.

Common tasks:

Removing duplicates  
Handling missing values  
Correcting formatting errors  
Filtering irrelevant data  

Example:

```

Age column:
23
25
NULL
29

```

Missing value handling:

- removal
- imputation

---

# 10. Exploratory Data Analysis

Exploratory Data Analysis (EDA) helps engineers **understand the structure of datasets**.

Common techniques:

- summary statistics
- distribution analysis
- correlation analysis
- visualization

Example questions:

- What variables exist?
- Which variables influence outcomes?
- Are there outliers?

EDA helps guide **model selection and feature engineering**.

---

# 11. Feature Engineering

Feature engineering involves **transforming raw data into meaningful inputs for models**.

Examples:

Converting timestamps into:

- hour
- day
- month

Creating ratios between variables.

Example:

```

Price per square foot

```

Feature engineering often determines **model performance quality**.

---

# 12. Data Pipelines and Processing Systems

AI products require automated data processing pipelines.

Pipeline tasks include:

- data ingestion
- transformation
- validation
- storage

Tools used in large-scale pipelines include:

- Apache Airflow
- Apache Spark
- Kafka
- distributed processing frameworks

Pipeline example:

```

Data Source
↓
Kafka Stream
↓
Spark Processing
↓
Data Warehouse
↓
ML Training

```

---

# 13. Data Storage Systems

Different storage systems serve different data needs.

### Relational Databases

Used for structured datasets.

Examples:

- PostgreSQL
- MySQL

### Data Warehouses

Designed for analytical queries.

Examples:

- BigQuery
- Snowflake

### Data Lakes

Store large volumes of raw data.

Examples:

- Amazon S3
- Hadoop HDFS

AI systems often combine multiple storage systems.

---

# 14. Data Quality and Validation

Poor data quality leads to unreliable AI systems.

Engineers implement validation checks.

Examples:

- schema validation
- range validation
- consistency checks

Example validation rule:

```

Age must be between 0 and 120

````

Ensuring data quality improves **model reliability**.

---

# 15. Numerical Computing Tools

Engineers use specialized tools to perform **large-scale numerical computations**.

Common libraries include:

### NumPy

Provides efficient numerical arrays and matrix operations.

Example:

```python
import numpy as np
matrix = np.array([[1,2],[3,4]])
````

### Pandas

Used for structured data analysis.

Example:

```python
import pandas as pd
data = pd.read_csv("dataset.csv")
```

These libraries enable efficient **data manipulation and analysis**.

---

# 16. Visualization and Analytical Reporting

Data visualization allows engineers to interpret patterns.

Common tools:

* Matplotlib
* Seaborn
* Plotly

Examples of visualizations:

* histograms
* scatter plots
* correlation heatmaps

Visualization helps engineers detect:

* anomalies
* relationships
* trends

---

# 17. Engineering Labs

Practical labs ensure students apply mathematical and data concepts.

### Lab 1 — Linear Algebra Operations

Students perform vector and matrix operations programmatically.

### Lab 2 — Statistical Analysis

Analyze datasets using statistical measures.

### Lab 3 — Data Cleaning Pipeline

Build scripts that clean and normalize datasets.

### Lab 4 — Data Visualization

Generate visual representations of datasets.

---

# 18. Applied Data Projects

Students complete practical data engineering projects.

### Project 1 — Data Analysis Platform

Build a program capable of:

* loading datasets
* performing statistical analysis
* generating reports

### Project 2 — Data Processing Pipeline

Develop a pipeline that:

* ingests raw data
* transforms datasets
* stores results in a database

### Project 3 — Feature Engineering System

Create a system that automatically transforms raw datasets into ML-ready features.

---

# 19. Competencies After Phase 3

Engineers completing Phase 3 possess the following capabilities.

### Mathematical Literacy

Ability to understand mathematical foundations behind machine learning.

### Data Analysis

Ability to interpret and analyze structured datasets.

### Data Engineering

Ability to design pipelines that ingest and process data.

### Numerical Computing

Ability to perform complex calculations using scientific computing libraries.

---

# Transition to Phase 4

After mastering computational systems, programming, and data analysis, engineers move to:

**Phase 4 — Machine Learning and Artificial Intelligence Engineering**

This phase introduces:

* machine learning algorithms
* neural networks
* model training
* model evaluation
* AI system deployment

