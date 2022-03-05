# Mission-to-Mars
Web scraping online data to create a web application using Flask, Python, and MongoDB.

## Overview of the Project
Robin has a goal to one day work for NASA.  She has a huge interest in Mars and has decided to develop a web page that she called **Mission to Mars** that would *scrape* data and images from various websites.  In the process she would:

  * Use Chrome Developer Tools to identify HTML components
  * Use BeautifulSoup and Splinter to automate the scrape
  * Use MongoDB to store the data
  * Use Flask to display the data

Robin would design her webpage to include the following information:

  * Latest Mars News
  * Feature Mars Image
  * Mars Facts
  * Mars Hemispheres

Robin built into her web page the ability to click the **Scrape New Data** button.  Once clicked, this allowed the scraping script to reconnect with the various websites, update the database, and display any new data and/or images.

Finally, she polished the website by using various Bootstrap components.

### Resources
Websites:
 * https://spaceimages-mars.com
 * https://galaxyfacts-mars.com
 * https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars
 * https://redplanetscience.com


Code:
 * Mission_to_Mars_Challenge.ipynb
 * Mission_to_Mars_Challenge.py
 * scraping.py
 * app.py
 * index.html


Software:
 * Python 3.7.11
 * Pandas 1.3.5
 * Jupyter Notebook
 * MongoDB
 * Visual Studio Code 1.65
 * Flask


## Deliverable 1:  Scrape Full-Resolution Mars Hemisphere Images and Titles
The goal of this deliverable was to use BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images and store in a dictionary.  In order to achieve this deliverable, the following steps were taken:
 * Code is written that retrieves the full-resolution image and title for each hemisphere image
 * The full-resolution images of the hemispheres are added to the dictionary
 * The titles for the hemisphere images are added to the dictionary
 * The list contains the dictionary of the full-resolution image URL string and title for each hemisphere image

Here is the original code and output:
![mars_hemi_images_titles_original_code](https://user-images.githubusercontent.com/94148420/156899089-e732452b-735e-4100-8867-ac36b4839a3b.PNG)


## Deliverable 2:  Update the Web App with Mars’s Hemisphere Images and Titles
For this deliverable, Python and HTML skills were used to add the code you created in Deliverable 1 to the scraping.py file, update the Mongo database, and modify modify the index.html file so the webpage contains all the information collected in this module as well as the full-resolution image and title for each hemisphere image.

Here is the code that defined the scraping function:
![scraping_function](https://user-images.githubusercontent.com/94148420/156899360-e64ea097-31fd-4157-b4cf-f010977b9d6f.PNG)

Additional functions to scraping.py allowed the scraping of various websites and looping HTML tags to collect information that would be stored in the MongoDB database.  Flask was used to create an app to display the information on the **Mission to Mars** web page.  A **Scrape New Data** button was created so that information could be updated/refreshed with a click!

Here are the original **Mission to Mars** web page components:

**Jumbotron**
![Jumbotron_original](https://user-images.githubusercontent.com/94148420/156899743-e4dc0718-d4bc-479d-aa72-78fd4ff669f5.PNG)

**Latest Mars News**
![Latest_Mars_News_original](https://user-images.githubusercontent.com/94148420/156899758-67c4a53e-15bf-453a-b510-1c23e4d6ee89.PNG)

**Latest Mars News after Scrape**
![Latest_Mars_News_after_scrape](https://user-images.githubusercontent.com/94148420/156899772-20666f7d-21d8-44db-bc37-5578f63b054f.PNG)

**Mars Facts**
![Mars_Facts_original](https://user-images.githubusercontent.com/94148420/156899778-f17fbc75-495d-41fa-95a6-e3decd49d4d3.PNG)

**Mars Hemispheres**
![Mars_Hemispheres_original](https://user-images.githubusercontent.com/94148420/156899785-900a78b3-26b0-45d3-9fa4-f7c532847317.PNG)

Using the MongoDB database made this possible:
![MongoDB_mars](https://user-images.githubusercontent.com/94148420/156899804-fcad4a5d-d01f-4236-92cb-240b94f91203.PNG)


## Deliverable 3:  Add Bootstrap 3 Components
Several Bootstrap components were added to *polish* the web page.

### Jumbotron Updated with Image, Red Button, & White Lettering
![Jumbotron_update_code](https://user-images.githubusercontent.com/94148420/156899908-cac8f027-f001-49f3-aae0-e1b5c4de3127.PNG)

![Jumbotron_update](https://user-images.githubusercontent.com/94148420/156899935-5741e664-f526-4514-a16c-06ec5ab9a98e.PNG)

### Web Page with Light Gray Background
![background_color_light_gray](https://user-images.githubusercontent.com/94148420/156900020-4153c6be-20de-4a36-b803-5c1d8d119340.PNG)

![webpage_background_color_light_gray](https://user-images.githubusercontent.com/94148420/156900066-7da14879-77ba-41f3-b082-b699cbd3098f.PNG)

### Orientation of Hemispheres on Single Row: "col-md-3"
![hemispheres_col_md_3](https://user-images.githubusercontent.com/94148420/156900199-bbc1ed2f-f5b7-4e0c-9400-367e4c8bd726.PNG)

![hemispheres_image_col_md_3](https://user-images.githubusercontent.com/94148420/156900235-d186dae7-0ba6-4983-8f00-fc8708c6a579.PNG)

### Website Responsiveness Tested with iPhone 12 Pro
![responsiveness_iPhone_12_Pro_update](https://user-images.githubusercontent.com/94148420/156900329-529ef35a-4b59-41a5-a8c4-14acc7a39c07.PNG)

## Summary
This was a very challenging project, but Robin is well on her way to accomplishing her goal of working for NASA in the future.
