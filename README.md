# Divtt

Divtt - Web Scraper

Brief Description:
Divtt is a powerful web scraper designed to extract emails, phone numbers, and links from any given URL. It offers the flexibility to save the extracted data in various user-selected formats. With the added feature of proxy support, Divtt ensures anonymity and efficient data retrieval. Additionally, it can decode encoded URLs, providing users with human-readable links.

Description:
Divtt simplifies web scraping by guiding users through the extraction process. It prompts the user for a target URL and allows them to specify whether to extract emails, phone numbers, or links. In cases where the user doesn't provide specific information, Divtt defaults to extracting all available data. The program then prompts for the desired output format and quantity. If no quantity is specified, Divtt extracts all possible data. The extracted data is saved in a dedicated folder at the location of the program, enhancing organization.

Installation:

NOTE: YOU NEED TO INSTALL THE GOOGLE DRIVE OF THE SAME OR COLSEST VER AND AFTER EXTRACT IT ADD THE PATH OF THAT IN THE GDRIVE VARIABLE

Before using Divtt, ensure you have Python and pip installed on your computer. If not, follow the steps below:

Install Python:

Visit Python's official website.
Download the latest version of Python for your operating system.
Run the installer and follow the on-screen instructions.
Install pip:

Check if pip is already installed by running the following command in the terminal:

pip --version

If not installed, download get-pip.py from https://bootstrap.pypa.io/get-pip.py.
Run the following command in the terminal to install pip:

python get-pip.py

Install Divtt dependencies:

Use the following command in the terminal to install the required packages for Divtt:

pip install requests random2 urllib3 beautifulsoup4 selenium Usage

Divtt's primary purpose is to extract phone numbers, email IDs, and links from a given URL. Users can customize the extraction process by specifying the type of data, output format, and quantity.

License:
Divtt is the solo creation of the author. The program is developed independently, leveraging the creator's skills and expertise
