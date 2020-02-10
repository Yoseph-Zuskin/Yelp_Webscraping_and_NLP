# Webscraping and Natural Language Processing to Classify Business Reviews on Yelp

This repository contains an IPython Notebook which was created by Yoseph Zuskin as part of the Data Acquisition Using APIs colloquium project for the Rotman School of Management's Master of Management Analytics program. The project involved using the Yelp API to retrieve the official IDs of Toronto businesses and using them to webscrape for full reviews. The webscraper was designed to reduce chances of being detected by slowing down the rate of visits to new pages and only selecting pages that are selectable from the first page which a real web visitor would be offered in teh botton of the webpage. A simple Naive Bayes classifier model was trained on reviews I managed to webscrape over two days. The results showed that the negative reviews were harder to classify, but the results from such a basic model are promising:

Accuracy: 0.8039314516129032

F-measure [negative]: 0.5900948366701791

F-measure [positive]: 0.8711493872143095

Precision [negative]: 0.6320541760722348

Precision [positive]: 0.8533419857235561

Recall [negative]: 0.5533596837944664

Recall [positive]: 0.8897158322056834
