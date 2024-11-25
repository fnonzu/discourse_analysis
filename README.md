## Discourse analysis support scripts

For the sake of media discourse analysis article writing the following scripts were used:

1. savewebpage2.py this script takes your url to the article, output folder and selectors that are corresponding to the html page. This script happed to not be that versitile in usage, so I used other software which works with API called grabzit. It can save the web pages quite in the nice word format. So furhter updates  to the script are needed to perform in the same way.

2. scrape_google_image.ipynb this script works in a semi-authomated manner. The input here is the MaxQDA generated metadata on coded images in word format. The script extracts the images we are interested in and places it in a folder structed with metadata in xlsx format. Then it will perform the visual search via Google lens using the scraper selenium. After you have a time to imput some observations on the image search and it will save this data to a metadata exsel table. You end up with a nice table for later analysis without a need to open each image separately and organize the table.

3. filter MAXDA codes.ipynb script performs analysis of existing codes in MaxQDA with filtering the output file from MaxqDA. It helped us to access the spatial distribution of the codes in the articles.
