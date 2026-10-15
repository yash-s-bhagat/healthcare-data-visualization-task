# healthcare-data-visualization-task
Healthcare Data Visualization

Internship: VirtualWorks-Lab — Data Analytics (Healthcare/Pharmacy)
Task ID: task2

Objective

Create visual representations of a cleaned healthcare dataset to explore disease distribution, age distribution, gender ratio, and medication usage.

Dataset

The project uses a synthetic dataset of 30 patient records containing patient ID, age, gender, disease, medication, and dosage. It contains no real patient information.

Tools Used

- Python
- Pandas
- Matplotlib
- CSV

Visualizations

1. Disease distribution — patient counts by disease.
2. Age distribution — histogram of patient ages.
3. Gender distribution — pie chart showing the gender ratio.
4. Medication usage — bar chart showing medication frequency.

Project Structure

- "data/healthcare_data_cleaned.csv" — cleaned healthcare dataset.
- "src/visualize_healthcare_data.py" — visualization script.
- "outputs/disease_distribution.png" — disease chart.
- "outputs/age_distribution.png" — age histogram.
- "outputs/gender_distribution.png" — gender pie chart.
- "outputs/medication_usage.png" — medication chart.
- "outputs/summary_metrics.csv" — overall summary.
- "outputs/disease_counts.csv" — disease counts.
- "outputs/gender_counts.csv" — gender counts.
- "outputs/medication_counts.csv" — medication counts.
- "requirements.txt" — required Python libraries.

How to Run

Install the required libraries:

pip install -r requirements.txt

Run the visualization script:

python src/visualize_healthcare_data.py

The script generates the charts and CSV summaries inside the "outputs/" folder.

Key Findings

- Total patient records: 30
- Unique patient IDs: 30
- Average age: 43.9 years
- Disease categories: 5
- Medication categories: 5

Flu and diabetes are the most frequent disease categories in this sample, with 7 records each. Paracetamol and metformin are the most frequently listed medications, with 7 records each.

Conclusion

This project demonstrates how healthcare data can be transformed into visual insights to understand disease frequency, patient age distribution, gender ratio, and medication usage.

Privacy and Limitations

This is an educational exercise using synthetic data. The charts are not medical evidence and must not be used for clinical decision-making.