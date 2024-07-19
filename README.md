**ETL Pipeline for Data Transformation**
This project provides an ETL (Extract, Transform, Load) pipeline designed to process and transform data from multiple sources, including CSV, JSON, and XML files.

**Features**:
Extraction: Reads data from CSV, JSON, and XML files.
Transformation: Converts heights from inches to meters and weights from pounds to kilograms.
Loading: Saves the transformed data into a CSV file.
Logging: Tracks the progress of the ETL process with timestamped logs.

**Files**:
extract_from_csv(file_to_process): Extracts data from CSV files.
extract_from_json(file_to_process): Extracts data from JSON files.
extract_from_xml(file_to_process): Extracts data from XML files.
transform(data): Transforms height and weight units.
load_data(target_file, transformed_data): Saves the transformed data into a CSV file.
log_progress(message): Logs the progress of the ETL process.

**Usage:**
Place your CSV, JSON, and XML files in the same directory as the script.
Run the script. It will process the files and generate transformed_data.csv.
Check log_file.txt for progress updates and timestamps.
