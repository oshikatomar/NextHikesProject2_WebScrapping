Web scraping, web harvesting, or web data extraction is data scraping used for extracting data from websites.
Web scraping software may directly access the World Wide Web using the Hypertext Transfer Protocol or a web browser.
While web scraping can be done manually by a software user, the term typically refers to automated processes implemented using a bot or web crawler.
It is a form of copying in which specific data is gathered and copied from the web, typically into a central local database or spreadsheet,
for later retrieval or analysis.

Scraping a web page involves fetching it and extracting from it. 
Fetching is the downloading of a page (which a browser does when a user views a page). 
Therefore, web crawling is a main component of web scraping, to fetch pages for later processing. Once fetched, extraction can take place.
The content of a page may be parsed, searched and reformatted, and its data copied into a spreadsheet or loaded into a database. 

def word_frequencies(words):
# Implement the word_frequencies function.  The words function parameter is a string.
# Your solution here
    freq = {}
    for word in words:
        freq[word] = words.count(word)
    return freq

# The main program.  Do not change it.
if __name__ == '__main__':
    words = input("Enter a sentence: ")
    your_dictionary = word_frequencies(words)
    sorted_keys = sorted(your_dictionary.keys())
    for key in sorted_keys:
        print(key + ': ' + str(your_dictionary[key]))
