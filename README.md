# property-webscraper

## How to install (macOS)

1. Clone this repository/folder to your local directory. Take note of where it is saved
2. Open Terminal
3. Use this command to move to your folder `cd <file location>`. For example, if it is saved in `Downloads`, the command should be `cd ~/Downloads/property-webscraper`
4. Run `pip install -r requirements.txt`

## How to use
1. Run the script with `python propguru_webscraper`
2. Paste the property guru link of the listing you would like the script to compile details from
3. The script will gather details for you and write it into a file named `property_scrape_results.csv`
4. The script will prompt you for another link - paste another link if you have one, and repeat until all links have been pasted.
5. Once done, press `Ctrl + C` to stop the script
6. You can then pass import the .csv file into an Excel sheet or Google Sheets
