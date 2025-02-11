# Fetch Assessment

This project is designed to retrieve data from a specified JSON, organize, quality check and email stakeholders

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/vidyun-ai/Fetch_assessment.git
   cd Fetch_assessment
   ```

2. **Set Up the Environment**:
   - Ensure you have [Python 3.7.3](https://www.python.org/downloads/release/python-373/) installed.
   - Install the required packages:
     ```bash
     pip install -r requirements.txt
     ```

## Usage

1. **Run the Application**:
   The application contains .ipynb file which can run on Google colab with data
   In order 

3. **Functionality**:
   - The application retrieves data from the specified JSON URL.
   - It processes the data to group items by `listId` and sorts them by `name`.
   - Items with blank or null `name` values are excluded from the display.

## Testing

To ensure the application works as expected:

1. **Scroll Through the List**: Navigate through the entire list to verify all items are displayed correctly.
2. **Reverse the List**: If applicable, use the provided functionality to reverse the list order and ensure it displays correctly.
3. **Search Functionality**: Test the search feature by searching for specific `name` or `listId` values to confirm accurate filtering.

## About

This project was developed as part of the Fetch Assessment for Software Engineer (Mobile) Apprenticeship.

