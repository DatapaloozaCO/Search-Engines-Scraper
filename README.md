# 🚀 Enhanced Search Engines Library

Welcome to the enhanced version of the Search Engines library – a powerful Python tool for querying popular search engines such as Google, Bing, Yahoo, and more! 🌐

## Features

- **Multi-Engine Support:** Query Google, Bing, Yahoo, DuckDuckGo, Startpage, Aol, Dogpile, Ask, Mojeek, Brave, and even the Dark Web with Torch!
- **Output Flexibility:** Easily generate output files in HTML, CSV, or JSON formats.
- **Search Filters:** Refine your results using filters for URL, title, and text.
- **Proxy Support:** Execute searches through HTTP and SOCKS proxies for enhanced privacy and control.
- **Extensibility:** Effortlessly add new search engines by creating custom classes. Just subclass the `SearchEngine` and override a few methods.
- **Python Compatibility:** Works seamlessly with both Python 2.7 and Python 3.x.
- **Easy Installation:** Install the library with a single command: `$ pip install enhanced-search-engines`.

## Requirements

Ensure you have Python 2.7 - 3.x installed, along with the following dependencies:
- [Requests](http://docs.python-requests.org/en/master/)
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

## Installation

Install the enhanced library using:
```bash
$ pip install enhanced-search-engines
```

## Usage

### As a Library:

```python
from enhanced_search_engines import Google

engine = Google()
results = engine.search("my query")
links = results.links()

print(links)
```

### As a CLI Script:

```bash
$ enhanced-search -e google,bing -q "my query" -o json,print
```

## Project History
This project was originally developed by a talented group of contributors:

@tasos-py - Tasos M Adamopoulos
@nikolasj5 - Nikolas Makiya Vichi
@csecht - Craig Echt
@hnrkcode - Hnrkcode

## Forked Project

This fork exists because the original project seems inactive. We're dedicated to enhancing the library by incorporating new features and improvements. Notable additions include the ability to pass proxy information for search queries. Join us in making this tool even more robust and versatile!

Feel free to explore the [repository](https://github.com/yourusername/enhanced-search-engines) for the latest updates and contribute to the project. Let's supercharge our searching capabilities together! 🚀✨
