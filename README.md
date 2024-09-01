# Critical Heat Flux Prediction using 2006 Groeneveld Look-up Tables (NUREG)

## Project Overview

This project aims to predict Critical Heat Flux (CHF) in dynamic scenarios using a dataset derived from steady-state experiments. The data used in this project is sourced from the United States Nuclear Regulatory Commission (U.S. NRC) library, titled "Critical Heat Flux Data Used to Generate the 2006 Groeneveld Lookup Tables (NUREG/KM-0011)".

## Dataset

The dataset includes 7 key parameters:
- **Tube Diameter (D)**
- **Heating Length (L)**
- **Pressure (P)**
- **Mass Flux (G)**
- **Critical Quality (X<sub>chf</sub>)**
- **Inlet Subcooling (Δh<sub>in</sub>)**
- **Inlet Temperature (T<sub>in</sub>)**

## AI/ML Model Architecture

The project utilizes several regression models to predict CHF:
- **Random Forest**
- **Gradient Boosting**
- **Support Vector Machines**
- **Neural Networks** (built using TensorFlow and Keras)

## Tools and Technologies

The following tools and technologies are used in the project:
- **Numpy**: For numerical computations
- **Pandas**: For data manipulation and analysis
- **Matplotlib** and **Seaborn**: For data visualization
- **Scikit-learn**: For implementing machine learning algorithms
- **Keras** and **TensorFlow**: For building and training deep learning models
