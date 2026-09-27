# NumPy Student Marks Analysis

A Python script that creates a NumPy array of student marks and calculates key statistical values including the mean, median, maximum, minimum, and standard deviation.

## Description

This project demonstrates how to efficiently perform basic numerical and statistical analysis on student performance data using the NumPy library in Python. It fulfills the deliverables outlined in Task 11 of the AI & ML track.

## Features

- Creates a specialized numerical array containing mock student marks.
- Computes essential descriptive statistics:
  - **Mean:** The mathematical average of the class scores.
  - **Median:** The middle value of the sorted data set.
  - **Maximum:** The highest individual score recorded.
  - **Minimum:** The lowest individual score recorded.
  - **Standard Deviation:** The spread of marks relative to the average.
- Formats and prints the results clearly in the terminal output.

## Prerequisites

To run this script, you must have Python and NumPy installed on your system.

### Install NumPy

If you do not have NumPy installed, run the following command in your terminal:

```bash
pip install numpy
```

## Usage

1. Clone or download the script file named `student_marks.py`.
2. Open your terminal or VS Code terminal.
3. Run the script using the following command:

```bash
python student_marks.py
```

## Example Output

When executed, the script will output data in the following format:

```text
--- STUDENT MARKS ANALYSIS ---
Dataset (Marks): [85 90 78 92 88 65 95 82 74 89]

Mean (Average) Mark: 83.80
Median Mark:         86.5
Maximum Mark:        95
Minimum Mark:        65
Standard Deviation:  8.74
```