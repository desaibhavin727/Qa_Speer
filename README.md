# Qa_Speer

-The given Java script is a web crawler that starts from a given URL (START_URL) and visits pages in a breadth first manner until a given number of pages (MAX_PAGES_TO_VISIT) has been reached. For each page, the script will check if a given word (SEARCH_WORD) is present. If the word is found, the script will print a message to the console. If the word is not found, the script will collect all internal links present on the page and add them to a list of pages to visit (pagesToVisit). The script will then visit the next page in the list.

-This process will continue until either the SEARCH_WORD is found or the MAX_PAGES_TO_VISIT has been reached.One potential issue with this script is that it will continue to add pages to the list of pages to visit even if the SEARCH_WORD has already been found. This could lead to the script visiting more pages than necessary.

-Another potential issue is that the script does not keep track of which links have already been visited. This could lead to the script visiting the same page multiple times which would be wasteful. Overall, this script is a simple web crawler that could be used to crawl a website and check for the presence of a given word. However, it is not very efficient and could be improved.
