# weather_app

This is a simple CLI application that uses Python's pandas and argparse libraries to iterate over a given number of files and generate reports.

## Directory Structure

- `raw_data`: Contains the data of weather from 2004-2016 for a local hill station murree.
- `file_mover`: Moves/unzips files from any directory specified by the user to the `raw_data` directory.
- `data_formatter`: Converts the raw data into pandas dataframes which are later used.
- `weather_calculations`: Contains models that perform all calculations specified by the task.
- `report_generator`: Forms reports in the format specified by the task.
- `weatherman`: This is the main app which has the code for the CLI.

## Setup Instructions

1. Clone the directory on your system.
2. Install pandas and argparse into your virtual environment.
3. Go to the root directory of the project.
4. Run the project from the terminal using the following command (This is just one example to illustrate the format):
   ```bash
   python weatherman.py <path_to_the_directory_where_your_files_are> -c <YEAR>/<MONTH>
                                                     
5. If there is any confusion typein the terminal:
   ```bash
                               python weatherman.py --help or -h
   
![Different Options](https://github.com/12Danish/Pandas_data_analysis_weather_app/raw/master/sample_images/instructions.jpg)

6. Bonus task:
   ```bash
                               python weatherman.py <path_to_the_directory_where_your_files_are> -b <YEAR>/<MONTH>

![Bonus Task](https://github.com/12Danish/Pandas_data_analysis_weather_app/raw/master/sample_images/bonus%20task.jpg)

   
7. First two tasks. Yearly/monthly reports:
  ```bash
                               python weatherman.py <path_to_the_directory_where_your_files_are> -e <YEAR>
  ```bash
                               python weatherman.py <path_to_the_directory_where_your_files_are> -a <YEAR>/<MONTH>


![Highest-Lowest](https://github.com/12Danish/Pandas_data_analysis_weather_app/raw/master/sample_images/highest-lowest.jpg)
                                                    
8. Third Task. Day-wise report:

  ```bash
                               python weatherman.py <path_to_the_directory_where_your_files_are> -c <YEAR>/<MONTH>


![Everyday Report](https://github.com/12Danish/Pandas_data_analysis_weather_app/raw/master/sample_images/everyday%20report.jpg)

## Learning:

Through this project, I gained a deep understanding of how to extract useful information from data using tools like pandas. This experience enhanced my knowledge of pandas DataFrames and equipped me with the skills to manipulate and analyze data effectively to obtain the desired results.
