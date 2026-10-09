# Medical Appointment No-Show Analysis

An exploratory analysis of 110,527 medical appointments in Brazil, examining how attendance varies with age, recorded SMS status, and the number of calendar days between booking and the appointment.

Completed as the Investigate a Dataset project in the Udacity Data Analyst Nanodegree content used for WGU D496 — Introduction to Data Science.

## Research Questions

- How does the appointment no-show rate vary across patient age groups?
- How does the no-show rate differ between recorded SMS categories?
- How does the no-show rate vary with waiting time?

The outcome variable is appointment attendance. The three explanatory variables are age, recorded SMS status, and waiting time.

## Tools

- Python
- pandas and NumPy for data inspection, cleaning, and summaries
- matplotlib for visualizations
- Jupyter Notebook for code, outputs, and written findings

## Dataset

The original dataset contains 110,527 rows and 14 columns. Each row represents an appointment, and a patient may have multiple appointments.

The original No-show column uses "Yes" for a missed appointment and "No" for an attended appointment.


## Project Files

- Investigate_a_Dataset.ipynb -- Analysis code, saved outputs, visualizations, and narrative
- Investigate_a_Dataset.html -- Exported HTML report
- noshowappointments-kagglev2-may-2016.csv -- Dataset
- README.md 

## Run the Analysis

1. Download the notebook and dataset.
2. Place noshowappointments-kagglev2-may-2016.csv in the same folder as the notebook.
3. Install the required packages: python -m pip install pandas numpy matplotlib notebook
4. From that folder, launch the notebook: jupyter notebook Investigate_a_Dataset.ipynb
5. Restart the kernel and run the analysis cells from top to bottom.
