# 4SF25CI113_3A

Kaggle Flight Delay Data Set
-----------------------------------------------------------

# Install dependencies as needed:
# pip install kagglehub[pandas-datasets]
import kagglehub
from kagglehub import KaggleDatasetAdapter

# Set the path to the file you'd like to load
file_path = ""

# Load the latest version
df = kagglehub.load_dataset(
  KaggleDatasetAdapter.PANDAS,
  "hrishitpatil/flight-data-2024",
  file_path,
  # Provide any additional arguments like 
  # sql_query or pandas_kwargs. See the 
  # documenation for more information:
  # https://github.com/Kaggle/kagglehub/blob/main/README.md#kaggledatasetadapterpandas
)

print("First 5 records:", df.head())

-----------------------------------------------------------------------

Overview of Data Transformation, Null Value Handling, Insight Generation, and Visualization of Flight Delay Data Set
->Analyzea a CSV dataset using Python and Pandas, performed the data transformations ,
handled null values using mean imputation, generated meaningful insights, and visualize the findings.

->Downloaded a relevant dataset in CSV format.
->Read the CSV file using Pandas.
->Studied the dataset and understand its structure and contents.
->Performed the required transformations, such as changing data types, dropping unnecessary columns, or adding new columns.
->Identified null values in the dataset.
->Handled null values using mean imputation wherever applicable.
->Generated meaningful insights from the dataset , Flight delay Analysis , Flight Analysis
->Visualized and generated insights using appropriate charts.



