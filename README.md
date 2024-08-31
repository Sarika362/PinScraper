# Pinterest Web Scraping 📌

## Overview 🌟
This project utilizes web scraping techniques to gather valuable insights from Pinterest. It focuses on extracting image data and pin details for analysis and application in various domains. The project includes two main scripts:

1. **Pinterest Pin Data Retrieval Script**: Extracts image URLs and alt text from Pinterest pins.
2. **Pinterest Image Scraping Class**: Searches Pinterest for images based on a keyword and saves them locally.

## Features 🚀

- **Pinterest Pin Data Retrieval**: Extracts and saves pin details like image URLs and alt text.
- **Image Scraping**: Searches Pinterest based on a keyword, downloads images, and ensures uniqueness by using image hashing.

## Getting Started 🚀

### Prerequisites 🛠️
Make sure you have the following installed:
- Python 3.x
- Edge WebDriver (handled by `webdriver_manager` in the script)
- Required Python libraries

### Installation 📥

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/Sarika362/Pinterest-Web-Scraping.git
    cd pinterest-web-scraping
    ```

2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

### Usage 📝

#### Pinterest Pin Data Retrieval Script

1. **Run the Script**:
    ```bash
    python pinterest_pin_data_retrieval.py
    ```

2. **Enter the Pinterest Username**:
    ```
    Enter the Pinterest username: MariMoon
    ```

3. **Output**:
    The script will save pin details to a CSV file named `<username>_pins.csv`.

#### Pinterest Image Scraping Class

1. **Run the Script**:
    ```bash
    python pinterest_image_scraping.py
    ```

2. **Enter the Search Keyword**:
    ```
    Enter the keyword for searching images: nature
    ```

3. **Output**:
    The script will download images related to the keyword into a folder named `<keyword>`.

## Dataset 📚

- **Pinterest Pin Data Retrieval Script**: The dataset consists of Pinterest images and their metadata.
- **Pinterest Image Scraping Class**: Searches for and downloads images related to specified keywords.

## Model Architecture 🏗️

- **Pinterest Pin Data Retrieval Script**: Uses Selenium to scrape image URLs and alt text.
- **Pinterest Image Scraping Class**: Uses requests and BeautifulSoup for scraping, and OpenCV for image processing and uniqueness checking.

## Results 📊

- Successfully retrieves and saves Pinterest pin data.
- Downloads images related to user-defined keywords and ensures that they are unique.

## Example Output 🖼️

- **Pinterest Pin Data Retrieval Script**: 
  - Saved file: `MariMoon_pins.csv`
  
- **Pinterest Image Scraping Class**: 
  - Folder with images: `nature/`

## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements 🙏

- The dataset is provided by Pinterest.
- Selenium, requests, BeautifulSoup, OpenCV, and other libraries are used in this project.
