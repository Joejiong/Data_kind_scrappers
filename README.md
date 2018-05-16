# Data_kind_scrappers

data kind is a volunteer organization

ROLE: EA Web Scraper

DataKind DataJam
Effective Altruism
Data Acquisition (Charities in SE Asia)

the word file https://docs.google.com/document/d/1s6jSXTJkGm6w46uGjHacL04tHAPtxc04RB_biwFwfqY/edit

Short url of this document: https://tinyurl.com/eajam20180110 

DataJam Guide Steps:
Log-in to EA-DKSG Trello: https://trello.com/b/XMGw6Uzb/ea-sg-x-dksg
Choose 1 Weblink work on from this link: https://tinyurl.com/ea-charities 
Choose only a Weblink which has the status of either Taken or Open 
If you intend to work on a Weblink which is already Taken, click on its corresponding Trello link to find the current volunteer/s working on it.
You may do one of the following:
Ask the existing card members if you can join 
If all’s good, add your name accordingly in the card and start contributing (ask the existing members where you can contribute)
Choose another Weblink from Step 2
If you’ve chosen a Weblink with an Open status, please do the following:
Update the status of the website to Taken.
Add a new card under the “DataJam Tasklist” in trello.
		
Use the following format for the card name:
 	Create Org Info CSV File from <Shortname of your Datasource>
	

In the card, add the corresponding label (choose one):


Add yourself to the card
	
Edit the description and add the following description template:
	
Datasource:
Scriptfiles used to scrape:
Filename of Org Info CSV File:

	Here’s an example:
	
	
	You may add the “Scriptfiles used to scrape” 
and “Filename of Org Info CSV File” info later 
once you have attached those files to the card.

Copy the Trello link of your task card


Update the Trello link field of your chosen Weblink


Once you have a card, your goal is to eventually create a CSV file containing the orgs scraped from your data source. 
Here are some guidelines: 
CSV header fieldnames need to exist from the following list:
https://tinyurl.com/fieldnames 
If there’s a field you want to capture that is not existing yet, add it to the list along with the description.
Fieldnames are in lowercase underscore separated format (e.g. cause_area)
Don’t worry on the standardization of org field values for now (e.g. cause_area: child vs children vs kids). We’ll have another round of cleanup for those. First goal is to capture scraped data. Clean later. 
This is to help facilitate when combining the CSV files later.
Have only one org per observation (row)
You may use several scripts (one to scrape data from the site, and another one to transform the scraped data into the expected CSV output with the expected fieldnames)
Scraping Techniques: You may refer to the following cards for scraping approaches/tips (discussed from previous datajam):
Map Scraping Discussion: https://trello.com/c/SBBuqZYk/4-try-google-maps-open-street-maps 
Website Scraping Discussion: https://trello.com/c/rbKhJ2rx/9-what-techniques-could-be-useful 

If the card is done, you may move the card to the “Done” list.
	Done means:
Expected output (Org Info CSV File) is attached to the card
All scripts used to extract, transform, and eventually generate the CSV file are attached to the card.
Card description is updated accordingly
Status of Weblink is updated to Complete in https://tinyurl.com/ea-charities 
	


