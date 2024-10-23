# DS_346_Final_HI
All files needed to run our group project. 

^Arlo  Steyn 24713848
^Stephan Delport 24710083
^Andre van der Merwe 24923273

For Scraping and Wrangling the data (Unnecessary, the data is here):
-- cd CVScraperAndWrandler
-- python3 scraper.py           #When 5000 data points are scraped...these files are sent to a json file.
-- python3 wrangler.py          #Uses these json files to wrangle and preprocess the data.

To use any of our models please use Kaggles online notebook. Activate Internet and use the T4 Tesla GPU.
For input, add the processed_data.json file in the CVScraperAndWrandler/wrangled_data/ folder, IFF you want to train.

Then add the model you want to test or train.

For Training, run either the 1_EpochCBB.ipynb file or the chatnbietjiebol10k.ipynb file. (TRaining is already done and unnecessary...all files needed are here)

For testing and using the trained models, run the chatcbbinference.ipynb script. 
Again ensure that the model you want is uploaded from the Models/ folder into kaggle.

in the chatcbbinference.ipynb, for prompts, change the 'prompt' variable for the prompt you want to use.