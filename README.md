# Divtt-Web_Scraper

## Description
Divtt is a powerful web scraping tool built in Python. It's designed to extract phone numbers, images, and potentially emails from websites. This tool can be particularly useful for gathering data to train machine learning models, especially for image classification tasks.

## Features
- Extracts phone numbers from web pages
- Downloads images from specified websites
- Customizable number of items to extract
- Saves extracted data in a user-specified folder
- Flexible output format (e.g., txt, csv)

## Technologies Used
- Python
- Requests library
- Regular Expressions (re)
- BeautifulSoup4
- urllib

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/DivyanshTiwari20/Divtt.git
   ```
   Or download the ZIP file from the [GitHub repository](https://github.com/DivyanshTiwari20/Divtt.git).

2. Install the required dependencies:
   ```
   pip install requests beautifulsoup4
   ```

## Usage
To use Divtt, follow these steps:

1. Run the script.
2. Enter the URL of the site you want to scrape when prompted.
3. Specify the number of phone numbers and images you want to extract. Press Enter without a number to extract all available images.
4. Provide a name for the folder where downloaded files should be saved.
5. Specify the desired file extension for saving data (e.g., txt, csv).

## Example
```
python divtt.py
Enter the URL to scrape: https://example.com
Number of phone numbers to extract (press Enter for all): 10
Number of images to download (press Enter for all): 
Folder name for downloads: example_data
File extension for saving data: txt
```

## Target Audience
Divtt can be used by anyone interested in web scraping, particularly:
- Data scientists and machine learning engineers gathering training data
- Researchers collecting web data
- Developers learning about web scraping techniques

## System Requirements
Divtt is designed to run on any system with Python installed. It doesn't require high-end hardware.

## Contribution
Feedback and contributions are welcome. Please feel free to submit issues or pull requests to the GitHub repository.

## Disclaimer
Ensure you have the right to scrape content from websites before using this tool. Always respect robots.txt files and website terms of service.

## Future Updates
I am open to feedback and plans to update the tool in the future. Stay tuned for new features and improvements!
