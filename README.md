# Schedule Generator (SUPER TTS)

## Description

This project, SUPER TTS (Super Timetable Scheduler), is a Python-based tool designed to generate and manage university course schedules. It creates all possible schedule combinations based on a given list of classes and provides various filtering and output options.

## Features

- Generate all possible schedule combinations
- Apply filters to schedules:
  - Free days filter
  - End time filter
  - Professor filter
- Order schedules by subject days
- Export schedules to Excel

## Requirements

- Python 3.x
- openpyxl library

## Installation

1. Clone this repository or download the source code.
2. Install the required library:

```
pip install openpyxl
```

## Usage

1. Run the script:

```
python schedule_generator.py
```

2. Follow the on-screen menu to interact with the program:

   - Calculate all schedules
   - Set filters
   - Output to Excel
   - Order schedules by subject days

3. Use the filtering options to narrow down the schedules based on your preferences.

4. Export the final schedules to an Excel file for easy viewing and further analysis.

## Customization

To customize the classes and course information, modify the `aulas` dictionary in the script. Each course should have a list of possible class times and associated information.

## Contributing

Feel free to fork this repository and submit pull requests with any improvements or bug fixes.

## License

This project is open-source and available under the MIT License.