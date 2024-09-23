
# VulScrapper
VulScrapper is a Python-based web scraping tool that collects vulnerability data from web pages. It stores the extracted information in a database file and provides a user-friendly Streamlit web application for data visualization and reporting. It is integrated with an automatic alert system and an AI-powered feature for suggesting mitigation strategies automatically.










## Deployment

To deploy this application locally, follow these steps:

#### Clone this repository
```bash
     git clone https://github.com/FATEH02/VulScrapper.git
     cd VulScrapper
```
#### Install requirements

```bash
    pip install -r requirements.txt
```
#### run god_scrapper.py
```bash
    python3 god_scrapper.py
```
This tool uses Selenium to scrape websites and BeautifulSoup for parsing the HTML content. The scraped data is stored in a CSV file using Python's csv module, and Pandas is used for managing and analyzing the dataset
#### run stream.py
```bash
    streamlit run stream.py
```
### This script creates a web application using Streamlit 
#### a csv database show that will show a list of all vulnarebilities colums like
|ProductName|Version|OEM|SeverityLevel|Vulnerability|MitigationStrategy|PublishedDate|UniqueID|
|:--|---|---|---|---|---|--|--|

##### screenshot
![App Screenshot](https://github.com/FATEH02/VulScrapper/blob/main/images/csvdatabase.png)

## Filters
![App Screenshot](https://github.com/FATEH02/VulScrapper/blob/main/images/filterpannel.png)

##  Detail of Vulnerability
![App Screenshot](https://github.com/FATEH02/VulScrapper/blob/main/images/specificdetail.png)

## Email Send
![App Screenshot](https://github.com/FATEH02/VulScrapper/blob/main/images/email%20send.png)

## Genrative Explaination
![App Screenshot](https://github.com/FATEH02/VulScrapper/blob/main/images/genratedbyai.png)

## visualize scraped data
![App Screenshot](https://github.com/FATEH02/VulScrapper/blob/main/images/visualization.png)



## Features

- generative ai interaction
- smooth conversation
- firebase intigration
- flow and coroutines


## Screenshots

![App Screenshot](https://github.com/FATEH02/AI-messaging-app/blob/master/git.png)
![App Screenshot](https://github.com/FATEH02/AI-messaging-app/blob/master/git2.png)


## API Reference

#### Get all items

```http
  GET /api/items
```

| AI | Model     | Description                |
| :-------- | :------- | :------------------------- |
| `Gemini` | `Gemini-1,5-flash` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| BAAS | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `firebase`      | `cloud` | **Required**. use firebase|


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`API_KEY`
`implementation(libs.hilt.android)`
`ksp(libs.hilt.android.compiler)`
`implementation ("io.coil-kt:coil-compose:2.4.0")`
`implementation ("androidx.hilt:hilt-navigation-compose:1.0.0")`
`implementation("com.google.ai.client.generativeai:generativeai:0.1.2")`




## FAQ

#### i want to collabrate with you 

sure i am ready just email me 

#### recommended collabration topic

AI

