# HUDOC-Analysis
Download and search HUDOC documents to create case law overviews

## Running HUDOC Analysis
For Windows and Linux, you can use the pre-built executables. To run from source, install python 3.7+ and pip. Then, in the source directory, run "pip install -r requirements.txt". After the installation finishes, you can run the tool with "python hudoc_analysis.py".

## Create sets
Download documents from HUDOC filtered by timespan, doctype, language, respondent. You can also include links to Strasbourg Observer posts mentioning each downloaded document. For english judgments and decisions, the tool allows filtering out parties' submissions for a better overview (experimental). Document metadata and text is stored in an SQLite 3 file for each set and can be easily exchanged or used for analysis. Set merging is possible for better customization of datasets.

## Perform keyword and regex search on sets
In a second step, you can define headers for topics you are interested in and keywords and regex queries for each header. The tool searches the documents in your set and structures matches by article and header. You can analyze the documents in the tool's own metadata view or export to .docx. To create meaningful overviews, you cann approve or disapprove each document returned by your keyword/regex search, resulting in a list of hand picked documents you consider helpful in your research.

## Feedback and bug reports
The tool is under active developtment. Feedback and bug reports are greatly appreciated, ideally on LinkedIn (https://www.linkedin.com/in/jan-nicklaus/) or via email (jfnicklaus@gmail.com). Thank you for trying HUDOC analysis!
