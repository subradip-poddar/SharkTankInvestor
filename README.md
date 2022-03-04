# SharkTankInvestor
This is the data scrapped of all the pitches made up potential startup's to established bussiness tycoons of India with all the details of Investments made, equity share, Name of investor etc.
Procedure: -

The Site had a table with all the investor details.

Firstly, I took remote control of the website to automate the process of scrapping using selenium.Then I extracted the page source.

Then Extracted the table using select command of the BeautifulSoup module.

After this, I defined a function where I extracted tablehead, rows and details of the table and then converted it to a DataFrame

Finally,converted the DataFrame to a .csv file.
