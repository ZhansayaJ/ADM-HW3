# ADM Homework 3

### This is the repository dedicated to Homework 3 for ADM course. 
#### Group 31 - Zhansaya Jumasheva.

- [__`main.ipynb`__]( ): - contains answers to Questions 1 and 2

  # Project Description

This Python project focuses on building a search engine for master's degree courses by collecting data from various university websites, preprocessing the information, and implementing conjunctive queries based on course descriptions.

## Data Collection

### 1.1 Get the List of Master's Degree Courses
- Web scrape MSc degrees from university websites.
- Collect URLs associated with each course from the first 400 pages, resulting in 6000 unique URLs.
- Save the URLs in a .txt file.

### 1.2 Crawl Master's Degree Pages
- Download HTML for each collected URL.
- Save HTML pages immediately to avoid data loss.
- Organize HTML pages into folders based on page numbers.

### 1.3 Parse Downloaded Pages
- Extract specific information from HTML documents, including course name, university, faculty, full or part-time status, description, start date, fees, modality, duration, city, country, administration mode, and URL.

## Preprocessing

### 2.0 Text Preprocessing
- Remove stopwords, punctuation, and perform stemming on all collected information using the NLTK library.

### 2.0.1 Preprocessing the Fees Column
- Extract numeric information from the fees column using methods such as regex.
- Convert fees to a common currency (USD, EUR, etc.) using an appropriate API.

## Conjunctive Query

### 2.1 Create Your Index
- Create a vocabulary file mapping each word to a term_id.
- Build an Inverted Index dictionary.

## Conclusion

This project aims to develop a search engine capable of retrieving relevant master's degree courses based on user queries. By collecting, preprocessing, and indexing data, the search engine enables efficient and accurate retrieval of information from a vast corpus of university websites.
