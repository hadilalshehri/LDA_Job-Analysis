# Job Mining Project in Sauid Arabia

This project aims to analyze and mine job postings from linkedIn Platform and provide insights into the Saudi job market trends and requirements. The project will use web scraping and data mining techniques to extract relevant information from job postings, such as job titles, descriptions, company, job Date, and locattion, and analyze them to identify common patterns and trends.

## Getting Started

To get started with this project, you will need to have Python 3 installed on your computer or you can use Google colab 

You will also need to install the following Python libraries:

- BeautifulSoup
- Selenium
- NLTK
- Matplotlib
- Pandas

You can install these libraries using pip, as follows:

```
pip install beautifulsoup4
pip install selenium
pip install nltk
pip install matplotlib
pip install pandas
```
In addtiotn to the requirment you need chrome drivire on Job posting code and  uplaud the location places file for Mining the location.
for Saudi Arabia the location is installed on the ' LDA code/ sau_places' folder 

Once you have installed the required libraries and files, you can run the several code will be descibe on Project Structer section. 

job mining application by running the `main.py` file. The application will prompt you to enter a job title and location, and it will then scrape job postings from various websites and provide insights into the job market trends and requirements.

## Project Structure

The project is structured as follows:

- `web_scraping` - This Folder contains code for scraping job postings from linkedIN.
- 'scrab.ipynp' -  This code can scrabe the jobe posting from linkedIn you need to provide the username, Password and job search link from linkedIn.
- `scrabweb.ipynp` - This code is same as 'scrab.ipnyp' but it more accurate but it take long time oon processing. It access the job one be one. 
- `LDA Code` - This Folder contains LDA Job Mining code for two Major.
- `LDA_Job_Search_Data` - This code will analyze and Mine ' Data Science'  Job
- `LDA_Job_Search_SF` - This code will analyze and Mine ' Software Engineer'  Job
- 
## Contributing

Contributions to this project are welcome. If you would like to contribute, please fork the project and submit a pull request with your changes.


