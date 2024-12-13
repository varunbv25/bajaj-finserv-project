## **Overview**
This project analyzes patient data to derive insights regarding missing values, gender distribution, age groups, and medicine prescriptions. The analysis is performed using a JSON dataset containing patient details and consultation data.

## **Files Included**
∘ data.ipynb: A Jupyter Notebook containing the code for analyzing the data.<br>
∘ DataEngineeringQ2.json: The JSON file with patient data used for analysis.

## **Features**
∘ The project includes various functions to perform the following analyses:
∘ Analyze Missing Values: Identifies and calculates the percentage of missing values in key fields such as first name, last name, and birth date.
∘ Calculate Female Percentage: Computes the percentage of female patients after imputing missing gender values.
∘ Analyze Age Groups: Categorizes patients into age groups (Child, Teen, Adult, Senior) based on their birth dates and calculates counts for each group.
∘ Analyze Medicine Count: Calculates the average number of medicines prescribed per consultation.
∘ Identify Third Most Prescribed Medicine: Determines the third most frequently prescribed medicine from the dataset.
∘ Analyze Medicine Status: Evaluates the active versus inactive status of prescribed medicines.
∘ Validate Indian Mobile Numbers: Checks the validity of Indian mobile numbers in the dataset.

## **Requirements**
To run this project, ensure you have the following installed:
∘ Python 3.x
∘ Pandas library
∘ Jupyter Notebook

## **Usage**
∘ Download or clone this repository to your local machine.
∘ Open data.ipynb in Jupyter Notebook.
∘ Run each cell sequentially to perform the analyses. Ensure that DataEngineeringQ2.json is in the same directory as data.ipynb.

## **Example Outputs**
∘ The notebook will output various statistics, including:
∘ Missing value counts and percentages for each field.
∘ Female percentage after imputing missing data.
∘ Counts of patients in different age groups.
∘ Average number of medicines prescribed.
∘ The third most prescribed medicine along with its count.
∘ Active and inactive medicine percentages.

## **Conclusion**
This project provides valuable insights into patient data management and can be expanded further to include additional analyses or visualizations as needed.
