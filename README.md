# Pandora's Programmers @ SGX3-Hackathon-Project-2024

## Pandora's Programmers

### Mentor
**Charlie Dey**       
Texas Advanced Computing Center

### Team members
**Christian Henry**   

GitHub Lead 

Winston-Salem State University

**Catalina Tovar** 

Presentation Lead

Jackson State Univeristy

**LeahMonet Morgan**  

Poster Lead

Southern University A & M College

**Jesutofarati Ajala**   

Code Lead

University of Southern Mississippi

## Event Info
[SGX3 ADMI24 Hackathon](https://hackhpc.github.io/sgx3admi24/)


## Project Description

Our goal was to develop a form that validates the input and processes the site data for storage and further analysis, allows users to input a site URL, and then ingests and adds to the HPC-ED (High-Performance Computing and Engineering Data) database. 

### Project Goals

We wanted to develop a user-friendly form for URL input, implement functionality to ingest and process the site data wuile ensuring the input URL is valid and accessible. Then we store the processed data in the HPC-ED database and enable further analysis of the data.

### Features

A few features of our project:

User-Friendly Form: A simple and intuitive form for users to input site URLs.

URL Validation: Ensures that only valid and accessible URLs are accepted.

Data Processing: Automated data extraction and processing from the provided URLs.

Database Integration: Efficient storage of processed data in the HPC-ED database.

Logging: Detailed logging of the ingestion process for monitoring and debugging.

The HTML code creates a simple form for adding website information to the HPC-ED database which includes fields for URL, title, description, and category, and uses CSS for styling. Ultimately,we designed the form to be as user-friendly and visually appealing as possible within the period of time we were given. The Python code reads a JSON file (hpced-all.json) containing metadata about various entries and constructs a graph using the NetworkX library. Each entry with a title is added as a node in the graph, with the title serving as the node identifier and the rest of the entry's content as node attributes.
