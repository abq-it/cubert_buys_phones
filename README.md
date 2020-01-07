# cubert_buys_phones
Price generator for chat bot.

Uses the python modules lxml, and requests. 
Download using the following commands:
pip install lxml
pip install requests 

Run app using the following command:
python MainApp.py

To add an item to be tracked edit Qscraper.py.
Inside the ScrapeHandler class's init function there is a class dictionary phones.
Each dictionary entry should look like the following:

self.phones = {
  'BrandName_version_storage_carrier' : 'static url address to the items eBay search',
  <next entry>
}
  
Good Luck!

-ABQ-recycling
