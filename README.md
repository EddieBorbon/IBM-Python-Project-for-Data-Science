# Web Scraping Lab

## Lab Description

This lab is designed to introduce you to web scraping using Python and the Beautiful Soup library. The goal is to teach you how to extract and manipulate data from web pages by applying fundamental concepts and scraping techniques.

In this lab, you will learn to:
1. **Create and use Beautiful Soup objects** to parse HTML content.
2. **Navigate the HTML structure** using tags, attributes, and navigable strings.
3. **Apply filters** to search and extract specific data.
4. **Download and scrape web content** using Python.

## What I Learned

### Lab Objectives

- **Beautiful Soup Objects**: I learned how to create and use Beautiful Soup objects to efficiently parse HTML and XML content.
- **Tags**: I understood how to access and manipulate HTML tags, including extracting text and attributes from them.
- **HTML Navigation**: I learned to navigate the HTML structure using relationships between elements such as children, parents, and siblings.
- **HTML Attributes**: I practiced extracting and working with attributes of HTML tags to get additional information.
- **Navigable Strings**: I discovered how to handle the text contained within HTML tags and perform operations on these texts.
- **Data Filtering**: I used filters to search and extract specific data from a web page, facilitating the collection of relevant information.
- **`find_all` and `find` Methods**: I learned to use these methods to search for multiple or single instances of elements in the HTML.

### Downloading and Extracting Web Content

- **Using Requests**: Implemented the Requests library to download the content of a web page.
- **Parsing Content**: Used Beautiful Soup to analyze and extract data from the downloaded content.
- **Practical Example**: Performed basic scraping that involved finding and extracting paragraphs (`<p>`) from a web page, demonstrating how to obtain useful information programmatically.

## Installing Libraries

Some libraries may be pre-installed in your lab environment. If you need to install the following libraries, run the following commands:

```bash
pip install requests
pip install beautifulsoup4
